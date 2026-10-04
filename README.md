<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>شات صوتي</title>

<style>
*{box-sizing:border-box}

body{
  margin:0;
  font-family:Arial,sans-serif;
  background:#0d0d16;
  color:white;
}

header{
  padding:20px;
  text-align:center;
  font-size:25px;
  font-weight:bold;
  background:#171725;
}

.room{
  margin:20px auto;
  max-width:600px;
  padding:20px;
}

.card{
  background:#191927;
  border-radius:22px;
  padding:20px;
  margin-bottom:18px;
}

h2{
  margin-top:0;
}

.users{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:12px;
}

.user{
  text-align:center;
  background:#252538;
  border-radius:18px;
  padding:15px 5px;
}

.avatar{
  width:60px;
  height:60px;
  margin:auto;
  border-radius:50%;
  background:#6957e8;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:28px;
}

.status{
  text-align:center;
  color:#aaa;
  margin:15px;
}

.buttons{
  display:flex;
  gap:10px;
  justify-content:center;
  flex-wrap:wrap;
}

button{
  border:0;
  border-radius:15px;
  padding:15px 20px;
  color:white;
  background:#6957e8;
  font-size:16px;
}

button.active{
  background:#e74c3c;
}

input{
  width:100%;
  padding:15px;
  border:0;
  border-radius:12px;
  margin-bottom:10px;
  background:#29293a;
  color:white;
  font-size:16px;
}

.message{
  background:#29293a;
  padding:10px 14px;
  border-radius:12px;
  margin:7px 0;
}
</style>
</head>

<body>

<header>🎙️ شات صوتي</header>

<div class="room">

<div class="card">
<h2>🔊 الغرفة الصوتية</h2>

<div class="users">

<div class="user">
<div class="avatar">👤</div>
<p>أنت</p>
</div>

<div class="user">
<div class="avatar">👨</div>
<p>محمد</p>
</div>

<div class="user">
<div class="avatar">👩</div>
<p>
