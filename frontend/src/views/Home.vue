<template>
  <div class="custom-home">
    <main role="main" class="inner cover">
      <h3 class="cover-heading">To Do List Manager</h3>
      <p class="lead">Click below to manage your to do list</p>
      <p class="lead">
        <router-link pill class="btn btn-lg custom-btn" to="/todolist">Manage list</router-link>
      </p>
      <h3 class="cover-heading">Information Page</h3>
      <p class="lead">Click below to find out what this is about!</p>
      <p class="lead">
        <router-link pill class="btn btn-lg custom-btn" to="/info">Get Info</router-link>
      </p>
    </main>
  </div>
</template>

<script>

export default {
  name: 'home'
}
</script>

