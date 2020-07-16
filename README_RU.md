# Radio Record to VK [[`EN`](README.md)|`RU`]
Скрипт для быстрого поиска музыки в ВК

# Быстрый старт
1. Перейдите: https://www.radiorecord.ru/player/
2. Зажми: Ctrl+Shift+I
3. Перейди в "Console"
4. Введи скрипт в консоль. 

## Script

```
(function(){var _a="window.open('https://vk.com/audio?q='+document.getElementById('music_mini_artist').innerText+' - '+document.getElementById('music_mini_song').innerText,'_blank','width=1100,height=800')";_b=document.getElementById("music_mini").children[1];_b.removeAttribute("onclick");_b.setAttribute("onclick",_a);_c=document.getElementById("music").children[5];_c.removeAttribute("onclick");_c.setAttribute("onclick",_a)}).call(this);console.log("Injected!")
```


# Как пользоваться?
Если вы все сделали по инструкции, то у вас должно появится «Injected» и «undefined» в консоли, после чего вы можете нажать на кнопку VK в правом нижнем углу, когда вам понравится играющий трек.
