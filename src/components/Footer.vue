<template>
    <div class="footer">
        <div class="footer-list">
            <div class="footer-info">
                <div class="footer-logo">
                    <icon-acarta></icon-acarta> 
                </div>
                <p class="text-inform">Our Customer Due Diligence platform helps you avoid <br> fines or losing clients due to AML while protecting you from cybercrime.</p>
                <h4>Approved Service Provider</h4>
                <img class="bada-logo" src="@/assets/img/bada-img.png" alt="BADA">
                <h4>In Partnership with</h4>
                <icon-law></icon-law>
                <p class="text-registration">Registered with the Information Commissioner's Office (ICO) Registration number: ZA679248</p>
                <p class="text-arc-pay">© Arc-Pay Ltd 2021</p>
            </div>
            <div class="footer-links">
                <div class="links-list">
                    <h4>Links</h4>
                    <ul>
                        <li>Home</li>
                        <li>About us</li>
                        <li>Why arcarta</li>
                        <li>Success Stories</li>
                        <li>FAQ's</li>
                        <li>Contact Us</li>
                        <li>Join</li>
                        <li>Invite</li>
                        <li>Compliance Quiz</li>
                        <li>ID Document Quiz</li>
                    </ul>
                </div>
                <div class="solutions-list">
                    <h4>Solutions</h4>
                    <ul>
                        <li>For Galleries</li>
                        <li>For Advisors</li>
                        <li>For Auctioneers</li>
                        <li>For Secure Payments</li>
                        <li>For Buyers & Collectors</li>
                        <li>Online AML Training</li>
                    </ul>
                </div>
                <div class="resources-list">
                    <h4>Resources</h4>
                    <ul>
                        <li>Articles</li>
                        <li>Resources</li>
                        <li>Help Centre</li>
                        <li>The Bigger Picture</li>
                        <li>Login</li>
                        <li>Brand Assets</li>
                        <div class="new-link">
                            <li>The Art Market Report</li>
                            <p>New</p>
                        </div>
                        
                    </ul>
                </div>
            </div>
        </div>
        <div class="social-list">
            <img class="social-img" src="@/assets/img/people-footer-img.png" alt="People">
            <div class="social-items">
                <p class="social-text">Privacy & Terms</p>
                <a class="item-twitter" href="#"><icon-twitter></icon-twitter></a>
                <a class="item-inst" href="#"><icon-instagram></icon-instagram></a>
                <a class="item-tube" href="#"><icon-you-tube></icon-you-tube></a>
            </div>
        </div>
    </div>
</template>

<script>
import IconTwitter from "./icons/IconTwitter.vue"
import IconInstagram from "./icons/IconInstagram.vue"
import IconYouTube from "./icons/IconYouTube.vue"
import IconAcarta from './icons/IconAcarta.vue'
import IconLaw from './icons/IconLaw.vue'

export default {
    components: {
        IconTwitter,
        IconInstagram,
        IconYouTube,
        IconAcarta,
        IconLaw,
    }
}
</script>

<style>
.footer{
    display: flex;
    flex-wrap: nowrap;
    flex-direction: column;
    margin-left: 120px;
    margin-right: 120px;
}

.footer-list{
    display: flex;
    flex-wrap: nowrap;
    justify-content: space-between;
    margin-bottom: 35px;
}

.footer-info{
    width: 340px;
    margin-right: 80px;
}

.footer-logo{
    margin-bottom: 19px;
}

.text-inform{
    font-weight: 400;
    font-size: 13px;
    line-height: 20px;
    letter-spacing: 0%;
    color: #313131;
    margin-bottom: 30.91px;
}

.footer-info h4{
    font-weight: 600;
    font-size: 13px;
    line-height: 20px;
    letter-spacing: 0%;
    color: #313131;
    margin-bottom: 9.91px;
}

.bada-logo{
    width: 76px;
    height: 76px;
    margin-bottom: 30.36px;
}

.text-registration{
    font-weight: 400;
    font-size: 13px;
    line-height: 20px;
    letter-spacing: 0%;
    color: #D3D3D3;
    margin-top: 19.47px;
    margin-bottom: 20px;
}

.text-arc-pay{
    font-weight: 400;
    font-size: 13px;
    line-height: 20px;
    letter-spacing: 0%;
    color: #D3D3D3;
}

.footer-links{
    display: flex;
}

.footer-links li{
    list-style-type: none;
    font-weight: 400;
    font-size: 12px;
    line-height: 20px;
    letter-spacing: 0%;
    color: #313131;
}

.footer-links h4{
    font-weight: 600;
    font-size: 13px;
    line-height: 20px;
    letter-spacing: 0%;
    color: #333333;
}

.links-list{
    width: 108px;
    margin-right: 108px;
}

.solutions-list{
    width: 139px;
    margin-right: 108px;
}

.resources-list{
    width: 187px;
}

.new-link{
    display: flex;
}

.new-link p{
    font-weight: 700;
    font-size: 11px;
    line-height: 21px;
    letter-spacing: 0%;
    text-align: center;
    color: #FFFFFF;
    width: 50px;
    height: 23px;
    opacity: 1;
    border-radius: 20px;
    background-color: #F9A28F;
    margin-left: 8px;
}

.social-list{
    display: flex;
    justify-content: space-between;
    margin-bottom: 80px;
}

.social-img{
    width: 161px;
    height: 76px;
    margin-left: 0px;
}

.social-items{
    display: flex;
    flex-wrap: nowrap;
    align-items: end;
    justify-items: center;
}

.social-text{
    font-weight: 400;
    font-size: 13px;
    line-height: 20px;
    letter-spacing: 0%;
    color: #D3D3D3;
    margin-right: 15px;
}

.item-twitter{
    margin-right: 10px;
    display: flex;
    justify-content: center;
}

.item-inst{
    margin-right: 10px;
    display: flex;
    justify-content: center;
}

.item-tube{
    margin-right: 15px;
    display: flex;
    justify-content: center;
}
</style>