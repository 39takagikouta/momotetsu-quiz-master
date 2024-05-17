# momotetsu-quiz-master

・概要
桃太郎伝説ワールドで貧乏神がターン終了時にランダムで出題してくる、国か島か湖に関するクイズの対策アプリです。

・ターゲット
桃太郎電鉄ワールドを定期的にやる機会があるが、貧乏神のクイズに正答できない人

・機能
ユーザー登録機能
実際にゲーム内で問われる、国旗に関するクイズを出題する機能
実際にゲーム内で問われる、島に関するクイズを出題する機能
実際にゲーム内で問われる、湖に関するクイズを出題する機能
それぞれの回答時に、google map の API を用いて場所を教示する機能
それぞれの回答時に、openAI API を用いてその国（国旗）・島・湖について説明する機能
それぞれの解答結果を記録する機能
各ユーザーが間違えた問題を記録し、それらのみを再度復習できる機能
回答結果を twitter で投稿できる機能
LINE、Google ログイン機能

・ER 図
[![Image from Gyazo](https://i.gyazo.com/8fcf0f6ee9cce91050eb8a23b27aacca.png)](https://gyazo.com/8fcf0f6ee9cce91050eb8a23b27aacca)

・画面遷移図
[![Image from Gyazo](https://i.gyazo.com/23a37b6bdf782a0b43edeba0a1c05879.jpg)](https://gyazo.com/23a37b6bdf782a0b43edeba0a1c05879)
