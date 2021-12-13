<template>
    <div class="page-success">
        <div class="columns is-multiline">
            <div class="column is-12">
                <h1 class="title">Thank you fro placing the order.</h1>

                <p>Your order will be processed within 48 hours.</p>
            </div>
        </div>
    </div>
</template>

<script>
import axios from 'axios'

export default {
    name: 'Success',
    
    mounted() {
        document.title = 'Success | Ecommerce'
    },
}
</script>