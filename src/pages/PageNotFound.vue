<template>
    <div class="page not-found">
        <div class="columns">
            <div class="column">
                <h1 class="title">Page not found</h1>
                <p>
                    Oh oh... we couldn't find the page you requested.
                </p>
                <div class="columns">
                    <div class="column">
                        <router-link class="button" to="/still-wrong">hi!</router-link>
                    </div>
                    <div class="column">
                        <router-link class="button" to="/">bye!</router-link>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'pageNotFound'
}
</script>

<style lang="sass" scoped>
  .page-not-found

</style>
