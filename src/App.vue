<template>
  <p>123</p>
  <TweetsList />
  <Facebook />
</template>

<script>
import List from './components/List'
import Facebook from '@/components/Facebook'
export default{
  components: {
    TweetsList: List,
    Facebook
  }
}
</script>