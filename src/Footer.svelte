
   <script>
    let footerLinks = [
      { text: "Home", url: "https://templesofindia.org/" },
      { text: "About Us", url: "https://templesofindia.org/" },
      { text: "Nearby Temples", url: "https://templesofindia.org/" },
      { text: "Download App", url: "https://templesofindia.org/" },
      { text: "Donate to Us", url: "https://templesofindia.org/" }
    ];
  
    let searchLinks = [
      { text: "Watch Video", url: "https://templesofindia.org/" },
      { text: "Disclaimer", url: "https://templesofindia.org/" },
      { text: "Our Blog", url: "https://templesofindia.org/" },
      { text: "Donate for Dharma", url: "https://templesofindia.org/" }
    ];
    let currentYear = new Date().getFullYear();
  </script>
 <main>
  <div class="footer">
    <div class="footer__container">
      <div>
        <h4>Temples of India</h4>
        <p>World's Largest Hindu Temples Portal.</p>
      </div>
  
      <nav class="footer__nav">
        <ul class="footer__nav-list">
          <p>Quick Links</p>
          {#each footerLinks as link}
            <li class="footer__nav-item">
              <a href={link.url} class="footer__nav-link">{link.text}</a>
            </li>
          {/each}
        </ul>
      </nav>
      <nav class="footer__nav">
        <ul class="footer__nav-list">
          <p>Search Temples</p>
          {#each searchLinks as link}
            <li class="footer__nav-item">
              <a href={link.url} class="footer__nav-link">{link.text}</a>
            </li>
          {/each}
        </ul>
      </nav>
      <div class="footer__social">
        <a href="https://templesofindia.org/" class="footer__social-link">
          <i class="material-icons">f</i>
        </a>
        <a href="https://templesofindia.org/" class="footer__social-link">
          <i class="material-icons">in</i>
        </a>
      </div>
    </div>
    <div class="footer__copyright">
      <p class="footer__copyright-text">
        ©Temples of India 2020-{currentYear} | Email: contact@templesofindia.org
      </p>
    </div>
  </div>
</main>
  <style>
    a {
      color: #a50740;
    }
    a:hover {
      color: #333;
    }
    .footer {
      background-color: #ffe240;
      color: #a50740;
      padding: 20px 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      bottom: 0;
      width: 100%;
    }
    .footer__container {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      width: 80%; /* Adjust container width as needed */
      margin: 0 auto;
    }
    .footer__nav {
      display: flex;
    }
    .footer__nav-list {
      list-style: none;
      padding: 0;
      margin: 0;
    }
    .footer__nav-item {
      margin-right: 20px;
    }
    .footer__nav-link {
      text-decoration: none;
      color: #333;
    }
    .footer__social {
      display: flex;
    }
    .footer__social-link {
      margin-right: 10px;
      font-size: 1.2em;
      color: #333;
    }
  
    .footer__copyright {
      margin-top: 20px;
      text-align: center;
    }
  
    .footer__copyright-text {
      font-size: 0.8em;
      color: #333;
    }
    @media screen and (max-width: 768px) {
      .footer__container {
        flex-direction: column;
        align-items: left;
        text-align: left;
      }
  
      .footer__nav {
        justify-content: left;
      }
  
      .footer__nav-item {
        margin: 10px 0;
      }
    }
  </style>
  