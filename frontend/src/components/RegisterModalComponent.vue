<template>
    <div class="modal fadein" id="registerModal" tabindex="-1" aria-labelledby="registerLabel" aria-hidden="true">
        <div class="modal-dialog modal-dialog-centered">
            <div class="modal-content bg-dark">
                <div class="modal-body bg-dark">
                    <button type="button" class="btn-close btn-close-white" data-bs-dismiss="modal"
                        aria-label="Close"></button>
                    <div class="myform bg-dark">
                        <h1 class="text-center">Register</h1>
                        <form>
                            <div class="mb-3 mt-4">
                                <label for="exampleInputEmail1" class="form-label">Email address</label>
                                <input type="email" class="form-control" id="exampleInputEmail1"
                                    aria-describedby="emailHelp">
                            </div>
                            <div class="mb-3 mt-4">
                                <label for="inputUsername" class="form-label">Username</label>
                                <input type="text" class="form-control" id="inputUsername">
                            </div>
                            <div class="mb-3 mt-4">
                                <label for="inputPhoneNumber" class="form-label">Phone Number</label>
                                <input type="tel" class="form-control" id="inputPhoneNumber">
                            </div>
                            <div class="mb-3">
                                <label for="exampleInputPassword1" class="form-label">Password</label>
                                <input type="password" class="form-control" id="exampleInputPassword1">
                            </div>
                            <button type="submit" class="btn btn-light mt-3">REGISTER</button>
                            <p>Already Registered? <a data-bs-toggle="modal" data-bs-target="#loginModal"
                                    href="/login">Sign In</a></p>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "RegisterModalComponent",
}
</script>

<style scoped>
h1 {
    font-size: 2.3em;
    font-weight: bold;
}

.myform {
    padding: 2em;
    color: #fff;
}

@media (max-width: 576px) {
    .myform {
        max-width: 90%;
        margin: 0 auto;
    }
}

.form-control:focus {
    box-shadow: inset 0 -1px 0 #7e7e7e;
}

.form-control {
    background-color: inherit;
    color: #fff;
    padding-left: 0;
    border: 0;
    border-radius: 0;
    border-bottom: 1px solid #fff;
}

.btn {
    width: 100%;
    font-weight: 800;
    background-color: #fff;
    border-radius: 0;
    padding: 0.5em 0;
}

.btn:hover {
    background-color: inherit;
    color: #fff;
    border-color: #fff;
}

p {
    text-align: center;
    padding-top: 2em;
    color: grey;
}

p a {
    color: #e1e1e1;
    text-decoration: none;
}

p a:hover {
    color: #fff;
}
</style>
