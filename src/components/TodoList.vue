<template>
  <div>
    <input type="text" class="todo-input" placeholder="What needs to be done" v-model="newTodo">

    Todo list goes here
  </div>
</template>

<script type="text/javascript">
  export default {
    name: 'todo-list',
    data() {
      return {
        newTodo: '',
        todos: [
          {
            id: 1,
            title: 'Todo1',
            completed: false
          }
        ]
      }
    }
  }
</script>

<style scoped>
/*  h1, h2 {
    font-weight: normal;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }*/

  .todo-input {
    width: 100%;
    padding: 10px 18px;
    font-size: 18px;
    margin-bottom: 16px;


  }


</style>
