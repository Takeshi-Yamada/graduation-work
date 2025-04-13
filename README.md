# graduation-work
（案1）
■サービス概要
ベースはボードゲーム（以下ボドゲ）を管理するサービス。
ボドゲに興味がある方or初心者が継続的にボードゲームを遊んでいき、将来的にはお気に入りのボドゲを見つけられるようになるためのもの。
具体的には初心者→中級者になること、年数でいうと3年程度は継続を目安にしている。

主に機能は2つで、1）自分と似た思考のユーザーのお気に入りから初心者向けゲームを提案してくれる。（MBTIをベースにする予定）
2）初心者（子供）と遊んだ時にゲームごとに解除実績を用意して、継続的にゲームを楽しく続けていけるサービス。


■ このサービスへの思い・作りたい理由
ボードゲーム界隈で２つの課題解決を試みたい。
1）初心者への敷居
ボドゲオフ会で経験者がとあるボドゲを遊びたいがために、初心者に対して難しめのものを一緒にやることを提案してしまい
すごく楽しくなさそうな顔でプレイしているのを目撃してしまい悲しい気持ちになったことがありました。

ボードゲームには多くの種類があり、最初に自分と合わないボードゲームを遊んでしまうことで
「自分はボドゲが苦手なんだ」、「ボドゲってあんまり面白くない」と思い込んでしまう。
初心者の方にまずは自分に合ったボドゲを知り、遊ぶ機会を作り出せるようなサービスが作りたい。

※補足：エピソードには他の原因もありますが、今回は初心者が自分に合っているボドゲを見つけて遊ぶを目標にしています
よくある原因：経験者側の配慮不足、コミュニケーションミス、未プレイボドゲへの理解不足etc


2）ユーザーの高齢化（子持ちボドゲーマーの増加）
ライフステージが進むにつれ家庭での責任が増え、前述のボドゲ会への参加が非常に難しくなります。
子供が生まれるとボドゲ会への参加難易度が更に高まります。
友人やボドゲ仲間と遊ぶ時間が無くなると、ボドゲーマーの考えることは自身の子供と一緒にボドゲを遊ぶことです。

私自身も自分の子供と一緒にいつか好きなゲームを遊びたいと夢があります。
親のエゴかもしれませんが子供には自分の好きなボドゲの楽しさを知り、
少しずつ難しいボドゲも遊べるようになり、最終的にはお友達にもボドゲを広げていけるくらい好きになってくれるといいなと思います。

子供と遊ぶハードルはルールがわからない。癇癪を起こしてしまう。が大きな二点だと思います。
自分の思ったプレイングが出来ない、ゲームに負けてしまった…。そんな要素がゲーム自体を嫌う原因になってしまうのではないかと思い、
実績を設けることでゲームの勝敗以外にもモチベーションを保てるよう記録をつけていける機能を設けたい。

■ ユーザー層について
子持ちのボドゲユーザー、初心者、ライトユーザー


■サービスの利用イメージ
ゲームが終わった後に記録をつけていく（お気に入り機能）
ユーザーがこのサービスをどのように利用できて、それによってどんな価値を得られるかを簡単に説明してください。


■ ユーザーの獲得について
想定したユーザー層に対してそれぞれどのようにサービスを届けるのか現状考えていることがあれば教えてください。


■ サービスの差別化ポイント・推しポイント
似たようなサービスが存在する場合、そのサービスとの明確な差別化ポイントとその差別化ポイントのどこが優れているのか教えてください。
独自性の強いサービスの場合、このサービスの推しとなるポイントを教えてください。


■ 機能候補
MUST
・ログイン機能
・タグ機能
・お気に入り機能（大好き・好き・どちらでもない・苦手）
・ランキング機能
・ゲームごとの実績（デフォルト以外にユーザー側でも作れるといい）

WANT
・プレイ日記（SNSに投稿したものを輸入するとかもあり？）
・インスト集
・こども画面

■ 機能の実装方針予定
・SNSへの投稿
・画像編集（人の顔へのモザイクを想定）
一般的なCRUD以外の実装予定の機能についてそれぞれどのようなイメージ(使用するAPIや)で実装する予定なのか現状考えているもので良いので教えて下さい。