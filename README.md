# WanNyafullSearch  
迷い犬、迷い猫を探すシステム、HackUのハッカソンで開発しました。  
AndroidApp（ゲームアプリ） + WebApp（迷い犬迷い猫を探すWebページ）で構成されています。  
ゲームアプリでは、犬派チームと猫派チームに別れ近所の犬や猫を撮影します。  
画像認識により犬か猫と判断されると、自分のチームへ得点が加算されます。  
また、撮影した犬猫の写真に対して「スマホを撫でる」「スマホをよしよしする」などの愛情表現をすると更に得点が上がります。  
Webページでは、ゲームアプリで取得した犬や猫の写真と位置情報を元に迷い犬と迷い猫を検索することができます。  
使用した顔認識APIを呼び出すPHP、住所から緯度経度を取得するPHPなどをバックアップ。  
![Wannyafull_images](https://github.com/RyRySuzu/images/blob/master/wannyafull_modal_min.png)
