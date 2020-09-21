<template>
  <div class="home">
    <Counter 
    :year ="2020"
    :month="11"
    :date="16"
    :hour="10"
    :minute="10"
    :second="12"
    :millisecond="14"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Counter from "@/components/Counter.vue";
export default {
  name: "Home",
  components: {
    Counter
  }
};
</script>
