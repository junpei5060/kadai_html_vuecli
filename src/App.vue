<template>
  <div class="all">
  <Header></Header>
  <TopImage></TopImage>
  <About></About>
  <Course></Course>
  <News></News>
  <Access></Access>
  <Contact></Contact>
  <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import About from './components/About.vue';
import Course from './components/Course.vue';
import TopImage from './components/TopImage.vue';
import News from './components/News.vue';
import Access from './components/Access.vue';
import Contact from './components/Contact.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',

  components: {
    Header,
    TopImage,
    About,
    Course,
    News,
    Access,
    Contact,
    Footer
  },

  data: () => ({
    //
  }),
};
</script>

<style>
.all{
  margin: 0 auto;
  width: 1200px;
}
</style>