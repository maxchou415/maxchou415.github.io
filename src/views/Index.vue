<template>
  <div class="ui stackable container grid">
    <div class="ui four wide column">
      <div class="left-block">
        <NameCard />

        <div class="space">
          <p>&nbsp;</p>
        </div>

        <Menu />

        <div class="space">
          <p>&nbsp;</p>
        </div>

        <div class="ui container">
          <div class="ui segment">
            <div class="extra content">
              <h4>I love/interest in:</h4>
              <ul>
                <li>Talk with who has self-starter.</li>
                <li>Do something with a reasonable/philosophical reason.</li>
              </ul>

              <h4>I hate:</h4>
              <ul>
                <li>Talk, cowork with who are not match <b>I love/interest in</b> field.</li>
                <li>Who is wasting my time.</li>
              </ul>
            </div>
          </div>
        </div>

        <div class="space">
          <p>&nbsp;</p>
        </div>

        <div class="ui container">
          <div class="ui segment">
            Last modified: Sun, 3 Mar 2019 06:05:08 +0000
          </div>
        </div>

      </div>
    </div>
    <div class="ui twelve wide column">
      <SectionAbout />

      <div class="space">
        <p>&nbsp;</p>
      </div>

      <SectionExperiences />

      <div class="space">
        <p>&nbsp;</p>
      </div>

      <SectionProjects />
    </div>
  </div>
</template>

<script>
import NameCard from '@/components/Index/NameCard'
import Menu from '@/components/Index/Menu'

// Sections
import SectionAbout from '@/components/Index/SectionAbout'
import SectionExperiences from '@/components/Index/SectionExperiences'
import SectionProjects from '@/components/Index/SectionProjects'

export default {
  name: 'index',
  components: {
    NameCard,
    Menu,

    SectionAbout,
    SectionExperiences,
    SectionProjects
  }
}
</script>

<style scoped>
</style>
