# Radio Record to VK [`EN`|[`RU`](README_RU.md)]
Script for quickly finding music in VK

# Quick start
1. Go: https://www.radiorecord.ru/player/
2. Ctrl+Shift+I
3. Go: "Console"
4. Type script in console. 

## Script

```
(function(){var _a="window.open('https://vk.com/audio?q='+document.getElementById('music_mini_artist').innerText+' - '+document.getElementById('music_mini_song').innerText,'_blank','width=1100,height=800')";_b=document.getElementById("music_mini").children[1];_b.removeAttribute("onclick");_b.setAttribute("onclick",_a);_c=document.getElementById("music").children[5];_c.removeAttribute("onclick");_c.setAttribute("onclick",_a)}).call(this);console.log("Injected!")
```


# How it works?
After you have done everything according to the instructions and the console displays “Injected” and «undefined», you can press the VK button in the lower right corner when you enjoy playing the track.
