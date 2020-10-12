# My-First-Website
von Erik Neubauer

HTML:

<!DOCTYPE html>
<html>
  <head>
    <style>
      </style>
    <link rel="stylesheet" type="text/css" href="CSS_project.css" media="screen"/>
  </head>
  <body>
    <div>
      <p class="header"><h1><u>Alles über mich!</u></h1></p>
     <p>
      Auf dieser Website möchte Ich einwenig über mich selber erzählen.
    </p>
    <h2><u>Fakten über mich</u></h2>
      <p>
      Grundsätzlich Interessiere Ich mich für alles was mit Technik und Software zu tun hat. 
      <br>
        Programmieren ist einer meiner Hauptbeschäftigungen am PC. 
      <br>
      Ab und zu spiele Ich auch gerne am PC etwas, falls ich nichts zu tun habe.
      </p>
    <h2><u>Programmieren</u></h2>
      <p>
        Ich programmiere seid ca. 6 Monaten, von denen ich jedoch 
        <br>
        nur 4 Monate aktiv war. Hauptsächlich programmiere Ich in C# mit Unity. 
      <br>
        <p>
        Hier kommt man zu der Offizielen <a href="https://unity.com/de">Unity Website</a>, <br> falls man mehr über Spielentwicklung lesen möchte.
       </p>
       <p>
        <hr><iframe width="560" height="315" src="https://www.youtube.com/embed/rE03nC4K_Eg" frameborder="0" allowfullscreen></iframe>
      </p>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/19/Unity_Technologies_logo.svg/2000px-Unity_Technologies_logo.svg.png" width="200px">
    </p>
    </div>
  </body>
</html>


CSS:


body {
  text-align: center;
  font-family: 'Roboto-Bold', sans-serif;
  color: #2e2e2e;
  background-image: url("https://wallpaper-mania.com/wp-content/uploads/2018/09/High_resolution_wallpaper_background_ID_77700445417.jpg");
  }

p {
  font-size:14pt;
  font-family: 'Roboto', sans-serif;
  }

li {
  padding-bottom: 5px;
  font-size:10pt;
  }
  
h2 {
  padding-top: 25px;
  }

.header {
  font-size: 15pt;
}
