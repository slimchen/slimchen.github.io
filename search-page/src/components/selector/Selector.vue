<template>
    <el-select v-model="value" filterable :placeholder="select.name" @change="change">
    <el-option
      v-for="item in this.select.data"
      :key="item.value"
      :label="item.label"
      :value="item.value">
    </el-option>
  </el-select>
</template>

<script>
    export default {
        name: "Selector",
        data() {
      return {
        value: ''
      }
    },
    computed:{
        get(){
            this.select.result && this.select.change(this.select.result)
            return this.select.result
        },
        set(){

        }
    },
    props: {
        select:Object
    },
    methods:{
        change(val){
            console.log(val)
            this.select.result = val
            this.select.change && this.select.change(this.buildChildern(val))
        },
        buildChildern(val){
            let data = this.select.data.find(item=>{
                return item.value==val
            })

            return data.children
        }
    }
    }
</script>

<style scoped>
</style>