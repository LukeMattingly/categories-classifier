<template>
    <div class="category">
      <h1>This is an category page</h1>
      <p style="white-space: pre-line;">{{ message }}</p>
      <textarea v-model="message" placeholder="add multiple lines"></textarea>

    </div>
  </template>
  
  <style>
  @media (min-width: 1024px) {
    .category {
      min-height: 100vh;
      display: flex;
      align-items: center;
    }
  }
  </style>
  