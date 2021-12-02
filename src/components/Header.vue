<template>
    <div class="header">
        <div class="headerItem headerItemLeft">
            <img @click="$router.push({ name: 'Home' })" class="headerItemElement headerLogo" src="https://static1.smartbear.co/swagger/media/assets/images/swagger_logo.svg" alt="" width="165px" />
            <div class="headerItemElement">
                <span class="headerItemElementItem headerItemElementItemLabel">
                    Why Appier
                </span>
                <span class="material-icons headerItemElementItem headerItemElementItemIcon">
                    expand_more
                </span>
            </div>
            <div class="headerItemElement">
                <span class="headerItemElementItem headerItemElementItemLabel">
                    Tools
                </span>
                <span class="material-icons headerItemElementItem headerItemElementItemIcon">
                    expand_more
                </span>
            </div>
            <div class="headerItemElement">
                <span class="headerItemElementItem headerItemElementItemLabel">
                    Resources
                </span>
                <span class="material-icons headerItemElementItem headerItemElementItemIcon">
                    expand_more
                </span>
            </div>
        </div>
        <div class="headerItem headerItemRight">
            <div class="headerItemElement">
                <span class="material-icons">
                    search
                </span>
            </div>
            <div class="headerItemElement">
                <button class="btn btn-light signInBtn" @click="$router.push({ name: 'SignIn' })">
                    Sign In
                </button>
            </div>
            <div class="headerItemElement" @click="$router.push({ name: 'TryFree' })">
                <button class="btn btn-success">
                    Try Free
                </button>
            </div>
        </div>
        <div class="chat">
            <span class="chatIcon btn btn-danger material-icons w-100 h-100">
                chat_bubble
            </span>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    
    .header {
        z-index: 5;
        position: fixed;
        top: 0px;
        left: 0px;
        width: 100%;
        height: 65px;
        background-color: rgb(255, 255, 255);
        box-shadow: 0px 0px 5px rgb(200, 200, 200);
        display: flex;
        justify-content: space-between;
        box-sizing: border-box;
        padding: 0px 85px;
    }

    .headerItem {
        display: flex;
        align-items: center;
    }

    .headerItemElement {
        display: flex;
        align-items: center;
        margin: 10px;
    }

    .headerItemElementItem {
        margin: 0px 5px;
    }

    .headerItemElementItemLabel {
        font-size: 18px;
    }

    .headerItemElementItemIcon {
        font-size: 28px;
        font-weight: normal;
    }
    
    .headerItemLeft {
        width: 65%;
        align-items: center;
    }

    .signInBtn {
        border: 1px solid rgb(0, 150, 0);
        background-color: rgb(255, 255, 255);
    }

    .chat {
        position: fixed;
        top: calc(100% - (75px + 25px));
        left: calc(100% - (75px + 25px));
        width: 75px;
        height: 75px;
        display: flex;
        align-items: flex-end;
        justify-content: center;
    }

    .chatIcon {
        font-size: 36px;
        box-sizing: border-box;
        padding-top: 20px;
    }

    .headerLogo {
        cursor: pointer;
    }

</style>