<template>
    <section class="nav">
        <div class="nav-logo">
            <img src="https://i.redd.it/kgtwwxcjod151.jpg" alt="logo" class="logo" height="100" width="100">
        </div>
        <div class="nav-menu">
            <ul class="nav-menu-list">
                <li class="nav-list-item"><a href = "/">About Me</a></li>
                <li class="nav-list-item"><a href = "/contact">Contact</a></li>
            </ul>
        </div>
    </section>
</template>

<script>
export default {
    
}
</script>

<style lang='sass' scoped>
    .nav
        position: fixed
        left: 0
        top: 0
        bottom: 0
        background: #B8BDB5
        display: flex
        flex-direction: column
        align-items: center
        width: 20vw
        .nav-logo
            margin: 100px
            .logo
                border-radius: 50%
        .nav-menu
            color: white
    .nav-menu-list
        list-style: none
        padding: 0
        .nav-list-item
            background: #889696
            padding: 10px 20px
            text-align: center
            margin: 10px auto
            cursor: pointer 
            &:hover 
                width: 100%
            a:link
                color: white
            a:visited
                color: silver
</style>