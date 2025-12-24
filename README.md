<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Music Player UI</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:Arial, sans-serif;
}

body{
  background:#121212;
  height:100vh;
  display:flex;
  justify-content:center;
  align-items:center;
}

.player{
  background:#1f1f1f;
  width:320px;
  padding:25px;
  border-radius:20px;
  text-align:center;
  box-shadow:0 10px 30px rgba(0,0,0,0.6);
}

.player img{
  width:100%;
  border-radius:15px;
}

.player h3{
  margin-top:15px;
  color:#fff;
}

.player p{
  color:#aaa;
  font-size:14px;
  margin-bottom:15px;
}

/* Progress bar */
.progress{
  width:100%;
  height:6px;
  background:#333;
  border-radius:5px;
  overflow:hidden;
  margin-bottom:20px;
}

.progress span{
  display:block;
  width:60%;
  height:100%;
  background:#1db954;
}

/* Controls */
.controls{
  display:flex;
  justify-content:center;
  gap:15px;
}

.controls button{
  width:45px;
  height:45px;
  border-radius:50%;
  border:none;
  background:#333;
  color:#fff;
  font-size:18px;
  cursor:pointer;
  transition:0.3s;
}

.controls button:hover{
  background:#1db954;
  transform:scale(1.1);
}
</style>
</head>

<body>

<div class="player">
  <img src="https://via.placeholder.com/300" alt="Album Art">
  <h3>Song Title</h3>
  <p>Artist Name</p>

  <div class="progress">
    <span></span>
  </div>

  <div class="controls">
    <button>⏮</button>
    <button>▶</button>
    <button>⏭</button>
  </div>
</div>

</body>
</html>
