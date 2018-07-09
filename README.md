# フリーランスエンジニアが合同会社を設立するまでの流れ

## 本ドキュメントについて

- 個人事業主と法人でどちらがメリットがあるか、については記載していません。
- 株式会社と合同会社の違いについても一部記載していますが、あくまで設立までの作業手順に重点を置いています。
- 1エンジニアが個人的に調べた内容なので、誤りや個人的な意見を含んでいる点にご注意ください。

## 株式会社と合同会社の比較

| 項目 | 株式会社 | 合同会社 |
| --- | --- | --- |
| 登記費用 | 15万円 | 6万円 |
| 節税的なメリット | 同じ | 同じ |
| 決算公告 | 必要 | 不要 |

※ 決算公告以外の公告については合同会社も実施する必要がある。
http://www.moj.go.jp/MINJI/minji81.html

## 設立の流れ

### 電子定款を作成する

- 定款は紙と電子定款がある。
- 電子定款の場合、定款に貼る収入印紙代４万円が不要となる。
- freeeで作成できそう。

### 登記書類の作成

- 設立登記申請書（申請書+登記すべき事項を記した用紙＋登録免許税貼付台紙）
- 払込証明書

### 印鑑届出書

印鑑届出書とは、会社の実印となる代表者印を法務局に申請するためのもの。

#### 印鑑の作成
印鑑の大きさは、商業登記規則の第9条で定められている大きさで作成する（参照: 商業登記規則 第9条）
```
印鑑の大きさは、辺の長さが一センチメートルの正方形に収まるもの又は辺の長さが三センチメートルの正方形に収まらないものであつてはならない。
```

#### 印鑑届出書

下記のところからダウンロードして記入する。

商業・法人登記の申請書様式：法務局 -> 第８ 印鑑届書 -> 持分会社
http://houmukyoku.moj.go.jp/homu/COMMERCE_11-1.html#anchor8

### 代表社員就任承諾書

定款に記載した場合は必要なし。

### 代表社員、本店所在地及び資本金決定書

定款に記載した場合は必要なし。


### 法人設立届出書

- 法人設立の日以後2ヶ月以内に税務署に提出する。
- 届出書は下記のページからダウンロードできる `［手続名］内国普通法人等の設立の届出｜国税庁`
https://www.nta.go.jp/taxes/tetsuzuki/shinsei/annai/hojin/annai/1554_2.htm



## 健康保険

- 医療保険制度には `健康保険組合` と `全国健康保険協会（協会けんぽ）` がある。
- 健康保険組合は被保険者数が700人以上が対象。
- エンジニアが法人成りするケースでは、個人事業主の場合の`国民健康保険`から`協会けんぽ`に変更するケースが多い。

健康保険の新規適用手続きは`日本年金機構`に説明がある。
http://www.nenkin.go.jp/service/kounen/jigyosho-hiho/jigyosho/20150311.html

また、上の事業者としての届けの他に、役員を含めた従業員分の被保険者としての届けも必要である。
http://www.nenkin.go.jp/service/kounen/kenpo-todoke/hihokensha/20140718.html

※ 法人成りとは関係ないが、40歳から64歳までは介護保険料（1.5%前後）も加算される。
https://www.kyoukaikenpo.or.jp/g3/cat330/1995-298


## 厚生年金保険

新規適用手続きは、健康保険と同じ用紙のため一緒に申請する。

厚生年金保険料については `都道府県毎の保険料額表 | 全国健康保険協会` を参照。
https://www.kyoukaikenpo.or.jp/g3/cat330/sb3150/

平成30年度 東京の場合、18.3000%。

従業員であれば労使折半となるが、フリーランスエンジニアで法人成りしたケースでは、結局は全て自身で支払う必要がある。

## 労働保険（労災保険・雇用保険）

労働者（パートタイマー、アルバイトを含む、役員は除く）を一人も雇用していなければ、労働保険（労災保険、雇用保険）に加入する必要はない。

参考: 労働保険とはこのような制度です｜厚生労働省
https://www.mhlw.go.jp/bunya/roudoukijun/howtoroudouhoken/index.html

## 法人向けの生命保険（退職金積立て）

### 退職金

退職所得の計算方法
```
（源泉徴収される前の金額 - 退職所得控除額） ✕ 1/2 = 退職所得の金額
```

|勤続年数A|退職所得控除額|
|---|---|
|20年以下|40万円✕A|
|20年超|800万円 + 70万円✕(A - 20年)|

### キーワード

- 全額損金、半額損金がある（半額が損というわけではないらしい）
- 養老保険
- 法人保険は損金扱いにできる
- ニッセイ福利厚生プランについて
https://www.nissay.co.jp/hojin/shohin/keiei/plan/


## 経営セーフティ共済

- 取引先が倒産した場合などに借入れできる制度。
- 掛金は月額5千円〜20万円で、損金にできるため節税効果がある。
- 解約時には、条件によっては掛金の100%が解約手当金となる。

### 注意事項

- *解約手当金は収入となるため、結局は納税の先延ばし、あるいはある程度のコントロールができるだけ、という点に注意。*
- 収益の大きなブレがないフリーランスエンジニアの場合は、節税のコントロールの余地が少なく、メリットがないのではないか（個人の考え）。

### 経営セーフティ共済の参考URL
- 中小機構: http://www.smrj.go.jp/kyosai/tkyosai/about/features/index.html


## パートナーを役員にする場合

- 業務時間・内容によって、常勤役員・非常勤役員のどちらになるかが決まる。
- フリーランスエンジニアのパートナーで、月に数日、数時間程度の経理作業を手伝っているくらいの場合、非常勤役員とすることができる。
- 非常勤役員かつ、年103万円以下の給与の場合、所得税がかからない。
- また年130万円以下の場合には、社会保険証は被扶養者（第3号）の扱いとなる。

### パートナーを役員にする場合の参考URL
- https://www.nta.go.jp/taxes/shiraberu/taxanswer/shotoku/1800.htm


## クラウド会計ソフト freee 法人向け料金プラン

|プラン名|月額|年額|
|---|---|---|
|ライト|約2,140円|約21,400円|
|ビジネス|約4,300年|約43,000円|

### 会社設立 freee を利用する場合の特記事項
- 通常であれば、電子定款の事務手数料が5,000円。年間契約することで0円になるキャンペーン中。
- 2018年7月に新プランの提供開始予定

### freee の参考URL

- 会社設立 freee: https://www.freee.co.jp/launch/
- 法人プラン: https://www.freee.co.jp/houjin/price/
