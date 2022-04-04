<template>
<div>
<section>
  <Header/>
  </section>



      <section>
  <About/>
    </section>


      <section>
  <Services/>
    </section>

          <section>
  <Testimonials/>
    </section>

       <section>
  <Contact/>
    </section>

        <section>
  <Footer/>
    </section>

</div>
</template>

<script>

import Header from '@/components/Header'
import About from '@/components/About'
import Services from '@/components/Services'
import Testimonials from '@/components/Testimonials'
import Contact from '@/components/Contact'
import Footer from '@/components/partials/Footer'

export default {
  name: 'IndexPage',

  components: {
    Header,
    About,
    Services,
    Testimonials,
    Contact,
    Footer
  }
}
</script>
