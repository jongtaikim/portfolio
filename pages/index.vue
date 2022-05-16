<template>
  <div class="container">
    <div class="text-center">
      <strong style="font-size:40px">{{count}}</strong>
       <div>
         <button 
          type="button" 
          @click="count++" 
          class="border-1 rounded bg-gray-100 p-3"
          >
          +증가
          </button>
       </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      count: 0
    }
  }
}
</script>

<style>
  .container {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
  }
</style>