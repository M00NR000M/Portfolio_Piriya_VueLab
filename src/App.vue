<template>
  <historys></historys>
  <contacts></contacts>
</template>

<script>
import Historys from "./page/Historys.vue";
import Contacts from "./page/Contacts.vue";
export default {
  name: "App",
  components: {
    Historys: Historys,
    Contacts: Contacts,
  },
};
</script>