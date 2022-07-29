<script>
	import Navbar from '../components/Navbar.svelte';
    import Footer from '../components/Footer.svelte';
</script>

<Navbar/>
<!--Banner-->
<div class="d-block container-fluid" style="background-color: orange;">
    <div class="row p-5">
      <div class="d-inline col">
        <h1>WE AIM TO REACH EVERY EAR</h1>
        <hr>
        <h5 class="pt-4 pb-4">3 Tiny Bones is a student-led 501(c)(3) nonprofit destigmatizing hearing loss and
          educating communities on healthy hearing to create a more inclusive society. We’re also helping deaf/hard of
          hearing youth to overcome their challenges and connect with one another.</h5>
        <a href="mission.html" role="button" class="mt-5 btn btn-lg btn-primary">Read Our Mission Statement
        </a>
      </div>
      <div class="d-inline col d-flex justify-content-center p-3">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/DmF2OKm8IU4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
        </iframe>
      </div>
    </div>
  </div>

  <!--Main Body-->
  <div class="row py-4">
    <div class="col">
      <!--Other Content-->
      <div style="background-color: teal;">
        <div class="row p-3">
          <div class="d-inline col d-flex justify-content-center p-3">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/zrmsdmKJl9g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
          <div class="col">
            <h1>Our Pledge</h1>
            <hr>
            <h5 class="pt-4 pb-4">Enter some content for the pledge and why they should do it here.</h5>
            <a href="#" role="button" class="mt-5 btn btn-lg btn-primary">Take the Pledge
            </a>
          </div>
        </div>
      </div>
    </div>
    <div class="col-md-auto px-4 overflow-auto">
      <!--Twitter Content-->
      <a class="twitter-timeline" href="https://twitter.com/3tinybones?ref_src=twsrc%5Etfw">Tweets by 3tinybones</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
    </div>
  </div>
<Footer/>