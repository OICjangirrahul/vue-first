<template>
       <body>
        
        <!-- header -->
        <div id="top-container">
            <img class="top-cloud" :src="require('../assets/images/cloud.png') " alt="">
            <div class="title-text">
                <h1>I'm Garima</h1>
                <h2>a <span>Soft</span>ware Developer</h2>
            </div>
            <img class="bottom-cloud" :src="require('../assets/images/cloud.png') " alt="">
            <img class="mountain" :src="require('../assets/images/mountain.png') " alt="">
        </div>
        <!-- end header -->

        <!-- main content -->
        <div id="middle-container">
            <div class="profile">
                <img src="assets/images/circle-cropped.png" alt="">
                <h2>Hello</h2>
                <p class="intro">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolores maiores quis blanditiis explicabo, similique voluptas quaerat architecto et vitae natus consequuntur quae. Blanditiis quasi ea quae exercitationem sit, ab ut!</p>
            </div>
            <hr>
            <div class="skills">
                <h2>Skills</h2>
                <div class="skill">
                    <img class="top-image" src="https://i.giphy.com/media/L8K62iTDkzGX6/giphy.webp" alt="">
                    <h3>Developer</h3>
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem recusandae doloribus, omnis neque enim consequatur animi at voluptatum quibusdam qui aliquid fugiat officia soluta placeat minus blanditiis eligendi odio nisi.
                    </p>
                </div>
                <div class="skill">
                    <img class="middle-image" src="https://www.qamadness.com/wp-content/themes/qamadness/dist/images/gif-animation/manual-automated.gif" alt="">
                    <h3>Testing</h3>
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem recusandae doloribus, omnis neque enim consequatur animi at voluptatum quibusdam qui aliquid fugiat officia soluta placeat minus blanditiis eligendi odio nisi.
                    </p>
                </div>
                <div class="skill">
                    <img class="bottom-image" src="https://i.pinimg.com/originals/18/a4/94/18a4949fc9c8067172d3b96e302e7097.gif" alt="">
                    <h3>Designing</h3>
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem recusandae doloribus, omnis neque enim consequatur animi at voluptatum quibusdam qui aliquid fugiat officia soluta placeat minus blanditiis eligendi odio nisi.
                    </p>
                </div>
            </div>
            <hr>
            <div class="contact-me">
                <h2>Get in Touch</h2>
                <h3>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</h3>
                <p class="contact-message">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                <a class="btn" href="mailto:example@gmail.com">Contact</a>
            </div>
        </div>

        <!-- end main content -->

        <!-- footer -->

        <div id="bottom-container">
            <a class="footer-link" href="#">LinkedIn</a>
            <a class="footer-link" href="#">Github</a>
            <a class="footer-link" href="#">Twitter</a>
            <p class="copyright">&copy; 2021 Your Name.</p>
        </div>

        <!-- end footer -->

    </body>
</template>




<style scoped>
 body {
    margin: 0px;
    text-align: center;
    font-family: 'Times New Roman', Times, serif;
}

a {
    text-decoration: none;
    color: #79018C;
}

h1 {
    font-size: 90px;
    color: #fff;
    font-family: 'Sacramento', cursive;
}

h2 {
    font-size: 30px;
    color: #9A0680;
    font-family: 'Fuzzy Bubbles', cursive;
}

h3 {
    color: #4C0070;
    font-size: 20px;
    font-family: 'Indie Flower', cursive;
}

p {
    font-size: 17px;
    color: #79018C;
}

span {
    color: #fff;
}

hr {
    width: 4%;
    border-style: dotted;
    border-width: 18px;
    border-bottom: none;
    border-color: #f3efef;
    margin: 100px auto 120px;
}

#top-container {
    background-color: #160040;
    position: relative;
}

.top-cloud {
    position: absolute;
    top: 100px;
    right: 300px;
}

.bottom-cloud {
    position: absolute;
    bottom: 300px;
    left: 300px;
}

.title-text {
    padding: 100px 0px;
}

#middle-container {
    margin: 100px 0px;
}

.intro {
    width: 30%;
    margin: 30px auto;
}

.skill {
    width: 50%;
    margin: 100px auto 120px;
    text-align: left;
}

.top-image {
    width: 30%;
    float: left;
    margin-right: 30px;
    border-radius: 20px;
}

.middle-image {
    width: 30%;
    float: right;
    margin-left: 30px;
    border-radius: 20px;
}

.bottom-image {
    width: 30%;
    float: left;
    margin-right: 30px;
    border-radius: 20px;
}

.contact-me {
    width: 40%;
    margin: 40px auto 20px;
}

.contact-message {
    margin:40px auto 20px;
}

.btn
{
    background-color: #160040;
    padding: 10px 20px;
    font-size: 20px;
    border-radius: 20px;
}

.btn:hover {
    background-color: #4C0070;
    color: #fff;
}

#bottom-container {
    background-color: #160040;
    padding: 40px 0 60px;
}

.footer-link {
    margin: 0 20px;
}

.footer-link:hover {
    color: #fff;
}

.copyright {
    padding: 20px 0;
}
</style>

<script>
export default {
    name: 'one'
}
</script>