<template>
    <header>
        <nav>
            <ul class="fd">
                <li class="nav-item">
                    first nav item
                </li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
  name: 'HeaderPage',
};
</script>

<style scoped>
header {
    background-color: rgba( 214, 234, 214, 1 );
    padding: 5px 10px;
    margin-top: 10px;
    margin-bottom: 20px;
}

li.nav-item {
    background-color: red;
    height: 40px;
}
</style>
