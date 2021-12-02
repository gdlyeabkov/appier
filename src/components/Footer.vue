<template>
    <div class="footer">
        <div class="footerItem footerTop">
            <img class="footerTopLogo" width="150px" src="https://static1.smartbear.co/swagger/media/images/logos/sw_full-wt.svg" alt="" />
            <div class="footerTopColumns">
                <div class="footerTopColumn">
                    <span class="footerTopColumnItem footerTopColumnHeader">
                        Swagger Open Source
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        Open Source License
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        Swagger Forum
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        Swagger IRC
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        Swagger Community
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        Swagger Projects
                    </span>
                </div>
                <div class="footerTopColumn">
                    <span class="footerTopColumnItem footerTopColumnHeader">
                        Swagger
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        About Swagger                        
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        Blog
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        Support
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        News
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        Contact Us
                    </span>
                </div>
                <div class="footerTopColumn">
                    <span class="footerTopColumnItem footerTopColumnHeader">
                        Pro Tools
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        SwaggerHub
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        Swagger Inspector
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        SwaggerHub Enterprise
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        SwaggerHub vs OSS
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        SwaggerHub Integrations
                    </span>
                </div>
                <div class="footerTopColumn">
                    <span class="footerTopColumnItem footerTopColumnHeader">
                        Resources
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        OpenAPI Specification
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        Resources
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        Open Source Docs
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        Swagger Inspector Docs
                    </span>
                    <span class="footerTopColumnItem footerTopColumn">
                        
                        SwaggerHub Docs
                    </span>
                </div>
            </div>
        </div>
        <div class="footerItem footerMiddle">
            <div>
                <span class="footerMiddleHeaderLabel footerMiddleHeaderLabelFirst">
                    Explore
                </span>
                <span class="footerMiddleHeaderLabel">
                    SmartBear
                </span>
                <span class="footerMiddleHeaderLabel">
                    Tools
                </span>
            </div>
            <div>
                
            </div>
            <div>

            </div>
            <div>
                <div>
                    <span>
                        Contact Us | 
                    </span>
                </div>
                <div>
                    <span>
                        +1 617-684-2600 USA|
                    </span>
                </div>
                <div>
                    <span>
                        +353 91 398300 EUR|
                    </span>
                </div>
                <div>
                    <span>
                        +61 391929960 AUS
                    </span>
                </div>
            </div>
        </div>
        <div class="footerItem footerBottom">
            <div class="footerBottomRow">
                <span class="copyright">
                    © 2021 SmartBear Software. All Rights Reserved.
                </span>
                <div>
                    <button class="fab fa-twitter btn btn btn-light socialMediaBtn">
                        
                    </button>
                    <button class="fab fa-facebook btn btn btn-light socialMediaBtn">
                        
                    </button>
                    <button class="fab fa-linkedin btn btn btn-light socialMediaBtn">
                        
                    </button>
                    <button class="fab fa-youtube btn btn btn-light socialMediaBtn">
                        
                    </button>
                </div>
            </div>
            <div class="footerBottomRow">
                <div class="footerBottomRowItem">
                    <span class="footerBottomRowItemElement">
                        Privacy
                    </span>
                    <span class="footerBottomRowItemElement">
                        |
                    </span>
                    <span class="footerBottomRowItemElement">
                        Terms of Use
                    </span>
                    <span class="footerBottomRowItemElement">
                        |
                    </span>
                    <span class="footerBottomRowItemElement">
                        Site Map
                    </span>
                    <span class="footerBottomRowItemElement">
                        |
                    </span>
                    <span class="footerBottomRowItemElement">
                        Website Terms of Use
                    </span>
                    <span class="footerBottomRowItemElement">
                        |
                    </span>
                    <span class="footerBottomRowItemElement">
                        Security
                    </span>
                </div>
                <div>

                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    
    .footer {
        width: 100%;
        display: flex;
        flex-direction: column;
        height: 1000px;
    }

    .footerItem {
        
    }

    .footerTop {
        box-sizing: border-box;
        padding: 75px;
        display: flex;
        flex-direction: column;
        height: 450px;
        background-size: cover;
        background-position: 0% 50%;
        background-image: url('https://static1.smartbear.co/swagger/media/images/backgrounds/photos/sw-ws-bgphoto5.png');    
    }

    .footerMiddle {
        background-color: rgb(0, 50, 100);
        height: 500px;
        box-sizing: border-box;
        padding: 35px;
        display: flex;
        flex-direction: column;
    }

    .footerBottom {
        background-color: rgb(25, 25, 25);
        height: 165px;
        box-sizing: border-box;
        padding: 25px 65px;
    }

    .footerMiddleHeaderLabel {
        color: rgb(255, 255, 255);
        font-size: 22px;
    }

    .footerMiddleHeaderLabelFirst {
        text-decoration: underline;
        text-underline-offset: 25px;
        text-decoration-color: rgb(200, 150, 0);
    }

    .footerTopLogo {
        /* margin-top: 75px; */
    }

    .footerTopColumn {
        display: flex;
        flex-direction: column;
        margin: 0px 35px;
    }

    .footerTopColumnHeader {
        color: rgb(0, 150, 0) !important;
        font-size: 24px !important;
        margin: 5px !important;
    }

    .footerTopColumnItem {
        color: rgb(255, 255, 255);
        font-size: 18px;
        margin: 3px;
    }

    .footerTopColumns {
        display: flex;
        justify-content: center;
    }

    .footerBottomRow {
        display: flex;
        justify-content: space-between;
    }

    .copyright {
        color: rgb(150, 150, 150);
        font-size: 18px;
    }

    .socialMediaBtn {
        margin: 0px 5px;
    }

    .footerBottomRowItemElement {
        color: rgb(255, 255, 255);    
        margin: 0px 5px;
        font-size: 18px;
    }

</style>