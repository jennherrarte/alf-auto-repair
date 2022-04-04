<template>
<div>
<section>
  <NavBar/>
  </section>

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

import NavBar from '@/components/partials/NavBar'
import Header from '@/components/Header'
import About from '@/components/About'
import Services from '@/components/Services'
import Testimonials from '@/components/Testimonials'
import Contact from '@/components/Contact'
import Footer from '@/components/partials/Footer'

export default {
  name: 'IndexPage',

  components: {
    NavBar,
    Header,
    About,
    Services,
    Testimonials,
    Contact,
    Footer
  }
}
</script>
