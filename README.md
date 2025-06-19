<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chris & Angel</title>
</head>
 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>A & C Navbar</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@500;700&display=swap" rel="stylesheet">
  <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Merienda:wght@300..900&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
  .logo-text {
      font-weight: 700;
      font-size: 20px;
      color: #000;
    }
    body {
      font-family: 'Great Vibes', cursive;
    }

    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      background-color: white;
      border-bottom: 1px solid #eee;
    }

    .logo-container {
      display: flex;
      align-items: center;
      font-size: 20px;
    }
    .logo {
      width: 40px;
      height: 40px;
      margin-right: 10px;
    }
  .nav-links {
      display: flex;
      gap: 40px;
      font-weight: 500;
    }

    .nav-links a {
      text-decoration: none;
      color: #120028;
      font-size: 16px;
      transition: color 0.2s;
    }

    .nav-links a:hover {
      color: #6c4bd3;
    }

    .cta-button {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .btn {
      background-color: #6c4bd3;
      color: white;
      padding: 12px 24px;
      border-radius: 50px;
      font-weight: bold;
      border: none;
      cursor: pointer;
      font-size: 14px;
    }

    .icon-circle {
      background-color: #6c4bd3;
      color: white;
      width: 40px;
      height: 40px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 18px;
    }
 body {
  margin: 0;
  font-family: 'Great Vibes', cursive;
  background: linear-gradient(to bottom right, #000,#000);
  color: black;

}

header.hero {
  text-align: center;
  padding: 80px 20px;
}

.hero h1 {
  font-size: 150px;
  font-weight: bold;
  font-family: "Merienda", cursive;
  font-optical-sizing: auto;
}

.hero h2 {
  font-size: 10px;
  margin-top: 10px;
}

.about {
  padding: 60px 20px;
  text-align: center;
  background: black;
}

.about h3 {
  font-size: 1.8em;
  margin-bottom: 20px;
}

.about p {
  max-width: 700px;
  margin: auto;
  line-height: 1.6;
}

.services {
  padding: 60px 20px;
  background: black;
  text-align: center;
}

.service-cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  margin-top: 30px;
}

.card {
  background: #fff;
  color: #000;
  border-radius: 12px;
  width: 300px;
  padding: 15px;
  text-align: left;
}

.card img {
  width: 100%;
  border-radius: 8px;
}

.card h4 {
  margin: 15px 0 10px;
}

.packages {
  padding: 60px 20px;
  background: black;
  text-align: center;
}

.package-cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 25px;
  margin-top: 30px;
}

.pkg {
  background: #fff;
  color: #000;
  border-radius: 12px;
  width: 280px;
  padding: 20px;
}

.pkg h4 {
  color: black;
}

.pkg ul {
  text-align: left;
  padding-left: 20px;
}

.pkg button {
  margin-top: 15px;
  padding: 10px 20px;
  background: black;
  color: white;
  border: none;
  border-radius: 6px;
  cursor: pointer;
}

.fulfillment {
  padding: 50px 20px;
  background: #000;
}

.fulfillment ul {
  max-width: 700px;
  margin: auto;
  text-align: left;
  padding-left: 20px;
}

.contact {
  padding: 50px 20px;
  background: #0d022d;
  text-align: center;
}

.contact a {
  color: black;
  text-decoration: none;
}

@media (max-width: 768px) {
  .service-cards, .package-cards {
    flex-direction: column;
    align-items: center;
  }

  .hero h1 {
    font-size: 2em;
  }

  .hero h2 {
    font-size: 1.5em;
  }
}
/* Base Setup (unchanged) */
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: linear-gradient(to bottom right, black);
  color: white;
  overflow-x: hidden;
}

h1, h2, h3, h4 {
  margin: 0;
  padding: 0;
}

/* Animations */
@keyframes fadeIn {
  from { opacity: 0; transform: translateY(30px); }
  to { opacity: 1; transform: translateY(0); }
}

/* Animation Helper */
.animate {
  opacity: 0;
  animation: fadeIn 1s ease forwards;
}

.hero, .about, .services, .packages, .fulfillment, .contact {
  animation: fadeIn 1.5s ease forwards;
}

/* HERO */
header.hero {
  text-align: center;
  padding: 80px 20px;
}

.hero h1 {
  font-size: 2.5em;
  font-weight: bold;
}

.hero h2 {
  font-size: 2em;
  margin-top: 10px;
}

/* ABOUT */
.about {
  padding: 60px 20px;
  text-align: center;
  background: black;
}

/* SERVICES */
.services {
  padding: 60px 20px;
  background: black;
  text-align: center;
}

.service-cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  margin-top: 30px;
}

.card {
  background: #fff;
  color: black;
  border-radius: 12px;
  width: 300px;
  padding: 15px;
  text-align: left;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover {
  transform: scale(1.05);
  box-shadow: 0 10px 20px rgba(255, 255, 255, 0.2);
}

.card img {
  width: 100%;
  border-radius: 8px;
}

.card h4 {
  margin: 15px 0 10px;
}

/* PACKAGES */
.packages {
  padding: 60px 20px;
  background: black;
  text-align: center;
}

.package-cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 25px;
  margin-top: 30px;
}

.pkg {
  background: #fff;
  color: #000;
  border-radius: 12px;
  width: 280px;
  padding: 20px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.pkg:hover {
  transform: translateY(-10px);
  box-shadow: 0 10px 25px rgba(0,0,0,0.3);
}

.pkg h4 {
  color: black;
}

.pkg ul {
  text-align: left;
  padding-left: 20px;
}

.pkg button {
  margin-top: 15px;
  padding: 10px 20px;
  background: white;
  color: black;
  border: none;
  border-radius: 6px;
  cursor: pointer;
  transition: background 0.3s ease, transform 0.2s ease;
}

.pkg button:hover {
  background: #9e5fff;
  transform: scale(1.05);
}

.fulfillment {
  padding: 50px 20px;
  background: black;
  text-align: center;
  
}

.fulfillment ul {
  max-width: 700px;
  margin: auto;
  text-align: left;
  padding-left: 20px;
}

/* CONTACT */
footer.contact {
  padding: 50px 20px;
  background: black;
  text-align: center;
}

.contact a {
  color: #9e7dff;
  text-decoration: none;
  transition: color 0.3s ease, border-bottom 0.3s ease;
}

.contact a:hover {
  color: #ffffff;
  border-bottom: 1px solid #ffffff;
}


@media (max-width: 768px) {
  .service-cards, .package-cards {
    flex-direction: column;
    align-items: center;
  }

  .hero h1 {
    font-size: 2em;
  }

  .hero h2 {
    font-size: 1.5em;
  }
}


  </style>
   
<body>

  <header class="navbar">
     <div class="logo-text">Chris & Angel</div>
    <div> </div>

    <nav class="nav-links">
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Services</a>
      <a href="#">Contact</a>
    </nav>
    <div class="cta-button">
      <button class="btn">GET STARTED</button>
      <div class="icon-circle">↗</div>
    </div>
  </header>
 
    <header class="hero">
    <h1><span>Chris & Angel</span></h1>
    <h2>DIGITAL CONSULTING</h2>
  </header>

  <section class="about">
    <div class="about-text">
      <h3>About<br><span>Digital Consulting</span></h3>
      <p>
        Chris & Angel positions itself as a full-service digital marketing partner offering SEO, analytics, and data security solutions. They emphasize driving measurable results—like website traffic growth and higher conversions—while ensuring your digital operations are both optimized and secure.
      </p>
    </div>
  </section>

  <section class="services">
    <h3>Digital Consulting Services</h3>
    <div class="service-cards">
      <div class="card">
        <img src="j 1@3x.png" alt="Digital Audit" />
        <h4>Digital Audit</h4>
        <p>Review your current digital setup to find gaps, risks, and opportunities for improvement.</p>
      </div>
      <div class="card">
        <img src="j 2@3x.png" alt="Digital Strategy" />
        <h4>Digital Strategy</h4>
        <p>Create a step-by-step plan to grow your digital presence and reach business goals.</p>
      </div>
      <div class="card">
        <img src="j 3@3x.png" alt="Design and Implementation" />
        <h4>Design and Implementation</h4>
        <p>Develop and launch tailored digital solutions based on your business needs.</p>
      </div>
    </div>
  </section>

  <section class="packages">
    <h3>Our Packages</h3>
    <div class="package-cards">
      <div class="pkg">
        <h4>Starter Package – $299/month</h4>
        <ul>
          <li>SEO setup</li>
          <li>Google Business Profile optimization</li>
          <li>1 social media platform (4 posts/month)</li>
          <li>Email support</li>
        </ul>
        <button>MAKE IT YOURS</button>
      </div>
      <div class="pkg">
        <h4>Growth Package – $699/month</h4>
        <ul>
          <li>SEO (on-page & local)</li>
          <li>Google Ads (up to $1K)</li>
          <li>2 platforms (8 posts/month)</li>
          <li>Blog content (1/month)</li>
          <li>Strategy call</li>
        </ul>
        <button>MAKE IT YOURS</button>
      </div>
      <div class="pkg">
        <h4>Pro Package – $1,299/month</h4>
        <ul>
          <li>Advanced SEO + backlinking</li>
          <li>Google + Meta Ads (up to $3K)</li>
          <li>3 platforms (12 posts/month)</li>
          <li>Landing pages, blog (2/month)</li>
          <li>Dedicated account manager</li>
        </ul>
        <button>MAKE IT YOURS</button>
      </div>
    </div>
  </section>

  <section class="fulfillment">
    <h3>✅ Service Fulfillment</h3>
    <p><strong>Fulfillment Policy</strong></p>
    <ul>
      <li>Work begins within 1–3 business days after payment.</li>
      <li>Timelines depend on scope; we’ll keep you updated.</li>
      <li>Cancel anytime with 7 days’ notice before billing cycle.</li>
      <li>No refunds once work starts. Contact us for billing issues.</li>
      <li>Email: <a href="mailto:chris@chrisandangelinc.com">chris@chrisandangelinc.com</a></li>
    </ul>
  </section>

  <footer class="contact">
    <h4>Get a quote or set<br>up a consultation.</h4>
    <p><strong>Phone:</strong> <a href="tel:+18326920351">+1 832 692 0351</a></p>
    <p><strong>Email:</strong> <a href="mailto:chris@chrisandangelinc.com">chris@chrisandangelinc.com</a></p>
  </footer>
  </div>
 </div>
</div>
</body>
</html>
