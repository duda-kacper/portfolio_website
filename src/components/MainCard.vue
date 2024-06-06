<template>
    <div class="main-container">
        <div class="container-one">
            <div class="profile">
                <img src="../assets/Profile_image.jpg" alt="">
                <h3>Kacper Duda</h3>
                <p>Software tester</p>
            </div>
            <div class="social-links">
                <div class="link">
                    <a href="">
                        <img src="../assets/GitHub.png" alt="GitHub image">
                        <h2>GitHub</h2></a>
                </div>
                <div class="link">
                    <a href="">
                        <img src="../assets/Linkedin.png" alt="Linkedin image">
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
                    <img src="../assets/Postman.png" alt="">
                    <img src="../assets/Postman.png" alt="">
                    <img src="../assets/Postman.png" alt="">
                </div>
                <div class="button-container">
                    <div class="projects-button">
                        <a href="">My Projects</a>
                    </div>
                    <div class="projects-button">
                        <a href="">My Resume</a>
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
img{
    height: 20px;
}

.main-container{
    display:flex;
    flex-direction: row;
    background-color: #909090;
    border-radius: 25px;
}

.container-one{
    background-color: #a07171;
    padding: 2.5%;
    width: 30%;
    border-top-left-radius: 25px;
    border-bottom-left-radius: 25px;
}

.profile img{
    height: 5rem;
    border-radius: 50%;
}

.link a{
    text-decoration: none;
    color: #2c3e50;
    font-size: 10px;
}

.link img{
    height: 2rem;
}

.container-two{
    background-color: #7586cf;
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
    height:  2.5rem;
}

.button-container{
    margin-top: 5%;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
}

.projects-button{
    background-color: #a618df;
    border-radius: 15px;
    padding: 5px;
    margin: 5px;
}

.projects-button a{
    text-decoration: none;
    color: #ffffff;
}
</style>