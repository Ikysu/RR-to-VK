# Quick start
1. Go: https://www.radiorecord.ru/player/
2. Ctrl+Shift+I
3. Go: "Console"
3. Type script in console. 

## Script

```
(function(){var _a=document.getElementById("music_mini").children[1];_a.removeAttribute("onclick");_a.setAttribute("onclick","window.open('https://vk.com/audio?q='+document.getElementById('music_mini_artist').innerText+' - '+document.getElementById('music_mini_song').innerText,'_blank','width=1100,height=800')")}).call(this);alert("Injected!")
```

