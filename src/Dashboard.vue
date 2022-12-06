<template>
    <div class="dashboard">
          <div class="title">Welcome!</div>
    </div>
  </template>
  
  <script>
  import { defineComponent } from 'vue'
  
  export default defineComponent({
    name: 'Dashboard',
  })
  </script>
  
  <style scoped>
  .dashboard{
    padding: 30px 30px 20px;
  }
  
  .title {
    font-size: 24px;
    font-weight: 700;
    margin-bottom: 30px;
  }
  
  .message {
    overflow-wrap: anywhere;
  }
  
  .link {
    color: black;
    text-decoration-color: black;
  }
  </style>