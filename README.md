何か不具合があっても当方では一切の責任を負いません。

sengokuixa-meta
===============

戦国IXAを変態させるツール

動作確認
--------

* Firefox24esr + Scriptish
* （確か・・・Firefox9以上必須）

インストール
------------

* このツールを使用するには[Scriptish](https://addons.mozilla.org/ja/firefox/addon/scriptish/)を事前にインストールしておく必要があります
* 最新バージョンのインストールは[こちら](https://raw.githubusercontent.com/moonlit-g/sengokuixa-meta/master/sengokuixa-meta.user.js)
* ハンゲの方は[こちら](https://raw.githubusercontent.com/moonlit-g/sengokuixa-meta/hangame/sengokuixa-meta.user.js)
 - 動作が被ってしまいますので、本家版も最新に更新してください。

更新履歴
--------

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
