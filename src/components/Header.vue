<template>
    <nav class="header">
      <h1>FashionHub</h1>
      <ul>
        <li><a href="#">Category</a></li>
        <li><a href="#">Brand</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">FAQ's</a></li>
      </ul>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'Header',
  };
  </script>
  
  <style>
  .header {
    display: flex;
    justify-content: space-between;
    padding: 10px 20px;
    background-color: #f8f8f8;
    align-items: center;
  }
  .header ul {
    display: flex;
    gap: 15px;
    list-style-type: none;
  }
  .header ul li a {
    text-decoration: none;
    color: #333;
  }
  </style>
  