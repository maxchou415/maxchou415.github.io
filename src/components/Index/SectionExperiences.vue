<template>
  <div id="experiences">
    <h1>Employment History</h1>

    <div class="ui styled fluid accordion container">
      <div class="title">
        <div class="ui green horizontal label float-right">San Francisco, CA</div>
        <i class="dropdown icon"></i>
        Miso Technologies Inc. - Software Engineer - Feb. 2020 ~ Present
      </div>
      <div class="content">
        <p class="transition hidden">
          Miso is providing a responsive real-time manner to deliver a deeply contextual feed of the research papers, news articles, blog posts, and open-source repos.
        </p>
        <b>Experience: </b>
        <ul>
          <li>Front-end development with designed product flow from designer and CTO.</li>
          <li>Implemented binary-size-based-jsonline-chunk uploading.</li>
          <li>Implemented frontend layouts, components on Nuxt.js by using Bulma, Pug as template.</li>
        </ul>
      </div>

      <div class="title">
        <div class="ui green horizontal label float-right">Taipei, Taiwan</div>
        <i class="dropdown icon"></i>
        MyProGuide - Lead Software Engineer - Feb. 2019 ~ Oct. 2019
      </div>
      <div class="content">
        <b>Experience: </b>
        <ul>
          <li>Refactored RESTful API, making the loading time <b>250x</b> faster.</li>
          <li>Implemented Micro-service-Mapping-Module to manage Micro-service endpoints.</li>
          <li>Optimized SQL Queries, saving <b>$300 USD</b> per month.</li>
        </ul>
      </div>

      <div class="title">
        <div class="ui green horizontal label float-right">Taipei, Taiwan</div>
        <i class="dropdown icon"></i>
        WeMo Scooter - Software Engineer - Jan. 2018 ~ Nov. 2018
      </div>
      <div class="content">
        <p class="transition hidden">
          WeMo Scooter is a top and most-popular electric scooter rentel company in Taiwan.
        </p>
        <b>Experience: </b>
        <ul>
          <li>Responded for backend development, mainly focused on Scooter maintenance system API. Handled <b>3000+</b> online scooters, and <b>10000+</b> Daily active users.</li>
          <li>Used TypeORM and Sequelize to implement SQL querying, schema management, and migration. (MSSQL and PostgreSQL)</li>
          <li>Implemented a Token-based application using Redis. (Middleware and Management)</li>
          <li>Query parking lots in a certain area by using the PostgreSQL coordinate statement.</li>
          <li>Implemented periodical application by using Crontab.</li>
          <li>Implemented RESTful API using Express.js.</li>
          <li>Migrated applications from AWS to GCP to reduce latency.</li>
        </ul>
      </div>

      <div class="title">
        <div class="ui green horizontal label float-right">San Francisco and Taiwan</div>
        <i class="dropdown icon"></i>
        Mochai - CTO, Startup - Aug. 2017 ~ Jan. 2018
      </div>
      <div class="content">
        <p class="transition hidden">
          Mochai is the first Traditional Chinese Medicine (TCM) analytics platform leveraging machine learning technology that connects consumers and suppliers in the world. Mochai is able to help the consumers analyze and keep their prescriptions so people can have better understandings for their usage of TCM products. Mochai also provides a very cost-effective way for TCM suppliers to generate their product info and to connect with their customers.
        </p>
        <b>Experience: </b>
        <ul>
          <li>Data integration with Machine Learning API.</li>
          <li>Implemented account role-based middleware for each API endpoint.</li>
          <li>Implemented data charts using Chart.js.</li>
          <li>Implemented MVP stage Single-Page-Application using Vue.js.</li>
          <li>Implemented user and data analysis by collecting user events.</li>
          <li>Stored data in MongoDB and used Mongoose to make queries and manage schema using Node.js.</li>
          <li>Conducted Local Market Research in the San Francisco Bay Area.</li>
        </ul>
      </div>

      <div class="title">
        <div class="ui green horizontal label float-right">Taipei, Taiwan</div>
        <i class="dropdown icon"></i>
        BoniO - Software Engineering Intern - Jun. 2015 ~ Sep. 2015
      </div>
      <div class="content">
        <p class="transition hidden">
          BoniO is a EdTech company. One of products of BoniO is "PaGamO" - The World's First Online Gaming Platform for Education.
        </p>
        <b>Experience: </b>
        <ul>
          <li>Implemented back-end with Ruby on rails.</li>
          <li>Implemented front-end with Angular.js.</li>
        </ul>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'SectionExperiences'
}
</script>
<style scoped>
.float-right {
  float: right;
}
</style>
