<template>
    <section class="home">
        <div class="hero" data-aos="fade-up">
            <h1>Hello, I’m <span class="highlight">Emman</span> 👋</h1>
            <h2>I build clean, fast, and reliable web apps.</h2>
            <p>
                Full Stack Developer specializing in Vue.js, Pinia, Laravel, and PHP.
            </p>
            <div class="buttons">
                <a href="#projects" class="btn">View Projects</a>
                <a href="/resume.pdf" class="btn secondary" download>Download Resume</a>
            </div>
        </div>

        <div class="about" data-aos="fade-up">
            <h2>About Me</h2>
            <p>
                I’m a developer with experience in full-stack apps using Vue 3, Laravel, and more. I've collaborated
                with teams in Vietnam, Myanmar, and Japan and love optimizing code and workflow.
            </p>
            <p>
                I enjoy teaching, building cool side projects, and exploring animation in frontend tech.
            </p>
        </div>
    </section>
</template>

<script setup>
// You can set up AOS or Motion here later
</script>

<style scoped>
.home {
    padding: 2rem;
}

.hero {
    text-align: center;
    margin-top: 4rem;
}

.hero h1 {
    font-size: 3rem;
    font-weight: bold;
}

.hero h2 {
    font-size: 1.5rem;
    margin-top: 1rem;
}

.highlight {
    color: #42b883;
}

.buttons {
    margin-top: 2rem;
}

.btn {
    background: #42b883;
    color: white;
    padding: 0.75rem 1.5rem;
    margin-right: 1rem;
    border-radius: 8px;
    text-decoration: none;
}

.btn.secondary {
    background: #35495e;
}

.about {
    margin-top: 5rem;
    max-width: 700px;
    margin-left: auto;
    margin-right: auto;
    text-align: center;
}
</style>