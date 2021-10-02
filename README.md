# FIRST WEBPAGE CREATED BY CODING!!
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Healthy Living</title>
    <style>
      body {
        font-family: Cerebri Sans, Helvetica, Arial, sans-serif;
      }
      section {
        margin: 120px 0;
      }
      h2 {
        font-weight: 900;
        color: black;
        font-size: 32px;
        line-height: 48px;
        margin: 0;
        text-align: center;
        padding: 0 0 24px;
      }
      h1 {
        color: greenyellow;
        text-align: center;
        font-size: 38px;
      }
      p2 {
        font-size: 18px;
        line-height: 30px;
        font-family: PT Mono, monospace;
        text-align: center;
      }
      button {
        border-radius: 25px;
        margin: 0 auto;
        display: block;
        background-color: orange;
        border: 1px solid #885df1;
        color: black;
        font-size: 16px;
        line-height: 22px;
        padding: 16px 24px;
        text-decoration: none;
        transition: all 200ms ease;
      }
      button:hover {
        color: #fff;
        background: #885df1;
        cursor: pointer;
      }
      footer {
        text-align: center;
        color: rgb(109, 36, 109);
        font-size: 17px;
      }
      .marginauto {
        margin: 10px auto 20px;
        display: block;
      }
    </style>
  </head>
  <body>
    <h1>Balanced Diet</h1>
    <h2>Best way to Healthy Living🎯</h2>
    <p1>
      <div>
        <img
          class="marginauto"
          src="https://s3.amazonaws.com/shecodesio-production/uploads/files/000/018/126/original/666.png?1633204610"
          alt="balance diet picture"
        />
      </div>
    </p1>
    <br />
    <p2>
      A balanced diet is a diet that contains differing kinds of foods in
      certain quantities and proportions so that the requirement for calories,
      proteins, minerals, vitamins and alternative nutrients is adequate and a
      small provision is reserved for additional nutrients to endure the short
      length of leanness.
      <br />
      <a href="https://www.healthline.com/health/balanced-diet"
        >Learn more about balanced Diet</a
      >
      <br />
      <button class="download-button">Download Your Free Diet Chart💪🏼</button>
      <br />
      <footer>"Page created by Priya.Lalani"🍁</footer>
    </p2>
    <script>
      function download() {
        let name = prompt("what is your name?");
        let email = prompt("what is your email address?");
        alert(
          "Thank you" +
            " " +
            name +
            "😎" +
            ",We will email your chart soon,Meanwhile eat healthy." +
            "🍀"
        );
      }
      let downloadButton = document.querySelector(".download-button");
      downloadButton.addEventListener("click", download);
    </script>
  </body>
</html>
