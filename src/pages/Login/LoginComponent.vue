<template>
    <div class="main">
       <div class="login">
           <div class="content-login">
               <header>
                   <h1>Login do Sistema</h1>
               </header>
               <div class="form">
                   <form>
                        <div class="form-group">
                            <label for="exampleInputEmail1">E-mail</label>
                            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Seu email">
                        </div>
                        <div class="form-group">
                            <label for="exampleInputPassword1">Senha</label>
                            <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Senha">
                        </div>
                        <button type="submit" class="btn btn-primary" @click.prevent="login">Entrar</button>
                    </form>
               </div>
           </div>
       </div>
    </div>
</template>

<script>
export default {
    name: 'LoginComponent',

    data(){
        return {

        }
    },
    methods: {
        login(){
            this.$router.push({name: 'home'});
        }
    }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;400;700&display=swap');

.main {
    display: flex;
    height: 100%;
    flex-direction: row;
    font-family: 'Roboto','sans-serif';
}

.login {
    display: flex;
    width: 100%;
    height: 100vh;
    justify-content: center;
    align-items: center;
    background: #e4e4e4;

}

.content-login {
    width: 400px;
    height: 450px;
    background: #82ACFA;
    border-radius: 7px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

}

header {
    width: 100%;
    display: flex;
    justify-content: center;
}

h1 {
    color: white;
    font-size: 28px;
}

.form{
    width: 70%;
    margin-top: 15%;
}

.form label {
    color: white;
}
</style>