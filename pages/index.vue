<template>
  <div class="container">
    <h1 class="cv-title">Curriculum Vitae</h1>
      <div class="profile">
        <img src="/images/profile.jpg" alt="Profile Picture" />
        <div class="profile-content">
          <h1>HELLO !</h1>
          <p>I'm Nuha Rona Zahra, a Student at Brawijaya University currently majoring Information Technology and love to design UI/UX, Graphic Design and making poster.</p>
        </div>
    </div>

    <section class="experience">
      <h2>Experience</h2>
      <ul>
        <li>
          <h3>UI/UX Designer at second semester</h3>
          <p>Made application called collego, an ojek online application that provide for college student and others.</p>
        </li>
      </ul>
    </section>

    <section class="education">
      <h2>Education</h2>
      <ul>
        <li>
          <h3>SMA Negeri 2 Bojonegoro</h3>
          <p>2020-2023</p>
          <p>Science</p>
        </li>
        <li>
          <h3>Universitas Brawijaya</h3>
          <p>2023-Present</p>
          <p>Information Technology</p>
        </li>
      </ul>
    </section>

    <section class="skills">
  <h2>Portofolio</h2>
  <ul>
    <li>
      <div class="skill-item">
        <img src="/images/skill1.png" alt="Skill 1" width="100" height="100" />
        <span>Keychain</span>
        <p>Keychain "Teknologi Informasi"</p>
      </div>
    </li>
    <li>
      <div class="skill-item">
        <img src="/images/skill2.png" alt="Skill 2" width="100" height="100" />
        <span>UI/UX</span>
        <p>Collego</p>
      </div>
    </li>
  </ul>
</section>

    <section class="languages">
      <h2>Languages</h2>
      <p>Indonesia native speaker but also often using english.</p>
      <ul>
        <li>
          <span>English</span>
          <div class="progress-bar">
            <div class="progress" style="width: 70%;"></div>
          </div>
        </li>
        <li>
          <span>Indonesian</span>
          <div class="progress-bar">
            <div class="progress" style="width: 95%;"></div>
          </div>
        </li>
      </ul>
    </section>

    <section class="software">
  <h2>Software</h2>
  <p>Some software that i usually use.</p>
  <ul>
    <li>
      <img src="/images/figma.png" alt="Figma" width="50" height="50" />
      <span>Figma</span>
    </li>
    <li>
      <img src="/images/ai.png" alt="Adobe Illustrator" width="50" height="50" />
      <span>Adobe Illustrator</span>
    </li>
    <li>
      <img src="/images/vsc.png" alt="Visual Studio Code" width="50" height="50" />
      <span>Visual Studio Code</span>
    </li>
    <li>
      <img src="/images/canva.png" alt="Canva" width="50" height="50" />
      <span>Canva</span>
    </li>
  </ul>
</section>

    <section class="contact">
      <h2>Contact</h2>
      <p>Please contact me through this information.</p>
      <p>
        Email: <a href="mailto:nuharonazz@gmail.com">nuharonazz@gmail.com</a>
      </p>
      <p>
        LinkedIn: <a href="https://www.linkedin.com/in/nuha-rona-zahra-b82374289/" target="_blank">Nuha Rona Zahra</a>
      </p>
      <p>
        Instagram: <a href="https://www.instagram.com/nuharonazz?igsh=NWV1ZGVqNmNlMm4w&utm_source=qr">nuharonazz</a>
      </p>
    </section>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Pinyon+Script&display=swap');

body {
  font-family: 'Arial', sans-serif;
  background: linear-gradient(to bottom, #800000, #f0f0f0);
  margin: 0;
  padding: 0;
  line-height: 1.6;
  color: #333;
}

.container {
  max-width: 900px;
  margin: 50px auto;
  background: linear-gradient(to bottom, #fdcbf9, #cbf9f5); 
  padding: 20px;
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
}

.cv-title {
  font-family: 'Pinyon Script', cursive; 
  font-size: 100px; 
  color: #ffffff; 
  text-align: center;
  margin-bottom: 40px; 
}


.profile {
  display: flex; 
  align-items: flex-start; 
  padding: 20px 0;
}

.profile img {
  width: 150px;
  border-radius: 50%;
  border: 3px solid #fefcfc;
  margin-right: 20px; 
}

.profile-content {
  display: flex;
  flex-direction: column; 
}

.profile h1 {
  margin: 0;
  font-size: 32px;
  color: #800000;
  line-height: 1.2;
}

.profile p {
  font-size: 18px;
  color: #555;
  margin-top: 10px; 
}

h2 {
  font-size: 28px;
  margin: 30px 0 20px;
  color: #800000; 
  border-bottom: 2px solid #800000; 
  display: inline-block;
}

.experience, .education {
  margin-bottom: 10px;
}

.experience h3, .education h3 {
  margin: 5px 0;
  font-size: 22px;
  color: #333;
}

.experience p, .education p {
  margin: 5px 0;
  color: #555;
  font-style: italic;
}

ul {
  list-style-type: none;
  padding: 0;
}

ul li {
  padding: 10px 0;
  border-bottom: 1px solid #ddd;
}

ul li:last-child {
  border-bottom: none;
}

.skills ul {
  display: flex;
  flex-wrap: wrap;
  gap: 20px; 
}

.skill-item {
  display: flex;
  flex-direction: column; 
  align-items: center; 
}

.skill-item img {
  margin-bottom: 10px; 
}



.languages {
  margin-bottom: 10px;
}

.languages ul {
  list-style-type: none;
  padding: 0;
}

.languages li {
  margin: 10px 0;
}

.languages span {
  font-weight: bold;
}

.progress-bar {
  background-color: #ddd; 
  border-radius: 5px;
  height: 20px; 
  margin-top: 5px; 
  width: 50%;
  max-width: 400px; 
}

.progress {
  background-color: #800000; 
  height: 100%;
  border-radius: 5px; 
  transition: width 0.5s ease; 
}


.software {
  margin-bottom: 30px;
}

.software ul {
  list-style-type: none;
  padding: 0;
}

.software li {
  margin: 10px 0;
  display: flex;
  align-items: center; 
}

.software img {
  margin-right: 10px; 
}


.contact {
  padding: 20px 0;
}

.contact p {
  font-size: 18px;
  color: #555;
}

.contact p a {
  color: #800000; 
  text-decoration: none;
}

.contact p a:hover {
  text-decoration: underline;
}

@media (max-width: 768px) {
  .container {
    padding: 15px;
  }

  .profile img {
    width: 120px;
  }

  .profile h1 {
    font-size: 28px;
  }

  h2 {
    font-size: 24px;
  }

  .experience h3, .education h3 {
    font-size: 20px;
  }
}
</style>
