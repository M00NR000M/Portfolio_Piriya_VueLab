<template>
  <ul v-for="history in historys" :key="history.id">
    <li>
      <button>
        {{ history.id }}
        {{ history.Fname }}
        {{ history.Lname }}
        {{ history.Day }}
        {{ history.Old }}
        {{ history.Title }}
      </button>
    </li>
  </ul>
</template>

<script>
export default {
  data: () => ({
    historys: [
      { id: "Profile" },
      { id: "ชื่อ", Fname: "พิรยะ" },
      { id: "นามสกุล", Lname: "ยอดแก้ว" },
      { id: "วันเกิด", Day: "2/05/2000" },
      { id: "อายุ", Old: "21" },
      { id: "ทักษะ" },
      { Title: "C#,C++,Java,SQL,HTML" },
    ],
  }),
};
</script>