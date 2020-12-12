<template>
  <div class="wrapper-content wrapper-content--fixed">
    <div class="container">
      <Promo />
      <Intro title="My last posts:" />
      <!-- posts -->
      <PostsList :posts="posts" />
      <!-- contacts -->
      <Contacts />
    </div>
  </div>
</template>

<script>
import Promo from "@/components/Promo.vue";
import Intro from "@/components/UI/Intro.vue";
import PostsList from "@/components/blog/PostsList.vue";
import Contacts from '@/components/Contacts.vue';

export default {
  components: {
    Contacts,
    PostsList,
    Intro,
    Promo,
  },
  data() {
    return {
      posts: [
        {
          id: 1,
          title: "1 post",
          descr: "Lorem ipsum dolor sit amet consectetur adipisicing elit",
          img:
            "https://images.pexels.com/photos/3690511/pexels-photo-3690511.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
        },
        {
          id: 2,
          title: "2 post",
          descr: "Lorem ipsum dolor sit amet consectetur adipisicing elit",
          img:
            "https://images.pexels.com/photos/4666751/pexels-photo-4666751.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
        },
        {
          id: 3,
          title: "3 post",
          descr: "Lorem ipsum dolor sit amet consectetur adipisicing elit",
          img:
            "https://images.pexels.com/photos/1894350/pexels-photo-1894350.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500",
        },
      ],
    };
  },
};
</script>
