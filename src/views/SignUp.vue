<template>
    <div>
        <Header />
        <div class="background">
            <img src="https://app.swaggerhub.com/img/swaggerhub-logo.svg" alt="" width="300px" />
            <div class="form">
                <span class="formHeader formItem">
                    SIGN UP
                </span>
                <button class="formItem w-100 btn btn-dark">
                    Create Account with Github
                </button>
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
                    <input v-model="login" placeholder="Введите имя пользователя аккаунта" type="text" class="form-control" />
                </div>
                <label for="" class="formItem fieldLabel">
                    User Name
                </label>
                <div class="formItem input-group">
                    <span class="material-icons input-group-text">
                        person
                    </span>
                    <input v-model="email" placeholder="Введите E-mail аккаунта" type="text" class="form-control" />
                </div>
                <label for="" class="formItem fieldLabel">
                    Email
                </label>
                <div class="formItem input-group">
                    <span class="material-icons input-group-text">
                        lock
                    </span>
                    <input v-model="password" placeholder="Создайте пароль" type="text" class="form-control" />
                </div>
                <div class="formBtns formItem">
                    <span class="formItem">
                        Have an account? <span class="link" @click="$router.push({ name: 'SignIn' })">Log in</span>
                    </span>
                    <button class="btn btn-primary formItem">
                        SIGN UP
                    </button>
                </div>
                <hr />
                <span class="formItem">
                    By signing up for AppierHub you agree to our <span class="link">Terms of Use</span> and our <span class="link">Privacy Policy</span>
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
    name: 'SignUp',
    data() {
        return {
            login: '',
            email: '',
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
        height: 575px;
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

    .formHeader {
        font-size: 28px;
        align-self: flex-start;
    }

</style>