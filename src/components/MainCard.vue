<template>
    <div class="wrapper">
        <div class="main-container">
            <div class="container-one">
                <div class="profile">
                    <img src="../assets/Profile_image.jpg" alt="">
                    <h3>Kacper Duda</h3>
                    <p>Software tester</p>
                </div>
                <div class="social-links">
                    <div class="link">
                        <a href="https://github.com/duda-kacper" target="_blank">
                            <img src="../assets/GitHub.png" alt="GitHub image not found">
                            <h2>GitHub</h2></a>
                    </div>
                    <div class="link">
                        <a href="https://www.linkedin.com/in/dudakacper/" target="_blank">
                            <img src="../assets/Linkedin.png" alt="Linkedin image not found">
                            <h2>Linkedin</h2>
                        </a>
                    </div>
                </div>
            </div>
            <div class="container-two">
                <div class="about-me">
                    <h1>About me</h1>
                    <p>I am an ambitious, open to gain knowledge, young person who has experience working as a low-code platform tester. My enthusiasm and practice in the IT industry combined with theoreticalknowledge as well as passion for testing provide a solid basis for my development in this position.
                        The ability to think analytically along with my scrupulousness in performing assigned tasks allowsme to thoroughly analyze requirements and detect potential errors. I can work in a team and have ahigh work culture. In my free time, I am interested in history and try to expand my professionalknowledge. In the future, I want to develop towards test automation.</p>
                </div>
                <div class="technology-section">
                    <h1>Technologies studied</h1>
                    <div class="logos">
                        <img src="../assets/HTML.png" alt="HTML image not found">
                        <img src="../assets/CSS.png" alt="CSS image not found">
                        <img src="../assets/SQL.png" alt="SQL image not found">
                        <img src="../assets/Postman.png" alt="Postman image not found">
                    </div>
                    <div class="button-container">
                        <div class="projects-button">
                            <a href="https://github.com/duda-kacper?tab=repositories" target="_blank">My Projects</a>
                        </div>
                        <div class="projects-button">
                            <a href="https://drive.google.com/file/d/1Jfzl63MGR_9zkwHuPCUilI4Q1nAr9d2T/view?usp=sharing" target="_blank">My Resume</a>
                        </div>
                    </div>
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
    .wrapper{
        display: flex;
    justify-content: center;
    }
    img{
        height: 20px;
    }

    .main-container{
        display:flex;
        flex-direction: row;
        background-color: #CECECE;
        border-radius: 25px;
        width: 60%;
        background-color: #A0D4FF;
        box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
    }

    .container-one{
        background-color: #1292EE;
        padding: 2.5%;
        width: 30%;
        border-radius: 25px;
        box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
    }

    .profile img{
        height: 5rem;
        border-radius: 50%;
    }

    .link a{
        text-decoration: none;
        color: #2C3E50;
        font-size: 10px;
    }

    .link img{
        height: 2rem;
    }

    .container-two{
        margin: 2.5%;
        width: 70%;
        border-radius: 25px;
    }

    .about-me{
        text-align : left;
        margin-left: 10px;
        margin-right: 10px;
    }

    .logos img{
        height:  3rem;
        margin-right: 10px;
    }

    .button-container{
        margin-top: 3%;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }

    .projects-button{
        background-color: #005CA4;
        border-radius: 15px;
        padding: 7.5px;
        margin: 5px;
    }

    .projects-button a{
        text-decoration: none;
        color: #ffffff;
    }

    @media  only screen and (max-width: 950px) {
        .main-container{
            width: 95%;
        }
    }
</style>