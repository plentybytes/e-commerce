<template>

    <div class="container">
        <div class="text-center" style="margin: 20px 0px 20px 0px;">
            <span class="text-secondary">Laravel Vue CRUD Example</span>
        </div>
 
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="collapse navbar-collapse">
                <div class="navbar-nav">
                    <router-link to="/home" class="nav-item nav-link">Home</router-link>
                    <router-link to="/login" class="nav-item nav-link">Login</router-link>
                    <router-link to="/search" class="nav-item nav-link">Search Items </router-link>
                </div>
            </div>
        </nav>
        <br/>
        <router-view></router-view>
    </div>

</template>
 
<script>
    export default {}
</script>