<template>
  <div class="wrapper-content wrapper-content--fixed">
    <section class="about">
      <div class="container">
        <h1 class="title">About my blog:</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis ipsa
          facilis quae adipisci fugiat amet necessitatibus cum, officiis veritatis in
          sapiente. Tenetur, mollitia ad temporibus fugiat ipsam cupiditate porro
          consequuntur?
        </p>
        <Intro title="Lorem ipsum dolor sit amet" />
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis ipsa
          facilis quae adipisci fugiat amet necessitatibus cum, officiis veritatis in
          sapiente. Tenetur, mollitia ad temporibus fugiat ipsam cupiditate porro
          consequuntur?
        </p>
        <img src="@/assets/img/about.jpg" alt="" />
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis ipsa
          facilis quae adipisci fugiat amet necessitatibus cum, officiis veritatis in
          sapiente. Tenetur, mollitia ad temporibus fugiat ipsam cupiditate porro
          consequuntur?
        </p>
      </div>
    </section>
  </div>
</template>

<script>
import Intro from "@/components/UI/Intro.vue";
export default {
  components: {
    Intro,
  },
};
</script>

<style lang="scss">
.about {
  text-align: center;
  p {
    margin-bottom: 10px;
  }
}
</style>
