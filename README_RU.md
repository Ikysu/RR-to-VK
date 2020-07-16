# Quick start [[EN](README.md)|[RU](README_RU.md)]
1. Перейдите: https://www.radiorecord.ru/player/
2. Зажми: Ctrl+Shift+I
3. Перейди в "Console"
4. Введи скрипт в консоль. 

## Script

```
(function(){var _a=document.getElementById("music_mini").children[1];_a.removeAttribute("onclick");_a.setAttribute("onclick","window.open('https://vk.com/audio?q='+document.getElementById('music_mini_artist').innerText+' - '+document.getElementById('music_mini_song').innerText,'_blank','width=1100,height=800')")}).call(this);console.log("Injected!")
```


# Как пользоваться?
Если вы все сделали по инструкции, то у вас должно появится «Injected» в консоли, после чего вы можете нажать на кнопку VK в правом нижнем углу, когда вам понравится играющий трек.
