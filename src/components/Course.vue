<template>
  <div class="col-12 col-md-6 offset-md-3 text-center">
    <div class="card">
    <div class="card-body">
      <h4 class="card-title"><b>Nombre Curso: </b>{{ enrolled.courseName }}</h4>
      <h6 class="card-subtitle mb-2 text-muted"><b>Horas: </b>{{ enrolled.courseDurationHours }}</h6>
      <p class="card-text"><b>Role: </b>{{ enrolled.role.roleName }}</p>
    </div>
  </div>
  </div>

</template>

<script>
export default {
  name: "Course",
  props: {
    enrolled: Object
  }
}
</script>

<style scoped>

</style>
