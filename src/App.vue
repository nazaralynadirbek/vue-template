<template lang="pug">
    .container
        h1 Done
</template>

<script>
    export default {
        name: 'App'
    }
</script>

<style lang="sass">
    @import url('https://fonts.googleapis.com/css?family=Lato:300,400,700,900')

    html, body, img, h1, h2, h3, h4, h5, h6, ul, li, a, p
        margin: 0
        padding: 0
        border: none

    html
        height: 100%

    body
        height: 100%
        font-family: 'Lato', sans-serif

        -moz-osx-font-smoothing: grayscale
        -webkit-font-smoothing: antialiased

    button
        outline: none
        cursor: pointer

    li
        list-style: none

    a
        text-decoration: none

    .row
        display: block

    .col
        margin-right: 40px
        vertical-align: top
        display: inline-block

        &-2
            width: calc((100% - 40px) / 2)
        &-3
            width: calc((100% - 80px) / 3)
        &-4
            width: calc((100% - 120px) / 4)

        &:last-child
            margin: 0
</style>
