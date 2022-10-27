<template>
    <form>
        <h3>Sign up</h3>

        <div class= "form-group">
            <label>first Name</Label>
            <input type="text" class="form-control" v-model="first_name" placeholder="First Name"/>
        </div>

        <div class= "form-group">
            <label>Last Name</Label>
            <input type="text" class="form-control" v-model="last_name" placeholder="Last Name"/>
        </div>

        <div class= "form-group">
            <label>Email</Label>
            <input type="text" class="form-control" v-model="email" placeholder="Email"/>
        </div>

        <div class= "form-group">
            <label>Password</Label>
            <input type="password" class="form-control" v-model="password" placeholder="Password"/>
        </div>

        <div class= "form-group">
            <label>Comfirm Password</Label>
            <input type="password" class="form-control" v-model="password_confirm" placeholder="Comfirm Password"/>
        </div>

        <button class="btn btn-primary btn-block">Sign Up</button>
    </form>
</template>

<script>
    export default{
        name:'Register'
    }
</script>

