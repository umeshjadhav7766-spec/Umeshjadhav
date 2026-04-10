# Umeshjadhav
Umeshjadhav photography portfolio 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Umesh Jadhav | Photography</title>

<style>
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background: #0f0f0f;
  color: white;
}

/* Navbar */
nav {
  display: flex;
  justify-content: space-between;
  padding: 20px 50px;
  background: black;
  position: sticky;
  top: 0;
}

nav h2 {
  color: red;
}

nav a {
  color: white;
  margin-left: 20px;
  text-decoration: none;
}

/* Hero */
.hero {
  height: 100vh;
  background: url('photo1.jpg') center/cover;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  text-align: center;
}

.hero h1 {
  font-size: 60px;
}

.btn {
  padding: 12px 25px;
  background: red;
  color: white;
  border-radius: 5px;
  text-decoration: none;
}

/* Gallery */
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px,1fr));
  gap: 15px;
  padding: 20px;
}

.gallery img {
  width: 100%;
  border-radius: 10px;
  transition: 0.4s;
}

.gallery img:hover {
  transform: scale(1.05);
}

/* Contact */
.contact {
  text-align: center;
  padding: 40px;
}

.contact a {
  display: inline-block;
  margin: 10px;
  padding: 12px 20px;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  transition: 0.3s;
}

/* Buttons */
.whatsapp {
  background: green;
}

.instagram {
  background: linear-gradient(45deg, #feda75, #d62976, #962fbf);
}

.contact a:hover {
  transform: scale(1.1);
}

/* Footer */
footer {
  background: black;
  text-align: center;
  padding: 20px;
}
</style>

</head>

<body>

<nav>
  <h2>Umesh Jadhav</h2>
  <div>
    <a href="#">Home</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<div class="hero">
  <h1>Umesh Jadhav</h1>
  <p>Photography & Videography</p>
  <a href="#contact" class="btn">Contact Me</a>
</div>

<section id="gallery">
  <h2 style="text-align:center;">My Work</h2>
  <div class="gallery">
    <img src="photo1.jpg">
    <img src="photo2.jpg">
    <img src="photo3.jpg">
    <img src="photo4.jpg">
    <img src="photo5.jpg">
  </div>
</section>

<section id="contact" class="contact">
  <h2>Contact Me</h2>
  <p>📞 7483852981</p>
  <p>📧 umeshjadhav8863@gmail.com</p>

  <a href="https://whatsapp.com/channel/0029VbBidF0ADTO68fJmqz3U" class="whatsapp" target="_blank">
    💬 WhatsApp
  </a>

  <a href="https://instagram.com/mr_umesh_ak36" class="instagram" target="_blank">
    📸 Instagram
  </a>

</section>

<footer>
  <p>© 2026 Umesh Jadhav</p>
</footer>

</body>
</html>
