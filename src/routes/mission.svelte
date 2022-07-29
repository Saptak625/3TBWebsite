<script>
	import Navbar from '../components/Navbar.svelte';
    import Footer from '../components/Footer.svelte';
</script>

<svelte:head>
    <title>Our Mission</title>
</svelte:head>


<Navbar/>
<!--Main Document-->
<div class="d-flex flex-column justify-content-center text-center p-4">
    <!--Text-->
    <h1 class="p-2">Our Mission</h1>
    <h3 class="p-2">We aim to destigmaize hearing loss and create a more inclusive society through our "HEAR" principle.</h3>

    <!--HEAR Definition-->
    <div class="card-group w-75 p-4 mx-auto">
      <div class="card text-center py-4">
        <div class="card-body">
          <i class="fa-solid fa-hand-holding-heart fa-3x p-3"></i>
          <h5 class="card-title p-2">Help</h5>
          <p class="card-text p-2">the underprivileged hearing loss community by providing essential equipment and
            materials.</p>
          <a href="#" class="btn btn-primary w-75">Learn how we are fulfilling the Help Pillar!</a>
        </div>
      </div>
      <div class="card text-center py-4">
        <div class="card-body">
          <i class="fa-solid fa-chalkboard-teacher fa-3x p-3"></i>
          <h5 class="card-title p-2">Educate</h5>
          <p class="card-text p-2">youth about different types of hearing loss and how to protect their hearing by
            practicing healthy hearing habits.</p>
          <a href="#" class="btn btn-primary w-75">Learn how we are fulfilling the Educate Pillar!</a>
        </div>
      </div>
      <div class="card text-center py-4">
        <div class="card-body">
          <i class="fa-solid fa-bullhorn fa-3x p-3"></i>
          <h5 class="card-title p-2">Advocate</h5>
          <p class="card-text p-2">for youth with hearing loss to raise awareness and have safer hearing experiences as
            a society.</p>
          <a href="#" class="btn btn-primary w-75">Learn how we are fulfilling the Advocate Pillar!</a>
        </div>
      </div>
      <div class="card text-center py-4">
        <div class="card-body">
          <i class="fa-solid fa-globe fa-3x p-3"></i>
          <h5 class="card-title p-2">Reach</h5>
          <p class="card-text p-2">kids and teens with hearing loss by creating a community to support each other through their challenges.</p>
          <a href="#" class="btn btn-primary w-75">Learn how we are fulfilling the Reach Pillar!</a>
        </div>
      </div>
    </div>
  </div>
<Footer/>