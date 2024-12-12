<template>
  <div>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Cart</a></li>
      </ul>
    </nav>
    <h1>Welcome to HelloWorld Component</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
};
</script>

<style>
/* Simple navigation styling */
nav ul {
  list-style-type: none;
  display: flex;
  gap: 10px;
}
button {
  margin: 5px;
}
h1 {
  font-size: 1.5rem;
  color: #333;
}
</style>