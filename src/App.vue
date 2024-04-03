<template>
  <div class="portfolio">
    <header>
        <h1>My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">hoby</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main class="main-background">
  <section class="about">
    <div class="profile-info">
      <h2 class="bold-heading">BIODATA SAYA</h2>
      <p>Perkenalkan nama saya Ririn Juliyanti. Saya Mahasiswi Universitas Islam Riau angkatan 2022. 
        Fakultas Teknik, Program Studi Teknik Informatika.</p>
    </div>
    <div class="profile-photo">
      <img src="/src/assets/bg1.jpeg" alt="" class="profile-picture">
    </div>
  </section>
  <section class="projects">
  <h2><strong>KEAHLIAN</strong></h2>
  <p>Microsoft Word <br>
    Microsodt Power point
  </p>
  <div class="project">
    <h3><strong>HOBBY</strong></h3>
    <p>Hoby saya bermain Badminton</p>
  </div>
  <div class="project">
    <h3><strong>PENGALAMAN</strong></h3>
    <p>Magang di CV Intel Komputer <br>
    panitia IT Funday 2023 </p>
  </div>
</section>

<section class="contact">
  <h2><strong>Contact Me</strong></h2>
  <p>Email: ririnjuliyanti@student.uir.ac.id</p>
</section>

</main>

    <footer>
      <p>&copy; 2024 My Portfolio</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style scoped>

.portfolio header {
  background-color: 	#008B8B; 
  padding: 10px 0; 
  display: flex; 
  justify-content: space-between; 
  align-items: center; 
}

.portfolio header h1 {
  margin: 0; 
  color: #fff; 
}

.portfolio header nav ul {
  list-style: none; 
  margin: 0;
  padding: 0;
}

.portfolio header nav ul li {
  display: inline; 
}

.portfolio header nav ul li a {
  color: #fff; 
  text-decoration: none; 
  padding: 10px 20px; 
}

.portfolio header nav ul li a:hover {
  background-color: #B0C4DE; 
}

.about {
  display: flex;
  justify-content: space-between;
  
}

.profile-info {
  flex: 1;
}

.profile-photo {
  flex: 1;
  text-align: right;
}

.profile-picture {
  width: 160px; 
  height: auto;
  border-top: 50%;
}
.bold-heading {
  font-weight: bold;
}
section {
  margin-bottom: 40px;
}
.main-background {
  background-color: #B0E0E6; 
  padding: 20px;
}

.about {
  margin-top: 50px; 
}

.bold-heading {
  font-weight: bold;
  font-size: 100x;
  margin-bottom: 10px;
}
.profile-info p {
  font-size: 18px; 
}

.contact h2 strong{
  font-weight: bold;
  display: block; 
  margin-bottom: 20px; 
}
.projects h2 strong,
.projects h3 strong {
  font-weight: bold;
  display: block; 
  margin-bottom: 20px; 
  
}

footer {
  background-color: #008B8B; 
  color: #fff; 
  text-align: center; 
  padding: 20px; 
}
</style>