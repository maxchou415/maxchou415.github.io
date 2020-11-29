<template>
  <div>
    <h1>Education</h1>

    <div class="ui card grid container" v-for="school in schools" :key="school.id">
      <div class="ui segment">
        <div class="ui relaxed grid">
          <div class="school-container">
            <div class="logo">
              <img
                :src="require(`@/assets/${school.image}`)"
                :alt="`${school.name} Logo`">
            </div>
            <div class="info">
              <h3>{{school.name}}</h3>
              <div>
                {{school.degree}}
                <span v-if="school.major">, </span>
                {{school.major}}
              </div>
              <p>{{school.period}}</p>
            </div>
            <div class="self-end">
              <h1>{{school.location}}</h1>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      schools: [{
        id: 0,
        name: 'University of London',
        major: 'Computer Science',
        degree: 'Bachelor of Science',
        period: 'Oct. 2020 ~ Present',
        image: 'logo_uol.png',
        location: '🇬🇧'
      }, {
        id: 1,
        name: 'Y Combinator Startup School',
        major: '',
        degree: 'Course',
        period: 'Sep. 2016',
        image: 'logo_yc.svg',
        location: '🇺🇸'
      }]
    }
  }
}
</script>

<style lang="scss" scoped>
.school-container {
  display: flex;
  flex: 1;
  padding: 1.5rem;
  padding-left: 2rem;

  > .logo {
    max-width: 5rem;
    flex-grow: 1;
  }
  > .info {
    padding-left: 2rem;
    flex-grow: 3;
  }
}
</style>
