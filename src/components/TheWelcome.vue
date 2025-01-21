<script setup>
</script>

<template>
  <div class="home">
    <!-- Hero Section -->
    <header class="hero">
      <h1>Welcome to Emerald Building & Maintenance</h1>
      <p>Your trusted partner for property transformation and improvement. We deliver quality and excellence in every project.</p>
      <a href="#services" class="cta-button">Explore Our Services</a>
    </header>

    <!-- About / Company Overview Section -->
    <section class="about">
      <h2>About Us</h2>
      <p>
        At Emerald Building & Maintenance, we offer a comprehensive range of services to enhance and transform your property. Our expert team is dedicated to delivering high-quality solutions tailored to your needs.
      </p>
      <p>
        We believe in building lasting relationships with our clients through trust, quality, and attention to detail.
      </p>
    </section>

    <!-- Services Section -->
    <section class="services" id="services">
      <h2>Our Expertise</h2>
      <p>
        We provide a wide range of professional services to meet all your building and maintenance needs:
      </p>
      <ul>
        <li>💎 New Builds</li>
        <li>💎 Home Renovations</li>
        <li>💎 Extensions</li>
        <li>💎 Composite & Timber Decking</li>
        <li>💎 Block Paving</li>
        <li>💎 Fencing</li>
        <li>💎 Drainage Solutions</li>
        <li>💎 Artificial Grass Installation</li>
        <li>💎 Telescopic Safety Barriers</li>
      </ul>
      <a href="/services" class="cta-button">See All Services</a>
    </section>

    <!-- Contact Section -->
    <footer class="contact">
      <h2>Contact Us</h2>
      <p>If you’re ready to start your next project or need a consultation, feel free to get in touch with us.</p>
      <a href="/contact" class="cta-button">Contact Information</a>
    </footer>
  </div>
</template>

<style>
.home {
  font-family: 'Arial', sans-serif;
}

.hero {
  background: #2c3e50;
  color: #fff;
  padding: 4rem 2rem;
  text-align: center;
}

.hero h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 1.5rem;
}

.cta-button {
  padding: 10px 20px;
  background-color: #1abc9c;
  color: #fff;
  text-decoration: none;
  font-size: 1.1rem;
  border-radius: 5px;
}

.cta-button:hover {
  background-color: #16a085;
}

.about,
.services,
.contact {
  padding: 2rem;
  text-align: center;
}

.about h2,
.services h2,
.contact h2 {
  font-size: 2rem;
  color: #2c3e50;
  margin-bottom: 1rem;
}

.services ul {
  list-style: none;
  padding: 0;
}

.services li {
  font-size: 1rem;
  margin: 0.75rem 0;
}

footer {
  background: #ecf0f1;
  padding: 2rem 0;
}
</style>
