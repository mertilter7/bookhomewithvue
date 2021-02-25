<template>
  <div id="app">
      <header>
        <Navbar></Navbar>
      </header>
        <BookList></BookList>
      
      
  </div>
</template>

<script>
  import Navbar from './components/Navbar';
  import BookList from './components/BookList';

  export default {
    name: 'app',
    components : {
      Navbar,
      BookList
    }
  }
</script>

<style>
 * {
   margin: 0;
   padding: 0;
   box-sizing: border-box;
 }
 body {
   font-family: sans-serif;
 }
 header {
   width: 100vw;
   background-color: plum;
   padding: 15px;
 }
</style>
