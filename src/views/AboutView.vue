<template>
    <div class="test">
        <h1>This is a Test page.</h1>
        <button id="te">test</button>
    </div>
</template>
<script>
axios
    .get({
        method: "get",
        url: "http://localhost:81/notice/list",
    })
    .then(function (response) {})
    .then(function () {});
</script>

<style>
@media (min-width: 1024px) {
    .about {
        min-height: 100vh;
        display: flex;
        align-items: center;
    }
}
</style>
