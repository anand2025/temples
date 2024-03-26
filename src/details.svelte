<script>
  let templeDetails = {
    name: "Sri Ranganathar Temple",
    deity: "Vishnu",
    location: "Tamil Nadu, Coimbatore, India",
    openTimings: "Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday\n07:00 am - 09:00 am",
    poojaTimings: "NO DATA",
    otherDeities: "NO DATA"
  };
</script>

<main>
  <div class="home">
    <h1>{templeDetails.name}</h1>
    <p>{templeDetails.deity}</p>
    <h3>Location</h3>
    <p><b>{templeDetails.location}</b></p>
    <h3>Open Timings</h3>
    <p>{templeDetails.openTimings}</p>
    <h3>Pooja Timings</h3>
    <p>{templeDetails.poojaTimings}</p>
    <h3>Other Deities</h3>
    <p>{templeDetails.otherDeities}</p>
  </div>
</main>

<style>
  h3 {
    color: #a50740;
  }

  p {
    color: #000;
  }

  .home {
    margin-left: 10%;
    margin-right: 20%;
  }
</style>

  