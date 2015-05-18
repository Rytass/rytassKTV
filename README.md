# rytassKTV

//kkbox parser 

use this urls

華語 http://www.kkbox.com/tw/tc/charts/chinese-daily-song-latest.html
西洋 http://www.kkbox.com/tw/tc/charts/western-daily-song-latest.html
日語 http://www.kkbox.com/tw/tc/charts/japanese-daily-song-latest.html
韓語 http://www.kkbox.com/tw/tc/charts/korean-daily-song-latest.html
嘻哈 http://www.kkbox.com/tw/tc/charts/hiphop_rnb-daily-song-latest.html
搖滾 http://www.kkbox.com/tw/tc/charts/rock-daily-song-latest.html
電子 http://www.kkbox.com/tw/tc/charts/electronic-daily-song-latest.html
古典 http://www.kkbox.com/tw/tc/charts/classical-daily-song-latest.html
爵士 http://www.kkbox.com/tw/tc/charts/jazz-daily-song-latest.html
療癒 http://www.kkbox.com/tw/tc/charts/world_music-daily-song-latest.html

JS code

for (i = 0; i < 100; i++) {
    console.log(document.getElementsByTagName("h4")[i].getElementsByTagName("a")[0].text);
}