<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Profile Page</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <div class="profile-card">
    <img src="https://randomuser.me/api/portraits/men/75.jpg" alt="Profile Photo" class="profile-photo" />
    <h1 id="name">John Doe</h1>
    <p id="bio">Web Developer & Designer. Passionate about creating interactive user experiences.</p>
    <div class="contact-info">
      <p><strong>Email:</strong> john.doe@example.com</p>
      <p><strong>Phone:</strong> +1 234 567 8900</p>
    </div>

    <button id="toggle-btn">Show More Info</button>

    <div id="extra-info" class="hidden">
      <h3>About Me</h3>
      <p>I love coding, traveling, and photography. I have 5 years of experience in front-end development.</p>
      <h3>Skills</h3>
      <ul>
        <li>HTML / CSS / JavaScript</li>
        <li>React & Vue</li>
        <li>Node.js & Express</li>
        <li>UI/UX Design</li>
      </ul>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
