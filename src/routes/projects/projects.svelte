<div class="container">
    <div class="top">
        <div class="project-image" >
            <img src="static\1.png" alt="project">
        </div>
    </div>
    <div class="middle">
        <div class="project-description">
            <div style="font-family: 'Times New Roman', Times, serif;font-size: 3em;letter-spacing: 5px;">M!n! project</div>
            <p>Portfolio template m!n! project <br> by laylico store</p>
        </div>
    </div>
    <div class="bottom">
        <div class="project-image">
            <img src="static\3.png" alt="project">
        </div>
    </div>
</div>

<!-- Can u go decorate by yourself. changing image add padding or margin something -->

<style>
    .container {
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      align-items: center;
      width: 100%;
      height: 100;
    }

    .bottom {
        position: absolute;
        bottom: 0%;
    }

    .top {
        position: absolute;
        top: 0%;
    }

    .middle {
        position: absolute;
        flex: 2;
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
        font-size: 120%;
        top: 38%;
    }

    .project-image {
        max-width: 100%;
        max-height: 100%;
    }

    .project-description {
        text-align: center;
        padding: 2rem;
    }
</style>