<template>
    <div>
        <h1>contact us!</h1>
 
         <section>
       <Form/>
    </section>

         <section>
       <Map/>
    </section>

    </div>
</template>

<script>
import Map from '@/components/subcomponents/Form'
import Form from '@/components/subcomponents/Map'

export default {
 

  components: {
    Map,
    Form
  }
}
</script>


<style>
    h1 {
        font-size: 20px;
    }
</style>