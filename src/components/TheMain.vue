<template>
  <div class="row row-cols-5">
    
  </div>
</template>

<script>
import axios from 'axios'

export default {
  name: 'TheMain',
  data(){
    return {
      musicList: null
    }
  },
  mounted(){
    axios.get('https://flynn.boolean.careers/exercises/api/array/music')
      .then((resp) => {
        this.musicList = resp.data.response
      })
  }
}
</script>


<style scoped lang="scss">

</style>
