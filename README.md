<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Portfolio</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f5f5f5;
    }

    header {
      background: #222;
      color: white;
      padding: 30px;
      text-align: center;
    }

    section {
      padding: 40px;
      max-width: 800px;
      margin: auto;
    }

    .project {
      background: white;
      padding: 20px;
      margin: 15px 0;
      border-radius: 8px;
    }

    button {
      padding: 10px 15px;
      border: none;
      background: #007BFF;
      color: white;
      cursor: pointer;
      border-radius: 5px;
    }

    button:hover {
      background: #0056b3;
    }

    #contact {
      display: none;
      margin-top: 20px;
      background: #eee;
      padding: 15px;
      border-radius: 8px;
    }
  </style>
</head>

<body>

<header>
  <h1>Your Spartans-k9</h1>
  <p>What you do (Dog Trainer-K9-specialist )</p>
</header>

<section>
  <h2>My Work</h2>

  <div class="project">
    <h3>Specialty</h3>
    <p>Basic Obedience. Behavior Modification.</p>
  </div>

  <div class="project">
    <h3>Boarding</h3>
    <p>Going on a fmily trip. We will make sure your dog is safe, feed, with good manners.</p>
  </div>

  <button onclick="toggleContact()">Show Contact Info</button>

  <div id="contact">
    <p>Email: edgarvaldezpettrainer@gmail.com</p>
    <p>Phone: 831-975-3632</p>
  </div>
</section>

<script>
  function toggleContact() {
    const contact = document.getElementById("contact");
    contact.style.display =
      contact.style.display === "none" ? "block" : "none";
  }
</script>

</body>
</html>
