<template>
  <TheNavbar/>
  <TheTabs/>
</template>
<script>
import TheNavbar from "@/components/TheNavbar";
import TheTabs from "@/components/TheTabs";

export default {
  name: 'App',
  components: {
    TheTabs,
    TheNavbar,
  }
}
</script>


