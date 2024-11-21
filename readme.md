<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Responsive GitHub Profile</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #181818;
      color: white;
      text-align: center;
    }

    h2 img {
      vertical-align: middle;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      align-items: center;
      padding: 20px;
    }

    .profile-image {
      max-width: 100%;
      height: auto;
      margin: 20px;
    }

    pre {
      background-color: #282c34;
      color: #61dafb;
      padding: 15px;
      overflow-x: auto;
      border-radius: 5px;
      max-width: 100%;
      text-align: left;
      margin: 20px auto;
    }

    .icons img {
      margin: 10px;
      height: 50px;
    }

    .stats {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin-top: 20px;
    }

    .stats img {
      max-width: 100%;
      height: auto;
    }

    @media (max-width: 768px) {
      .profile-image {
        max-width: 70%;
      }

      .stats img {
        max-width: 90%;
      }
    }
  </style>
</head>
<body>
  <h2>
    <img src="https://media4.giphy.com/media/MaI6BylfjAkDkfk4OC/giphy.gif" width="50">
    Hi, I'm MagoPato!
    <img src="https://media.giphy.com/media/mGcNjsfWAjY5AEZNw6/giphy.gif" width="50">
  </h2>

  <div class="container">
    <img src="https://user-images.githubusercontent.com/46275040/130966311-1f677328-a329-4799-9476-264fbb914fb2.png" alt="Profile Image" class="profile-image">
    <pre>
const MagoPato = {
  pronouns: "he" | "him",
  code: [Javascript, C/C++, HTML, CSS, Python, Java, SQL],
  tools: ["Node.js", "Chrome DevTools", "Xampp", "Microcontroladores (Arduino, ESP32, Raspberry Pi)"],
  hardwareDevelopment: {
    programming: ["Programación de microcontroladores Arduino y ESP32"],
    designPrototyping: ["Diseño y prototipado de proyectos electrónicos con Arduino"],
    sensorIntegration: ["Integración de sensores y actuadores con microcontroladores"]
  },
  artificialIntelligence: ["Machine Learning", "computer vision", "ARIMA", "SARIMA", "LSTM", "TensorFlow"],
  challenge: "I am doing the #100DaysOfCode challenge focused on react and typescript"
}
    </pre>
  </div>

  <div class="icons">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/arduino/arduino-original.svg" alt="Arduino">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="C">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" alt="Bootstrap">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" alt="PHP">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java">
  </div>

  <div class="stats">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MagoPato&theme=github_dark&hide_progress=true" alt="Top Languages">
    <img src="https://data-card-for-spotify.herokuapp.com/api/card?user_id=2266hwwnnjonhwg6q7vr2zooq&limit=3&hide_top_tracks=1&show_border=1" alt="Spotify Card">
  </div>
</body>
</html>