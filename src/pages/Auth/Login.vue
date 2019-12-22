<template>
    <div>
        <label>User Name Or Email</label><input type="text" placeholder="User name or email" id="usename_or_email"/>
        <label>Password</label><input type="password" placeholder="Password" id="password"/>
        <button id="btn-login">{{ buttonName }}</button>
    </div>
</template>
<script>
    export default {
        name: 'Login',
        props: {
            buttonName: String
        }
    }
</script>