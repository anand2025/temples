<script>
    let isOpen = false;
  
    function toggleDetails() {
      isOpen = !isOpen;
    }
  </script>
  <main>
  <section class="temple-details">
    <button on:click={toggleDetails} tabIndex="0">
      Special Features
    </button>
    <div class="details" style="{ isOpen ? 'display: block' : 'display: none' }">
      <p><b>Foundation Year</b></p>
      <p>500-1000 years old</p>
      <p><b>Sthala Tree</b></p>
      <p><b>Theertham</b></p>
      <p>Palsunai, Padma theertham, Sengothai Sunai, Kannimar Sunai, Pasumani Sunai</p>
      <p><b>Ratham</b></p>
      <p><b>Architecture</b></p>
      <p>Dravidian Architecture</p>
      <p><b>Other Speciality</b></p>
      <p>All merciful Lord Ranganatha appears in a standing form facing east pleasing the mind of His devotees.</p>
      <hr>
    </div>
  </section>
  <section class="temple-details">
    <button on:click={toggleDetails} tabIndex="0">
      Sthala Puran
    </button>
    <div class="details" style="{ isOpen ? 'display: block' : 'display: none' }">
    <p>Maharshi Kalava was in penance for a quite number of years to have the darshan of Lord Narayana.  One Durmadhan, son of a Gandarva Viswasu by name was bathing in the tank with his wives.  Maharshi Vasishta was returning from Mount Kailash after a darshan of Lord Shiva.  Seeing the sage, Durmadha’s wives stopped bathing and came out of the tank in respect to the sage.  But Durmadha continued bathing nude.  Angry Vasishta cursed Dhurmada to be born a demon.  The wives fell at the feet of Sage Vasishta and begged for relief.  Responding to their prayer, sage said that their husband would be back to them in a short time.</p>
    <hr>
    </div>
  </section>
  <section class="temple-details">
    <button on:click={toggleDetails} tabIndex="0">
      Architecture
    </button>
    <div class="details" style="{ isOpen ? 'display: block' : 'display: none' }">
    <p>All merciful Lord Ranganatha appears in a standing form facing east pleasing the mind of His devotees.  Thumbikkai Azhwar and Mother grace the devotees from their respective shrines.  Adequate space is created around the temple to facilitate car festival and movement of devotees during festival times.  Many visit the temple frequently as the environment and the climate are helpful to keep them healthy and free from any disease.  Irulars, a tribal community are living near the temple.  The car of the temple is aesthetically made by skilled craftsmen.</p>
    <p>The devotee crowd is huge on new moon days and Saturdays.  There are shrines for Lord Vinayaka, Sri Anjaneya and Acharya Sri Ramanuja.</p>
    <hr>
    </div>
  </section>
  <section class="temple-details">
    <button on:click={toggleDetails} tabIndex="0">
      Alankar of Deity
    </button>
    <div class="details" style="{ isOpen ? 'display: block' : 'display: none' }">
    
    </div>
  </section>
  <section class="temple-details">
    <button on:click={toggleDetails} tabIndex="0">
      Prayers and Benefits
    </button>
    <div class="details" style="{ isOpen ? 'display: block' : 'display: none' }">
    <p><b>Special Vratas and Prayers</b></p>
    <p>Those facing the impact of some curses pray for relief.</p>
    <p><b>Offerings to Deity</b></p>
    <p>Devotees perform Tirumanjanam to Lord and Mother with sweet pudding-sarkarai pongal nivedhana.</p>
    <p><b>Stotras and Mantras</b></p>
    <hr>
    </div>
  </section>
  <section class="temple-details">
    <button on:click={toggleDetails} tabIndex="0">
      Festivals
    </button>
    <div class="details" style="{ isOpen ? 'display: block' : 'display: none' }">
    <p>Car festival is celebrated in the temple on Chitra Poornima day in April-May.</p>
    <hr>
    </div>
  </section>
  <section class="temple-details">
    <button on:click={toggleDetails} tabIndex="0">
      Sodasha Upcharas
    </button>
    <div class="details" style="{ isOpen ? 'display: block' : 'display: none' }">
    <hr>
    </div>
  </section>
  <section class="temple-details">
    <button on:click={toggleDetails} tabIndex="0">
      Prasadhas
    </button>
    <div class="details" style="{ isOpen ? 'display: block' : 'display: none' }">
      <hr>
    </div>
  </section>
  <section class="temple-details">
    <button on:click={toggleDetails} tabIndex="0">
      Social Activities
    </button>
    <div class="details" style="{ isOpen ? 'display: block' : 'display: none' }">
    <p><b>Annadhan</b></p>
    <p><b>Marriage</b></p>
    <p><b>Ear Boring</b></p>
    <p><b>Head Shave</b></p>
    <p><b>Danaas</b></p>
    <p><b>Education Facilities</b></p>
    <p><b>Social Drives</b></p>
    <p><b>Other Activities</b></p>
    <hr>
    </div>
  </section>
  <section class="temple-details">
    <button on:click={toggleDetails} tabIndex="0">
      Arjita Seva
    </button>
    <div class="details" style="{ isOpen ? 'display: block' : 'display: none' }">
    <hr>
    </div>
  </section>
</main>
  <style>
    button{
      border: none;
      font-size: large;
      font-weight: 650;
      color: #a50740;
      background-color: #fff;
    }
    .temple-details {
      padding: 20px;
      margin-left: 8%;
      cursor: pointer;
    }
  
    .details {
      margin-top: 10px;
    }
  </style>
  