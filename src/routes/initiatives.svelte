<script>
	import Navbar from '../components/Navbar.svelte';
    import Footer from '../components/Footer.svelte';
</script>

<svelte:head>
    <title>Our Initiatives</title>
</svelte:head>


<Navbar/>
<div class="d-flex flex-column justify-content-center text-center p-4">
    <h1 class="p-2">Initiatives and Campaigns</h1>
    <h5 class="p-2">Learn about what we are doing to fulfill <a href="mission">our "HEAR" principles</a>!</h5>

    <h3 class="pt-4">Latest Initiatives</h3>
    <hr class="mx-auto w-75">

    <div class="d-flex w-75 mx-auto align-items-stretch p-4">
        <div class="card mx-3" style="flex-grow: 1; flex-basis: 0;">
            <img src="/logo.png" class="card-img-top p-4" alt="3TB Logo">
            <div class="card-body">
            <h5 class="card-title">HEAR Better Pledge</h5>
            <p class="card-text">A pledge to healthier hearing built on 4 simple principles: </p>
            <ul class="list-group list-group-flush text-start">
                <li class="list-group-item"><strong>H</strong>earing Safety</li>
                <li class="list-group-item"><strong>E</strong>arplug Usage</li>
                <li class="list-group-item"><strong>A</strong>way from Loud Noises</li>
                <li class="list-group-item"><strong>R</strong>ecognizing Harmful Sounds</li>
            </ul>
            <a href="#" class="btn btn-primary my-3">Learn More</a>
            </div>
        </div>
        <div class="card mx-3" style="flex-grow: 1; flex-basis: 0;">
            <img src="/logo.png" class="card-img-top p-4" alt="3TB Logo">
            <div class="card-body">
            <h5 class="card-title">Safe Hearing Zones</h5>
            <p class="card-text">We believe our ears should be safe wherever we go, for whichever journey we embark on. Safe Hearing Zones exhibit 3 key principles:</p>
            <ul class="list-group list-group-flush text-start">
                <li class="list-group-item">Hearing Safety at Events</li>
                <li class="list-group-item">Hearing Health Education</li>
                <li class="list-group-item">Hearing Support</li>
            </ul>
            <a href="#" class="btn btn-primary my-3">Learn More</a>
            </div>
        </div>
        <div class="card mx-3" style="flex-grow: 1; flex-basis: 0;">
            <img src="/noise_hazards.png" class="card-img-top" alt="Noise Hazards Logo">
            <div class="card-body">
            <h5 class="card-title">Noise Hazards Campaign</h5>
            <p class="card-text">Learn to appreciate the work that our ears do through a series of videos and a video game about 10 common noise hazards we face in our everyday lives such as:</p>
            <ul class="list-group list-group-flush text-start">
                <li class="list-group-item">Fireworks</li>
                <li class="list-group-item">Kitchen Appliances</li>
                <li class="list-group-item">Power Tools</li>
            </ul>
            <a href="#" class="btn btn-primary my-3">Learn More</a>
            </div>
        </div>
    </div>
</div>
<Footer/>