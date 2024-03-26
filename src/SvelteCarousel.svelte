<script>
    import Carousel from "svelte-carousel";
    const images = [
      {
        url: "https://templesofindia.org/assets/compressed/de57bb046af9aedd4f39566099997f21_942.png",
        description: "image1",
      },
      {
        url: "https://templesofindia.org/assets/compressed/1c9d49ab0497a1ac22bb73c2c681e3e6_942.png",
        description: "image2",
      },
      {
        url: "https://templesofindia.org/assets/compressed/tofi-banner.jpg",
        description: "image3",
      },
      
    ];
    let carousel; // for calling methods of the carousel instance
    const handleNextClick = () => {
      carousel.goToNext();
    };
  </script>
  
  <Carousel
      bind:this={carousel}
      let:loaded
      autoplay
      autoplayDuration={3000}
      autoplayProgressVisible
  >
      {#each images as src, imageIndex (src)}
        <div class="img-container">
          {#if loaded.includes(imageIndex)}
            <img src={src.url} alt={src.description} width={1000} height={500} />
          {/if}
        </div>
      {/each}
  </Carousel>
  