# 21_ilin_map_guide
## 課題番号-プロダクト名

もりのあんぜんきち

## 課題内容（どんな作品か）

Google map 等のマップアプリのナビを利用しても、道を迷う人がいますので、特に小さな子供です。

そこで、カメラで、目的地は右・左のどちらにあるのかを示せるアプリがあれば便利かと思いましたので、今回の作品を作ってみました。


## 工夫した点・こだわった点

1．カメラを利用して、目的地はどの方向にあるかを示す

2．年齢を問わず、シンプルで可愛いレイアウト


カメラをブラウザに表示するコードは、下記のサイトを参考して作成しました。

https://www.digitalocean.com/community/tutorials/front-and-rear-camera-access-with-javascripts-getusermedia


デバイスの向きを取得するコードは、下記のサイトを参考して作成しました。

https://web.dev/articles/device-orientation?hl=ja


デバイスの向きをカメラビデオの中に表示するため、three.js のドキュメントを参考して作成しました。

https://threejs.org/docs/#api/en/math/Vector3
https://threejs.org/docs/#api/en/cameras/PerspectiveCamera


## 難しかった点・次回トライしたいこと(又は機能)

1．目的地をカメラ目線に適切に表示することが難しいです。今でもちゃんとできていません。

2．携帯電話などのモバイルデバイスの向きを正しく計算することも難しいです。現在はまずキャリブレーションが必要です。今後は自動的にキャリブレーションできる機能を作りたいです。


## 質問・疑問・感想、シェアしたいこと等なんでも

カメラを画面に映る関数と携帯電話の向きを取得する関数を作るためいろいろ調べてみましたが、未だにうまく行かないところがいっぱいあります。

また、作りたい機能がいっぱいあって、いろいろトライしていましたが、まず動けるアプリを作ろうと思って、めちゃくちゃ読みづらいコードになってしまっています。今後もし時間があったら、コードをもっと分かりやすくように修正したいです。
