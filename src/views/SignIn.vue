<template>
    <div>
        <Header />
        <div class="background">
            <img src="https://app.swaggerhub.com/img/swaggerhub-logo.svg" alt="" width="300px" />
            <div class="form">
                <button class="formItem w-100 btn btn-dark">
                    Log in with Github
                </button>
                <span class="formItem link">
                    Login with SSO
                </span>
                <span class="formItem">
                    - OR -
                </span>
                <label for="" class="formItem fieldLabel">
                    User Name or Email
                </label>
                <div class="formItem input-group">
                    <span class="material-icons input-group-text">
                        person
                    </span>
                    <input v-model="login" placeholder="Введите ваше имя пользователя или E-mail" type="text" class="form-control" />
                </div>
                <label for="" class="formItem fieldLabel">
                    User Name or Email
                </label>
                <div class="formItem input-group">
                    <span class="material-icons input-group-text">
                        lock
                    </span>
                    <input v-model="password" placeholder="Введите ваш пароль" type="text" class="form-control" />
                </div>
                <div class="formBtns formItem">
                    <span class="link">
                        Forgot Login Info?
                    </span>
                    <button class="btn btn-primary formItem">
                        LOG IN
                    </button>
                </div>
                <hr />
                <span class="formItem">
                    New to AppierHub? <span class="link" @click="$router.push({ name: 'SignUp' })">Sign Up</span>
                </span>
            </div>
        </div>
        <Footer />
    </div>
</template>

<script>

import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'

export default {
    name: 'SignIn',
    data() {
        return {
            login: '',
            password: ''
        }
    },
    components: {
        Header,
        Footer
    }
}
</script>

<style scoped>
    
    .background {
        position: relative;
        top: calc(50px + 15px);
        left: 0px;
        background-color: rgb(0, 0, 0);
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 100%;
    }

    .form {
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        align-items: center;
        margin: 50px 0px;
        width: 40%;
        background-color: rgb(255, 255, 255);
        border-radius: 8px;
        height: 500px;
        box-sizing: border-box;
        padding: 35px;
    }

    .fieldLabel {
        align-self: flex-start;
    }

    .formItem {
        margin: 5px 0px;
    }

    .formBtns {
        width: 100%;
        justify-content: space-between;
        display: flex;
    }

    .link {
        cursor: pointer;
        color: rgb(0, 100, 200);
    }

</style>