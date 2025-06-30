git clone https://github.com/thanit302/my-website.git
cd my-website
@import url('https://fonts.googleapis.com/css2?family=Comic+Relief:wght@400;700&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: whitesmoke;
    font-family:  "Comic Relief", system-ui;;
  }
  
  #gif {
    height: 100%;
    width: 100%;
      cursor: zoom-in;
  }
  
  #gif:active {
      transform: scale3d(1.3,1.3,1.3);
  }
  
  h2 {
    text-align: center;
    font-size: 1.5em;
    color: #e94d58;
    margin: 15px 0;
  }
  #btn-group {
    width: 100%;
    height: 50px;
    display: flex;
    justify-content: center;
    margin-top: 50px;
  }
  button {
    position: absolute;
    width: 150px;
    height: inherit;
    color: white;
    font-size: 1.2em;
    border-radius: 30px;
    outline: none;
    cursor: pointer;
    box-shadow: 0 2px 4px gray;
    border: 2px solid #e94d58;
    font-size: 1.2em;
  }
  button:nth-child(1) {
    margin-left: -200px;
    background: #e94d58;
  }
  button:nth-child(2) {
    margin-right: -200px;
    background: white;
    color: #e94d58;
  }
  
  #no-btn {
    cursor: not-allowed;
  }ading arm.css…]()

git add .
git commit -m "<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div id="wrapper">
    <h2 id="question">Do You Love me? </h2>
    <img
         id="gif"
         alt="gif"
         src="https://media.giphy.com/media/FTGah7Mx3ss04PcasF/giphy.gif"
         />
    <div id="btn-group">
      <button id="yes-btn">Yes</button>
      <button id="no-btn">No</button>
    </div>
  </div>

  <script src="scrips.js"></script>
</body>
</html> "
git push origin main
