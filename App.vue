<script src="https://unpkg.com/vue"></script>

<div id="app">
    {{ message }}
</div>

<script>
    var app = new Vue({
        el: '#app',
        data: {
        message: 'Hello, Vue!'
        }
    })
</script>