<template>
    <form>
        <h3>Login</h3>

        <div class="form-group">
            <label>Email</label>
            <input type="email" class="form-control" plcaeholder="Email"/>
        </div>

        <div class="form-group">
            <label>Password</label>
            <input type="Password" class="form-control" plcaeholder="Password"/>
        </div>

        <button class="btn btn-primary btn-block">Login</button>
    </form>
</template>

<script>
export default{
    name: 'Login'
}
</script>