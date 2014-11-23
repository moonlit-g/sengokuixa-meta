何か不具合があっても当方では一切の責任を負いません。

sengokuixa-meta
===============

戦国IXAを変態させるツール

動作確認
--------

* Firefox31esr + Scriptish0.1.11

インストール
------------

* このツールを使用するには[Scriptish](https://addons.mozilla.org/ja/firefox/addon/scriptish/)を事前にインストールしておく必要があります
* y鯖最新版のインストールは[ここ](https://raw.githubusercontent.com/moonlit-g/sengokuixa-meta/master/sengokuixa-meta.user.js)をクリック
* hm鯖最新版のインストールは[ここ](https://raw.githubusercontent.com/moonlit-g/sengokuixa-meta/master/sengokuixa-meta-hm.user.js)をクリック
* mixiは期と章が取得できないので、[こちら](https://raw.githubusercontent.com/moonlit-g/sengokuixa-meta/master/mixi-support.user.js)も合わせてインストールしてください
 - ログイン後、家紋をクリックすると期と章を尋ねられますので入力すると地図画面での不具合が治ると思います

更新履歴
--------

### 1.4.4.10
2014/11/23
* チャット欄の座標リンクを修正(Thanks>>477,495)
* 入札中ページでリンクが張れていなかったのを修正
* 取引条件のインポート、エクスポート機能を追加

### 1.4.4.9
2014/11/21
* 不具合対応
 - 書状が削除できなくなっていたのを修正(Thanks>>439)
 - 高速訓練が追加されたことによるレイアウト修正(Thanks>>441)

### 1.4.4.8
2014/11/20
* 9章対応
 - データ修正
 - 章の取得を修正(@Todo)
 - チャット欄のボタン配置修正(Thanks>>431)
 - 受信箱のレイアウト修正
 - 兵士作成施設のレイアウト修正
* hm鯖除外
 - hm鯖用は別ファイルになりましたので必要な方は↑からインストールしてください

### 1.4.4.6
2014/11/12
* アップデート対応
 - Ajax通信のヘッダ修正
 - 地図画面の必要攻撃力表示
 - 部隊編成のページャー対応

### 1.4.4.5
2014/11/09

* ミニマップを影武者の出現時間帯別に色分け
* 取引フィルタに「即落札以外」を追加
* 取引検索の拡充
 - 複数条件をまとめて検索できます

### 1.4.4.4
2014/10/12

* チャット履歴と書状の座標っぽいものをリンクするように変更
 - 一般的なアンカータグ
* 銅銭、金、金の購入、便利機能を復活
 - カードブロック内に移動しています
* 金山ショートカットを追加
 - メニュー内の【投資設定】で登録した資源量を投資します
* 兵士退避ロジックの変更
 - 一時的に指揮力降順でソートして退避させるようにしたので、余ることが減ったはず
* お気に入り部隊をコンテキストメニューから登録できるように

### 1.4.4.3
2014/10/04

* 金購入のリンクを修正

### 1.4.4.2
2014/09/21

* 取引の機能を拡張
 - フィルタ、ソートの実装
 - カードNo.とスキル名に検索用リンクを追加
 - 検索条件の入力フィールドで4桁の数値を入力した場合はカードNo.で検索する
* サイドバーでタイトルをクリックすると折り畳むように
* 集計機能で最初のカードが出力されないのを修正

### 1.4.4.1
2014/09/18

* ハンゲmixi版を本家版に統合
* 出品画面で手取りボタンを押した場合に、出品額を変更するだけに変更
* 「参加せよ」を静止画に変更
* 兵士編成画面に集計機能を追加
 - 読み込み済みの武将のみです
 - 出力ファイルの文字コードはUTF-8N、改行コードはLFです
 - ファイル名は「鯖名_日時.csv」です
* チャット履歴で座標っぽいものをクリックすると該当座標の地図画面に遷移
* スキル強化の追加スロット画面のメッセージを非表示に変更

### 1.4.4.0
2014/09/04

* 陣被りチェックの追加

### 1.4.3.9
2014/09/02

* 加勢部隊への対応
* コンテキストメニューで限界突破合成ができないのを修正
* 部隊ダイアログを開いている際に状況が変化したら登録されない件が直ってる…といいな

### 1.4.3.8
2014/08/23

* 精鋭部隊の取り扱いを変更
 - 部隊編成の精鋭画面を表示することで記憶します。 
記憶はソート順ですが、配置は隊番号順になりますので、 
ソートを「隊番号」「昇順」にしておかないと違う部隊が配置されますので注意。
* 課金、便利機能などをサイドバーから削除、ヘッダーの金からポップアップメニューでアクセス可
* ヘッダの資源表示を省スペース化
* 出陣状況画面のタイトルを変更
* キーボードショートカットを追加
 - 詳細は「?」キーで表示されるヘルプを参照してください
* 追加スロットのオートページャーの不具合を修正

### 1.4.3.7
2014/08/14

* スキル削除ができなくなっていた不具合を修正

### 1.4.3.6
2014/08/06

* 追加合成の不具合修正
* 取引画面上部にページャーを追加
* 合成時に組を選んでいた場合に、オートページャーで全武将を読み込んでいたのを修正
* 占いを初期非表示に

### 1.4.3.5
2014/08/06

* 加勢部隊の取り下げ(branch:support)
 - ハンゲ1.4.3.5ベース
* 部隊編成の仕様変更に対応
* カードレアリティのクラス名変更に対応
* 国移動非表示

### 1.4.3.4
2014/07/25

* 東西戦での速度を2倍に
* 精鋭部隊のトグル表示を部隊番号の所だけに変更

### 1.4.3.3
2014/07/15

* 再編成の不具合修正
* 加勢専用部隊の即出陣対応
* 部隊編成画面のレイアウト調整
* 限界突破に一部対応
* 童対応
* スキルテーブル更新
* とりあえずハンゲを対象外に(↑のでおねがいします。追加機能に関しては別途対応予定です)

### 1.4.3.2
2014/07/05

* 一括レベルアップ、即落札で確認ダイアログを表示
* 部隊編成ダイアログや部隊編成画面のデッキモードで小隊長を表示するように
* 加勢専用部隊に暫定対処(運営のテスト期間中用)

### 1.4.3.1
2014/07/05

* 7/3のアップデートに伴う編成画面の変更に対応

### 1.4.3.0
2014/07/02

* ショートカットキーの追加
 - `u`:カード合成
 - `l`:戦国くじ
 - `?`:ショートカットキーの一覧

* 一括レベルアップ機能
 - 分配済みのステータスポイントがある場合に極振りになるように未使用分を振り分けます。  
未分配のときはスキップします。

* 合成表の更新確認
 - 鯖選択画面で合成表の更新をチェックします。

* 精鋭部隊関係
 - 精鋭部隊画面での初期表示を部隊長のみにしました。  
ステータス欄のクリックでトグル表示になります。
 - ポップアップメニューから精鋭部隊を配置できるようにしました。

* 拠点情報の自動登録
 - 地図画面の拠点情報画面に「拠点情報を自動登録」というメニューが追加されています。  
チェックするとフィルタに従って表示された拠点などの情報が座標情報に登録されます。

* 連続強化合成
 - 部隊編成のモード切り替えで連続強化を追加しました。  
複数のカードを選択した状態でポップアップメニューから「スキル連続強化」を選択するとダイアログが表示されます。  
各スキルの目標とするレベルを入力して「銅銭」か「金」を選択すると1枚ずつ消費して強化合成を行います。  
複数スキルが対象となった場合は低レベルのものから実行します。  

* カード合成画面
 - オートページャーを追加。
 - 合成確認画面をスキップ。

* 取引
 - オートページャーを追加。
 - 各ページのタイトルを修正。
 - 取引期限まで24時間以上ある場合の表示方法を変更。
 - 即落札の場合は確認なしで落札するように変更。

* 出品画面
 - 「取引」ボタンは同一カードを検索します。(別タブで表示)
 - 「出品」ボタンは入力欄の数値で出品します。
 - 「手取り」ボタンは入力欄の数値が手取り額になるよう手数料を上乗せして出品します。

### 1.4.2.4
2014/06/11

* 【兵士退避】メニューを部隊メニューの最下部へ移動

### 1.4.2.3
2014/06/10

* 精鋭部隊が実装されていない環境でも動作するように修正 fixed #5

### 1.4.2.2
2014/06/09

* 機能追加
 - 部隊メニューに【兵士退避】を追加。待機兵を可能な限り武将に割り当てます。
 - 秘境メニューに各秘境へのショートカットを追加。

### 1.4.2.1
2014/06/09

* Firefox29でスキル合成表が壊れる現象に対処
* スキル合成表更新

### 1.4.2.0
2014/06/04

* スキル合成表更新(メニューから更新)
* フィルタにレアリティを追加
* カードのコンテキストメニューからレベルアップをするときなどに別タブで開くように
* バージョン番号の整理

### 1.4.1.3
2014/06/04

* スキル合成表をGitHubのJSONファイルから取得するよう変更
 - クエストメニューに「合成表更新」があります
* 兵士編成画面に攻防2%ボタンを追加
* ワールド選択画面で告知をデフォルトで非表示
 - 告知バー(？)をクリックすると切り替わります

### 1.4.1.0
2014/05/30

* 東西戦の仕様変更(各国8砦)に対応

### 1.4.0.0
2014/05/18

* 8章対応(限界突破はまだ)

### 1.3.2.1
2014/05/13

* スキルテーブル更新
* 東西戦の砦増加に対応

### 1.3.2.0
2014/04/23

* スキルテーブル更新

### 1.3.1.11
2014/04/23

* オリジナルからFork

### オリジナルの更新履歴
* [Version History](https://github.com/metameta/sengokuixa-meta/wiki/Version-History)


オリジナルへのリンク
------------------------
[metameta氏](https://github.com/metameta)の[sengokuixa-meta](https://github.com/metameta/sengokuixa-meta)

Special Thanks
--------------
* 株式会社スクウェア・エニックス
* [戦国IXA wiki](http://www.ixawiki.com/)
* [ポケットサウンド](http://pocket-se.info/)様
* 2chのツールスレ
