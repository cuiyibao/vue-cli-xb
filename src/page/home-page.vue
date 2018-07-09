<template>
  <div>
    <h1>{{title}}</h1>
    <todo-list></todo-list>
    <ul>
      <li v-for="(item, index) in dataList">id: {{item.id}} , name: {{item.name}}</li>
    </ul>
  </div>
</template>

<script>
import TodoList from '@/components/todo-list'
import {tree} from '../network/mock/tree'
export default {
  data() {
    return {
      title: '首页',
      dataList: []
    }
  },
  components:{
    TodoList
  },
  created() {
    this.dataList = tree.data
  }
}
</script>

<style lang="scss" scoped>
</style>
