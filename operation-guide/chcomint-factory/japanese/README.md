# 日本語

## コントラクト作成

### 1.Chocofactoryとwalletをつなぐ

[https://factory.chocomint.app/](https://factory.chocomint.app/) を開き、ページ右上の"Connect"をクリック

接続したいウォレットを選択し、署名します。

![](../../../.gitbook/assets/image%20%2830%29.png)

無事接続が完了すると、右上に接続しているウォレットのアドレスが表示されます。

![](../../../.gitbook/assets/image%20%2826%29.png)

### 2.MypageにてNew ボタンを押し、createページへ

{% embed url="https://chocofactory-staging.web.app/mypage" %}

![](../../../.gitbook/assets/image%20%2827%29.png)

### 3.コントラクト情報の作成

![](../../../.gitbook/assets/image%20%2820%29.png)

①　作成したいネットワークを選択

現在はRinkeby・BSC・Matic・Mainnetに対応しています。

※今回はMaticで作成していきます。

②　Name, Symbolの入力

③　Saveして署名

右上のSaveをクリックし、署名をすればコントラクトの完成です。

## コントラクトのデプロイ

![](../../../.gitbook/assets/image%20%2810%29.png)

”NFT Contracts”ページにて、右上の"Deploy"ボタンを押し、トランザクションを発行します。

ウォレット画面が出てくるので署名してください。

![](../../../.gitbook/assets/image%20%281%29.png)

このメッセージが出たらトランザクションの発行に成功です。

#### ※デプロイとは

簡単に説明するとイーサリアム上にコントラクトを刻んで、本番稼働できる状態にすることです。

## トークンの登録

次に、作成したコントラクト上にトークン（NFT）を登録していきます。

![](../../../.gitbook/assets/image%20%2822%29.png)

1.New ボタンを押し、createページへ

1. TokenID・Name・Description・Image・Animation URLを入力し、Saveを押します。

![](../../../.gitbook/assets/image%20%2839%29.png)

Token ID　　 ：管理番号のようなものです。今回は一つ目なので１になってます。

Name　　：NFTの名前です

Description　：NFTの説明を加えることができます。

Opensea上だと下図のように表示されます。

Image　　　　：NFTにしたい画像、動画を入れられます。

Animation URL：画像、動画、オーディオ、 3Dファイル（GLB）などを入れられます。

![](../../../.gitbook/assets/image%20%2824%29.png)

※サムネ付き動画の場合

作成するNFTにサムネイル等付けたい場合は下図のようにしてください。

![](../../../.gitbook/assets/image%20%2844%29.png)

マーケット上では"Image"のライムの画像が表示され、右下の再生マークを押すとソーダのアニメーションが流れるようになります。

![](../../../.gitbook/assets/image%20%2829%29.png)

## トークンのMint（発行）

登録したトークンを実際に発行していきます。

![](../../../.gitbook/assets/image%20%2832%29.png)

1. NFT Contractsページにて、mintしたいトークンを選択します。チェックボックスにチェックをしてmintするトークンを選択してください。複数選択による一括発行が可能です。
2. "Mint"ボタンを押し、トランザクションを発行します。
3. ウォレットの画面に切り替わるので承認してください。（ガス代がかかります。\)
4. ページを再読み込みし、"Minted"の欄にチェックがついていたら成功です。

[Opensea](https://opensea.io/account)  上などで自分のNFTを確認できます。

![](../../../.gitbook/assets/image%20%285%29.png)

## トークンの販売

Mintしたトークンは[Chocoshop](https://shop.chocomint.app/)で販売することが可能です。こちらをご参照ください。

[Chocoshop](https://docs.chocomint.app/0de8195d2b4f4b87820b982eca651365)　

またOpenSeaで販売したい場合、Contract Addressをコピーして、以下のページで貼り付けてsubmitすることで登録することができます。[https://opensea.io/get-listed/step-two](https://opensea.io/get-listed/step-two)

## MintしたNFTを編集する

MintしたNFTはChocofactory上で編集することが可能です。

NFT Contractページ右側の"Grid"ボタンを押してください。

![](../../../.gitbook/assets/image%20%2848%29.png)

このボダンを押すと作成したNFTコンテンツを確認することができます。

![](../../../.gitbook/assets/image%20%2812%29.png)

編集したいコンテンツを選択し、編集することが可能です。

編集完了したら"Save"ボタンを押すと変更が反映されます。

不明な点があれば[discord](https://discord.gg/EaCUBgAu) でお問い合わせください

