<template>
    <div class="main">
       <div class="login">
           <div class="content-login">
               <header>
                   <h1>Login do Sistema</h1>
               </header>
           </div>
       </div>
    </div>
</template>

<script>
export default {

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
    justify-content: center;
    align-items: center;
    background: #e4e4e4;

}

.content-login {
    margin-top: 5%;
    width: 400px;
    height: 450px;
    background: #82ACFA;
    border-radius: 7px;
    display: flex;
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
</style>