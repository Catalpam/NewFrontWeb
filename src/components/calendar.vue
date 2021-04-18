<template >
  <el-calendar>
    <template #dateCell="{ data }">
      <p
        :class="data.isSelected ? 'is-selected' : ''"
        @click="calendarOnClick(data)"
      >
        {{ data.isSelected ? "✔️" : "" }}
        {{ data.day.split("-").slice(1).join("月") + "日" }}
      </p>
    </template>
  </el-calendar>
</template>


<script>
export default {
  name: "diary_calendar",
  data() {
    return {
      value: new Date(),
    };
  },
  methods: {
    calendarOnClick(data) {
        console.table(data.day.constructor)
        this.$router.push({ 
            path: `/diary/${data.day}` ,
        });
        this.$notify({
          title: '芜湖起飞！',
          message: `成功切换至${data.day}的每日随便写。`,
          type: 'success'
        });

    },
  },
};
</script>

<style>
.is-selected {
  color: #1989fa;
}
</style>

