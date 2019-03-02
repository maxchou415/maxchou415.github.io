<template>
  <div id="projects">
    <h1>Projects</h1>
    <h3>Startup Project</h3>

    <div class="ui link doubling stackable cards">
      <div class="card">
        <div class="image">
          <img src="https://i.imgur.com/Vnl5nzs.png">
        </div>
        <div class="content">
          <div class="header">Mochai</div>
          <div class="meta">
            <a>Startup</a>
          </div>
          <div class="description">
            Mochai is the first Traditional Chinese Medicine (TCM) analytics platform leveraging machine learning technology that connects consumers and suppliers in the world. 
          </div>
        </div>
        <div class="extra content">
          <span class="left floated">
            2017
          </span>
          <span class="right floated">
            <a class="mini ui green button" href="https://mochai.io/" target="_blank">Go</a>
          </span>
        </div>
      </div>
      <div class="card">
        <div class="image">
          <img src="https://i.imgur.com/7DVmLsS.png">
        </div>
        <div class="content">
          <div class="header">Silicon Trip</div>
          <div class="meta">
            <span class="date">Startup</span>
          </div>
          <div class="description">
            Silicon Trip is a NPO for run event for junior/high school student who located in Taiwan. We will let them has more sense that know how Silicon Valley works and attend for Two days Hackathon.
            All of students will learn team work, new technologies, and how Silicon Valley works while in the 3 days event.
          </div>
        </div>
        <div class="extra content">
          <span class="left floated">
            2016
          </span>
          <span class="right floated">
            <button class="mini ui red button">No longer available</button>
          </span>
        </div>
      </div>
    </div>
    
    <h3>Open Source Project</h3>
    <div class="ui link doubling stackable cards">
      <div class="card">
        <div class="image">
          <img src="https://i.imgur.com/s3t6Hpx.png">
        </div>
        <div class="content">
          <div class="header">Node-EnvChecker</div>
          <div class="meta">
            <a>Open Source Tool</a>
          </div>
          <div class="description">
            A easy way to check required environment variables but which is lost.
          </div>
        </div>
        <div class="extra content">
          <span class="left floated">
            2018
          </span>
          <span class="right floated">
            <a class="mini ui green button" href="https://www.npmjs.com/package/node-envchecker" target="_blank">Go</a>
          </span>
        </div>
      </div>
    </div>

    <h3>Just for FUN Project</h3>
    <div class="ui link doubling stackable cards">
      <div class="card">
        <div class="image">
          <img src="https://images.pexels.com/photos/277559/pexels-photo-277559.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260">
        </div>
        <div class="content">
          <div class="header">IoTDoorControl</div>
          <div class="meta">
            <a>Open Source Tool</a>
          </div>
          <div class="description">
            Most of apartment in Taiwan has intercom for communicate with someone who at the Lobby. They do go with remote door open function; A button located on intercom. But They can not trigger the function by internet, so you can not open the door everywhere, even at home.
          </div>
        </div>
        <div class="extra content">
          <span class="left floated">
            2018
          </span>
          <span class="right floated">
            <a class="mini ui green button" href="https://github.com/maxchou415/IoTDoorControl-Server" target="_blank">Go</a>
          </span>
        </div>
      </div>

      <div class="card">
        <div class="image">
          <img src="https://images.pexels.com/photos/96380/pexels-photo-96380.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260">
        </div>
        <div class="content">
          <div class="header">CKHC Sheet Management Platform</div>
          <div class="meta">
            <a>Open Source Tool</a>
          </div>
          <div class="description">
            Sheet management platform of Chien Kuo High School Harmonica Club.
          </div>
        </div>
        <div class="extra content">
          <span class="left floated">
            2018
          </span>
          <span class="right floated">
            <a class="mini ui green button" href="https://github.com/maxchou415/CKHC-Sheet-API" target="_blank">Go</a>
          </span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SectionProjects'
}
</script>
