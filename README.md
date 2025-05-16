# 250516_css_carousel
記事『[JavaScript不要! HTMLとCSSでつくるカルーセルUI](https://ics.media/entry/250516/)』のデモコードです。

デモで使用している画像はいずれも[Unsplash](https://unsplash.com/)で取得しています。撮影者のクレジットは以下のとおりです。

①シンプルなカルーセル
- [flower_01](https://unsplash.com/ja/%E5%86%99%E7%9C%9F/%E3%82%AF%E3%83%AD%E3%83%BC%E3%82%BA%E3%82%A2%E3%83%83%E3%83%97%E5%86%99%E7%9C%9F%E3%81%AE%E3%82%AA%E3%83%AC%E3%83%B3%E3%82%B8%E8%89%B2%E3%81%AE%E3%82%B1%E3%82%B7%E3%81%AE%E8%8A%B1-qUACwpVjwoM) -  [Susanne Schwarz](https://unsplash.com/ja/@lennonsdaughter)による撮影
- [flower_02](https://unsplash.com/ja/%E5%86%99%E7%9C%9F/%E6%98%BC%E9%96%93%E3%81%AE%E7%99%BD%E3%81%84%E7%A9%BA%E3%81%AE%E4%B8%8B%E3%81%AB%E3%83%94%E3%83%B3%E3%82%AF%E3%81%A8%E7%99%BD%E3%81%AE%E8%8A%B1-kxvn1ogpTtE) -  [TOMOKO UJI](https://unsplash.com/ja/@ujitomo)による撮影
- [flower_03](https://unsplash.com/ja/%E5%86%99%E7%9C%9F/%E7%99%BD%E3%81%84%E8%8A%B1%E3%81%AE%E6%B5%85%E3%81%84%E3%83%94%E3%83%B3%E3%83%88%E5%86%99%E7%9C%9F-yzgF-AQt1sQ) -  [Aaron Burden](https://unsplash.com/ja/@aaronburden)による撮影
- [flower_04](https://unsplash.com/ja/%E5%86%99%E7%9C%9F/%E7%99%BD%E3%81%84%E8%8A%B1%E3%81%AE%E6%B5%85%E3%81%84%E7%84%A6%E7%82%B9%E6%92%AE%E5%BD%B1-urUdKCxsTUI) -  [Anthony DELANOIX](https://unsplash.com/ja/@anthonydelanoix)による撮影
- [flower_05](https://unsplash.com/ja/%E5%86%99%E7%9C%9F/%E5%92%B2%E3%81%8F%E9%9D%92%E3%81%84%E8%8A%B1%E3%81%B3%E3%82%89%E3%81%AE%E3%82%AF%E3%83%AD%E3%83%BC%E3%82%BA%E3%82%A2%E3%83%83%E3%83%97%E5%86%99%E7%9C%9F-F6ZzivdSQ5k) -  [Sora Sagano](https://unsplash.com/ja/@sorasagano)による撮影

②インジケーターに画像を設定したカルーセル
- [product_01](https://unsplash.com/ja/%E5%86%99%E7%9C%9F/%E7%99%BD%E3%81%84%E6%A3%9A%E3%81%AE%E4%B8%8A%E3%81%AB%E7%BD%AE%E3%81%8B%E3%82%8C%E3%81%9F%E7%B7%91%E8%89%B2%E3%81%AE%E3%83%A9%E3%82%B8%E3%82%AA-kVjagkIY3bQ) -  [John Sin](https://unsplash.com/ja/@qoph_s)による撮影
- [product_02](https://unsplash.com/ja/%E5%86%99%E7%9C%9F/%E3%82%B9%E3%82%BF%E3%83%B3%E3%83%89%E3%81%AE%E4%B8%8A%E3%81%AB%E7%BD%AE%E3%81%8B%E3%82%8C%E3%81%9F%E9%A6%99%E6%B0%B4%E3%81%AE%E3%83%9C%E3%83%88%E3%83%AB-_3i9GiOc6i0) -  [Ubaid E. Alyafizi](https://unsplash.com/ja/@ibnualyafizi)による撮影
- [product_03](https://unsplash.com/ja/%E5%86%99%E7%9C%9F/%E3%83%94%E3%83%B3%E3%82%AF%E3%81%AE%E8%83%8C%E6%99%AF%E3%81%AB%E8%96%AC%E3%81%AE%E3%83%9C%E3%83%88%E3%83%AB-tFTWq1R3ukQ) -  [Suleman Serwar](https://unsplash.com/ja/@musi_studio)による撮影
- [product_04](https://unsplash.com/ja/%E5%86%99%E7%9C%9F/%E7%99%BD%E3%81%84%E7%AE%B1%E3%81%AE%E4%B8%8A%E3%81%AB%E7%BD%AE%E3%81%8B%E3%82%8C%E3%81%9F%E8%B5%A4%E3%81%84%E8%8A%B1%E7%93%B6-t7qnV7V0qKc) -  [Sanni Sahil](https://unsplash.com/ja/@sannisahil)による撮影
- [product_05](https://unsplash.com/ja/%E5%86%99%E7%9C%9F/%E7%99%BD%E3%81%84%E3%83%9C%E3%83%BC%E3%83%AB%E3%81%8C%E5%85%A5%E3%81%A3%E3%81%9F%E7%99%BD%E3%81%84%E3%83%9C%E3%82%A6%E3%83%AB-zdHbEJ2TKQA) -  [Mediamodifier](https://unsplash.com/ja/@mediamodifier)による撮影


③横幅いっぱいのカルーセル
- [landscape_01](https://unsplash.com/ja/%E5%86%99%E7%9C%9F/%E6%B0%B4%E5%9F%9F%E3%82%92%E6%A8%AA%E5%88%87%E3%82%8B%E7%B7%91%E3%81%AE%E5%B1%B1-Bkci_8qcdvQ) -  [Kalen Emsley](https://unsplash.com/ja/@kalenemsley)による撮影
- [landscape_02](https://unsplash.com/ja/%E5%86%99%E7%9C%9F/%E6%98%BC%E9%96%93%E3%81%AE%E6%9B%87%E3%82%8A%E7%A9%BA%E3%81%AE%E4%B8%8B%E5%BA%83%E3%81%84%E9%87%8E%E8%8D%89%E3%81%AE%E4%B8%8A%E3%81%AB%E9%80%A0%E5%B2%A9-M9O6GRrEEDY) -  [🧔‍♂️ Michal Kmeť](https://unsplash.com/ja/@mitko)による撮影
- [landscape_03](https://unsplash.com/ja/%E5%86%99%E7%9C%9F/%E7%B7%91%E3%81%A8%E8%8C%B6%E8%89%B2%E3%81%AE%E5%B4%96%E3%81%AE%E9%A2%A8%E6%99%AF%E5%86%99%E7%9C%9F-xcC5ozHk_N8) -  [Joseph Barrientos](https://unsplash.com/ja/@jbcreate_)による撮影
- [landscape_04](https://unsplash.com/ja/%E5%86%99%E7%9C%9F/%E5%B1%B1%E3%81%AE%E5%BE%8C%E3%82%8D%E3%81%AB%E3%81%82%E3%82%8B%E7%81%B0%E8%89%B2%E3%81%AE%E9%81%93-2SOoG8-xbCA) -  [Jean-Pierre Brungs](https://unsplash.com/ja/@johnnyabroad)による撮影
- [landscape_05](https://unsplash.com/ja/%E5%86%99%E7%9C%9F/%E6%9C%A8%E3%80%85%E3%81%AB%E5%9B%B2%E3%81%BE%E3%82%8C%E3%81%9F%E6%B0%B4%E5%9F%9F-_LuLiJc1cdo) -  [Kalen Emsley](https://unsplash.com/ja/@kalenemsley)による撮影