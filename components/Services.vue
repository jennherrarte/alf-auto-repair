<template>
    <div class="services">
        <h1>Services</h1>
 
         <section>
       <Service/>
    </section>

    </div>
</template>

<script>
import Service from '@/components/subcomponents/Service'

export default {
 

  components: {
    Service
  }
}
</script>


<style lang="scss">
    .services {
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding-left: 150px;
      padding-right: 150px;
      text-align: center;
    }
</style>