<template>
    <div class="footer-container" id="footer">
        <div class="footer-items-container">
            <p>At <strong>Hello Pure Gold</strong>, we specialize in providing unparalleled expertise and guidance in the exciting world of bullion and gold trading</p>
            <div class="cntnt-items-container">
                <strong>Company</strong>
                <ul class="baba-flex-col">
                    <li class="pointer" @click="$router.push('/about')">About Us</li>
                    <li class="pointer" @click="$router.push('/why-us')">Why us</li>
                    <li class="pointer" @click="$router.push('/services')">Services</li>
                    <li class="pointer" @click="$router.push('/aml-policy')">AML Policy</li>
                </ul>
            </div>
            <div class="news-letter baba-flex-col">
                <!-- <strong>newsletter</strong> -->
                <p>Contact details - Dubai branch</p>
                <div class="news-letter-items baba-flex-col">
                    <p>+971 45702217, +971 561130204</p>
                    <p>hellopuregoldllc@gmail.com</p>
                    <p>Ahmad Al Hammadi Building, office # 203,Al Musalla Road, Deira, Dubai, UAE</p>
                </div>
                <p>Contact details - Bangladesh branch</p>
                 <div class="news-letter-items baba-flex-col">
                     <p>+88001304100304</p>
                    <p>hellopuregold.bd@gmail.com</p>
                    <p>Rupayan FPAB Tower,37 Culvert Road,Nayapaltan, Dhaka -1000, Bangladesh</p>
                </div>
                <!-- <div class="email">
                    <input type="text" class="mail-input">
                    <button class="pointer">Submit</button>
                </div> -->
            </div>
        </div>
        <div class="footer-items2-container">
            <div class="social-media">
                <img class="pointer" width="30" height="30" src="https://img.icons8.com/ios-filled/50/FFFFFF/whatsapp--v1.png" alt="whatsapp--v1"/>
                <img class="pointer" width="30" height="30" src="https://img.icons8.com/ios-filled/50/FFFFFF/linkedin-circled--v1.png" alt="linkedin-circled--v1"/>
                <img class="pointer" width="30" height="30" src="https://img.icons8.com/ios-filled/50/FFFFFF/facebook-circled--v1.png" alt="facebook-circled--v1"/>
                <img class="pointer" width="30" height="30" src="https://img.icons8.com/ios-filled/50/FFFFFF/twitter.png" alt="twitter"/>
                <img class="pointer" width="30" height="30" src="https://img.icons8.com/ios-filled/50/FFFFFF/youtube-play.png" alt="youtube-play"/>
            </div>
            <div class="store">
                <a href="https://play.google.com/store/apps/details?id=com.tecnavis.hello_pure_android" rel="noopener" target="_blank">
                    <img class="pointer" src="https://img.litedev.com/images/static/play-store.svg" alt="youtube-play"/>
                </a> 
                <a href="https://apps.apple.com/in/app/hello-pure-golds/id6630372372" rel="noopener" target="_blank">
                    <img class="pointer" src="https://img.litedev.com/images/static/app-store.svg" alt="youtube-play"/>
                </a>
            </div>
        </div>
    </div>
</template>

<script setup>
</script>