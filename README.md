
## 最初にやること
```bash
git npm i
git clone https://github.com/scla-sagauniv/B-komachi.git
```
## 開発の手順
#### おおまかな流れ
1．開発する機能のissueを立てる（github issues参照）  
2．ブランチを切る（```git checkout -b {ブランチ名}```）  
3．機能実装（vscode,ローカルで開発）  
4．切ったブランチにpush  
5．プルリクエスト出してmainにmerge
#### 開発用サーバ起動
```bash
npm run dev
```
#### 機能実装後
実装できたら
```bash
git add {変更したファイル名}
git commit -m "コミットメッセージ"
git push origin {ブランチ名}
```
gitの理解に不安がある　→　これでも見てろ：https://zenn.dev/atsushi101011/articles/4e0e36d238a3b8  
pushができたらgithubで確認、プルリクを出す  
マージするの怖い！ってなったら後藤を呼んでください　代わりにENTERします

#### 気をつけてほしいこと
* 基本は二人での開発になると思います
* 機能開発を始める前に今いるブランチを要確認！mainブランチでの作業は避けましょう
* お互いの作業内容を把握しましょう
* 同じファイルを同時に編集するのはできるだけ避けましょう
* こまめに```git pull```を行って、ブランチを最新の状態に保ちましょう
* 困ったらメンターさんをガン頼りしてね　質問内容は明確に！
