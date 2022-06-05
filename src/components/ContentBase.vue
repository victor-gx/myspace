<template>
    <div calss="home">
        <div class="container">
            <div class="card">
                <div calss="card-body">
                    <slot></slot>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "ContentBase",
}
</script>

<style scoped>
.container {
    margin-top: 20px;
}
</style>
