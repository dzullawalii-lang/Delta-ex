# Delta-ex
D
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Break In 1 Script Share</title>

<style>
body{
    margin:0;
    padding:0;
    font-family:Arial, sans-serif;
    background:#050816;
    overflow:hidden;
    color:white;
}

.bg{
    position:fixed;
    width:100%;
    height:100%;
    background:
    radial-gradient(circle at top,#00aeff33,transparent 40%),
    radial-gradient(circle at bottom,#0066ff22,transparent 40%),
    #050816;
    animation:bgmove 6s infinite alternate;
}

@keyframes bgmove{
    0%{filter:hue-rotate(0deg);}
    100%{filter:hue-rotate(40deg);}
}

.container{
    position:relative;
    z-index:2;
    width:90%;
    max-width:900px;
    margin:40px auto;
    background:rgba(10,10,20,0.95);
    border:2px solid #00aaff;
    border-radius:20px;
    padding:20px;
    box-shadow:0 0 25px #00aaff;
}

.title{
    text-align:center;
    font-size:35px;
    color:#00bfff;
    text-shadow:0 0 15px #00bfff;
    margin-bottom:10px;
}

.desc{
    text-align:center;
    color:#aaa;
    margin-bottom:25px;
}

.codebox{
    background:#000;
    border:1px solid #00aaff;
    border-radius:15px;
    padding:15px;
    overflow:auto;
    max-height:500px;
}

pre{
    color:#00ff88;
    white-space:pre-wrap;
    font-size:14px;
}

button{
    margin-top:20px;
    width:100%;
    padding:14px;
    font-size:17px;
    border:none;
    border-radius:12px;
    background:#00aaff;
    color:white;
    cursor:pointer;
    transition:0.3s;
    font-weight:bold;
}

button:hover{
    background:#0088cc;
    transform:scale(1.02);
    box-shadow:0 0 20px #00aaff;
}

.footer{
    text-align:center;
    margin-top:20px;
    color:#666;
    font-size:13px;
}

.glow{
    animation:glow 2s infinite alternate;
}

@keyframes glow{
    from{text-shadow:0 0 10px #00aaff;}
    to{text-shadow:0 0 25px #00eeff;}
}
</style>
</head>

<body>

<div class="bg"></div>

<div class="container">

<div class="title glow">BREAK IN 1 CHEAT</div>

<div class="desc">
Simple Food Spawner GUI Script | Delta Executor
</div>

<div class="codebox">
<pre id="script">
-- Script Cheat Break In 1 | Delta Executor
-- Simple Food Spawner dengan GUI

local Players = game:GetService("Players")
local player = Players.LocalPlayer
local mouse = player:GetMouse()

local gui = Instance.new("ScreenGui")
gui.Name = "CheatGui"
gui.ResetOnSpawn = false
gui.Parent = player:WaitForChild("PlayerGui")

local frame = Instance.new("Frame")
frame.Name = "MainFrame"
frame.Size = UDim2.new(0, 250, 0, 150)
frame.Position = UDim2.new(0, 20, 0, 20)
frame.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
frame.BorderSizePixel = 0
frame.Parent = gui
frame.Active = true
frame.Draggable = true

local title = Instance.new("TextLabel")
title.Text = "BREAK IN 1 CHEAT"
title.Size = UDim2.new(1, 0, 0, 30)
title.BackgroundColor3 = Color3.fromRGB(0, 100, 200)
title.TextColor3 = Color3.new(1, 1, 1)
title.Parent = frame

local spawnBtn = Instance.new("TextButton")
spawnBtn.Name = "SpawnButton"
spawnBtn.Text = "Spawn Makanan"
spawnBtn.Size = UDim2.new(0.9, 0, 0, 35)
spawnBtn.Position = UDim2.new(0.05, 0, 0.25, 0)
spawnBtn.BackgroundColor3 = Color3.fromRGB(0, 150, 0)
spawnBtn.TextColor3 = Color3.new(1, 1, 1)
spawnBtn.Parent = frame

spawnBtn.MouseButton1Click:Connect(function()
    print("Spawn Food!")
end)
</pre>
</div>

<button onclick="copyScript()">COPY SCRIPT</button>

<div class="footer">
Made By Delta Executor
</div>

</div>

<script>
function copyScript(){
    const text = document.getElementById("script").innerText;

    navigator.clipboard.writeText(text);

    alert("Script berhasil di copy!");
}
</script>

</body>
</html>
