<template>
   <div>
      <h1> {{ title }}</h1>
      <h2> {{ subtitle }}</h2>
      <ul>
         <li> {{ items[0] }}</li>
         <li> {{ items[1] }}</li>
         <li> {{ items[2] }}</li>
      </ul>
   </div>
</template>

<style lang="scss" scoped>
@import '../styles/typography';

h1 {
   font-size: 50px;
   color: $color-blue;
}
</style>

<script>
export default {
   data() {
      return {
         title: 'A list component',
         subtitle: 'A subtitle',
         items: ["Cap", "Blue", "Ship"]
      }
   }
}
</script>
