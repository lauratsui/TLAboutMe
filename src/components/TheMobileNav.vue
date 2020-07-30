<template>
    <section class="nav">
        <div class="nav-logo">
            <img src="https://img.favpng.com/14/12/13/cat-icon-design-icon-png-favpng-0hmD7vw79EmtTwWMXUSAgXZWH.jpg" alt="logo" class="logo" height="75" width="75">
        </div>
        <div class="nav-menu">
            <ul class="nav-menu-list">
                <li class="nav-list-item">About Me</li>
                <li class="nav-list-item">Github</li>
            </ul>
        </div>
    </section>
</template>

<script>
export default {
    
}
</script>

<style lang="sass" scoped>
    .nav
        background: #333
        display: flex
        flex-direction: column
        justify-content: space-around
        align-items: center
        .nav-logo
            margin: 20px auto

        .nav-menu
            width: 100% 
</style>