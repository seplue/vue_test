<template>
    <div>
        <p>
            http://ron-swanson-quotes.herokuapp.com/v2/quotes
        </p>
        <p>
            {{status}}
        </p>
    </div>

</template>

<script>
    const axios = require("axios");
    export default {
        name: "AxiosTest",
        data: function() {
            return {
                status: "Hello World!"
            }
        },
        created: function () {
            this.loadQuote();
        },
        methods: {
            loadQuote: function () {
                this.status = "Loading...";
                var app = this;
                axios.get("http://ron-swanson-quotes.herokuapp.com/v2/quotes")
                    .then( function(response){
                        console.log(response)
                        app.status = response.data[0];
                    })
                    .catch(function(error){
                        app.status = "An error occurred" + error;
                    })
            }

        },
    }
</script>

<style scoped>

</style>

http://ron-swanson-quotes.herokuapp.com/v2/quotes
