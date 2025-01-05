<template>
  <header>
    <h1>Jeffrey Conti's Portfolio</h1>
    <nav>
      <li><a href="#about">About</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#skills">Technical Skills</a></li>
    </nav>
  </header>
  <main>
    <body>
      <section class="about" id="about">
        <h2>About Section</h2>
        <p>
          I’m a passionate programmer and data enthusiast with a unique blend of
          experience in healthcare and technology. After 8 years in the nursing
          field, I transitioned into tech by completing a full-stack development
          bootcamp. Throughout my career, I have excelled at teamwork,
          collaboration, and communication—skills that have been invaluable in
          both healthcare and tech environments. My technical expertise includes
          Java, JavaScript, Vue.js, SQL, and more, with hands-on experience
          deploying applications and working with databases. I’m excited to
          combine my analytical mindset, technical skills, and ability to work
          seamlessly with others to create impactful solutions and drive
          data-driven decisions.
        </p>
      </section>
      <section class="projects" id="projects">
        <h2>Project Section</h2>
        <a href="https://www.DataRN.com" target="_blank">Data RN</a>
      </section>
      <section class="skills" id="skills">
        <h2>Skills Sections</h2>
        <ul>
          <li>Java</li>
          <li>JavaScript</li>
          <li>HTML</li>
          <li>CSS</li>
          <li>Vue.js</li>
          <li>OOP</li>
          <li>Spring Boot</li>
          <li>PostgreSQL</li>
          <li>SQL</li>
          <li>Git</li>
          <li>Tableau</li>
          <!-- <li></li>
          <li></li>
          <li></li> -->
        </ul>
      </section>
      <section class="interests" id="interests">
        <h2>Interests Section</h2>
        <ul>
          <li>Skiing</li>
          <li>Rock Climbing</li>
          <li>Surfing</li>
          <li>Backpacking</li>
          <li>Flying FPV Drones</li>
          <li>Financial Investments</li>
          <li>EcoRevive: Streets & Shores</li>
        </ul>
      </section>
    </body>
  </main>
  <footer>
    <h2>Footer</h2>
    <ul>
      <li>
        <a
          href="https://www.linkedin.com/in/jeffreycontideveloper/"
          target="_blank"
          rel="noopener noreferrer"
          >LinkedIn</a
        >
      </li>
      <li>
        <a
          href="https://github.com/JeffreyConti"
          target="_blank"
          rel="noopener noreferrer"
          >Github</a
        >
      </li>
      <li><a href="" target="_blank" rel="noopener noreferrer">Resume</a></li>
    </ul>
  </footer>
</template>

<script></script>

<style>
html {
  scroll-behavior: smooth;
}
body {
  margin: 0;
  width: 100vw;
}
header {
  display: flex;
  flex-direction: column;
  align-items: center;

  top: 0;
  left: 0;
  position: sticky;
  background-color: white;
  padding: 10px 20px;
}
nav {
  display: flex;
  list-style-type: none;
  gap: 10px;
}
main {
  display: flex;
  flex-direction: column;
  padding: 60px;
}
.about{

}
.about p{
  padding: 20px;
}
.skills ul{
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  list-style-type: none;
  padding-left: 20px;
  

}
.interests ul{
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  list-style-type: none;
  padding-left: 20px;

}
footer {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 100vw;;
  padding: 10px;
  border-top: black solid 3px;
}
footer ul {
  display: flex;
  flex-direction: row;

  list-style-type: none;
  gap: 20px;
}
</style>
