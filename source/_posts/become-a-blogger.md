---
title: 2.0 x Double Y & C
date: 2016-03-17 10:57:35
categories:
- Front-end
tags:
- Self-Reflection
- Gulp
- Hexo
cover: 2016/become-a-blogger/cover.jpg
banner: cover.jpg
---
有些人看過我的個人網頁 1.0，那是一個既沒有框架也沒有模板的悲劇。事隔一年，終於升級了！本文就要來談談打了一年新手怪的心路歷程，以及 Gulp 和 Hexo 的使用心得。

<!--more-->
- - - 
### 先來談談 1.0 到 2.0 的過程

{% asset_img "gulp.jpg" "Gulp" %}

[Gulp](http://gulpjs.com/ "gulpjs.com") 是一個很好用的 "任務自動化管理工具（Build System）"，推薦 *Joel Longie* 在 YouTube 上的 [Gulp 教學][youtube] 很適合新手。不過我一直到今年初終於下定決心要衝等的時候，我才學會兩件事：

1. 想學和真的動手有很大的距離。
2. 所有學習都從模（ㄈㄨˋ）仿（ㄓˋ）開始。

Gulp 功能強大，~~大至把人送上火星~~，小至完成我的三個小願望：

1. **編譯 Jade 檔**，擺脫老是沒關緊的 HTML 標籤。
2. **編譯 Sass 檔**，沒辦法回頭了！
3. **自動刷新頁面**，我就是懶呀。

我只要編寫 *src* 資料夾裡的原檔（需要經過編譯的檔案），Gulp 便會把編譯好的檔案丟到 *dist* 資料夾。完整的專案可以參考我的 [GitHub][portfolio]，而我的 [Github Pages][page] 就是上傳已經整理好、可以隨時發布的 *dist* 資料夾。

實際的使用方法可以多爬文或參考完整的專案，[OXXO.STUDIO 的教學文][blog] 推薦給大家。

懂得運用 Gulp 對我在學習前端上是一個重要的進程，這段期間包括弄懂框架（Framework）、熟悉預處理器（Preprocessor）、了解套件管理（Package Control）等等。最近在 GitHub 上種草的時候，便有感持續進步所帶給我的喜悅。說不定我種的不是含羞草，是大麻。

回到 [個人網頁 2.0][page]，總結兩個心得：

1. 我要和 [Foundation](http://foundation.zurb.com/) 分手！
2. 第一次用手機瀏覽後才知道 RWD 真的很難（哭）。

目前還在尋找加入 Contact Form 的可能性，也會以更好的設計為目標持續努力。最近收集了不少優秀的 Protfolio Pages，相較之下，自己的作品還很陽春呀（掩面）。

但最重要的還是，透過這個過程來 **認識並整理自己**。

[youtube]:https://www.youtube.com/watch?v=LmdT2zhFmn4&list=PLv1YUP7gO_viROuRcGsDCNM-FUVgMYb_G
[portfolio]:https://github.com/irene84111/portfolio
[blog]:http://www.oxxostudio.tw/articles/201503/gulp-install-webserver.html
[page]:http://irene84111.github.io

- - - 

### 再來說說 Double Y & C 是什麼

就是 "YYC" 呀！Ya Yin Chang 的縮寫。由於太像某 Y*K 拉鏈大廠，只好避掉俗氣來個自我感覺良好。

{% asset_img "hexo.jpg" "Hexo" %}

大推現在很夯的 [Hexo](https://hexo.io/)，這個容易上手的網誌框架讓手殘如我也可以第一次就輕鬆架設。在設定部署的時候，才發現原來可以透過 `gh-pages` 分支來新增各種分頁在自己的 GitHub Pages 下（[官方教學文][page-tutorial]）， 也可以參考我的 [config.yml][] 設定。

「反正一開始有沒什麼流量，就寫吧！」

受到 Caesar 大大的刺激之後，就先從每週至少一文開始吧！

> In the 21st Century, Everyone’s a writer.


[page-tutorial]:https://help.github.com/articles/creating-project-pages-manually/
[config.yml]:https://github.com/irene84111/blog/blob/master/_config.yml