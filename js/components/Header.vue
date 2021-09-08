<template>
    <header class="header">
        <a href="index.html">
            <h1>Q&A Website</h1>
        </a>
        <nav>
            <ul class="flex">
                <li><a href="index.html">Home</a></li>
            </ul>
        </nav>

        <ul class="flex">
            <li><a href="login.php">Login</a></li>
            <li><a href="register.php">Register</a></li>
        </ul>   
    </header>
</template>
<script>
export default {
    data() {
        return {
            message: ""
        };
    }
}
</script>