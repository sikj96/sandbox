<template>
    <footer>
        <div class="container">
            <p>&copy; {{ currentYear }} My Website. All rights reserved.</p>
        </div>
    </footer>
</template>

<script>
export default {
    data() {
        return {
            currentYear: new Date().getFullYear()
        };
    }
};
</script>

<style scoped>
footer {
    background-color: #f5f5f5;
    padding: 20px;
    text-align: center;
}
</style>