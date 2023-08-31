<div class="container">
  <div class="align">
    <div class="header">PORTFOLIO</div>
    <div class="vertical-text">
      <p>Srinakharinwirot University <br> Pattaraporn Nophirun </p>
    </div>
    <div class="image_home">
      <img src="static\test.png" alt="home" width="1225" height="685"/>
    </div>
  </div>
</div>

<style>
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100%;
  }

  .vertical-text {
    display: inline-block;
    text-align: left;
    writing-mode: vertical-lr;
    transform: rotate(180deg);
    transform-origin: bottom;
    font-size: 24px;
    position: absolute;
    left: 2%;
    top: 35%;
  }

  .header {
    position: absolute;
    display: inline-block;
    font-size: 18em;
    font-family: 'Times New Roman', Times, serif;
    letter-spacing: 10px;
    top: 1%;
    right: 0%;
    z-index: 2;
  }

  .image_home {
    position: absolute;
    right: 0%;
    bottom: 0%;
  }
</style>
