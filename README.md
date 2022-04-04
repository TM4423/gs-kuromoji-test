# gitpod-kuromoji-linebot-gsacademy-sample-202003

[![Image from Gyazo](https://i.gyazo.com/19c25a0f75928371965917c2a715e242.png)](https://gyazo.com/19c25a0f75928371965917c2a715e242)

## npm インストール

```
npm i express kuromoji @line/bot-sdk axios
```

## LINE関連の設定

```js
const config = {
    channelSecret: '作成したBOTのチャンネルシークレット',
    channelAccessToken: '作成したBOTのチャンネルアクセストークン'
};
```

こちらを自分の設定に書き換える