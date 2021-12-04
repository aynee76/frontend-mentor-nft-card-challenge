## Welcome to GitHub Pages

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  <link rel="stylesheet" href="./style.css">
  <title>Frontend Mentor | NFT preview card component</title>

  <link rel="stylesheet" href="https://fonts.google.com/specimen/Outfit">

  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>
    .attribution {
      font-size: 11px;
      text-align: center;
    }


    .attribution a {
      color: hsl(228, 45%, 44%);
    }
  </style>
</head>

<body>

  Equilibrium #3429

  Our Equilibrium collection promotes balance and calm.

  0.041 ETH
  3 days left

  Creation of Jules Wyvern

  <!--start-->
  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
    Coded by <a href="#">zainab Abdulmumin</a>.
  </div>

  <!--nft starts here-->
  <main>
    <div id="mobile">
      <div class="img-section">
        <div class="eye"><img src="images/eye-fill.svg" alt="">
        </div>
      </div>
      <!--paragraphs-->
      <div class="wrapper">
        <div>
          <p class="fp">Equilibrum #3429</p>
          <p class="sp">Our Equilibrum collection promotes balance and calm</p>
        </div>
        <!--icons here-->
        <div class="icons">
          <div class="icontag"><img src="images/icon-ethereum.svg"> <span>0.041ETH</span>
          </div>
          <div class="icontag"><img src="images/icon-clock.svg">
            <span>3 days left</span>
          </div>
          <!--line here-->
        </div>
        <div class="line">
        </div>
        <!--avatar here-->
        <div class="avatar">
          <img src="images/image-avatar.png" class="avatar">
          <p><span>Creation of</span> <span>Jules Wyvern</span></p>
        </div>
      </div>
    </div>

  </main>
</body>

</html>


