<template>
  <div class="light">
    <Header />
    <main id="main">
      <section id="scriptCont">
        <div class="container">
          <WrapTitle name1="Script" name2="Reference" />
          <div class="script__cont"></div>
        </div>
      </section>
      <ContInfo />
    </main>
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';
import WrapTitle from '@/components/WrapTitle.vue';
import ContInfo from '@/components/ContInfo.vue';

export default {
  components: {
    Header,
    Footer,
    WrapTitle,
    ContInfo,
  },
};
</script>

<style lang="scss">
#scriptCont {
  background-color: #000;
  color: #fff;
}
</style>
