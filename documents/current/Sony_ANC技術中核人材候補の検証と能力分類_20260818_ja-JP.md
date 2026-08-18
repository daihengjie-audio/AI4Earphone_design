# Sony ANC技術中核人材候補の検証と能力分類

- バージョン：v1.1
- 検証日：2026-08-18
- 対象：Sonyの公開技術インタビュー、製品開発者インタビュー、公開特許、論文
- 用途：技術人材調査、協業・採用前の公開情報による一次スクリーニング

> 本文は公開された職務情報のみを使用し、私的な連絡先は収集しない。特許の発明者であることは、当該請求項に記載された発明への貢献を示すにとどまり、現在の役職、製品責任者としての地位、または全技術能力を自動的に証明するものではない。Google Patentsの法的状態表示も正式な法的見解ではない。

## 1. 結論概要

候補リストの技術方向は概ね妥当だが、元の記述には、公式に確認できる製品上の役割、特許発明者としての記録、未確認の個人帰属が混在している。公開証拠の強さに基づき、以下の人材プールに整理することを推奨する。

1. **ANC全体アーキテクチャ／技術リーダーシップ**：Kohei Asada（浅田宏平）が最も強い証拠を持つ。
2. **中核ANC/DSP／個人最適化**：Shinpei Tsuchiya、Tetsunori Itabashi、Yushi Yamabe、Shigetoshi Hayashi。
3. **適応モード／装着状態・音響経路推定**：Yushi Yamabe、Kyosuke Matsumoto、Yasunobu Murata、Mahendra Kodavati、Naoki Shinmen。
4. **マイク、風雑音、AI音認識**：Yuji Tokozume、Shogo Shinkai、Hayami Tobise。
5. **ドライバーユニット／音響設計**：Kohei Kikuchi。
6. **機構小型化／製品パッケージング**：Dai Matsubara。
7. **現行製品レベルのANC追加候補**：Masayoshi Hasegawa。公開された開発者インタビューではWF-1000XM5のANC音響担当とされ、追加価値が高い。

重要な事実修正：

- 浅田氏の日本語氏名は **浅田宏平** であり、「浅田浩平」ではない。
- 床爪氏の論文上の氏名は **Yuji Tokozume／床爪佑司** であり、「床爪裕次」ではない。
- 英語表記は **Shinpei Tsuchiya** であり、「Tsuchiva」ではない。
- US12100379B2の発明者は **Yushi YamabeとMahendra Kodavati** であり、Yasunobu Murataではない。
- **Hayami TobiseとMahendra Kodavatiは別人で、公開特許上の技術領域も異なる**。一つの候補として統合すべきではない。
- US9236041B2の発明者が **Kohei AsadaとTetsunori Itabashi** である点は確認できた。
- 同族特許、共同発明、製品インタビューだけから、個人をWF-1000XM4/XM5の「技術責任者」と断定できない。本稿では該当記述を「公開確認できず」として扱う。

## 2. 能力分類マトリクス

| 候補者 | A 全体構想/リーダー | B ANC/DSP | C 適応/個人最適化 | D マイク/風雑音/AIセンシング | E ユニット/受動音響 | F 機構/小型化 | G 空間/オープン型ANC | 証拠レベル |
|---|---:|---:|---:|---:|---:|---:|---:|---|
| Kohei Asada 浅田宏平 | ★★★ | ★★★ | ★★★ | ★ | ★ | ★ | ★★★ | A |
| Shinpei Tsuchiya 土屋慎平 | ★★ | ★★★ | ★★★ | ★ | — | — | ★ | A |
| Tetsunori Itabashi 板橋哲紀（漢字は本人一次情報で要確認） | ★ | ★★★ | ★ | — | — | — | ★★ | B |
| Yushi Yamabe 山部雄史 | ★★ | ★★★ | ★★★ | ★★ | — | — | ★ | A-/B+ |
| Shigetoshi Hayashi 林重俊 | ★ | ★★★ | ★★ | ★ | ★ | — | ★★★ | B |
| Naoki Shinmen 新免直樹 | — | ★★ | ★★ | ★ | ★★★ | ★★ | ★★★ | B |
| Yasunobu Murata 村田泰伸 | — | ★★ | ★★★ | ★ | — | — | ★ | B |
| Mahendra Kodavati | — | ★★ | ★★★ | ★ | — | — | ★ | B |
| Kyosuke Matsumoto 松本恭輔（漢字は本人一次情報で要確認） | — | ★★ | ★★★ | ★★ | — | — | — | B |
| Yuji Tokozume 床爪佑司 | — | ★★ | ★★ | ★★★ | — | — | — | A-/B+ |
| Shogo Shinkai 新開章吾（特許上の表記） | — | ★ | ★ | ★★★ | ★★ | ★ | — | B |
| Hayami Tobise 飛瀬隼美（漢字は本人一次情報で要確認） | — | — | — | ★★★ | ★★ | ★★ | — | B |
| Kohei Kikuchi 菊地浩平 | — | ★ | — | — | ★★★ | ★ | — | A |
| Dai Matsubara 松原大 | — | — | — | ★ | ★ | ★★★ | — | A |
| Masayoshi Hasegawa（追加候補） | ★ | ★★★ | ★★ | ★★ | ★★ | — | — | A-/B+ |

証拠レベル：A＝Sony公式ページまたは公式製品開発者インタビューが直接支持、B＝特許・論文・信頼できる媒体が技術貢献を直接支持、C＝弱い手掛かりまたは二次的帰属のみ。星数は能力領域との公開証拠上の関連度であり、社内職位を示さない。

### 2.1 年齢、経験年数、役職／Leader類型マトリクス

| 候補者 | 年齢／経験（2026年時点） | 公開役職または役割 | Leaderか、どの類型か | 判断根拠 |
|---|---|---|---|---|
| Kohei Asada 浅田宏平 | **年齢非公開**；1993年入社、Sony在籍約33年 | Corporate Distinguished Engineer | **該当：L1 組織横断の音響技術戦略Leader** | Sony公式が、組織横断の音技術戦略と人材育成を率いる責任を明記 |
| Shinpei Tsuchiya 土屋慎平 | **約39～41歳（低確度推定）**；2007年学部卒、2009年入社 | Sony R&D CenterのANC研究開発 | **L3/L4 アルゴリズム・個人最適化の中核貢献者**；正式な人事管理職の証拠なし | 九州大学の経歴、SonyのWH-1000XM3公式インタビュー |
| Tetsunori Itabashi | **年齢非公開**；少なくとも2006年からANC特許活動 | Sony/Sony Groupの研究著者・発明者 | **L3/L4 ANCフィルタ・空間ANCのシニア技術貢献者**；組織Leaderは未確認 | 初期デジタルANC特許、2022年空間ANC論文 |
| Yushi Yamabe 山部雄史 | **年齢非公開**；少なくとも2000年代後半からANC発明活動 | Sony Corporation；2022 Sony Outstanding Engineer | **L2 プリンシパル専門家型の技術中核**；最高位の個人工学表彰だが管理職とは限らない | Sony Outstanding Engineer Award 2022公式ページ |
| Shigetoshi Hayashi 林重俊 | **年齢非公開**；少なくとも2000年代から音響発明活動 | Sony Groupの研究著者・発明者 | **L3 空間／オープン型ANC技術中核**；正式な管理職の公開証拠なし | ANC特許、Sony掲載の2022年空間ANC論文 |
| Naoki Shinmen 新免直樹 | **年齢非公開**；少なくとも2010年代から音響発明活動 | Sony発明者 | **L4 音響経路／構造技術貢献者**；Leader身份は未確認 | 音響経路、オープン型ANC特許 |
| Yasunobu Murata 村田泰伸 | **年齢非公開**；少なくとも2010年代からANC発明活動 | Sony発明者 | **L4 こもり感、外音、補正アルゴリズム貢献者**；Leader身份は未確認 | ANC、外音、個人補正特許 |
| Mahendra Kodavati | **年齢非公開**；少なくとも2019年から関連特許活動 | Sony発明者 | **L4 装着状態／音響経路の技術貢献者**；Leader身份は未確認 | US12100379B2 |
| Kyosuke Matsumoto | **年齢非公開**；少なくとも2016年から関連特許活動 | Sony発明者 | **L4 適応モード／信号処理貢献者**；Leader身份は未確認 | US11030988B2等 |
| Yuji Tokozume 床爪佑司 | **約31～34歳（低確度推定）**；2016年に東京大学修士課程、その後Sony R&D | Sony Groupの研究著者・発明者 | **L4 AI音認識／振動センシング専門家**；WF-1000XM4/XM5のプロジェクトLeaderは未確認 | 東京大学/OpenReviewの経歴、論文、Sony特許 |
| Shogo Shinkai 新開章吾 | **年齢非公開**；少なくとも2010年代から関連特許活動 | Sony発明者 | **L4 風雑音／マイク音響構造の貢献者**；Leader身份は未確認 | 風雑音信号処理、流路／空洞特許 |
| Hayami Tobise | **年齢非公開**；少なくとも2020年代から関連特許活動 | Sony発明者 | **L4 風雑音流路／空洞構造の貢献者**；Leader身份は未確認 | US20250227403A1 |
| Kohei Kikuchi 菊地浩平 | **年齢非公開**；WF-1000XM5/XM6への参加を公開確認 | Sonyヘッドホン音響設計担当 | **L3 製品音響機能領域の技術Owner／中核メンバー**；人事管理Leaderとは確認できない | Sony WF-1000XM5/XM6公式開発者ページ |
| Dai Matsubara 松原大 | **年齢非公開**；WF-1000XM5への参加を公開確認 | Sonyヘッドホン機構設計担当 | **L3 製品機構機能領域の中核メンバー**；機構チーム責任者とは確認できない | WF-1000XM5開発インタビュー |
| Masayoshi Hasegawa（追加） | **年齢非公開**；公開資料では2016年からSonyヘッドホン音響に従事 | WF-1000XM5 ANC音響担当 | **L3 製品ANC機能領域の技術Owner／中核メンバー**；組織管理Leaderとは確認できない | Sony公式開発者ページと開発インタビューの交差確認 |

年齢の扱い：Sonyは大半の技術者の生年月日を公開していない。TsuchiyaとTokozumeのみ、公開された学歴年から広い年齢範囲を示したが、いずれも**低確度の推定であり、公開された実年齢ではない**。他の人物については、特許年や外見から年齢を推測せず、確認可能な職務活動開始時期を代替指標として示した。

Leader類型：

- **L1 戦略技術Leader**：組織横断の技術戦略や人材方針を公に担う。現時点で公式に直接確認できるのはAsadaのみ。
- **L2 プリンシパル専門家／表彰型技術中核**：社内最高水準の個人工学表彰を受け、技術方向に影響し得るが、組織管理職とは限らない。Yamabeが該当。
- **L3 製品・機能領域の技術Owner／中核メンバー**：特定製品世代のANC、音響、機構、アルゴリズムに公開された責任を持つが、人事管理を行うとは限らない。
- **L4 シニア研究／発明貢献者**：特許・論文で継続的な技術貢献は確認できるが、正式なLeader肩書やプロジェクト管理権限を示す公開情報はない。

## 3. 候補者別検証

### 3.1 Kohei Asada／浅田宏平 — 維持、最優先

- **確認済み**：1993年にSony入社。2008年発売の世界初デジタルノイズキャンセリングヘッドホンMDR-NC500Dの開発を率いた。Sony Distinguished Engineer。
- **確認済み**：Sony公式WH-1000XM3インタビューは、AsadaとShinpei Tsuchiyaが新ANCアルゴリズムを開発し、商品設計部門とQN1を開発したと明記する。
- **確認済み**：近年のSony公式インタビューは、空間NCと音波伝搬制御への取り組みを明記する。
- **判断**：ANC技術戦略、システム構想、世代横断アルゴリズム基盤、空間ANCの中核候補として最適。
- **修正**：「ANCの魂」といった主観表現を避け、「デジタルANC開発リーダー、Sony Distinguished Engineer」とする。
- 出典：[Sony Distinguished Engineer](https://www.sony.com/en/SonyInfo/technology/distinguished_engineer/KoheiAsada.html)、[Sonyインタビュー](https://www.sony.com/en/SonyInfo/technology/stories/entries/interview_de_asada/)、[WH-1000XM3公式インタビュー](https://www.sony.com/en/SonyInfo/technology/stories/entries/WH-1000XM3/)

### 3.2 Shinpei Tsuchiya／土屋慎平 — 維持、高優先

- **確認済み**：Sony公式WH-1000XM3インタビューでは、新ANCアルゴリズム／QN1開発メンバーであり、Personal NC Optimizerの開発担当と明記される。
- **特許証拠**：Asadaらと、耳装着型収音、ヘッドホン装置、FF ANC関連発明に参加。
- **判断**：ヘッドホンANCアルゴリズム、個人補正、製品実装が強み。
- **修正**：「超低遅延ANC」は主にAsadaの公式インタビューで支持され、Tsuchiya単独の成果としては扱わない。
- 出典：[WH-1000XM3公式インタビュー](https://www.sony.com/en/SonyInfo/technology/stories/entries/WH-1000XM3/)、[九州大学公開経歴](https://www.design.kyushu-u.ac.jp/en/topics/4377/)、[US10667047B2](https://patents.google.com/patent/US10667047B2/en)

### 3.3 Tetsunori Itabashi — 維持、高優先

- **確認済み**：US9236041B2の発明者はKohei AsadaとTetsunori Itabashi。デジタル経路と並列アナログ経路を組み合わせ、帯域、低減量、デジタル機能の両立を狙うノイズキャンセル用フィルタ回路。
- **判断**：ANC中核回路／DSP構成に分類する。後年の共同論文だけから「空間ANC責任者」とは断定しない。
- **法的状態の注意**：Google Patentsは米国特許をfee-related expiredと表示するが、正式判断にはUSPTO案巻確認が必要。
- 出典：[US9236041B2](https://patents.google.com/patent/US9236041B2/en)、[Sony掲載の空間ANC論文](https://www.sony.com/ja/SonyInfo/technology/publications/secondary-channel-estimation-in-spatial-active-noise-control-systems-using-a-single-moving-higher-order-microphone/)

### 3.4 Yushi Yamabe／山部雄史 — 維持、高優先

- **特許証拠**：US11030988B2は環境音の動的解析、ANC／外音モードおよび制御を扱う。Asada、Murataとの特許はANC、外音、こもり感除去信号の組み合わせを扱う。
- **特許証拠**：US12100379B2はMahendra Kodavatiとの共同発明で、音響経路／装着状態解析に基づくANC処理を扱う。
- **公式評価**：Sony Outstanding Engineer Award 2022で、1000Xシリーズを進化させたノイズキャンセリング音響技術への貢献が最高位の個人工学表彰を受けた。
- **判断**：適応外音モード、音響経路／装着状態、ANCと外音の協調が強み。
- **修正**：Sony公式製品ページで本人がWH-1000XM3責任者である証拠は見つからない。「関連技術の中核発明者」とし、「XM3プロジェクト責任者」としない。
- 出典：[Sony Outstanding Engineer Award 2022](https://www.sony.com/en/SonyInfo/technology/stories/entries/SOE2022/)、[US11030988B2](https://patents.google.com/patent/US11030988B2/en)、[US12100379B2](https://patents.google.com/patent/US12100379B2/en)、[Yushi Yamabe特許一覧](https://patents.justia.com/inventor/yushi-yamabe)

### 3.5 Yasunobu Murata／村田泰伸 — 維持、特許帰属を修正

- **確認済み**：Asada、Yamabeとの共同特許は、ANC信号、外音／こもり感除去信号とその混合、位置に基づくモード制御を直接扱う。
- **確認済み**：AsadaとのUS20230223001/US12300210は、耳内音響特性、補正フィルタ、学習モデルを扱う。
- **誤り修正**：US12100379B2はMurataの特許ではない。発明者はYamabeとKodavati。
- **判断**：こもり感、外音融合、個人音響補正に分類する。WF-1000XM4/XM5での具体的役割は未確認。
- 出典：[Yasunobu Murata特許一覧](https://patents.justia.com/inventor/yasunobu-murata)、[US12300210B2](https://patents.google.com/patent/US12300210B2/en)

### 3.6 Shigetoshi Hayashi／林重俊 — 維持、高優先

- **特許証拠**：Asada、Itabashiらと、低コスト雑音低減、適応雑音制御、耳内個人差パラメータ選択、オープン型ヘッドホンANCなどに参加。
- **論文証拠**：2022年の空間ANC二次経路推定論文のSony側著者。
- **判断**：ANCシステムアルゴリズム、個人差推定、オープン型／空間シナリオが強み。「マルチマイク」は各特許で確認し、唯一の中核タグに一般化しない。
- 出典：[Shigetoshi Hayashi特許一覧](https://patents.justia.com/inventor/shigetoshi-hayashi)、[US11445289B2](https://patents.google.com/patent/US11445289B2/en)、[Sony掲載の空間ANC論文](https://www.sony.com/ja/SonyInfo/technology/publications/secondary-channel-estimation-in-spatial-active-noise-control-systems-using-a-single-moving-higher-order-microphone/)

### 3.7 Naoki Shinmen／新免直樹 — 維持、中高優先

- **特許証拠**：US20210295815A1/US11664006B2は、ドライバー前面空間から外部への音響経路と開口近傍マイク配置により、雑音低減効果とシステム安定性を改善する。オープン型ANC発明にも参加。
- **判断**：音響経路、トランスデューサ／マイク配置、オープン構造、システム安定性が強み。
- **修正**：「イヤーピース、ドライバー前後空洞、受動遮音責任者」という元記述は具体的すぎ、公開証拠が不足する。
- 出典：[US20210295815A1](https://patents.google.com/patent/US20210295815A1/en)、[US11445289B2](https://patents.google.com/patent/US11445289B2/en)

### 3.8 Yuji Tokozume／床爪佑司 — 維持、AIセンシングで高優先

- **論文証拠**：ICLR 2018論文は深層音認識を扱い、先行論文はエンドツーエンド環境音分類を扱う。
- **特許証拠**：US20240274151A1はYuki Yamamoto、Toru Chinenとの共同発明で、複数マイクにより装着者の特定音／発話と他者音声を区別する。特許一覧には風雑音制御、振動／骨センシングも含まれる。
- **判断**：DNN音イベント／音声検出、マルチマイクと振動センサ融合が強みで、従来型ANCフィルタそのものが主領域ではない。
- **修正**：WF-1000XM4/XM5「技術責任者」の公開証拠はなく、Speak-to-Chatの全実装を本人に単独帰属させない。
- 出典：[ICLR 2018](https://openreview.net/forum?id=B1Gi6LeRZ)、[US20240274151A1](https://patents.google.com/patent/US20240274151A1/en)、[特許一覧](https://patents.justia.com/inventor/yuji-tokozume)

### 3.9 Shogo Shinkai／新開章吾 — 維持、風雑音／構造領域

- **特許証拠**：US20250227403A1はHayami Tobiseらとの共同発明で、FFマイク周辺の流路、空洞、開口面積比、メッシュ、Helmholtz構造による風雑音低減を扱う。
- **特許証拠**：左右風雑音検出・制御に関する公開にも発明者として記録される。
- **判断**：風雑音、マイク音響空洞、構造とアルゴリズムの協調に適する。
- **修正**：「二重FF/FB構成責任者」とする証拠は不足。タッチセンサ特許とヘッドホンANCへの貢献も分けて扱う。
- 出典：[US20250227403A1](https://patents.google.com/patent/US20250227403A1/en)

### 3.10 Hayami Tobise — 維持、風雑音構造領域

- **特許証拠**：US20250227403A1の共同発明者で、風雑音流路、空洞、開口構造への貢献を直接支持する。
- **判断**：マイク周辺の流体／音響構造、機械的風雑音抑制に適する。
- **修正**：Mahendra Kodavatiと統合しない。両者の公開特許と能力証拠は異なる。
- 出典：[US20250227403A1](https://patents.google.com/patent/US20250227403A1/en)

### 3.11 Mahendra Kodavati — 維持、装着／音響経路領域

- **特許証拠**：US12100379B2はYamabeとの共同発明で、ANCフィルタ、音響経路／イヤーパッド状態解析と対応処理を扱う。
- **判断**：装着状態、音響経路同定、ANC適応に適する。風雑音空洞の候補ではない。
- 出典：[US12100379B2](https://patents.google.com/patent/US12100379B2/en)

### 3.12 Kyosuke Matsumoto — 維持、中優先

- **特許証拠**：US11030988B2はYamabe、Asadaとの共同発明で、環境音特徴の動的解析、フィルタリング、複数処理モードの制御を扱う。
- **判断**：適応外音／ANCモードと環境切替に適する。
- **修正**：「聴力補償責任者」という広いタグを支持する公開証拠は不足する。
- 出典：[US11030988B2](https://patents.google.com/patent/US11030988B2/en)

### 3.13 Kohei Kikuchi／菊地浩平 — 維持、ユニット／音響設計で高優先

- **公式証拠**：Sony WF-1000XM5開発者ページはKikuchiを音響設計メンバーとして掲載する。Dynamic Driver Xの構造、材料、チューニングを音響チームが説明する。WF-1000XM6ページでも音響設計として掲載。
- **特許証拠**：スピーカー装置、振動板エッジ関連特許はトランスデューサ構造能力を補強する。
- **判断**：ドライバーユニット、振動板、音響チューニング、ANC逆相信号の正確な再生が強み。ANCアルゴリズム責任者ではない。
- 出典：[WF-1000XM5公式開発者インタビュー](https://www.sony.jp/feature/products/headphone/230726_01/)、[WF-1000XM6公式開発者インタビュー](https://www.sony.jp/feature/products/music/260213/)、[US10993018B2](https://patents.google.com/patent/US10993018B2/en)

### 3.14 Dai Matsubara／松原大 — 維持、機構／小型化領域

- **信頼できる媒体の証拠**：WF-1000XM5発表時の開発インタビューで機構設計メンバーとして掲載。
- **判断**：製品レイアウト、小型化、構造統合、量産機構設計に適する。
- **修正**：SiPチップ設計や風雑音の空力設計全体を本人に帰属させる公開証拠は不足。「WF-1000XM5の機構設計貢献者」とする。
- 出典：[AV Watch開発インタビュー](https://av.watch.impress.co.jp/docs/news/1518887.html)

### 3.15 Masayoshi Hasegawa — 追加、高優先

- **公式／媒体交差証拠**：Sony WF-1000XM5公式開発者ページはANC音響担当Hasegawaを掲載し、What Hi-Fiの開発者インタビューはフルネームをMasayoshi Hasegawaとし、WF-1000XM5のANCを担当したと説明する。
- **判断**：元リストで欠けていた、現行TWS製品ANCの実装に最も近い候補。Asadaの長期アーキテクチャ役割と区別し、Hasegawaは現行製品レベルのANC音響実装に重点がある。
- **制限**：名の漢字と現在の社内職位はSony公式英語ページで直接確認できないため、推測で補わない。
- 出典：[WF-1000XM5公式開発者インタビュー](https://www.sony.jp/feature/products/headphone/230726_01/)、[What Hi-Fiインタビュー](https://www.whathifi.com/features/i-spoke-to-sonys-audio-experts-about-how-they-tune-the-wf-1000xm5-earbuds-stunning-sound)

## 4. 目的別の推奨人材構成

| 目的 | 第一候補 | 次候補／補完 | 理由 |
|---|---|---|---|
| 次世代ANC全体ロードマップ | Kohei Asada | Tetsunori Itabashi、Shinpei Tsuchiya | アーキテクチャ、デジタルANCの蓄積、製品アルゴリズム、個人最適化を補完 |
| オーバーヘッド型ヘッドホンANC/DSP | Shinpei Tsuchiya | Yamabe、Hayashi、Itabashi | QN1／個人最適化、環境モード、フィルタ構成 |
| TWS製品ANC実装 | Masayoshi Hasegawa | Kohei Kikuchi、Dai Matsubara | ANC音響、ドライバーによる逆相再生、機構小型化 |
| 装着差／漏れ適応 | Yamabe、Kodavati | Murata、Shinmen、Hayashi | 音響経路、イヤーパッド／装着状態、補正、安定性 |
| AI音認識／発話検出 | Yuji Tokozume | Kyosuke Matsumoto | DNN音認識、マルチマイク／振動融合、環境モード |
| 風雑音／マイク構造 | Shogo Shinkai、Hayami Tobise | Tokozume | 物理流路／空洞と検出アルゴリズムの補完 |
| ドライバー／受動音響 | Kohei Kikuchi | Naoki Shinmen | ユニット構造、逆相信号再生、音響経路 |
| オープン型／空間ANC | Kohei Asada、Shigetoshi Hayashi | Naoki Shinmen、Itabashi | 空間伝搬、オープンシステム、経路／構造、アルゴリズム |

## 5. 推奨する追加検証

1. Sony公式または本人の公開職務ページで、現在の在籍、所属組織、公開連絡経路を確認する。特許だけでは現在の在籍を証明できない。
2. 優先候補ごとに直近5～10件の特許族の独立請求項を抽出し、アルゴリズム、音響、機構、製品協調への貢献を分ける。
3. 「製品責任者／技術責任者」は、Sony公式開発者ページ、本人講演、信頼できる媒体の直接引用だけで認定する。直接証拠がなければ「関連発明への参加」とする。
4. 採用・協業では単一の「ANCの達人」を探すのではなく、アルゴリズム、マイク／風雑音、ドライバー、機構パッケージング、量産調整の少なくとも4能力を組み合わせる。

## 6. 総合信頼度

- **高信頼**：Asada、Tsuchiya、Kikuchi、Matsubara、Hasegawaの公開製品役割；Asada/ItabashiのUS9236041；Yamabe/KodavatiのUS12100379；Tokozumeの論文およびマルチマイク／振動音認識特許。
- **中信頼**：Hayashi、Shinmen、Murata、Matsumoto、Shinkai、Tobiseの技術方向は特許群で支持できるが、現在の役職と具体的製品責任は追加確認が必要。
- **使用すべきでない記述**：Murata＝US12100379の発明者、Tokozume＝WF-1000XM4/XM5技術責任者、Matsubara＝SiPチップ設計者、Shinkai＝二重FF/FB総合アーキテクチャ責任者。これらは現在の公開証拠に反するか、証拠不足である。
