<template>
  <div class="wrapper">
    <div class="header">Header</div>
    <div class="wrapper-content">
      <div class="view">
        <div class="container">
          <TweetsList />
          <Facebook />
        </div>
      </div>      
    </div>
    <div class="footer"> <p>Footer</p></div>
  </div>
 
  
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