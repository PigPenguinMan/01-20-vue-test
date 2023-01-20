<script >
 export default{ 
  data() {
    return{
      count : 5
    }
  },
  methods: {
    increment(){
      this.count ++ 
    }
  }
}
</script>

<template>
  <h1>{{ count }}</h1>
  <h3>vue로 확인하는 웹페이지 입니다 . 아래버튼을 누르면 값이 1씩 증가합니다</h3>
  <button v-on:click="increment"> 1+ </button>
</template>

<style >
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

