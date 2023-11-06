<template>
  <div class="todolist">
    <div class="todo-header">
      <h1 class="title">Список задач</h1>
      <input class="todo-inputtype" tipe="text" placeholder="укажите задачу"/>
      <button class="btn">+</button>
    </div>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'

export default {
  //name: 'App',
  date(){
    return{
      title:"Разработка приложения TodoList",
      number:0,
    };
  },
  methods:{
    addNumber(){

    },
  },
  // components: {
  //   HelloWorld
  // }
};
</script>

<style scope>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body{
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  background: linear-gradient(#21b8ba,#0ad077);
  background-repeat: no-repeat;
}
#app{
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 100px;
  margin-top: 75px;
}
.title{
  margin-top: 20px;
  font-size: 32px;
  text-align: center;
  margin-bottom: 30px;
}
.todo-inputtype{
  padding: 10px 20px;
  border: 1px solid #ccc;
  border-radius: 20px;
  width: 300px;
}
.btn{
  font-size: 40px;
  padding: 10px;
  border-radius: 50%;
}

</style>
