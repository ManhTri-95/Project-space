<template>
    <div class="hero">
        <header class="header">
            <div class="header__container">
                <div class="logo">
                     <img src="../assets/logo.png" alt="" />
                </div>
                <div class="header__right">
                    <nav class="nav-menubar">
                        <ul class="menubar">
                            <li class="menuitem"><a href="#">Home</a></li>
                            <li class="menuitem"><a href="#">Templates</a></li>
                            <li class="menuitem"><a href="#">Price</a></li>
                            <li class="menuitem"><a href="#">Help</a></li>
                        </ul>
                    </nav>
                    <a href="#" class="btn btn-small outline-primary">Get In Touch</a>
                </div>
            </div>
        </header>
    </div>
</template>

<script>

export default {
    name: 'Header',
   
}
</script>

<style scoped>
    @import './../assets/css/header.css';
    @import './../assets/css/button.css';
</style>