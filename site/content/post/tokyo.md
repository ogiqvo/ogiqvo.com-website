+++
date = "2015-12-16T14:53:29+09:00"
draft = false
title = "Tokyo | Ogiqvo is out"

+++

If you have ever been to Tokyo, and had a ride on trains, it's not so difficult to imagine how crowded the [Tokyo station](https://en.wikipedia.org/wiki/Tokyo_Station) is. It's the central terminal of trains in Tokyo, central terminal of all trains in Japan which is widely known as the most frequent railway networks on earth.

The problem is that there are nowhere you can see all the trains and **how frequent** it's running, one reason is because the station is massive, and other is that several platforms are existing underground.

[*Tokyo | Ogiqvo*](https://play.google.com/store/apps/details?id=com.ogiqvo.view.tokyo) is an Android app which emulates Tokyo station in your Android device. It's not only a map app, but an app that has **time axis**, which can also be set.

Let's have a look at the features.

* It's based on [Vector tile maps](https://github.com/opensciencemap/vtm), which is an extra-light, three-dimensional maps library. You can move, expand/shrink, rotate and even tilt the map view like alternative maps app like Google maps, Here maps and so on.
* Each cars' count, it's size and the position to stop is accurate. It can show exactly where the train stops.
* It shows Tokyo station's floor map with altitude. As a result, platforms underground will be displayed under platforms overground. I've punched holes that meant to be stairs.
* Rails contain altitude information. As a result, trains running underground will be displayed under trains running overground.
* It contains all trains' **REAL** timetable that departs and arrives Tokyo station (about 3,000 per day).
  * [Tokaido](https://en.wikipedia.org/wiki/Tokaido_Shinkansen) and [Sanyo Shinkansen](https://en.wikipedia.org/wiki/Sany%C5%8D_Shinkansen) (JR Central)
  * [Tohoku](https://en.wikipedia.org/wiki/Tohoku_Shinkansen), [Yamagata](https://en.wikipedia.org/wiki/Yamagata_Shinkansen) and [Akita Shinkansen](https://en.wikipedia.org/wiki/Akita_Shinkansen) (JR East)
  * [Joetsu Shinkansen](https://en.wikipedia.org/wiki/J%C5%8Detsu_Shinkansen) (JR East)
  * [Hokuriku Shinkansen](https://en.wikipedia.org/wiki/Hokuriku_Shinkansen) (JR East)
  * [Yamanote line](https://en.wikipedia.org/wiki/Yamanote_Line) (JR East)
  * [Keihin-Tohoku line](https://en.wikipedia.org/wiki/Keihin-T%C5%8Dhoku_Line) (JR East)
  * [Tokaido line](https://en.wikipedia.org/wiki/T%C5%8Dkaid%C5%8D_Main_Line), Ueno-Tokyo line connected to Joban line, [Narita line](https://en.wikipedia.org/wiki/Narita_Line), Utsunomiya line and Takasaki line (JR East)
  * [Chuo line rapid service](https://en.wikipedia.org/wiki/Ch%C5%AB%C5%8D_Main_Line) (JR East)
  * [Sobu line rapid service](https://en.wikipedia.org/wiki/S%C5%8Dbu_Main_Line)and [Yokosuka line](https://en.wikipedia.org/wiki/Yokosuka_Line), including [Narita Express](https://en.wikipedia.org/wiki/Narita_Express) (JR East)
  * [Keiyo line](https://en.wikipedia.org/wiki/Keiy%C5%8D_Line) and [Musashino line](https://en.wikipedia.org/wiki/Musashino_Line) (JR East)
  * [Marunouchi line](https://en.wikipedia.org/wiki/Tokyo_Metro_Marunouchi_Line) (Tokyo Metro)
* It contains all map data and timetable data itself, so network connection isn't needed after app installation.

Since the Vector tile maps library is licesned under [Lesser GNU Public License version 3](http://www.gnu.org/licenses/lgpl-3.0.html), Tokyo | Ogiqvo is also LGPLv3. You can download the source code from [here](https://github.com/ogiqvo/ogiqvo.com-opensciencemap-lgplv3).

東京の列車が世界でも類を見ないほど頻繁に発着することはよく知られており、それらが1日に3,000本も発着する[東京駅](https://ja.wikipedia.org/wiki/%E6%9D%B1%E4%BA%AC%E9%A7%85)ともなれば想像もできないほどの忙しさであることは想像に難くありません。

しかし駅が広大であることや、一部の列車は地下を走っていることもあり、列車が**どれだけ激しく**発着しているかを一望できる場所は地球上に存在しません。

[*Tokyo | Ogiqvo*](https://play.google.com/store/apps/details?id=com.ogiqvo.view.tokyo)は、東京駅を発着するすべての列車を3次元空間に再現するAndroid向けのアプリです。任意の時刻を設定すると、その時間に走っている列車とその位置を表示します。
