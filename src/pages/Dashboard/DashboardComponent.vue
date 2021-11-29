<template>
    <div class="main">

        <div class="sidebar">

        </div>

        <div class="content-right">

            <div class="navbar">

            </div>

            <div class="pages">
                
            </div>

        </div>
    </div>
</template>

<script>
export default {
    name:'DashBoardComponent',
}

</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;400;700&display=swap');

.main {
    width: 100%;
    height: 100vh;
}

.sidebar {
    width: 220px;
    height: 100vh;
    background-color:#82ACFA;
}

.content-right {
    width: calc(100% - 220px);
    height: 42.7rem;
    margin-top: -50%;
    margin-left: 13.7%;
    background-color: red;
}

.navbar {
    width: 100%;
    height: 70px;
    filter:brightness(90%);
    background-color: green;
}

.pages {
    width: 100%;
    height: auto;
    background-color: blue;
}

</style>