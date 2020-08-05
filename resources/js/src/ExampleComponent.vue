<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Example Component</div>

                    <div class="card-body">
                        I'm an example component.
                    </div>
                    <div>
                        {{message}}
                    </div>
                </div>
            </div>

            <div>
                <a-button type="primary">按钮</a-button>
            </div>

        </div>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                message: 'hello laravel-vue'
            }
        },
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
