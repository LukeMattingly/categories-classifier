<template>
    <div>
      <textarea v-model="inputText"></textarea>
      <button @click="saveInput">Save</button>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        inputText: "",
      };
    },
    methods: {
      saveInput() {
        // Here, you can save the value of inputText to your desired storage location.
        console.log(this.inputText); // Example: log the value to the console
      },
    },
  };
  </script>
  
  <style>
  textarea {
    width: 100%;
    height: 200px;
    padding: 12px;
    font-size: 16px;
    border-radius: 4px;
    border: 1px solid #ccc;
  }
  </style>