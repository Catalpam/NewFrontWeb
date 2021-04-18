<template>
  <div class="diary">
  <diary_calendar />
    <h1>This page is used to store my daily plan and summary of the day (Maybe?) </h1>
    <p> I will also write some daily reflections in this page. I plan to update it once a day in the morning and once a day in the evening. あれ, isn't this a diary?</p>
  </div>
  <router-view/>
</template>


<script>
import diary_calendar from "@/components/calendar.vue";

export default {
    components: {
        diary_calendar,
    }
}
</script>
