<!DOCTYPE html>

.full-doc {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.nav-bar {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  font-size: 50px;
  align-items: center;
  background: red;
  height: 100px;
  border: 5px solid black;
  position: fixed;
  width: 100%;
  top: 0;
}

.nav-bar a {
  text-decoration: none;
  color: #2F2D2E;
}

a:hover {
  color: blue;
}

.welcome-section {
  display: flex;
  flex-direction: column;
  align-items: center;
  background-image: url(https://lp-cms-production.imgix.net/2019-06/8ec64b64e1d0805b1101f6c70c7f5b31-tel-aviv.jpg);
  height: 1000px;
}

h1 {
  display: flex;
  font-size: 300px;
}

h2 {
  font-size: 100px;
  margin: -150px;
}

h3 {
  font-size: 50px;
  margin: 150px;
}

.my-projects {
  display: flex;
  height: 800px;
  justify-content: center;
  flex-direction: row;
  align-items: center;
  background: black;
}

h4 {
  font-size: 100px;
  color: green;
}

<div class="nav-bar">
    <a href=#about>About</a>
    <a href=#experience>Experience</a>
    <a href=#contact>Contact</a>
</div>
<div class="full-doc">
  <div class="nav-bar">
    <a href=#about>About</a>
    <a href=#experience>Experience</a>
    <a href=#contact>Contact</a>
  </div>
  <div class="welcome-section">
    <h1>Dillon Melet</h1>
    <h2><u>Copywriter and Editor</u></h2>
    <h3><u>Amateur Coder</u></h3>
  </div>
  <div class="my-projects">
    <h4>These Are Some Of My Projects</h4>
  </div><!DOCTYPE html>
<div class="full-doc">
  <div class="nav-bar">
    <a href=#about>About</a>
    <a href=#experience>Experience</a>
    <a href=#contact>Contact</a>
  </div>
  <div class="welcome-section">
    <h1>Dillon Melet</h1>
    <h2><u>Copywriter and Editor</u></h2>
    <h3><u>Amateur Coder</u></h3>
  </div>
  <div class="my-projects">
    <h4>These Are Some Of My Projects</h4>
  </div>
