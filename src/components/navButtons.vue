<template>
 <div id="nav">

     <div class="navContainer">
        <router-link to="/">
            <img class="icon" alt="home icon" src="../assets/ui.png"/>
        </router-link> |
     </div>
     <div class="navContainer">
        <router-link to="/feature1">
            <img class="icon" alt="info icon" src="../assets/info.png"/>
        </router-link>
     </div>

     <div class="navContainer">
        <router-link to="/feature2">
            <img class="icon" alt="target icon" src="../assets/target.png"/>
        </router-link>
     </div>

     <div class="navContainer">
        <router-link to="/about">
            <img class="icon" alt="target icon" src="../assets/target.png"/>
        </router-link>
     </div>

 </div>
</template>

<script>
export default {
    name: 'NavButtons',
    data() {
        return {

        }
    },
    methods: {

    }
}
</script>

<style scoped>

* {
    margin: 0;
    padding: 0;
}
.icon {
    width: 50px;
    height: 50px;
}

#nav {
    position: fixed;
    bottom: 0;
    width: 100%;
    display: flex;
    justify-content: space-between;
    border: 2px solid gold;
    padding: 0px;

}

.navContainer {
    background-color: darkcyan;
}
</style>