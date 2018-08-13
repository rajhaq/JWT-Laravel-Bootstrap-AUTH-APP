<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card card-default">
                    <div class="card-header">Example Component</div>

                    <div class="card-body">
                       MainApp
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name:'main-app',
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
