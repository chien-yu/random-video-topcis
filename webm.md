## WebM
介紹一個Google的封裝格式：WebM，是他們在[2010年的時候推出](https://www.engadget.com/2010/05/19/google-launches-open-webm-web-video-format-based-on-vp8/)的一個基於Matroska的規格。

這裡有一個[樣本影片](http://mirrors.standaloneinstaller.com/video-sample/video-sample.webm)，可以發現如果用Chrome打開它可以直接支援播放，但是Safari不行。

有興趣的話可以嘗試其他格式，像是Apple的[MOV](http://mirrors.standaloneinstaller.com/video-sample/star_trails.mov)，只能再Safari開。如果是通用的[ｍp4](http://mirrors.standaloneinstaller.com/video-sample/jellyfish-25-mbps-hd-hevc.mp4)就都可以。

## 背景
> Google says the format is efficient enough to support playback on lower-power devices like netbooks, tablets, and handhelds, while the encoding profiles are simple enough to limit complexity when you're trying to create WebM files.
([Source](https://www.engadget.com/2010/05/19/google-launches-open-webm-web-video-format-based-on-vp8/))

至於為什麼這個基於Matroska的格式可以在低功率使用者端比較有效率我還不清楚。但這篇[Quora問答](https://www.quora.com/How-do-you-choose-between-MP4-or-MKV-format)算是有一點見解，主要是說Matroska有比較廣泛的影像與聲音支援，基本上你想放什麼都行，不管解碼器能不能處理都可以先放了再說。除此之外還有各種的metadata也可以加在裡面，自由度很高。而且這是開源的，免費！

Quora的討論實在太多了，下一篇再繼續。
