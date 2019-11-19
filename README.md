<!doctype html>
<html>
<head>
<title>How to make a website</title>
<meta charset="utf-8" />
<style>
body{

background-color: #22B678;

}
</style>
</head>
<body>
<button onclick="document.getElementById('popup').style.display = 'block'">How to do a popup</button>
<div id="popup" style="display: none; color: #A511FF; background-color: #FFFF00;">
Add a div tag to your document then type id="id" and inside it, type hello or something like that. Then in your button tag, type onclick="document.getElementById('[your div id]').style.display = 'block'". Then add a hide button in the div tag and type onclick="document.getElementById('[your div id]').style.display = 'none'".
<button onclick="document.getElementById('popup').style.display = 'none'">Hide</button>
</div>
</body>
</html>
