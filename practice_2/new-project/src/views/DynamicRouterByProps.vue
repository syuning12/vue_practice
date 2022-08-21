<template>
  <div></div>
</template>

<script>
import axios from 'axios'
export default {
  props: ['a38ff1885b9de491'],
  created () {
    console.log('props', this.id)
    // console.log(this.$route.params.id);
    // const seed = 'a38ff1885b9de491'
    const seed = this.$route.params.id
    axios.get(`https://randomuser.me/api/?seed=${seed}`).then((res) => {
      console.log(res)
    })
  }
}
</script>
