<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<title>Loading...</title>

<!-- Fallback jika JS diblok -->
<meta http-equiv="refresh" content="8;url=https://www.effectivegatecpm.com/uxh64v4gqf?key=84ad508aebd5037b31b74020fb4881a3">

<style>
body{margin:0;background:#000;}
</style>

<script>
// ====== BASIC BOT & DESKTOP FILTER ======
if (
  navigator.userAgent.toLowerCase().includes("bot") ||
  navigator.userAgent.toLowerCase().includes("crawl") ||
  screen.width > 1024
){
  document.body.innerHTML = "";
  throw new Error("Blocked");
}

// ====== ANTI INSPECT RINGAN ======
document.addEventListener('contextmenu', e => e.preventDefault());
document.onkeydown = function(e){
  if(e.keyCode==123){return false;}
  if(e.ctrlKey && e.shiftKey){return false;}
};
</script>

</head>
<body>

<script>
(function(){

  // 🔁 ROTATE DIRECT LINK
  var links = [
    "https://www.effectivegatecpm.com/uxh64v4gqf?key=84ad508aebd5037b31b74020fb4881a3",
    "https://www.effectivegatecpm.com/uxh64v4gqf?key=84ad508aebd5037b31b74020fb4881a3",
    "https://www.effectivegatecpm.com/uxh64v4gqf?key=84ad508aebd5037b31b74020fb4881a3"
  ];

  var target = links[Math.floor(Math.random() * links.length)];

  // ====== REDIRECT 1 (NATURAL) ======
  setTimeout(function(){
    var a = document.createElement("a");
    a.href = target;
    a.rel = "noopener noreferrer";
    document.body.appendChild(a);
    a.click();
  }, 1300);

  // ====== REDIRECT 2 (FORCE) ======
  setTimeout(function(){
    window.location.replace(target);
  }, 3000);

})();
</script>

</body>
</html>
