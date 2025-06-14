<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Eloheh Healthcare Services</title>
  <style>
    body {
      background-color: #BD9A7A;
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }
    h1, h2 {
      color: #000000;
    }
    .bold {
      font-weight: bold;
    }
    .italic {
      font-style: italic;
    }
    .underline {
      text-decoration: underline;
    }
    .contact {
      font-family: Courier, monospace;
      font-size: 1.3em;
    }
    .last-modified {
      font-size: 0.8em;
      color: #f0e68c;
      font-family: 'Times New Roman', Times, serif;
    }
    .red {
      color: #e74c3c;   
    }
    .purple {
      color: #7851a9;
    }
  </style>
</head>
<body>
  <h1>Eloheh Healthcare Services</h1>
  <img src="https://drive.google.com/thumbnail?id=1-e4vj9zWNe5zxD9D4i75zwqh9oJNJRp_" alt="Healthcare Image" width="200" />

  <h2>Our Services</h2>
  <div class="services">
    <p><span class="bold underline">Basic Care Package</span> - <span class="italic">General Checkup + Wellness Tips</span> - $49.99/month</p>
    <p><span class="bold underline">Standard Care Package</span> - <span class="italic">Basic Care + Virtual Consultations</span> - $89.99/month</p>
    <p><span class="bold underline">Premium Care Package</span> - <span class="italic">Standard Care + Lab Tests + Priority Support</span> - $149.99/month</p>
    <p><span class="bold underline">Custom Care Package</span> - <span class="italic">Tailored Services Based on Your Needs</span> - Price Varies</p>
  </div>

  <h2>Why Choose Us?</h2>
  <ul>
    <li>Comprehensive healthcare solutions</li>
    <li class="red">Affordable pricing</li>
    <li class="purple">Expert medical professionals</li>
  </ul>

  <h2>Contact Us</h2>
  <p>If you have any questions or need further information, please <a href="mailto:hlumpcik@purdue.edu" class="contact">contact me</a>.</p>

  <h2>Additional Resources</h2>
  <p>For more information on healthcare, visit <a href="https://www.healthcare.gov" target="_blank">HealthCare.gov</a>.</p>
  <p>Download our <a href="https://drive.google.com/uc?export=download&id=18gWGULhJHKvTcSH-5GL_KnKt3mocrGZT" download>brochure</a> for more details.</p>

  <h2>Service Packages</h2>
  <ol>
    <li>Basic Care Package</li>
    <li>Standard Care Package</li>
    <li>Premium Care Package</li>
    <li>Custom Care Package</li>
  </ol>

  <p class="last-modified">Last modified: <span id="lastModified"></span></p>

  <script>
    document.getElementById('lastModified').textContent = document.lastModified;
  </script>
</body>
</html>
