---
title: データ編
tags: [2025 China Open Source Report]
---

# データ編

## 一、データ編の概要

### 1.1 オープンソース開発目標：世界的なビジョンから中国での実践へ

オープンソースは、ソフトウェア開発の一形態から、デジタル文明を支える基礎的な公共インフラへと発展してきた。オープンソースが社会、経済、技術の進歩にもたらす総合的な価値を体系的に評価するため、中国科学技術協会の国連経済社会理事会（ECOSOC）協議資格を持つオープンソース・イノベーション専門委員会は 2025 年、**「オープンソース開発目標」（Open Source Development Goals：OSDGs）**を正式に提唱した。これは、国連の持続可能な開発目標（SDGs）から着想を得て、オープンソースエコシステム向けに設計された世界規模の評価フレームワークである。

OSDGs は、**オープンソースは、より公正で効率的かつ持続可能な世界にどのように貢献できるか**という根本的な問いに答えることを目指している。従来の「コード数」や「Star 数」といった単一の尺度を超え、知識共有の促進、社会的に不利な立場にある人々の支援、グリーンコンピューティングの推進、デジタル主権の確保など、オープンソースがもたらす本質的な価値に注目する。このフレームワークは、次の三つの柱で構成される。

- **環境（Planet）**：エネルギー効率の最適化、資源節約、グリーン技術のイノベーションにおけるオープンソースの役割を評価する。
- **社会（People）**：教育機会の拡大、スキル向上、コミュニティの包摂性、人材の多様性における成果を測る。
- **ガバナンス（Governance）**：標準の共同策定、ルールの透明性、公正な協働、エコシステムの健全性を支える仕組みを評価する。

<center><img src="/image/data/figure-1-1-osdgs-framework.png" width="700"></center>

<center>図 1.1 OSDGs の全体フレームワーク</center>

<center>出典：『2025 全球开源发展报告』（日本語訳：2025 年世界オープンソース発展報告）</center>

『2025 中国オープンソース年度報告』は今年、OSDGs フレームワークを初めて全面的に採用し、データ編の構成を抜本的に見直した。中国の実情に立脚しながら、世界的なビジョンを中国国内の行動指針へと落とし込んでいる。本報告では、以下の主要な論点に焦点を当てる。

- 世界のオープンソース協働ネットワークにおける中国の開発者の役割と貢献の質
- オープンソースが中国の新たな質の生産力の発展と、重要技術の自立性・管理可能性の向上にどう寄与するか
- 地域間の調和ある発展という観点から見た、各省・市のオープンソースエコシステムの異なる発展経路と連携の可能性
- 「将来の貢献者」となる大学および若手開発者の育成の仕組みと参加の深さ

中国での実践を OSDGs の世界的な座標軸に位置づけることで、国際的な先進水準との比較と、中国独自のオープンソース発展経路の明確化を両立できる。これにより、政策立案、産業配置、コミュニティ形成に向けて、戦略性と実践性を兼ね備えた洞察を提供する。

### 1.2 指標体系とデータソース

OSDGs の各目標の達成度を科学的かつ客観的に測るため、本報告は**三層からなる段階的なオープンソース評価指標体系**を構築した。これは『2025 全球开源发展报告』（日本語訳：2025 年世界オープンソース発展報告）を基礎とし、中国のエコシステムの特徴に合わせて調整したものである。「行動―質―影響力」を論理的な軸として、段階的に評価を深める。

#### 1.2.1 第 1 層：活発度（Activity）

活発度は評価の基礎であり、実際に協働へ参加している開発者とプロジェクトを抽出するために用いる。本報告では、次の五種類の主要な貢献行動を活発度の構成要素として定義する。

- **OI（Open Issue）**：Issue を作成し、問題や要望を提示する。
- **ID（Issue Discussion）**：Issue の議論に参加し、フィードバックや解決策を提供する。
- **OPR（Open Pull Request）**：コードのマージリクエストを提出し、コードまたはドキュメントに貢献する。
- **PRR（Pull Request Review）**：他者のコードをレビューし、品質を確保する。
- **MPR（Merge Pull Request）**：Pull Request をマージし、統合を完了する。

集計期間中に上記のいずれかの行動を行ったアカウントのみを「アクティブ開発者」と認定する。この基準により、「Star」や「Fork」だけの参加度が低い行動を除外し、以降の分析を実際の協働データに基づいて行うことができる。

#### 1.2.2 第 2 層：貢献の質（Quality of Contribution）

活発な参加者を特定した後、その貢献の価値をさらに評価する必要がある。本報告は**「コミュニティ OpenRank」アルゴリズム**を採用し、個々のプロジェクト内の協働ネットワークに注目する。このアルゴリズムは、行動の種類（例：MPR は OI より重みが大きい）、交流相手（主要メンテナーとの交流は重みが大きい）、採用率などに基づき、特定プロジェクトにおける開発者の相対的な貢献の質を算出する。これにより、真の「コア貢献者」を特定する。

#### 1.2.3 第 3 層：影響力（Influence）

最終的には、個人や組織の貢献を世界のオープンソースエコシステムの中に位置づける必要がある。本報告は**「グローバル OpenRank」アルゴリズム**を採用し、数十億のノードを含む世界規模の開発者・プロジェクト協働グラフを構築する。このアルゴリズムは PageRank の考え方を応用し、「質の高い貢献者から注目され、協働の対象となるプロジェクトや開発者は、それ自体の影響力も高い」と捉える。これにより、プロジェクト、組織、地域を横断した統一的な影響力ランキングを作成し、企業、大学、行政区画、国家が世界のオープンソースエコシステムで占める戦略的位置を評価できる。

#### 1.2.4 データソースと処理

本研究のデータ収集と分析には、**[OpenDigger オープンソースプロジェクト](https://github.com/X-lab2017/open-digger)**と、その**[オンラインサービス](https://open-digger.cn)**を利用した。すべての行動データは、このプラットフォームを通じて体系的に収集・処理している。

対象期間は **2025 年 1 月 1 日から 2025 年 12 月 31 日まで**である。OpenDigger プラットフォームが構築した多次元のタグ体系（中国の 34 省級行政区、1,000 以上の企業、200 以上の技術分野など）を用い、世界のマクロ動向から中国国内のミクロなエコシステムまでを一貫して分析した。すべての生データと分析コードをオープンソースとして公開し、研究の透明性、検証可能性、再現可能性を確保している。

OpenDigger は、世界のオープンソースエコシステムの透明性と測定可能性の向上を目指すオープンデータ基盤である。X-lab オープンラボが開始し、木蘭オープンソースコミュニティでインキュベートされた。大学、研究機関、企業など、複数の機関による研究成果を技術基盤に取り入れている。OpenDigger は、オープンソースエコシステムの透明性、測定可能性、持続可能性を高めるため、オープンかつ中立で、多様な主体が参加する世界規模の共同ガバナンス体制を構築し、世界のオープンソースガバナンスを支えるデジタル公共インフラ（Public Digital Infrastructure）となることを目指している。

本報告の主要な評価指標である**OpenRank ノーススター指標**（OpenRank North Star Metric）は、OpenDigger の多次元データ体系を基礎として設計されている。OpenRank は、世界で初めて体系的かつ独自に構築されたオープンソース標準体系であり、中国工業情報化部の「2024 年団体標準応用・普及代表事例の公表について」（工信部科函〔2025〕19 号）に選定され、その信頼性と実用的価値が示されている。

図に示すとおり、OpenRank 指標体系は「開発者―プロジェクト」という二次元の視点から、OpenRank 貢献度（Contribution Impact）と OpenRank 影響力（Influence）の二軸による象限モデルを構築し、個人とプロジェクトのオープンソース参加の質と社会的価値を総合的に示す。

<center><img src="/image/data/figure-1-2-openrank-north-star-quadrant.png" width="700"></center>

<center>図 1.2 OpenRank ノーススター指標の象限図</center>

<center>出典：OpenDigger プラットフォーム文書</center>

OpenDigger プラットフォームの主要な成果の一つである OpenRank には、次の五つの特徴がある。

- **グローバルな視点**：複数のプラットフォームやプロジェクトにおける開発者の行動履歴を総合的に評価する。
- **影響力を重視**：貢献数だけでなく、技術の波及力と協働ネットワークにおける位置を重視する。
- **協働と交流を促進**：Issue、Pull Request、コメントなどの交流行動を重視する。
- **長期的な参加を促進**：時間減衰の仕組みを導入し、継続的な貢献を評価する。
- **堅牢性と高い拡張性**：プラットフォーム、言語、分野を横断した統一的な評価に対応する。

詳細は [OpenDigger ユーザー文書](https://open-digger.cn/docs/user-docs/intro)を参照されたい。

本報告では、GitHub、Gitee、AtomGit / GitCode、GitLab など複数のオープンソース協働プラットフォームのデータを分析した。**2025 年末**時点で、GitHub のアクティブ開発者は累計 **2,500 万人**、中国国内の Gitee / AtomGit / GitCode などでは累計約 **1,000 万人**、GitLab では累計約 **80 万人**に達した。アクティブリポジトリ数は、GitHub が **3,600 万件**を超え、中国国内の Gitee / AtomGit / GitCode などが **2,600 万件**を超え、GitLab は約 **73 万件**となった。

過去の中国オープンソース年度報告との大きな違いの一つは、Hugging Face を代表例とするモデルプラットフォームのデータを加え、世界および中国のオープンソースモデルエコシステムの変化をより包括的に観測したことである。2025 年末時点で、Hugging Face には累計約 **234 万件**のモデルと **47 万**のモデル公開者があり、2024 年末からそれぞれ **117 万件**、**21 万**増加した。増加率はそれぞれ **100%**、**80%**である。また、2025 年末までに、累計 **16 万人超**の開発者が協働行動を行い、対象となったモデルは累計 **21 万件超**に達した。2024 年からの増加率はそれぞれ約 **60%**、**140%**である。ここでいう「協働行動」とは、主にモデルリポジトリへの投稿やコメント、編集、リアクションなどの行動を指す。これは、Hugging Face に代表されるモデルプラットフォームが、単なるモデルの公開・配布基盤ではなく、モデル供給の拡大、開発者間の協働、エコシステムからのフィードバック循環を同時に支える重要なインフラへと発展していることを示している。

### 1.3 データ編の全体構成

OSDGs フレームワークに基づいて中国のオープンソースエコシステムの全体像を体系的に示すため、本データ編は四つの主要部分で構成し、「観測―比較―深掘り―展望」という一連の流れを形成する。

**第 2 部：オープンソースエコシステム観測体系**では、空間、主体、技術、人材という四つの側面から、中国のオープンソースエコシステムの基盤を描く四種類の動的マップを構築する。

- **オープンソース活発度マップ**：Activity と OpenRank の指標に基づき、世界の主要な国・地域におけるオープンソース参加の活発度を示す。
- **オープンソース貢献マップ**：Activity と OpenRank の指標に基づき、価値の高い貢献者の地理的分布と所属組織を明らかにする。
- **オープンソース技術マップ**：人工知能、クラウドネイティブ、基盤ソフトウェア、RISC-V などの主要分野における技術の変化とプロジェクト群の分布を追跡する。
- **オープンソース人材マップ**：開発者タグ、成長の軌跡、OSPP の活動データを組み合わせ、次世代のオープンソース人材がどこから生まれ、移動し、成長するかを示す。

**第 3 部：オープンソース影響力ランキング**では、観測結果を基礎として四つの主要ランキングを公表し、指標となる事例と今後の方向性を示す。

- **行政区画影響力ランキング**：世界および中国の各省・市が世界のオープンソースエコシステムで持つ総合的な影響力を定量評価し、地域のデジタル経済発展の評価に役立てる。
- **オープンソース企業影響力ランキング**：中国国内外のテクノロジー企業と非営利組織を対象に、オープンソース戦略への投資、プロジェクトの主導力、コミュニティにおけるリーダーシップを示す。
- **オープンソースプロジェクト影響力ランキング**：グローバル OpenRank 指標に基づき、基盤ソフトウェア、AI フレームワーク、開発ツール、データベースなど複数の分野から、年間で最も影響力のあるオープンソースプロジェクトを選出し、エコシステムにおける位置と協働の広がりを総合的に示す。
- **新興オープンソースプロジェクトランキング**：2025 年に初めて公開され、優れた実績を示した新規プロジェクトに焦点を当て、イノベーションの芽と将来性を捉える。

**第 4 部：オープンソース特別分析**

年間の主要テーマについて、掘り下げた分析を行う。

- **AI 大規模モデル年次分析**：Hugging Face の全体データに基づき、大規模モデルのオープンソースエコシステム、新たな協働形態、ライセンス上の課題、中国製技術への代替経路、コミュニティガバナンスの新たな形を体系的に分析する。
- **Open Source Promotion Plan（OSPP、開源之夏）年次分析**：近年の OSPP 活動データに基づき、大学における人材育成の成果、プロジェクトの完了品質、コミュニティへの成果還元の仕組みを評価し、持続可能なオープンソース教育の発展経路を検討する。

全体として、2025 年のデータ編は OSDGs を軸に三つの主要部を構成し、世界的な共通認識を踏まえながら中国の実情を深く分析する。中国のオープンソースの将来に関心を持つすべての読者に、**信頼でき、透明性が高く、行動につなげられる**年次資料を提供することを目指す。

## 二、オープンソースエコシステム観測体系

### 2.1 オープンソース活発度マップ

#### 2.1.1 位置づけ：オープンソース参加の「地理的基盤」

**オープンソース活発度マップ**（Open Source Activity Map：A-Map）は、世界の開発者によるオープンソース参加の地理的分布と規模を示し、参加の広がりとコミュニティ基盤を明らかにする。「誰が、どこから参加しているのか」を測る中核的な観測軸である。

本節では、**アクティブ貢献者数**（Number of Active Contributors：NAC）を主要指標とし、各国のオープンソースエコシステムへの参加規模と活動基盤を示す。**新規アクティブ開発者**とは、それ以前に対象プラットフォームで活動したことがなく、当該年に初めて活動を開始した開発者を指す。

#### 2.1.2 主な発見：規模の飛躍と構造の再編

#### 2.1.3 世界のアクティブ開発者数が過去最高を更新

GitHub Octoverse Report によると、**2025 年末**時点で世界の開発者数は **1.8 億人**を超え、このうち新規開発者は **3,600 万人超**だった。過去 10 年間に GitHub で活動した開発者（Active Developer）は累計 **2,493 万人**に達した。中国国内の Gitee / AtomGit / GitCode などでは約 **1,000 万人**、GitLab では約 **80 万人**となっている。

2025 年に世界で新たに活動を開始したオープンソース開発者は **500 万人超**だった。内訳は GitHub が **301 万人**、Gitee / AtomGit / GitCode などが全体で **200 万人**（アンケート編の調査データに基づく重複排除後）、GitLab が **12 万人超**である。

<div style="display: flex; justify-content: center; align-items: flex-start; gap: 8px; width: 100%; overflow-x: auto; margin: 16px 0;">
  <img src="/image/data/figure-2-1-new-active-developers-github.png" style="display: block; flex: 0 0 auto; width: calc((100% - 24px) / 4); min-width: 160px; max-width: none; margin: 0;">
  <img src="/image/data/figure-2-1-new-active-developers-gitee.png" style="display: block; flex: 0 0 auto; width: calc((100% - 24px) / 4); min-width: 160px; max-width: none; margin: 0;">
  <img src="/image/data/figure-2-1-new-active-developers-atomgit.png" style="display: block; flex: 0 0 auto; width: calc((100% - 24px) / 4); min-width: 160px; max-width: none; margin: 0;">
  <img src="/image/data/figure-2-1-new-active-developers-gitlab.png" style="display: block; flex: 0 0 auto; width: calc((100% - 24px) / 4); min-width: 160px; max-width: none; margin: 0;">
</div>

<center>図 2.1 2016～2025 年の世界の新規アクティブ開発者数の推移（左から GitHub、Gitee、AtomGit / GitCode、GitLab）</center>

<center>出典：OpenDigger プラットフォームのデータを基に作成</center>

図 2.1 が示すとおり、各プラットフォームにはそれぞれ明確な発展段階が見られる。

- **GitHub**：新規アクティブ開発者数は **158 万人**から **301 万人**へ増え、10 年間でほぼ倍増した。**2025 年は 301 万人**で、**2024 年の 280 万人**から **7.73%**増加した。世界のオープンソースエコシステムが拡大を続けながら、成熟した発展段階へ入りつつあることを示している。
- **Gitee**：2017 年に 42.2 万人へ小幅に減少した後は増加を続け、**2025 年には 161.2 万人**に達した。
- **AtomGit / GitCode**：**2023 年 9 月**に開始し、2025 年 11 月末に統合された新しいプラットフォームで、データは 3 年分に限られるが急速に成長している。**2025 年**の新規アクティブ開発者は **25 万人**で、2024 年の **5 万人**から **335%**増加し、新興プラットフォームの初期に典型的な急拡大を示した。
- **GitLab**：**2016～2022 年**は全体として急速に増え、**2022 年**にピークを迎えた。その後 2023～2024 年に大きく減少し、2025 年はやや回復したものの、開発者数の純増が高水準での調整局面に入ったことを示している。

GitHub と Gitee の全体的な推移からは、次の傾向が読み取れる。

- **2020 年以降、新規開発者数は急速な増加局面に入り**、オープンソースエコシステム全体の活発度と参加規模が拡大を続けた。
- **2020～2021 年の増加率は高水準**だった。その後も増加は続いたものの、伸び率は低下した。
- この変化には**新型コロナウイルス感染症の影響**が考えられる。感染拡大期にはリモートワークとオンライン協働の需要が高まり、開発者の参加を促した。**2022 年以降に感染状況が落ち着く**につれて増加率は通常の水準へ戻り、全体として「**急成長後の安定化**」という特徴を示している。

表 2.1 2016～2025 年の世界の新規アクティブ開発者数の増加率（GitHub）

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;">年</th><th style="text-align: center;">人数</th><th style="text-align: center;">前年比</th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">2017</td><td style="text-align: center;">1,559,743</td><td style="text-align: center;">-1.98%</td></tr>
    <tr><td style="text-align: center;">2018</td><td style="text-align: center;">1,729,865</td><td style="text-align: center;">10.91%</td></tr>
    <tr><td style="text-align: center;">2019</td><td style="text-align: center;">1,754,328</td><td style="text-align: center;">1.41%</td></tr>
    <tr><td style="text-align: center;">2020</td><td style="text-align: center;">2,096,742</td><td style="text-align: center;">19.52%</td></tr>
    <tr><td style="text-align: center;">2021</td><td style="text-align: center;">2,463,159</td><td style="text-align: center;">17.48%</td></tr>
    <tr><td style="text-align: center;">2022</td><td style="text-align: center;">2,389,476</td><td style="text-align: center;">-2.99%</td></tr>
    <tr><td style="text-align: center;">2023</td><td style="text-align: center;">2,721,043</td><td style="text-align: center;">13.88%</td></tr>
    <tr><td style="text-align: center;">2024</td><td style="text-align: center;">2,802,137</td><td style="text-align: center;">2.98%</td></tr>
    <tr><td style="text-align: center;">2025</td><td style="text-align: center;">3,018,649</td><td style="text-align: center;">7.73%</td></tr>
    </tbody>
  </table>
</div>

#### 2.1.4 中国は世界のオープンソース上位グループを維持

表 2.1 に示すとおり、2025 年末時点で GitHub における**中国**のアクティブ開発者は **210 万人超**で、**世界第 3 位**を維持し、世界のオープンソースエコシステムを支える主要な存在となっている。中国国内の Gitee / AtomGit / GitCode などを加えると、重複排除後の推計は **350 万人超**となり、**世界第 2 位**に相当する。一方、**米国とインド**が上位 2 か国を占め、開発者数で明確な優位を保ちながら、世界のオープンソースイノベーションとコミュニティ貢献を牽引している。**ドイツ、英国、カナダ**など欧州・北米諸国の活発度も高く、北米を中心に、アジアが急成長し、欧州が安定して発展する多極的な分布となっている。

表 2.2 2025 年末時点の国別アクティブ開発者数 Top 10（GitHub）

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;">順位</th><th style="text-align: center;">国</th><th style="text-align: center;">総数（万人）</th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">1</td><td style="text-align: center;">米国</td><td style="text-align: center;">508.42</td></tr>
    <tr><td style="text-align: center;">2</td><td style="text-align: center;">インド</td><td style="text-align: center;">254.87</td></tr>
    <tr><td style="text-align: center;">3</td><td style="text-align: center;">中国</td><td style="text-align: center;">210.63</td></tr>
    <tr><td style="text-align: center;">4</td><td style="text-align: center;">ブラジル</td><td style="text-align: center;">149.38</td></tr>
    <tr><td style="text-align: center;">5</td><td style="text-align: center;">ドイツ</td><td style="text-align: center;">116.02</td></tr>
    <tr><td style="text-align: center;">6</td><td style="text-align: center;">英国</td><td style="text-align: center;">101.76</td></tr>
    <tr><td style="text-align: center;">7</td><td style="text-align: center;">カナダ</td><td style="text-align: center;">86.11</td></tr>
    <tr><td style="text-align: center;">8</td><td style="text-align: center;">フランス</td><td style="text-align: center;">71.59</td></tr>
    <tr><td style="text-align: center;">9</td><td style="text-align: center;">ロシア</td><td style="text-align: center;">61.84</td></tr>
    <tr><td style="text-align: center;">10</td><td style="text-align: center;">ポーランド</td><td style="text-align: center;">41.22</td></tr>
    </tbody>
  </table>
</div>

<center><img src="/image/data/figure-2-2-country-new-active-developers-github.png" width="700"></center>

<center>図 2.2 2016～2025 年の国別新規アクティブ開発者数の推移（GitHub）</center>

<center>出典：OpenDigger プラットフォームのデータを基に作成</center>

国別の新規アクティブ開発者数の推移（図 2.2）には、明確な地域差が見られる。

- **米国は成熟期へ**：新規アクティブ開発者は 11.8 万人から 3.4 万人へ減少した。伸びは鈍化したものの既存の開発者層は非常に大きく、エコシステムが高度に成熟していることを示す。
- **中国では構造的な転換点**：2016～2018 年は着実に増加したが、2020 年以降は減少が続き、2025 年の GitHub における新規開発者は約 1.5 万人となった。一方、Gitee / AtomGit / GitCode などでは、アンケート編の調査データに基づく重複排除後で 100 万人を超えている。
- **インドが世界の成長を牽引**：2.1 万人から 5.4 万人へ増え、10 年間の増加率は約 167%に達した。世界首位を維持し、南アジアのオープンソースを支える中心となっている。
- **新興市場が急成長**：ブラジル（1.3 万人から 3.4 万人）、インドネシア（0.2 万人から 0.9 万人）などが急速に伸び、ラテンアメリカと東南アジアの新たな成長拠点となった。
- **欧州は全体として安定**：ドイツ、英国、フランス、カナダなどの新規開発者数は 1～2 万人の範囲を保ち、ロシアは小幅な変動にとどまった。全体として安定した発展段階にある。

**傾向のまとめ**：世界のオープンソース参加は「一極主導」から「多極並進」へ急速に移行している。地域の多様性が大きく高まり、新興市場が成長し、成熟市場が安定する新たな構造が形成されている。

### 2.2 オープンソース貢献マップ

#### 2.2.1 位置づけ：貢献は責任、共同構築は未来

**世界オープンソース貢献マップ**（Global Open Source Contribution Map：C-Map）は、各国および各主体によるオープンソースエコシステムへの実質的な技術投入と協働の深さを測る。単なる「技術利用者」から「エコシステムの共同構築者」へ進んでいるかを判断するための重要な尺度である。

本節では **OpenRank 貢献度**（OpenRank Contribution Impact）を主要指標とし、コードのコミット、レビューとフィードバック、問題修正など、質の高い協働行動に注目する。活発度や貢献数だけの集計を超えて、技術を共同構築する深さと持続可能性を示す。**OpenRank 影響力**が開発者のエコシステム内での位置的な優位性を表すのに対し、**OpenRank 貢献度**は開発者が実際にどれだけ貢献したかをより直接的に表す。

#### 2.2.2 主な発見：多極的な共同ガバナンスが加速し、米中のモデルが分化

OpenRank 指標体系と GitHub の 2016～2025 年のデータによると、世界のオープンソース貢献には三つの構造的な変化が見られる。

#### 2.2.3 成長速度の差が拡大し、新興市場が急成長期へ

世界のオープンソース開発者の OpenRank 貢献度（Contribution Impact）と OpenRank 影響力（Influence）の 2016～2025 年の推移を、次の二つの図に示す。

<center><img src="/image/data/figure-2-3-global-openrank-contribution-github.png" width="700"></center>

<center>図 2.3 2016～2025 年の世界のオープンソース開発者の OpenRank 貢献度（GitHub）</center>

<center>出典：OpenDigger プラットフォームのデータを基に作成</center>

<center><img src="/image/data/figure-2-4-global-openrank-influence-github.png" width="700"></center>

<center>図 2.4 2016～2025 年の世界のオープンソース開発者の OpenRank 影響力（GitHub）</center>

<center>出典：OpenDigger プラットフォームのデータを基に作成</center>

OpenRank 貢献度は 2016～2024 年に **747 万**から **2,052 万**へ安定して増加した。比較的滑らかな成長は、開発者による深い貢献の能力が継続的に高まったことを示す。一方、2025 年は約 **1,926 万**へ減少した。減少幅は比較的小さいものの、転換点が現れている。

OpenRank 影響力は 2016～2023 年に約 **2,635 万**から **9,088 万**へ急速に増加し、3 倍を超える規模となった。エコシステムの活発度とネットワーク上の影響力が大きく拡大し、2020 年以降は成長がさらに加速した。しかし 2024 年から減少に転じ、2025 年は約 **5,640 万**へ大きく低下し、一時的な縮小を示した。

2025 年は両指標が同時に低下し、特に貢献度の減少が目立った。協働ネットワークの接続密度や交流頻度が弱まり、主体をまたぐ協働における実質的な貢献が減ったため、貢献度が影響力より大きく調整した可能性がある。生成 AI ツールの普及により、従来はコミュニティで協働して行っていた作業の一部が技術によって代替された。個人の開発効率が向上する一方、開発者同士の交流や協働の必要性は低下した可能性がある。また、一部の中国の開発者が GitHub から GitCode や Gitee など国内プラットフォームへ移行し、多くのプロジェクトが小規模チームや個人で開発されるようになったことで、協働ネットワークの外部接続も相対的に弱まった。これらの要因が重なり、2025 年の指標全体が一時的に低下したと考えられる。

国別の OpenRank 貢献度（Contribution Impact）と OpenRank 影響力（Influence）の推移を、次の二つの図に示す。

<center><img src="/image/data/figure-2-5-country-openrank-contribution.png" width="700"></center>

<center>図 2.5 国別オープンソース開発者の OpenRank 貢献度の推移</center>

<center>出典：OpenDigger プラットフォームのデータを基に作成</center>

<center><img src="/image/data/figure-2-6-country-openrank-influence.png" width="700"></center>

<center>図 2.6 国別オープンソース開発者の OpenRank 影響力の推移</center>

<center>出典：OpenDigger プラットフォームのデータを基に作成</center>

図から、オープンソースエコシステムでは「規模の拡大」と「地域構造の再編」が同時に進んでいることが分かる。

- **強い成長力**：インドの OpenRank 貢献度は 10 年間で **6 倍**、ブラジルは **5 倍超**、中国は **3 倍**に増加した。新興市場がオープンソース技術を急速に取り入れ、地域に根ざしたイノベーションを進めている。
- **影響力構造の再編**：米国は依然として首位、ドイツは欧州首位を維持し、中国とインドが急上昇した。「米国・欧州が先導し、アジア・アフリカ・ラテンアメリカが追う」という新たな構造が形成されている。
- **貢献傾向の逆転**：米国の貢献度は 2021 年のピーク後に減少を続ける一方、中国は上昇を続け、世界で最も成長の速い主要国の一つとなった。
- **中国は貢献への投入を拡大**：影響力と比較すると、中国の開発者はより深い貢献を重視している。開発者の影響力は米国の約 3 分の 1 だが、貢献度の合計は米国の 50%近くに達し、なお **7.54%**の増加率で成長して他国との差を広げている。

考察：米国の開発者の貢献度は 2020 年以降減少しており、2025 年には**米中の貢献度増加率の差が 10%を超えた**。現在の傾向が続けば、**7 年後**には中国の開発者の貢献度が米国を上回り、世界首位になると推計される。

表 2.3 2025 年世界 OpenRank 貢献度 Top 10

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;">順位</th><th style="text-align: center;">国名</th><th style="text-align: center;">OpenRank 影響力</th><th style="text-align: center;">増加率</th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">1</td><td style="text-align: center;">米国</td><td style="text-align: center;">297,884</td><td style="text-align: center;">-14.70%</td></tr>
    <tr><td style="text-align: center;">2</td><td style="text-align: center;">中国</td><td style="text-align: center;">254,963</td><td style="text-align: center;">-1.89%</td></tr>
    <tr><td style="text-align: center;">3</td><td style="text-align: center;">ドイツ</td><td style="text-align: center;">79,742</td><td style="text-align: center;">-10.38%</td></tr>
    <tr><td style="text-align: center;">4</td><td style="text-align: center;">英国</td><td style="text-align: center;">58,146</td><td style="text-align: center;">-12.86%</td></tr>
    <tr><td style="text-align: center;">5</td><td style="text-align: center;">カナダ</td><td style="text-align: center;">44,731</td><td style="text-align: center;">-11.92%</td></tr>
    <tr><td style="text-align: center;">6</td><td style="text-align: center;">フランス</td><td style="text-align: center;">44,108</td><td style="text-align: center;">-12.87%</td></tr>
    <tr><td style="text-align: center;">7</td><td style="text-align: center;">インド</td><td style="text-align: center;">40,482</td><td style="text-align: center;">-13.13%</td></tr>
    <tr><td style="text-align: center;">8</td><td style="text-align: center;">オランダ</td><td style="text-align: center;">26,241</td><td style="text-align: center;">-15.11%</td></tr>
    <tr><td style="text-align: center;">9</td><td style="text-align: center;">ポーランド</td><td style="text-align: center;">20,284</td><td style="text-align: center;">-13.32%</td></tr>
    <tr><td style="text-align: center;">10</td><td style="text-align: center;">スイス</td><td style="text-align: center;">17,642</td><td style="text-align: center;">-15.12%</td></tr>
    </tbody>
  </table>
</div>

表 2.4 2025 年世界 OpenRank 影響力 Top 10

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;">順位</th><th style="text-align: center;">国名</th><th style="text-align: center;">OpenRank 影響力</th><th style="text-align: center;">増加率</th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">1</td><td style="text-align: center;">米国</td><td style="text-align: center;">1,789,364</td><td style="text-align: center;">-9.68%</td></tr>
    <tr><td style="text-align: center;">2</td><td style="text-align: center;">ドイツ</td><td style="text-align: center;">625,814</td><td style="text-align: center;">-7.75%</td></tr>
    <tr><td style="text-align: center;">3</td><td style="text-align: center;">中国</td><td style="text-align: center;">611,892</td><td style="text-align: center;">-15.20%</td></tr>
    <tr><td style="text-align: center;">4</td><td style="text-align: center;">英国</td><td style="text-align: center;">441,392</td><td style="text-align: center;">-10.30%</td></tr>
    <tr><td style="text-align: center;">5</td><td style="text-align: center;">インド</td><td style="text-align: center;">392,517</td><td style="text-align: center;">-14.65%</td></tr>
    <tr><td style="text-align: center;">6</td><td style="text-align: center;">フランス</td><td style="text-align: center;">341,508</td><td style="text-align: center;">-9.63%</td></tr>
    <tr><td style="text-align: center;">7</td><td style="text-align: center;">カナダ</td><td style="text-align: center;">312,094</td><td style="text-align: center;">-10.12%</td></tr>
    <tr><td style="text-align: center;">8</td><td style="text-align: center;">ブラジル</td><td style="text-align: center;">268,315</td><td style="text-align: center;">-13.51%</td></tr>
    <tr><td style="text-align: center;">9</td><td style="text-align: center;">オランダ</td><td style="text-align: center;">195,842</td><td style="text-align: center;">-8.83%</td></tr>
    <tr><td style="text-align: center;">10</td><td style="text-align: center;">日本</td><td style="text-align: center;">185,409</td><td style="text-align: center;">-11.55%</td></tr>
    </tbody>
  </table>
</div>

表 2.3（影響力）と表 2.4（貢献度）を総合すると、2025 年は上位 10 か国の両指標がいずれも前年から低下し、世界のオープンソースエコシステムの活発度が一時的に調整したことが分かる。

- **米国**は影響力と貢献度の双方で引き続き大幅に先行しているが、低下幅も比較的大きい。
- **中国**は影響力の低下幅が比較的小さく一定の安定性を示す一方、貢献度はより大きく低下した。ネットワーク構造の相対的な強さと、実際の成果創出力の低下との差が表れている。
- **欧州主要国**は全体として同時に低下し、変動幅も比較的近く、国別順位に大きな変化はなかった。

#### 2.2.4 世界の貢献フローの再編：集中型から多極的な流動へ

オープンソースエコシステムの協働範囲は拡大を続け、世界の開発者による貢献の流れも大きく変化している。2025 年の国境を越えた貢献データを分析したサンキーダイアグラム（図 2.7）は、国の間でオープンソース資源がどのように流れるかを示し、「一極主導」から「多方向の流動」へ進む傾向を明らかにしている。

<center><img src="/image/data/figure-2-7-global-project-contribution-flow.png" width="700"></center>

<center>図 2.7 世界のオープンソースプロジェクトへの貢献フロー分析</center>

<center>出典：OpenDigger プラットフォームのデータを基に作成</center>

サンキーダイアグラム（Sankey Diagram）は、国の間のオープンソースプロジェクト貢献度の流れを示す。左側が貢献を送り出す国、右側が米中を含む 10 か国への貢献の流入である。世界全体では、米国は依然としてオープンソース協働ネットワークの中心だが、その役割は「主導者」から「支援者」へ変化している。オープンソース資源の「純輸出国」として、米国の開発者はドイツ、英国、フランスなど欧州の技術先進国のプロジェクトへ大きく貢献し、インドやイスラエルなど新興エコシステムの技術開発にも深く参加している。これは、地域を越えた強い影響力と波及力を示す。

これに対し、中国はより「受け手」に近い。中国の開発者は Linux、Kubernetes、PyTorch など米国主導の主要な国際プロジェクトで活発に活動し、貢献密度も世界上位にある。しかし逆方向の流れは弱く、中国発プロジェクトへの海外からの実質的な参加は依然として限られている。世界のオープンソース協働には、なお「中心―周辺」構造が残っている。

この貢献フローの背景には、各国のオープンソースガバナンスの考え方、エコシステムの開放性、世界的な求心力の違いがある。特に米中という二大技術大国の間では、この差が二つの異なる貢献モデルへ発展している。両国のオープンソース共同構築の論理的な違いをさらに明らかにするため、米国発・中国発のオープンソースプロジェクトに対する世界からの貢献分布を比較した。

#### 2.2.5 米国と中国が世界の自国発オープンソースプロジェクトへの貢献を主導

表 2.5 のデータから、次のことが分かる。

- **米国発プロジェクトは高度に国際化**：2024 年の国内開発者による貢献は 38.21%にとどまり、6 割超を海外が占めた。中国（7.81%）、ドイツ（6.84%）、カナダ（5.06%）などが深く参加し、世界規模の協働開発ネットワークと強い「エコシステムの求心力」を形成している。
- **中国発プロジェクトは国内循環が中心**：国内からの貢献が 79.14%を占め、海外からの貢献は全体として少ない。米国（6.27%）、カナダ（1.59%）など一部の国がわずかに参加するにとどまり、国際協働の度合いは世界第 10 位で、「自ら構築し、自ら利用する」という現段階の特徴が表れている。
- **より深い意味**：今後のオープンソース競争の中心は、「人材の送り出し」から「エコシステムの求心力」へ移っている。世界の開発者を深い共同構築へ引きつけられるかが、国家のオープンソースにおけるリーダーシップを測る重要な基準となる。

表 2.5 2025 年の中国発・米国発オープンソースプロジェクトへの国別貢献 Top 10（左：中国、右：米国）

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
<table style="display: table; margin: 0 auto; text-align: center;">
  <thead>
    <tr>
      <th colspan="4" style="text-align: center;">中国主導プロジェクトへの国別貢献</th>
      <th colspan="4" style="text-align: center;">米国主導プロジェクトへの国別貢献</th>
    </tr>
    <tr>
      <th style="text-align: center;">順位</th>
      <th style="text-align: center;">国</th>
      <th style="text-align: center;">OpenRank 貢献度</th>
      <th style="text-align: center;">貢献度の割合</th>
      <th style="text-align: center;">順位</th>
      <th style="text-align: center;">国</th>
      <th style="text-align: center;">OpenRank 貢献度</th>
      <th style="text-align: center;">貢献度の割合</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: center;">1</td>
      <td style="text-align: center;">中国 CN</td>
      <td style="text-align: center;">25,103.68</td>
      <td style="text-align: center;">79.14%</td>
      <td style="text-align: center;">1</td>
      <td style="text-align: center;">米国 US</td>
      <td style="text-align: center;">119,864.31</td>
      <td style="text-align: center;">38.21%</td>
    </tr>
    <tr>
      <td style="text-align: center;">2</td>
      <td style="text-align: center;">米国 US</td>
      <td style="text-align: center;">1,986.42</td>
      <td style="text-align: center;">6.27%</td>
      <td style="text-align: center;">2</td>
      <td style="text-align: center;">中国 CN</td>
      <td style="text-align: center;">24,518.77</td>
      <td style="text-align: center;">7.81%</td>
    </tr>
    <tr>
      <td style="text-align: center;">3</td>
      <td style="text-align: center;">カナダ CA</td>
      <td style="text-align: center;">503.16</td>
      <td style="text-align: center;">1.59%</td>
      <td style="text-align: center;">3</td>
      <td style="text-align: center;">ドイツ DE</td>
      <td style="text-align: center;">21,472.93</td>
      <td style="text-align: center;">6.84%</td>
    </tr>
    <tr>
      <td style="text-align: center;">4</td>
      <td style="text-align: center;">ドイツ DE</td>
      <td style="text-align: center;">427.91</td>
      <td style="text-align: center;">1.35%</td>
      <td style="text-align: center;">4</td>
      <td style="text-align: center;">英国 GB</td>
      <td style="text-align: center;">18,612.48</td>
      <td style="text-align: center;">5.92%</td>
    </tr>
    <tr>
      <td style="text-align: center;">5</td>
      <td style="text-align: center;">シンガポール SG</td>
      <td style="text-align: center;">414.82</td>
      <td style="text-align: center;">1.31%</td>
      <td style="text-align: center;">5</td>
      <td style="text-align: center;">カナダ CA</td>
      <td style="text-align: center;">15,874.62</td>
      <td style="text-align: center;">5.06%</td>
    </tr>
    <tr>
      <td style="text-align: center;">6</td>
      <td style="text-align: center;">インド IN</td>
      <td style="text-align: center;">371.04</td>
      <td style="text-align: center;">1.18%</td>
      <td style="text-align: center;">6</td>
      <td style="text-align: center;">インド IN</td>
      <td style="text-align: center;">13,702.15</td>
      <td style="text-align: center;">4.36%</td>
    </tr>
    <tr>
      <td style="text-align: center;">7</td>
      <td style="text-align: center;">チェコ CZ</td>
      <td style="text-align: center;">231.42</td>
      <td style="text-align: center;">0.73%</td>
      <td style="text-align: center;">7</td>
      <td style="text-align: center;">フランス FR</td>
      <td style="text-align: center;">11,488.36</td>
      <td style="text-align: center;">3.66%</td>
    </tr>
    <tr>
      <td style="text-align: center;">8</td>
      <td style="text-align: center;">ブルガリア BG</td>
      <td style="text-align: center;">176.88</td>
      <td style="text-align: center;">0.56%</td>
      <td style="text-align: center;">8</td>
      <td style="text-align: center;">オランダ NL</td>
      <td style="text-align: center;">7,084.93</td>
      <td style="text-align: center;">2.26%</td>
    </tr>
    <tr>
      <td style="text-align: center;">9</td>
      <td style="text-align: center;">スウェーデン SE</td>
      <td style="text-align: center;">186.05</td>
      <td style="text-align: center;">0.59%</td>
      <td style="text-align: center;">9</td>
      <td style="text-align: center;">ポーランド PL</td>
      <td style="text-align: center;">5,844.71</td>
      <td style="text-align: center;">1.86%</td>
    </tr>
    <tr>
      <td style="text-align: center;">10</td>
      <td style="text-align: center;">英国 GB</td>
      <td style="text-align: center;">168.73</td>
      <td style="text-align: center;">0.53%</td>
      <td style="text-align: center;">10</td>
      <td style="text-align: center;">スイス CH</td>
      <td style="text-align: center;">5,982.44</td>
      <td style="text-align: center;">1.91%</td>
    </tr>
  </tbody>
</table>
</div>

米中のオープンソース分野での交流には、明確な非対称性がある。中国の開発者は米国主導プロジェクトに広く参加して発展を支えている一方、米国の開発者から中国発プロジェクトへの貢献は極めて限られる。この「一方向の参加」は、中国の技術コミュニティの学習力と実行力を示す一方、世界的な支持の獲得、プロジェクトの開放性、ガバナンスの透明性に課題があることも明らかにしている。

この構造的な課題を乗り越えるには、中国は「貢献規模」から「世界的な共同ガバナンス」へ進む必要がある。国家戦略、プラットフォーム基盤、人材育成を連携させ、国内循環の限界を越えて、「オープンソースを使う」から「オープンソースに貢献する」、さらに「オープンソースを主導する」段階へ移行することが求められる。

#### 2.2.6 世界の貢献の集中度が低下し、多極的な共同ガバナンスが加速

次に、2016～2025 年の国別アクティブ開発者の OpenRank 影響力が世界全体に占める割合を示す。

<center><img src="/image/data/figure-2-8-top5-country-openrank-share.png" width="700"></center>

<center>図 2.8 2016～2025 年の上位 5 か国のアクティブ開発者による OpenRank 影響力の世界シェア</center>

<center>出典：OpenDigger プラットフォームのデータを基に作成</center>

図 2.8 が示すとおり、過去 10 年間に**世界のオープンソース影響力は徐々に分散した**。

- 上位 5 か国の OpenRank 影響力の合計は、2016 年の 58.46%から 2025 年の 48.93%へ約 10 ポイント低下した。
- ドイツ、中国、インドなどの割合が着実に上昇し、エコシステムは「米国による一極主導」から「多様な主体による協調的な共同ガバナンス」へ移行している。

傾向の解釈：集中度の低下は米国の衰退ではなく、世界の協働ネットワークが深化した自然な結果である。オープンソースイノベーションへの参加主体が多様化し、力関係がより均衡しつつあることを示している。

### 2.3 オープンソース技術マップ

#### 2.3.1 位置づけ：技術が競争の場となり、オープンソースが最前線となる

**世界オープンソース技術マップ**（Global Open Source Technology Map：T-Map）は、各技術分野のオープンソースエコシステムにおける活発度、成長性、影響力の分布を示す。世界の技術イノベーションを動かす力と戦略的な重点の変化を捉え、「どの分野が急成長し、誰が技術の最前線を定義しているか」を判断するための中核的な観測手段である。

本節では、**アクティブオープンソースリポジトリ数**（Number of Active Open Source Repositories：NAOSR）と **OpenRank 影響力**（OpenRank Influence）を主要指標とする。前者は特定技術分野におけるプロジェクト活動の密度とエコシステムの活況を測り、後者は協働ネットワークの構造に基づいて、その分野の主体が持つ技術的な発言力とコミュニティへの影響力を定量化する。

#### 2.3.2 主な発見：AI が急成長を牽引し、複数分野が連携して発展

GitHub Octoverse Report によると、**2025 年末**時点で GitHub には **3.95 億件**の公開・オープンソースリポジトリ（public & open source repositories）があり、前年から **7,200 万件**増加した。過去 10 年間のアクティブリポジトリは GitHub で累計 **3,488 万件**、中国国内の Gitee / AtomGit / GitCode などで約 **2,700 万件**、GitLab で約 **70 万件**に達した。

2025 年の世界のアクティブリポジトリは **1,100 万件超**で、GitHub が **590 万件**、Gitee / AtomGit / GitCode などが全体で **500 万件**、GitLab が **11 万件超**だった。

<div style="display: flex; justify-content: center; align-items: flex-start; gap: 8px; width: 100%; overflow-x: auto; margin: 16px 0;">
  <img src="/image/data/figure-2-9-active-repositories-github.png" style="display: block; flex: 0 0 auto; width: calc((100% - 24px) / 4); min-width: 160px; max-width: none; margin: 0;">
  <img src="/image/data/figure-2-9-active-repositories-gitee.png" style="display: block; flex: 0 0 auto; width: calc((100% - 24px) / 4); min-width: 160px; max-width: none; margin: 0;">
  <img src="/image/data/figure-2-9-active-repositories-atomgit.png" style="display: block; flex: 0 0 auto; width: calc((100% - 24px) / 4); min-width: 160px; max-width: none; margin: 0;">
  <img src="/image/data/figure-2-9-active-repositories-gitlab.png" style="display: block; flex: 0 0 auto; width: calc((100% - 24px) / 4); min-width: 160px; max-width: none; margin: 0;">
</div>

<center>図 2.9 2016～2025 年のアクティブリポジトリ数（左から GitHub、Gitee、AtomGit / GitCode、GitLab）</center>

<center>出典：OpenDigger プラットフォームのデータを基に作成</center>

上図が示す 2016～2025 年の推移では、各プラットフォームの規模は拡大を続ける一方、成長のペースには差がある。世界のオープンソースプロジェクト数は全体として増加したが、発展段階、成長速度、変動の大きさはプラットフォームごとに異なる。

- **GitHub**：アクティブリポジトリは **223 万件**から **632 万件**へ増え、10 年間で約 **183%**成長した。特に**2020～2021 年**は、新型コロナウイルス感染症の拡大期にリモート協働とオンライン開発が増え、プロジェクト数が大きく伸びた。一部の年には成長が鈍化したものの、成熟したエコシステムとして安定した拡大を続けている。2025 年の顕著な増加は、AI 時代にアクティブリポジトリが急増し、AI によるイノベーションが一部の専門家主導から幅広い共同創造へ移りつつあることも示す。
- **Gitee**：初期に急成長し、アクティブリポジトリは **44.5 万件**から 2020 年の **330.6 万件**へ増加した。2021 年は 336.9 万件、**2022 年は 348.4 万件**となり、感染拡大期のリモート開発とオンライン協働需要も成長を後押しした。以後も着実に増え、**2023 年は 381.7 万件、2024 年は 387.5 万件**、2025 年には約 **438.9 万件**と現段階での最高値に達した。
- **AtomGit / GitCode**：**2023 年 9 月**に開始し、データは 3 年分に限られるが、2025 年には **60 万件超**へ急増し、新興プラットフォームの初期に見られる急速な拡大を示した。
- **GitLab**：2016～2022 年は増加を続け、2022 年にピークを迎えた。2023～2024 年に減少した後、2025 年は小幅に回復し、リポジトリ活動が急拡大から一時的な調整へ移ったことを示している。

四つのプラットフォームには明確な段階差がある。GitHub は成熟した安定成長、Gitee は継続的で堅調な成長とエコシステムの成熟、AtomGit / GitCode は初期の急成長、GitLab は急拡大から一時的な調整への移行という段階にある。

<center><img src="/image/data/figure-2-10-tech-domain-openrank-growth-trend.png" width="700"></center>

<center>図 2.10 2021～2025 年の技術分野別 OpenRank 影響力の成長傾向</center>

<center>出典：OpenDigger プラットフォームのデータを基に作成</center>

- **AI 大規模モデルが最大の成長分野となり、技術変革を牽引**：関連リポジトリの年平均成長率は **210%超**で、2024 年から全技術分野の首位となった。Qwen（通義千問）、Llama、DeepSeek などのオープンソースモデルが急速に 100 万単位の Star を獲得し、「Model as a Service」という新たな形を広げ、AI 応用への参入障壁を大きく下げた。
- **高成長分野が多様化し、エコシステムの強靭性が向上**：クラウドインフラ（Kubernetes、Terraform）は高い活発度を保ち、企業のデジタル変革を支える。フロントエンドのインタラクションフレームワーク（React、Vue）と新しいプログラミング言語（Rust、Go）は、開発効率と安全性から広く支持される。RISC-V などのオープンハードウェアプロジェクトも大きく成長し、「ポストムーア時代」の主要な技術経路と見なされている。
- **基盤ソフトウェアが着実に発展し、デジタル基盤を強化**：データベース（PostgreSQL、OceanBase）、OS（Linux、openEuler）、ビッグデータ（Spark、Flink）、IoT（EdgeX）などが安定して成長し、強固な技術インフラを構成する。
- **米中の技術的な発言力は構造的に分化**：米国は AI フレームワーク（PyTorch）、クラウドネイティブ（Kubernetes）、コンパイラなど基盤分野で引き続き主導する。中国は AI 大規模モデル（Qwen、ChatGLM）、OS（openEuler）、分散データベース（OceanBase）などで急速に追い上げ、一部の分野では同水準または部分的な先行を実現している。

**傾向のまとめ**：世界のオープンソース技術は「単一分野での突破」から「複数分野が連携した発展」へ移行し、AI が牽引し、クラウド基盤が支え、根幹技術が土台を築くエコシステムが形成されつつある。一方、技術標準の分断や相互運用性の不足はイノベーションの効率を妨げる可能性があり、新たな技術的分断に注意が必要である。

技術分野ごとの総合影響力、プロジェクト規模、プロジェクト当たりの平均影響力を直感的に比較するため、散布図型のバブルチャートで示す。バブルの大きさは総合影響力に比例する。

<center><img src="/image/data/figure-2-11-tech-domain-bubble-analysis.png" width="700"></center>

<center>図 2.11 技術分野別散布図・バブルチャート分析</center>

<center>出典：OpenDigger プラットフォームのデータを基に作成</center>

図 2.3.3 から、次の点が読み取れる。

- AI と大規模モデルは、総合影響力とプロジェクト規模の双方で首位にあり、現在最も影響力のある技術分野である。
- ビッグデータ・データエンジニアリングと IoT・エッジコンピューティングは、プロジェクト当たりの平均影響力が特に高く、上位 2 分野を占める。
- 産業用ソフトウェアはプロジェクト規模が最も小さいが、平均影響力は高い。
- 技術分野は、フロントエンドのような「大規模・中程度の影響力」と、ビッグデータのような「小規模・高影響力」という二つの特徴的な類型に分けられる。
- 総合影響力とプロジェクト規模には正の相関があるが、平均影響力の分布は比較的独立している。

### 2.4 オープンソース人材マップ

#### 2.4.1 位置づけ：人材はオープンソースエコシステムの中核的な推進力

**世界オープンソース人材マップ**（Global Open Source eXpertise Map：X-Map）は、影響力の高い開発者の世界的な分布を特定し、各国における中核的人材の蓄積と技術的リーダーシップの変化を示す。

本節では **OpenRank 影響力**（OpenRank Influence）を主要指標とし、OpenRank が 200 以上の高影響力開発者に注目する。地理的な所属と技術分野の分布を分析し、高度デジタル人材の集積とイノベーション能力における各国の戦略的競争力を明らかにする。この指標は単純な人材数を超え、協働ネットワークにおける開発者の技術的な発言力とコミュニティでのリーダーシップを示す。

#### 2.4.2 主な発見：米中の二つの中核が牽引し、世界の人材構造は多極的な発展段階へ

本報告では、**OpenRank > 200**を基準に「高影響力開発者」（High-Impact Contributors）を定義し、2016～2025 年の主要国における人数を追跡した。その結果、次の三つの傾向が明らかになった。

<center><img src="/image/data/figure-2-12-high-influence-developers-heatmap.png" width="700"></center>

<center>図 2.12 国別高影響力開発者ヒートマップ</center>

<center>出典：OpenDigger プラットフォームのデータを基に作成</center>

<center><img src="/image/data/figure-2-13-china-high-influence-developers-trend.png" width="700"></center>

<center>図 2.13 2016～2025 年の中国の高影響力開発者数の推移</center>

<center>出典：OpenDigger プラットフォームのデータを基に作成</center>

- **米国が引き続き首位で、10 年間に大幅増加**：高影響力開発者は **2016 年の 248 人**から **2025 年の 398 人**へ増え、世界首位を維持した。豊富な学術的蓄積、Google、Meta、Microsoft などの活発な企業エコシステム、Linux Foundation や Apache Software Foundation など成熟したオープンソース財団が、世界の技術標準とコミュニティにおける発言力を継続的に形成している。
- **中国が飛躍的に伸び、第 2 グループへ**：図 2.13 のとおり、中国の高影響力開発者は **2016 年の 11 人**から **2025 年の 110 人**へ急増し、**10 年間で 10 倍**となった。国家の「科学技術の自立自強」戦略の下で、Huawei、Alibaba、Tencent、ByteDance などの企業がオープンソースへの投資を拡大し、大学の研究成果を社会実装する仕組みが改善されたことに加え、Gitee や OpenAtom など国内プラットフォームが質の高い貢献者を評価・育成したことが成長を支えた。
- **欧州は安定した多極構造で、連携効果が顕著**：ドイツ（159 人）、英国（79 人）、フランス（53 人）、カナダ（53 人）などが着実に発展した。ドイツは産業用ソフトウェアと組み込みシステムの強みを生かし、自動車や IoT 分野で大きく貢献している。英国は Cambridge、Oxford などの大学を背景に AI とクラウドコンピューティングで強みを示し、カナダはオープンソースガバナンスとセキュリティ分野で高い影響力を持つ。

#### 2.4.3 世界の構造：米中が先導し、各国が並進、競争の重点は「人材の質」へ

現在の世界のオープンソース人材分布は、**「米中が先導し、各国が並進する」**多極構造となっている。

表 2.6 2025 年の国別高影響力開発者数と増加率

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;"><strong>国</strong></th><th style="text-align: center;"><strong>2025 年の高影響力開発者数</strong></th><th style="text-align: center;"><strong>増加率（2016～2025 年）</strong></th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;"><strong>米国</strong></td><td style="text-align: center;">398</td><td style="text-align: center;">+60%</td></tr>
    <tr><td style="text-align: center;"><strong>中国</strong></td><td style="text-align: center;">110</td><td style="text-align: center;">+900%</td></tr>
    <tr><td style="text-align: center;"><strong>ドイツ</strong></td><td style="text-align: center;">159</td><td style="text-align: center;">+178%</td></tr>
    <tr><td style="text-align: center;"><strong>英国</strong></td><td style="text-align: center;">79</td><td style="text-align: center;">+88%</td></tr>
    <tr><td style="text-align: center;"><strong>フランス</strong></td><td style="text-align: center;">53</td><td style="text-align: center;">+89%</td></tr>
    <tr><td style="text-align: center;"><strong>カナダ</strong></td><td style="text-align: center;">53</td><td style="text-align: center;">+29%</td></tr>
    </tbody>
  </table>
</div>

- 高影響力開発者は段階的に分布し、米国は 398 人で世界のリーダーシップの中心を維持する。中国は 900%の増加率で急速に追い上げ、両国が第 1・第 2 グループの中核を構成する。
- 欧州では、ドイツが 159 人、増加率 178%で「産業用ソフトウェアの中核」としての強みを示す。英国とフランスも戦略的な位置づけを背景に約 2 倍へ増え、地域で連携して発展している。
- 各国の高影響力開発者数と増加率は、「世界的リーダーシップ」や「産業の中核」といった戦略的位置づけと強く対応し、戦略的な方向性が技術人材の集積を促すことを示している。

## 三、オープンソース影響力ランキング

**エコシステム内の位置から影響力へ：オープンソース世界の「共通尺度」を構築**

今日のデジタル時代において、オープンソースは単なるコード共有を超え、世界のデジタル文明を支える重要なインフラとなった。誰が技術の未来を形づくり、公正な協働を促し、周縁化された人々を支援しているかを測るには、Star 数やコミット数など表面的な指標だけでなく、科学性、包摂性、将来性を備えた影響力評価体系が必要である。

本報告は OSDGs フレームワークを全面的に採用し、OpenRank ノーススター指標に基づいて、「行動―質―影響力」の三層からなる世界共通のランキング体系を構築した。本章では、行政区画、企業、成熟プロジェクト、新興プロジェクトという四つの影響力ランキングを公表する。中国のオープンソースが世界で占める位置だけでなく、地域連携、企業戦略、技術イノベーション、若手の活力を明らかにする。

集計期間は 2025 年 1 月 1 日から 2025 年 12 月 31 日までである。OpenDigger の多次元タグ体系（34 省級行政区、1,000 以上の企業、200 以上の技術分野）を用いて詳細に分析した。これらのランキングが指標となる事例と方向性を示し、国家のデジタル戦略、地域間の調和ある発展、企業のオープンソースガバナンス、若手人材の育成に役立つことを目指す。

### 3.1 行政区画影響力ランキング

オープンソースは技術イノベーションの原動力であると同時に、地域のデジタル経済の競争力を示す重要な要素でもある。「東数西算」（東部のデータを西部で計算処理する国家構想）や「全国統一大市場」などの国家戦略の下で、各省・市がオープンソースを通じて地域の技術エコシステムを築き、高度人材を引きつけ、新たな質の生産力を育成できるかは、地域の質の高い発展を測る重要な観点となる。

本節ではグローバル OpenRank 指標に基づき、香港、マカオ、台湾を含む中国の 34 省級行政区が世界のオープンソース協働ネットワークで持つ総合的な影響力を評価する。開発者数と活発度だけでなく、貢献の質、プロジェクトの主導力、地域を越えた協働能力を重視し、単純な数量評価を避ける。北京、上海、深圳といった従来のイノベーション拠点に加え、成都、西安、合肥など将来性のある地域を特定し、中西部の地域別支援策にデータを提供する。

#### 3.1.1 世界の行政区画影響力 Top 15：米国が引き続き主導し、新興市場が追い上げ

世界では、**カリフォルニア州**が OpenRank 5,574.8 で首位を維持し、他地域を大きく上回った。Apple、Google、Meta などシリコンバレーの企業集積に加え、Stanford や UC Berkeley の研究基盤、整備されたスタートアップ環境、開かれた協働文化が強みとなっている。

表 3.1 世界の行政区画影響力 Top 15

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;">#</th><th style="text-align: center;">行政区画</th><th style="text-align: center;">OpenRank</th><th style="text-align: center;">開発者数（万人）</th><th style="text-align: center;">国</th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">1</td><td style="text-align: center;">カリフォルニア州</td><td style="text-align: center;">5,574.8</td><td style="text-align: center;">593.96</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">2</td><td style="text-align: center;">イングランド</td><td style="text-align: center;">4,348.45</td><td style="text-align: center;">410.29</td><td style="text-align: center;">英国</td></tr>
    <tr><td style="text-align: center;">3</td><td style="text-align: center;">ニューヨーク州</td><td style="text-align: center;">25,213.87</td><td style="text-align: center;">275.68</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">4</td><td style="text-align: center;">ワシントン州</td><td style="text-align: center;">2,037.95</td><td style="text-align: center;">185.97</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">5</td><td style="text-align: center;">サンパウロ州</td><td style="text-align: center;">19,894.35</td><td style="text-align: center;">229.73</td><td style="text-align: center;">ブラジル</td></tr>
    <tr><td style="text-align: center;">6</td><td style="text-align: center;">オンタリオ州</td><td style="text-align: center;">1,844.54</td><td style="text-align: center;">162.63</td><td style="text-align: center;">カナダ</td></tr>
    <tr><td style="text-align: center;">7</td><td style="text-align: center;">ベルリン</td><td style="text-align: center;">1,628.85</td><td style="text-align: center;">115.85</td><td style="text-align: center;">ドイツ</td></tr>
    <tr><td style="text-align: center;">8</td><td style="text-align: center;">テキサス州</td><td style="text-align: center;">1,610.33</td><td style="text-align: center;">206.56</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">9</td><td style="text-align: center;">イル＝ド＝フランス地域圏</td><td style="text-align: center;">1,527.02</td><td style="text-align: center;">147.69</td><td style="text-align: center;">フランス</td></tr>
    <tr><td style="text-align: center;">10</td><td style="text-align: center;">ソウル特別市</td><td style="text-align: center;">1,465.92</td><td style="text-align: center;">187.52</td><td style="text-align: center;">韓国</td></tr>
    <tr><td style="text-align: center;">11</td><td style="text-align: center;">東京都</td><td style="text-align: center;">1,279.69</td><td style="text-align: center;">274.06</td><td style="text-align: center;">日本</td></tr>
    <tr><td style="text-align: center;">12</td><td style="text-align: center;">北京市</td><td style="text-align: center;">1,248.72</td><td style="text-align: center;">332.19</td><td style="text-align: center;">中国</td></tr>
    <tr><td style="text-align: center;">13</td><td style="text-align: center;">マサチューセッツ州</td><td style="text-align: center;">1,232.39</td><td style="text-align: center;">116.21</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">14</td><td style="text-align: center;">バイエルン州</td><td style="text-align: center;">1,083.71</td><td style="text-align: center;">79.08</td><td style="text-align: center;">ドイツ</td></tr>
    <tr><td style="text-align: center;">15</td><td style="text-align: center;">上海市</td><td style="text-align: center;">1,060.37</td><td style="text-align: center;">244.05</td><td style="text-align: center;">中国</td></tr>
    </tbody>
  </table>
</div>

次いで**イングランド**（4,348.95）が続き、英国が AI、フィンテック、ソフトウェア工学へ継続して投資していることを示す。ロンドン以外では同規模の集積には至っていないが、Oxford、Cambridge など大学を中心とするコミュニティが成長している。

**ニューヨーク州**（2,521.37）は第 3 位で、マンハッタンのフィンテックとロングアイランドの研究機関が影響力を支える。**ワシントン州**（2,037.95）は上位 3 地域には入らないものの、クラウドコンピューティング（Azure、AWS）や AI ツールチェーン（GitHub）への貢献で米国西部のもう一つの中核となっている。

ブラジルの**サンパウロ州**（1,989.35）とカナダの**オンタリオ州**（1,844.54）は第 5・第 6 位である。サンパウロは大規模なエンジニア層と製造業の変革需要を背景に、組み込みシステムと産業用ソフトウェアで強みを持つ。オンタリオは University of Toronto や University of Waterloo の研究資源を背景に、AI とブロックチェーンで独自の優位性を形成している。

ドイツの**ベルリン**（1,628.85）とフランスの**イル＝ド＝フランス地域圏**（1,527.02）は第 7・第 9 位で、欧州がガバナンス、標準の共同策定、グリーンコンピューティングで先導していることを示す。韓国の**ソウル特別市**（1,465.92）と日本の**東京都**（1,279.69）も上位に入り、東アジアがモバイルインターネット、スマート製造、基盤ソフトウェアに豊富な蓄積を持つことを示している。

**北京市**（1,248.72）と**上海市**（1,060.37）は第 12・第 15 位で、世界上位 20 地域に入る中国の二都市となった。両都市では「政府による支援、企業による主導、大学との連携」という効率的なモデルが形成されている。

#### 3.1.2 世界の地理的分布：誰が協働ネットワークを主導しているか

[世界行政区画別開発者 OpenRank ランキング（Top 100）](https://open-digger.cn/leaderboards?type=divisions)は、先行地域の技術力だけでなく、各国が世界の協働ネットワークへ参加する広がりと組織力も示す。一国から複数地域が Top 100 に入ることは、**多層的・多中心的なオープンソースイノベーション集積**が形成され、エコシステムの強靭性と人材を引きつける力が高いことを意味する。

Top 100 に入った行政区画数を国別に集計した結果を次に示す。

表 3.2 世界行政区画影響力 Top 100 の国別選出数

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;">順位</th><th style="text-align: center;">国</th><th style="text-align: center;">選出数</th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">1</td><td style="text-align: center;">米国</td><td style="text-align: center;">23</td></tr>
    <tr><td style="text-align: center;">2</td><td style="text-align: center;">ドイツ</td><td style="text-align: center;">10</td></tr>
    <tr><td style="text-align: center;">3</td><td style="text-align: center;">中国</td><td style="text-align: center;">8</td></tr>
    <tr><td style="text-align: center;">3</td><td style="text-align: center;">ブラジル</td><td style="text-align: center;">8</td></tr>
    <tr><td style="text-align: center;">5</td><td style="text-align: center;">カナダ</td><td style="text-align: center;">5</td></tr>
    <tr><td style="text-align: center;">5</td><td style="text-align: center;">インド</td><td style="text-align: center;">5</td></tr>
    <tr><td style="text-align: center;">7</td><td style="text-align: center;">スペイン</td><td style="text-align: center;">3</td></tr>
    <tr><td style="text-align: center;">7</td><td style="text-align: center;">フランス</td><td style="text-align: center;">3</td></tr>
    <tr><td style="text-align: center;">7</td><td style="text-align: center;">オーストラリア</td><td style="text-align: center;">3</td></tr>
    <tr><td style="text-align: center;">10</td><td style="text-align: center;">英国、韓国、ベトナム、ロシア、オランダ</td><td style="text-align: center;">2</td></tr>
    <tr><td style="text-align: center;">15</td><td style="text-align: center;">アルゼンチン、ベルギー、コロンビア、チェコ、フィンランド、インドネシア、アイルランド、イタリア、日本、ケニア、ノルウェー、パキスタン、ポルトガル、スリランカ、スウェーデン、スイス、トルコ、ウクライナ</td><td style="text-align: center;">1</td></tr>
    </tbody>
  </table>
</div>

**分析：多極化が進む一方、上位への集中は依然として顕著**

**米国は 23 地域で大幅に先行**し、カリフォルニア、ニューヨーク、テキサス、ワシントンなど主要な技術拠点を広く含む。企業主導、大学主導、コミュニティの自発的協働のいずれにおいても、成熟した多様なエコシステムを構築している。

**ドイツ（10 地域）**はベルリンやミュンヘンだけでなく、バイエルン州、ノルトライン＝ヴェストファーレン州、バーデン＝ヴュルテンベルク州など複数の州が入り、産業用ソフトウェア、組み込みシステム、OS での蓄積と幅広い動員力を示す。

**ブラジルと中国は各 8 地域で第 3 位**となり、新興経済国の成長を示した。

- **ブラジル**ではサンパウロ、リオデジャネイロ、ミナスジェライスなどが、Web 開発、教育ツール、地域向けインフラで質の高い貢献を続けている。
- **中国**では北京、上海、広東、浙江、江蘇、四川などが、東部・中部・西部の連携と産学研協力を形成し、OS、AI フレームワーク、データベースなど戦略分野で体系的な成果を上げている。

カナダ、インド、スペイン、フランス、オーストラリアなども複数地域が入り、世界は「一極主導」から「多極共生」へ移行している。一方、ランキング後半では一地域のみの国が多く、地域的な連携効果をまだ形成できていない国も多い。

今後の競争力は、個別の有力都市や企業だけでなく、国家レベルの基盤整備、教育体系への深い導入、地域間協働の制度化に左右される。

#### 3.1.3 中国の行政区画影響力 Top 15：二つの中核が先導し、多地域が発展

[中国国内ランキング](https://open-digger.cn/leaderboards?type=divisions-cn)では、「二つの中核による牽引、段階的な波及、地域間連携」という構造が見られる。

表 3.3 中国の行政区画影響力 Top 15

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;">#</th><th style="text-align: center;">行政区画</th><th style="text-align: center;">OpenRank</th><th style="text-align: center;">開発者数（万人）</th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">1</td><td style="text-align: center;">北京市</td><td style="text-align: center;">1,248.72</td><td style="text-align: center;">332.19</td></tr>
    <tr><td style="text-align: center;">2</td><td style="text-align: center;">上海市</td><td style="text-align: center;">1,060.37</td><td style="text-align: center;">244.05</td></tr>
    <tr><td style="text-align: center;">3</td><td style="text-align: center;">広東省</td><td style="text-align: center;">776.99</td><td style="text-align: center;">215.43</td></tr>
    <tr><td style="text-align: center;">4</td><td style="text-align: center;">台湾省</td><td style="text-align: center;">720.46</td><td style="text-align: center;">137.85</td></tr>
    <tr><td style="text-align: center;">5</td><td style="text-align: center;">浙江省</td><td style="text-align: center;">604.81</td><td style="text-align: center;">130.53</td></tr>
    <tr><td style="text-align: center;">6</td><td style="text-align: center;">江蘇省</td><td style="text-align: center;">288.68</td><td style="text-align: center;">81.51</td></tr>
    <tr><td style="text-align: center;">7</td><td style="text-align: center;">四川省</td><td style="text-align: center;">279.84</td><td style="text-align: center;">70.03</td></tr>
    <tr><td style="text-align: center;">8</td><td style="text-align: center;">湖北省</td><td style="text-align: center;">183.93</td><td style="text-align: center;">49.25</td></tr>
    <tr><td style="text-align: center;">9</td><td style="text-align: center;">陝西省</td><td style="text-align: center;">1,153.73</td><td style="text-align: center;">33.14</td></tr>
    <tr><td style="text-align: center;">10</td><td style="text-align: center;">福建省</td><td style="text-align: center;">934.61</td><td style="text-align: center;">24.34</td></tr>
    <tr><td style="text-align: center;">11</td><td style="text-align: center;">山東省</td><td style="text-align: center;">826.96</td><td style="text-align: center;">23.2</td></tr>
    <tr><td style="text-align: center;">12</td><td style="text-align: center;">湖南省</td><td style="text-align: center;">811.66</td><td style="text-align: center;">20.86</td></tr>
    <tr><td style="text-align: center;">13</td><td style="text-align: center;">重慶市</td><td style="text-align: center;">696.07</td><td style="text-align: center;">19.03</td></tr>
    <tr><td style="text-align: center;">14</td><td style="text-align: center;">安徽省</td><td style="text-align: center;">688.02</td><td style="text-align: center;">18.9</td></tr>
    <tr><td style="text-align: center;">15</td><td style="text-align: center;">遼寧省</td><td style="text-align: center;">504.79</td><td style="text-align: center;">16.58</td></tr>
    </tbody>
  </table>
</div>

**北京市**は OpenRank 1,248.72、開発者 332.19 万人で首位にあり、唯一の「超大型オープンソース拠点」である。Huawei、Baidu、Xiaomi、ByteDance などの本社、Tsinghua University、Peking University、Beihang University、中国科学院などの研究機関、海淀区や昌平区の産業園・イノベーション基金が強みを支える。

**上海市**は OpenRank 1,060.37、開発者 244.05 万人で第 2 位となった。外資系・多国籍企業の集積による国際標準との接続、AI 金融・ロボアドバイザー・ブロックチェーンの特色あるエコシステム、杭州・蘇州・南京との長江デルタ連携が特徴である。

**広東省**は OpenRank 776.99、開発者 215.43 万人で第 3 位となり、省級行政区として唯一 Top 3 に入った。特に深圳市（OpenRank 4,440.85）が牽引し、オープンハードウェア、RISC-V、IoT、AI チップ、ロボティクスで発展を続けている。

**台湾省**は OpenRank 7,200.46、開発者 137.85 万人で第 4 位となり、半導体設計、組み込みシステム、ソフトウェアツールチェーンでの蓄積を示した。台北市にはチップ検証や EDA ツール開発に携わるエンジニアが多い。

**浙江省**（604.81）と**江蘇省**（288.68）は第 5・第 6 位で、杭州と蘇州を中心に「デジタル経済」と「スマート製造」が発展を牽引する。杭州は Alibaba と Ant Group を背景にクラウド、データベース、AI 大規模モデルへ注力し、蘇州は産業インターネット、スマート製造、エッジコンピューティングに注力している。

**四川省**（279.84）、**湖北省**（183.93）、**陝西省**（1,153.73）など中西部も力強く成長している。成都、武漢、西安では大学、企業、コミュニティが連携するエコシステムが形成され、将来の成長拠点となりつつある。

#### 3.1.4 都市別の詳細分析：真の「オープンソースエンジン」はどこか

中国のオープンソースエコシステムの詳細な構造を明らかにするため、地級市別に OpenRank を分析した。

表 3.4 中国の都市別影響力 Top 15

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;">都市</th><th style="text-align: center;">省</th><th style="text-align: center;">開発者数（万人）</th><th style="text-align: center;">OpenRank 合計</th><th style="text-align: center;">1 万人当たり OpenRank</th><th style="text-align: center;">ランクイン企業</th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">北京市</td><td style="text-align: center;">直轄市</td><td style="text-align: center;">332.19</td><td style="text-align: center;">11,961.74</td><td style="text-align: center;">36.00872994</td><td style="text-align: center;">ByteDance、Baidu</td></tr>
    <tr><td style="text-align: center;">上海市</td><td style="text-align: center;">直轄市</td><td style="text-align: center;">244.05</td><td style="text-align: center;">10,184.38</td><td style="text-align: center;">41.73071092</td><td style="text-align: center;">ESPRESSIF、DaoCloud</td></tr>
    <tr><td style="text-align: center;">杭州市</td><td style="text-align: center;">浙江省</td><td style="text-align: center;">78.66</td><td style="text-align: center;">5,539.76</td><td style="text-align: center;">70.42664633</td><td style="text-align: center;">Alibaba、Ant Group</td></tr>
    <tr><td style="text-align: center;">深圳市</td><td style="text-align: center;">広東省</td><td style="text-align: center;">78.02</td><td style="text-align: center;">4,440.85</td><td style="text-align: center;">56.91937965</td><td style="text-align: center;">Huawei、Tencent</td></tr>
    <tr><td style="text-align: center;">台北市</td><td style="text-align: center;">台湾省</td><td style="text-align: center;">31.71</td><td style="text-align: center;">2,726</td><td style="text-align: center;">85.96657206</td><td style="text-align: center;">-</td></tr>
    <tr><td style="text-align: center;">成都市</td><td style="text-align: center;">四川省</td><td style="text-align: center;">43.22</td><td style="text-align: center;">2,541.42</td><td style="text-align: center;">58.80194354</td><td style="text-align: center;">-</td></tr>
    <tr><td style="text-align: center;">広州市</td><td style="text-align: center;">広東省</td><td style="text-align: center;">50.27</td><td style="text-align: center;">2,408.81</td><td style="text-align: center;">47.91744579</td><td style="text-align: center;">DCloud、Vipshop</td></tr>
    <tr><td style="text-align: center;">武漢市</td><td style="text-align: center;">湖北省</td><td style="text-align: center;">30.46</td><td style="text-align: center;">1,693.07</td><td style="text-align: center;">55.58338805</td><td style="text-align: center;">Deepin、Douyu</td></tr>
    <tr><td style="text-align: center;">南京市</td><td style="text-align: center;">江蘇省</td><td style="text-align: center;">32.32</td><td style="text-align: center;">1,607.67</td><td style="text-align: center;">49.74226485</td><td style="text-align: center;">-</td></tr>
    <tr><td style="text-align: center;">西安市</td><td style="text-align: center;">陝西省</td><td style="text-align: center;">20.88</td><td style="text-align: center;">1,061.61</td><td style="text-align: center;">50.8433908</td><td style="text-align: center;">-</td></tr>
    <tr><td style="text-align: center;">蘇州市</td><td style="text-align: center;">江蘇省</td><td style="text-align: center;">12.6</td><td style="text-align: center;">754.69</td><td style="text-align: center;">59.89603175</td><td style="text-align: center;">-</td></tr>
    <tr><td style="text-align: center;">長沙市</td><td style="text-align: center;">湖南省</td><td style="text-align: center;">10.75</td><td style="text-align: center;">590.25</td><td style="text-align: center;">54.90697674</td><td style="text-align: center;">-</td></tr>
    <tr><td style="text-align: center;">重慶市</td><td style="text-align: center;">重慶市</td><td style="text-align: center;">9.87</td><td style="text-align: center;">567.11</td><td style="text-align: center;">57.45795339</td><td style="text-align: center;">-</td></tr>
    <tr><td style="text-align: center;">合肥市</td><td style="text-align: center;">安徽省</td><td style="text-align: center;">9.91</td><td style="text-align: center;">554.26</td><td style="text-align: center;">55.92936428</td><td style="text-align: center;">iFLYTEK</td></tr>
    <tr><td style="text-align: center;">厦門市</td><td style="text-align: center;">福建省</td><td style="text-align: center;">9.19</td><td style="text-align: center;">527.67</td><td style="text-align: center;">57.41784548</td><td style="text-align: center;">-</td></tr>
    </tbody>
  </table>
</div>

北京、上海、杭州、深圳、台北、成都、広州は、中国のオープンソースを支える「七つの都市エンジン」である。

- **北京が二指標で首位、上海が続く**：北京はアクティブ開発者 332.19 万人、OpenRank 合計 11,961.74 でともに首位、上海は 244.05 万人、10,184.38 で第 2 位となった。両都市で中国全体の影響力の約 40%を占める。
- **杭州は中国大陸の人口当たり首位**：開発者 78.66 万人で 1 万人当たり OpenRank 70.43 を達成した。Alibaba と Ant Group が Dubbo、RocketMQ、Seata、Apache Flink、Tongyi Qianwen などを通じ、実運用、文書、コミュニティ運営を重視するプロダクションレベルのモデルを築いたことが背景にある。
- **深圳、成都、蘇州は異なる経路で発展**：深圳（56.92）は Huawei と Tencent の幅広い技術、成都（58.80）は DataCanvas など AI ネイティブ企業、蘇州（59.90）は製造業を背景とする産業用ソフトウェアとエッジコンピューティングが強みである。
- **台北は人口当たりで全国首位**：開発者 31.71 万人に対し 1 万人当たり OpenRank は 85.97 である。半導体設計、組み込み、オープンハードウェア、EDA ツールチェーンに強く、Linux カーネル、Chisel、OpenTitan など世界的プロジェクトへ質の高い貢献を行っている。

<center><img src="/image/data/figure-3-1-china-city-influence-heatmap.png" width="700"></center>

<center>図 3.1 中国の都市別影響力ヒートマップ</center>

<center>出典：OpenDigger プラットフォームのデータを基に作成</center>

- 活動は東部沿海、特に**京津冀**、**長江デルタ**、**珠江デルタ**の三大都市圏に集中している。
- 西安、合肥、長沙、重慶など中西部の一部都市は「第二のホットスポット」を形成し、地域連携の可能性を示す。
- 新疆、チベット、青海など西部は基盤が小さいが、近年の成長率は高く、「デジタル・シルクロード」戦略の進展を示している。

**比較：中国を世界の中でどう位置づけるか**

- 中国は「量」で世界上位に近づいたが、「質」にはなお差がある。北京と上海は世界 Top 15 に入ったものの、OpenRank はカリフォルニア州やイングランドを大きく下回る。
- 北京と上海の「二つの中核」は、基礎研究と産業応用の好循環を形成する中国独自の強みである。
- 成都、西安、武漢、合肥など中西部の都市が新たな勢力となり、沿海部への依存から内陸との連携へ移りつつある。
- 各地の政府が個別の支援策を打ち出し、オープンソースは技術上の選択から都市の戦略的資産へ変化している。

### 3.2 オープンソース企業影響力ランキング

企業はオープンソースエコシステムの中核的な参加者であり、重要な推進力である。中国企業の役割は、初期の「利用者」から「共同構築者」、さらには「先導者」へと大きく変化している。真の影響力は、単に一つのプロジェクトを公開することではなく、重要インフラの保守、透明なコミュニティガバナンス、組織を越えた開かれた協働、世界標準への貢献に表れる。

本節は 2025 年の中国オープンソース企業影響力ランキングを公表する。テクノロジー大手、基盤ソフトウェア企業、AI スタートアップ、非営利組織を対象とし、コミュニティ OpenRank とグローバル OpenRank を組み合わせて評価する。主要プロジェクトでのメンテナーとしての役割、Pull Request のマージ率、Issue への応答時間、文書の国際化など、質を重視している。

#### 3.2.1 世界のオープンソース企業影響力 Top 15：米中二強の構造が深化

2025 年の[世界オープンソース企業影響力ランキング](https://open-digger.cn/leaderboards?type=companies)では、**Microsoft** が OpenRank 205,596.64 で首位を維持した。Azure、Visual Studio Code、.NET などへの投資に加え、世界の開発者コミュニティで強い協働ネットワークと信頼関係を築いている。

表 3.5 世界のオープンソース企業影響力 Top 15

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;">#</th><th style="text-align: center;">企業名</th><th style="text-align: center;">OpenRank（前年比）</th><th style="text-align: center;">アクティブリポジトリ数</th><th style="text-align: center;">アクティブ開発者数</th><th style="text-align: center;">国</th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">1</td><td style="text-align: center;">Microsoft</td><td style="text-align: center;">205,596.64 (+47,395.82)</td><td style="text-align: center;">5,782</td><td style="text-align: center;">116,881</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">2</td><td style="text-align: center;">Huawei</td><td style="text-align: center;">89,368.78 (+12,607.45)</td><td style="text-align: center;">8,273</td><td style="text-align: center;">12,716</td><td style="text-align: center;">中国</td></tr>
    <tr><td style="text-align: center;">3</td><td style="text-align: center;">Google</td><td style="text-align: center;">75,962.65 (−21,091.96)</td><td style="text-align: center;">1,663</td><td style="text-align: center;">50,724</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">4</td><td style="text-align: center;">Amazon</td><td style="text-align: center;">49,969.58 (+10,234.11)</td><td style="text-align: center;">3,527</td><td style="text-align: center;">24,170</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">5</td><td style="text-align: center;">Meta</td><td style="text-align: center;">44,005.22 (+8,762.33)</td><td style="text-align: center;">706</td><td style="text-align: center;">23,311</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">6</td><td style="text-align: center;">RedHat</td><td style="text-align: center;">38,091.50 (+5,418.90)</td><td style="text-align: center;">817</td><td style="text-align: center;">7,828</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">7</td><td style="text-align: center;">NVIDIA</td><td style="text-align: center;">37,351.36 (+6,392.54)</td><td style="text-align: center;">681</td><td style="text-align: center;">12,781</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">8</td><td style="text-align: center;">Elastic</td><td style="text-align: center;">36,883.73 (+9,201.47)</td><td style="text-align: center;">412</td><td style="text-align: center;">3,802</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">9</td><td style="text-align: center;">Grafana Labs</td><td style="text-align: center;">30,430.93 (+7,845.22)</td><td style="text-align: center;">522</td><td style="text-align: center;">8,009</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">10</td><td style="text-align: center;">Alibaba</td><td style="text-align: center;">26,349.25 (−5,670.27)</td><td style="text-align: center;">2,797</td><td style="text-align: center;">14,595</td><td style="text-align: center;">中国</td></tr>
    <tr><td style="text-align: center;">11</td><td style="text-align: center;">Mozilla</td><td style="text-align: center;">25,539.37 (+3,102.84)</td><td style="text-align: center;">672</td><td style="text-align: center;">11,857</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">12</td><td style="text-align: center;">Hugging Face</td><td style="text-align: center;">23,794.95 (+5,212.82)</td><td style="text-align: center;">221</td><td style="text-align: center;">13,575</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">13</td><td style="text-align: center;">DataDog</td><td style="text-align: center;">20,850.26 (+4,337.61)</td><td style="text-align: center;">427</td><td style="text-align: center;">4,550</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">14</td><td style="text-align: center;">IBM</td><td style="text-align: center;">20,527.84 (−2,984.55)</td><td style="text-align: center;">2,119</td><td style="text-align: center;">13,712</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">15</td><td style="text-align: center;">Nabu Casa Inc.</td><td style="text-align: center;">19,967.42 (+18,421.03)</td><td style="text-align: center;">67</td><td style="text-align: center;">23,622</td><td style="text-align: center;">米国</td></tr>
    </tbody>
  </table>
</div>

**Huawei** は 89,368.78 で第 2 位となり、前年比 12,607.45 増加した。OpenHarmony、Ascend AI、KubeEdge への継続的な投資により、基盤ソフトウェア、AI チップ、IoT の各エコシステムへ同時に影響を与えている。**Google** は 75,962.65 で第 3 位だが、前年比 21,091.96 減少し、Android や TensorFlow などでコミュニティの分化と競争激化に直面している。

Amazon、Meta、RedHat が第 4～6 位となり、NVIDIA は第 7 位へ上昇した。CUDA、TensorRT などへの取り組みにより、ハードウェア企業から AI インフラプラットフォームへ移行している。**Hugging Face** は初めて Top 15 に入り、第 12 位となった。Model Hub、Inference API、Transformers によりモデルの再利用と導入を容易にし、研究と産業をつなぐ基盤となっている。

<center><img src="/image/data/figure-3-3-global-enterprise-influence-decade-shift.png" width="700"></center>

<center>図 3.2 世界企業のオープンソース影響力の 10 年間の推移</center>

<center>出典：OpenDigger プラットフォームのデータを基に作成</center>

主な発見は次のとおりである。

- **NVIDIA が周辺から中心へ**：2024 年に初めて Top 15 の第 10 位となり、2025 年は第 7 位へ上昇した。GPU、CUDA、TensorRT-LLM などを通じ、「計算資源＋フレームワーク＋コミュニティ」のエコシステムを構築した。
- **Hugging Face が AI オープンソースの新たな推進力に**：2023 年の第 14 位から 2024 年に第 12 位へ上昇し、2025 年も維持した。MaaS が世界の開発者に不可欠なインフラとなったことを示す。
- **Mozilla は主流での競争力が低下**：2016 年の第 5 位、2017 年の第 4 位から順位を下げ、2024～2025 年は第 11 位となった。Firefox は影響力を保つが、AI、クラウドネイティブ、開発者ツールで広範な影響を持つ新規プロジェクトが少ない。
- **中国企業が歴史的に躍進**：Huawei は 2023 年に第 3 位、2024～2025 年に第 2 位となり、世界上位 5 社に入る唯一の非米国企業となった。

<center><img src="/image/data/figure-3-2-global-enterprise-influence-2025-shift.png" width="700"></center>

<center>図 3.3 2025 年中の世界企業オープンソース影響力の順位変動</center>

<center>出典：OpenDigger プラットフォームのデータを基に作成</center>

- **NVIDIA が急上昇**：年初の第 9 位から年末の第 4 位へ上昇し、10 月には Amazon と Meta を一時上回った。
- **Elastic が再び上位へ**：年初の第 7～8 位から、OpenSearch と可観測性ツールチェーンの活動を背景に、年末は第 6 位となった。
- **新興勢力が成長**：Tenstorrent は 2025 年 10 月に初めて Top 15 に入り、年末には第 12 位となった。Ant Group と Zed Industry も 11 月に Top 15 に入り、従来の大手中心の構造が多様化している。

#### 3.2.2 中国のオープンソース企業影響力 Top 15：上位が先行し、新興勢力が成長

中国では、オープンソースは「技術上の補完」から「戦略上の必須要素」へ変化した。2025 年の[中国オープンソース企業影響力ランキング](https://open-digger.cn/leaderboards?type=companies-cn)は、上位の安定、明確なグループ分け、新企業の登場を示している。

表 3.6 中国のオープンソース企業影響力 Top 15

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;">#</th><th style="text-align: center;">企業名</th><th style="text-align: center;">OpenRank（前年比）</th><th style="text-align: center;">アクティブリポジトリ数</th><th style="text-align: center;">アクティブ開発者数</th><th style="text-align: center;">国</th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">1</td><td style="text-align: center;">Huawei</td><td style="text-align: center;">89,368.78 (+12,607.45)</td><td style="text-align: center;">8,273</td><td style="text-align: center;">12,716</td><td style="text-align: center;">中国</td></tr>
    <tr><td style="text-align: center;">2</td><td style="text-align: center;">Alibaba</td><td style="text-align: center;">26,349.25 (−5,670.27)</td><td style="text-align: center;">2,797</td><td style="text-align: center;">14,595</td><td style="text-align: center;">中国</td></tr>
    <tr><td style="text-align: center;">3</td><td style="text-align: center;">Ant group</td><td style="text-align: center;">18,679.05 (+4,002.61)</td><td style="text-align: center;">768</td><td style="text-align: center;">10,726</td><td style="text-align: center;">中国</td></tr>
    <tr><td style="text-align: center;">4</td><td style="text-align: center;">ByteDance</td><td style="text-align: center;">16,625.76 (+6,703.16)</td><td style="text-align: center;">458</td><td style="text-align: center;">12,398</td><td style="text-align: center;">中国</td></tr>
    <tr><td style="text-align: center;">5</td><td style="text-align: center;">Baidu</td><td style="text-align: center;">13,651.87 (−5,339.68)</td><td style="text-align: center;">152</td><td style="text-align: center;">5,841</td><td style="text-align: center;">中国</td></tr>
    <tr><td style="text-align: center;">6</td><td style="text-align: center;">PingCAP</td><td style="text-align: center;">7,917.36 (+1,878.88)</td><td style="text-align: center;">99</td><td style="text-align: center;">845</td><td style="text-align: center;">中国</td></tr>
    <tr><td style="text-align: center;">7</td><td style="text-align: center;">ESPRESSIF</td><td style="text-align: center;">6,141.94 (+1,226.29)</td><td style="text-align: center;">171</td><td style="text-align: center;">4,293</td><td style="text-align: center;">中国</td></tr>
    <tr><td style="text-align: center;">8</td><td style="text-align: center;">Tencent</td><td style="text-align: center;">5,717.46 (+1,492.99)</td><td style="text-align: center;">254</td><td style="text-align: center;">4,629</td><td style="text-align: center;">中国</td></tr>
    <tr><td style="text-align: center;">9</td><td style="text-align: center;">Fit2Cloud</td><td style="text-align: center;">4,945.60 (+2,065.73)</td><td style="text-align: center;">65</td><td style="text-align: center;">2,562</td><td style="text-align: center;">中国</td></tr>
    <tr><td style="text-align: center;">10</td><td style="text-align: center;">DaoCloud</td><td style="text-align: center;">4,558.18 (−8,306.29)</td><td style="text-align: center;">61</td><td style="text-align: center;">1,929</td><td style="text-align: center;">中国</td></tr>
    <tr><td style="text-align: center;">11</td><td style="text-align: center;">SelectDB</td><td style="text-align: center;">4,099.92 (+873.02)</td><td style="text-align: center;">11</td><td style="text-align: center;">756</td><td style="text-align: center;">中国</td></tr>
    <tr><td style="text-align: center;">12</td><td style="text-align: center;">LobeHub</td><td style="text-align: center;">4,037.59 (+231.96)</td><td style="text-align: center;">26</td><td style="text-align: center;">1,865</td><td style="text-align: center;">中国</td></tr>
    <tr><td style="text-align: center;">13</td><td style="text-align: center;">Zilliz</td><td style="text-align: center;">3,561.51 (−431.39)</td><td style="text-align: center;">55</td><td style="text-align: center;">1,502</td><td style="text-align: center;">中国</td></tr>
    <tr><td style="text-align: center;">14</td><td style="text-align: center;">openKylin</td><td style="text-align: center;">3,180.90 (−922.31)</td><td style="text-align: center;">1,283</td><td style="text-align: center;">773</td><td style="text-align: center;">中国</td></tr>
    <tr><td style="text-align: center;">15</td><td style="text-align: center;">StarRocks</td><td style="text-align: center;">2,770.29 (−762.91)</td><td style="text-align: center;">19</td><td style="text-align: center;">762</td><td style="text-align: center;">中国</td></tr>
    </tbody>
  </table>
</div>

Huawei は 89,368.78 で首位を維持し、第 2 位の Alibaba（26,349.25）を大きく上回った。OS、通信プロトコル、チップアーキテクチャへの体系的な投資により、中国製技術への代替と国際標準の共同策定を推進している。

Alibaba はデータベース、クラウド、ミドルウェアへの継続的な投資で第 2 位、Ant Group はブロックチェーン、金融向け分散システム、プライバシー保護計算で第 3 位となった。ByteDance は動画処理、推薦アルゴリズム、AIGC ツールチェーンを背景に第 4 位へ上昇した。Baidu は第 5 位で、PaddlePaddle の普及における課題から前年比で低下した。

垂直分野では、PingCAP（TiDB）、ESPRESSIF（RISC-V IoT チップ）、LobeHub（AI 可視化）、Zilliz（Milvus）が成長した。DaoCloud と openKylin もコンテナと OS で重要な影響力を持つ。

<center><img src="/image/data/figure-3-4-china-tech-enterprise-influence-decade-shift.png" width="700"></center>

<center>図 3.4 中国テクノロジー企業のオープンソース影響力の 10 年間の推移</center>

<center>出典：OpenDigger プラットフォームのデータを基に作成</center>

- **Huawei が大幅に先行**：2016 年の第 15 位から上昇し、2022 年以降は世界第 2 位を維持した。
- **ByteDance が急成長**：2021 年に初めて入り、2025 年は RAGFlow、verl などを背景に第 4 位となった。
- **Tencent は回復、Baidu は低下**：Tencent は第 8 位、Baidu は初期の第 2 位から第 5 位へ低下した。
- **垂直分野の新企業が登場**：PingCAP、ESPRESSIF、LobeHub、StarRocks などが Top 15 に入った。
- **一部企業は低下**：DaoCloud は 2024 年の Top 5 から 2025 年の第 10 位へ、StarRocks は 2024～2025 年に第 15 位へ低下した。コミュニティ投資の減少、AI ネイティブプロジェクトの不足、商用版・クラウドサービスへの機能移行などが要因として推測される。

<center><img src="/image/data/figure-3-5-china-enterprise-influence-2025-shift.png" width="700"></center>

<center>図 3.5 2025 年中の中国企業オープンソース影響力の順位変動</center>

<center>出典：OpenDigger プラットフォームのデータを基に作成</center>

- **ByteDance が大幅に上昇**：年初の第 4 位から、7 月に Baidu と Ant Group を上回り、年末は第 3 位となった。
- **DaoCloud が急低下**：年初の第 6 位から年末の第 15 位へ低下した。コミュニティ運営と更新頻度の低下、AI ネイティブインフラ分野での新規プロジェクト不足が、持続可能な投資の重要性を示している。
- **垂直分野で競争が激化**：PingCAP と ESPRESSIF、LobeHub、StarRocks、Zilliz がそれぞれデータベース、IoT、AI、ベクトル検索で存在感を高めた。
- **多極化が進展**：Huawei と Alibaba が第 1 グループ、ByteDance、Tencent、PingCAP が第 2 グループを形成し、各分野の企業が中国のエコシステムを多様化している。

### 3.3 オープンソースプロジェクト影響力ランキング

オープンソースプロジェクトの真の価値は、一時的な人気ではなく、技術エコシステムの基盤、開発者協働の中核、産業導入への橋渡しとなるかにある。2025 年には、基盤ソフトウェア、AI フレームワーク、開発ツールなどで発展を続ける成熟プロジェクトが、複雑で安定した協働ネットワークを築いた。

本報告はコード規模だけでなく、グリーンコンピューティング、教育機会、透明なガバナンスなど、OSDGs の環境・社会・ガバナンスへの貢献も重視する。

#### 3.3.1 世界のオープンソースプロジェクト影響力 Top 15：中国発プロジェクトが躍進し、基盤ソフトウェアと AI が牽引

[世界オープンソースプロジェクトランキング](https://open-digger.cn/leaderboards?type=projects)では、中国主導の基盤ソフトウェアが大きく先行し、Microsoft などのプロジェクト群も強さを維持した。AI 大規模モデル推論などの新分野も上位へ進出している。

表 3.7 世界のオープンソースプロジェクト影響力 Top 15

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;">順位</th><th style="text-align: center;">プロジェクト名</th><th style="text-align: center;">OpenRank</th><th style="text-align: center;">開発者数</th><th style="text-align: center;">設立組織</th><th style="text-align: center;">国</th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">1</td><td style="text-align: center;">OpenHarmony</td><td style="text-align: center;">60,089.18</td><td style="text-align: center;">6,487</td><td style="text-align: center;">OpenAtom Foundation</td><td style="text-align: center;">中国</td></tr>
    <tr><td style="text-align: center;">2</td><td style="text-align: center;">Azure</td><td style="text-align: center;">40,923.04</td><td style="text-align: center;">16,128</td><td style="text-align: center;">Microsoft</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">3</td><td style="text-align: center;">NixOS</td><td style="text-align: center;">26,457.31</td><td style="text-align: center;">9,521</td><td style="text-align: center;">Stichting NixOS Foundation</td><td style="text-align: center;">オランダ</td></tr>
    <tr><td style="text-align: center;">4</td><td style="text-align: center;">C#/.Net</td><td style="text-align: center;">26,444.52</td><td style="text-align: center;">14,266</td><td style="text-align: center;">Microsoft</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">5</td><td style="text-align: center;">LLVM</td><td style="text-align: center;">24,931.93</td><td style="text-align: center;">5,998</td><td style="text-align: center;">University of Illinois Urbana-Champaign</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">6</td><td style="text-align: center;">DataDog</td><td style="text-align: center;">20,850.26</td><td style="text-align: center;">4,550</td><td style="text-align: center;">DataDog</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">7</td><td style="text-align: center;">OpenShift</td><td style="text-align: center;">20,670.92</td><td style="text-align: center;">2,429</td><td style="text-align: center;">RedHat</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">8</td><td style="text-align: center;">VSCode</td><td style="text-align: center;">20,589.02</td><td style="text-align: center;">35,458</td><td style="text-align: center;">Microsoft</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">9</td><td style="text-align: center;">Home Assistant</td><td style="text-align: center;">19,967.42</td><td style="text-align: center;">23,622</td><td style="text-align: center;">Nabu Casa Inc.</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">10</td><td style="text-align: center;">openEuler</td><td style="text-align: center;">16,257.57</td><td style="text-align: center;">3,285</td><td style="text-align: center;">OpenAtom Foundation</td><td style="text-align: center;">中国</td></tr>
    <tr><td style="text-align: center;">11</td><td style="text-align: center;">Odoo</td><td style="text-align: center;">14,422.54</td><td style="text-align: center;">2,296</td><td style="text-align: center;">Odoo</td><td style="text-align: center;">ベルギー</td></tr>
    <tr><td style="text-align: center;">12</td><td style="text-align: center;">vLLM</td><td style="text-align: center;">12,862.73</td><td style="text-align: center;">10,254</td><td style="text-align: center;">-</td><td style="text-align: center;">-</td></tr>
    <tr><td style="text-align: center;">13</td><td style="text-align: center;">Rust</td><td style="text-align: center;">12,626.95</td><td style="text-align: center;">6,611</td><td style="text-align: center;">Rust Foundation</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">14</td><td style="text-align: center;">Swift</td><td style="text-align: center;">12,520.10</td><td style="text-align: center;">1,595</td><td style="text-align: center;">Apple</td><td style="text-align: center;">米国</td></tr>
    <tr><td style="text-align: center;">15</td><td style="text-align: center;">Conda Forge</td><td style="text-align: center;">11,431.75</td><td style="text-align: center;">4,402</td><td style="text-align: center;">-</td><td style="text-align: center;">-</td></tr>
    </tbody>
  </table>
</div>

OpenHarmony は OpenRank 6 万超で首位となり、第 2 位 Azure の約 1.5 倍に達した。openEuler も第 10 位に入り、中国が IoT 向け OS とサーバー OS で存在感を高めた。Microsoft は Azure、C#/.Net、VSCode の三プロジェクトが Top 10 に入り、VSCode の開発者数は全プロジェクトで最大だった。vLLM は第 12 位となり、生成 AI の普及により推論基盤が新たな競争分野になったことを示す。NixOS、LLVM、Rust も、再現可能なビルド、コンパイラ、メモリ安全性の重要性を示している。

表 3.8 世界オープンソースプロジェクト影響力 Top 100 の国別選出数

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;">順位</th><th style="text-align: center;">国</th><th style="text-align: center;">選出プロジェクト数</th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">1</td><td style="text-align: center;">米国</td><td style="text-align: center;">49</td></tr>
    <tr><td style="text-align: center;">2</td><td style="text-align: center;">中国</td><td style="text-align: center;">12</td></tr>
    <tr><td style="text-align: center;">3</td><td style="text-align: center;">ドイツ</td><td style="text-align: center;">3</td></tr>
    <tr><td style="text-align: center;">3</td><td style="text-align: center;">オランダ</td><td style="text-align: center;">3</td></tr>
    <tr><td style="text-align: center;">5</td><td style="text-align: center;">ロシア</td><td style="text-align: center;">2</td></tr>
    <tr><td style="text-align: center;">6</td><td style="text-align: center;">英国、イスラエル、フランス、アイスランド、カナダ、南アフリカ、ノルウェー、スイス、ブルガリア</td><td style="text-align: center;">1</td></tr>
    </tbody>
  </table>
</div>

米国が 49 件で大きく先行し、中国が 12 件で続く。中国は OpenHarmony、openEuler、MindSpore などにより、基盤ソフトウェアと AI での戦略的な成果を示している。

#### 3.3.2 中国のオープンソースプロジェクト影響力 Top 15：二つの OS が牽引し、AI と大規模モデルが全面的に成長

2025 年の[中国オープンソースプロジェクトランキング](https://open-digger.cn/leaderboards?type=projects-cn)では、OpenHarmony と openEuler が大きく先行し、AI フレームワークとツールチェーンも多数入った。「基盤ソフトウェア＋AI ネイティブ応用」が成長を支える構造となっている。

表 3.9 中国のオープンソースプロジェクト影響力 Top 15

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;">順位</th><th style="text-align: center;">プロジェクト名</th><th style="text-align: center;">OpenRank</th><th style="text-align: center;">開発者数</th><th style="text-align: center;">設立組織</th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">1</td><td style="text-align: center;">OpenHarmony</td><td style="text-align: center;">60,089.18</td><td style="text-align: center;">6,487</td><td style="text-align: center;">OpenAtom Foundation</td></tr>
    <tr><td style="text-align: center;">2</td><td style="text-align: center;">openEuler</td><td style="text-align: center;">16,257.57</td><td style="text-align: center;">3,285</td><td style="text-align: center;">OpenAtom Foundation</td></tr>
    <tr><td style="text-align: center;">3</td><td style="text-align: center;">MindSpore</td><td style="text-align: center;">8,064.37</td><td style="text-align: center;">1,211</td><td style="text-align: center;">Huawei</td></tr>
    <tr><td style="text-align: center;">4</td><td style="text-align: center;">PaddlePaddle</td><td style="text-align: center;">7,305.94</td><td style="text-align: center;">3,168</td><td style="text-align: center;">Baidu</td></tr>
    <tr><td style="text-align: center;">5</td><td style="text-align: center;">Apache Doris</td><td style="text-align: center;">4,031.07</td><td style="text-align: center;">747</td><td style="text-align: center;">Apache Software Foundation</td></tr>
    <tr><td style="text-align: center;">6</td><td style="text-align: center;">ModelScope</td><td style="text-align: center;">3,681.64</td><td style="text-align: center;">3,732</td><td style="text-align: center;">Alibaba</td></tr>
    <tr><td style="text-align: center;">7</td><td style="text-align: center;">VolcEngine</td><td style="text-align: center;">3,638.97</td><td style="text-align: center;">3,686</td><td style="text-align: center;">ByteDance</td></tr>
    <tr><td style="text-align: center;">8</td><td style="text-align: center;">Ant Design</td><td style="text-align: center;">3,288.48</td><td style="text-align: center;">3,288</td><td style="text-align: center;">Ant Group</td></tr>
    <tr><td style="text-align: center;">9</td><td style="text-align: center;">openKylin</td><td style="text-align: center;">3,180.90</td><td style="text-align: center;">773</td><td style="text-align: center;">OpenAtom Foundation</td></tr>
    <tr><td style="text-align: center;">10</td><td style="text-align: center;">TiDB</td><td style="text-align: center;">3,162.02</td><td style="text-align: center;">498</td><td style="text-align: center;">PingCAP</td></tr>
    <tr><td style="text-align: center;">11</td><td style="text-align: center;">Anolis OS</td><td style="text-align: center;">2,996.83</td><td style="text-align: center;">514</td><td style="text-align: center;">OpenAtom Foundation</td></tr>
    <tr><td style="text-align: center;">12</td><td style="text-align: center;">verl</td><td style="text-align: center;">2,785.19</td><td style="text-align: center;">2,875</td><td style="text-align: center;">ByteDance</td></tr>
    <tr><td style="text-align: center;">13</td><td style="text-align: center;">StarRocks</td><td style="text-align: center;">2,770.29</td><td style="text-align: center;">762</td><td style="text-align: center;">StarRocks</td></tr>
    <tr><td style="text-align: center;">14</td><td style="text-align: center;">Milvus</td><td style="text-align: center;">2,640.81</td><td style="text-align: center;">986</td><td style="text-align: center;">LF AI &amp; Data Foundation</td></tr>
    <tr><td style="text-align: center;">15</td><td style="text-align: center;">1Panel</td><td style="text-align: center;">2,304.38</td><td style="text-align: center;">1,369</td><td style="text-align: center;">Fit2Cloud</td></tr>
    </tbody>
  </table>
</div>

OpenHarmony と openEuler は端末側とクラウド側の OS 基盤を構成し、openKylin と Anolis OS も厚みを加えている。AI では MindSpore、PaddlePaddle、ModelScope、VolcEngine、verl が入り、訓練、推論、最適化への投資拡大を示す。Apache Doris、TiDB、StarRocks は分散データ基盤で競争力を保ち、Ant Design と 1Panel は上位の開発・運用ツールへの広がりを示す。

#### 3.3.3 2025 年中国オープンソースプロジェクト影響力急上昇ランキング

2025 年の中国ランキングで、前年からの順位上昇が大きい代表的なプロジェクトを示す。

表 3.10 中国オープンソースプロジェクト影響力急上昇 Top 10

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;">順位</th><th style="text-align: center;">総合順位（上昇幅）</th><th style="text-align: center;">プロジェクト名</th><th style="text-align: center;">OpenRank（前年比）</th><th style="text-align: center;">設立組織</th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">1</td><td style="text-align: center;">7（+1,582）</td><td style="text-align: center;">verl-project/verl</td><td style="text-align: center;">2,785.19 (+2,766.84)</td><td style="text-align: center;">ByteDance</td></tr>
    <tr><td style="text-align: center;">2</td><td style="text-align: center;">45（+484）</td><td style="text-align: center;">alibaba/spring-ai-alibaba</td><td style="text-align: center;">736.62 (+ 647.68)</td><td style="text-align: center;">Alibaba</td></tr>
    <tr><td style="text-align: center;">3</td><td style="text-align: center;">46（+676）</td><td style="text-align: center;">kvcache-ai/ktransformers</td><td style="text-align: center;">734.98 (+ 678.99)</td><td style="text-align: center;">Tsinghua University</td></tr>
    <tr><td style="text-align: center;">4</td><td style="text-align: center;">50（+339）</td><td style="text-align: center;">kwdb/kwdb</td><td style="text-align: center;">700.98 (+ 573.29)</td><td style="text-align: center;">KaiwuDB</td></tr>
    <tr><td style="text-align: center;">5</td><td style="text-align: center;">56(+252)</td><td style="text-align: center;">PaddlePaddle/FastDeploy</td><td style="text-align: center;">662.22(+490.94)</td><td style="text-align: center;">Baidu</td></tr>
    <tr><td style="text-align: center;">6</td><td style="text-align: center;">58(+413)</td><td style="text-align: center;">gpustack/gpustack</td><td style="text-align: center;">641.9(+537.58)</td><td style="text-align: center;">GPUstack.ai</td></tr>
    <tr><td style="text-align: center;">7</td><td style="text-align: center;">63(+437)</td><td style="text-align: center;">XiaoMi/ha_xiaomi_home</td><td style="text-align: center;">558.72(+463.29)</td><td style="text-align: center;">Xiaomi</td></tr>
    <tr><td style="text-align: center;">8</td><td style="text-align: center;">89(+1,434)</td><td style="text-align: center;">kvcache-ai/Mooncake</td><td style="text-align: center;">428.71(+409.14)</td><td style="text-align: center;">Tsinghua University</td></tr>
    <tr><td style="text-align: center;">9</td><td style="text-align: center;">91(+402)</td><td style="text-align: center;">ant-design/x</td><td style="text-align: center;">420.09 (+323.20)</td><td style="text-align: center;">Ant Group</td></tr>
    <tr><td style="text-align: center;">10</td><td style="text-align: center;">100(+1,233)</td><td style="text-align: center;">deepseek-ai/DeepSeek-V3</td><td style="text-align: center;">394.05 (+370.39)</td><td style="text-align: center;">DeepSeek</td></tr>
    </tbody>
  </table>
</div>

- **ByteDance が AI インフラの新たな形を牽引**：`verl-project/verl` は 1,582 位上昇して第 7 位となった。RLHF 訓練を標準化・再現可能にし、AI Agent 製品を支えている。
- **大学発プロジェクトが躍進**：Tsinghua University の `ktransformers` と `Mooncake` は、大規模モデルの推論最適化と訓練スケジューリングに注力し、産業界でも採用された。
- **企業向け AI ツールチェーンが成熟**：`spring-ai-alibaba`、`FastDeploy`、`ant-design/x` は、Java、推論導入、フロントエンドで AI を実運用へつなげる。
- **垂直分野での価値が顕在化**：KaiwuDB の `kwdb`、Xiaomi の `ha_xiaomi_home`、GPUStack.ai の `gpustack` は、AIoT、スマートホーム、GPU リソース管理という具体的な課題を解決する。
- **イノベーションは「用途を定義する」段階へ**：汎用性だけでなく、RLHF、推論、IoT、スマートホームなど具体的な利用場面に結びついたプロジェクトが急成長している。

### 3.4 新興オープンソースプロジェクトランキング

オープンソースエコシステムの活力は、成熟プロジェクトの安定した発展だけでなく、新たな勢力の継続的な登場からも生まれる。2025 年には、AI 大規模モデル、エージェント、プライバシー保護計算、RISC-V ツールチェーン、持続可能なソフトウェア工学などで新規プロジェクトが急成長した。

本節は 2025 年 1 月 1 日以降に初めて公開され、優れた実績を示したプロジェクトを対象とする。成長速度、技術の独自性、コミュニティの活発度、長期的な可能性を評価する。

#### 3.4.1 世界の新興オープンソースプロジェクトランキング：AI が先導し、多様な分野が発展

表 3.11 世界の新興オープンソースプロジェクト Top 30

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;">順位</th><th style="text-align: center;">プロジェクト名</th><th style="text-align: center;">月平均 OpenRank</th><th style="text-align: center;">技術分野</th><th style="text-align: center;">主要言語</th><th style="text-align: center;">説明</th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">1</td><td style="text-align: center;">DigitalPlatDev/FreeDomain</td><td style="text-align: center;">1,219.0694</td><td style="text-align: center;">応用・ソリューション</td><td style="text-align: center;">HTML</td><td style="text-align: center;">誰でも利用できる無料ドメインサービス</td></tr>
    <tr><td style="text-align: center;">2</td><td style="text-align: center;">CherryHQ/cherry-studio</td><td style="text-align: center;">270.4182</td><td style="text-align: center;">AI・フロントエンド</td><td style="text-align: center;">TypeScript</td><td style="text-align: center;">複数の LLM プロバイダーと deepseek-r1 に対応するデスクトップクライアント</td></tr>
    <tr><td style="text-align: center;">3</td><td style="text-align: center;">ggml-org/llama.cpp</td><td style="text-align: center;">240.24</td><td style="text-align: center;">AI・プログラミング言語・開発</td><td style="text-align: center;">C++</td><td style="text-align: center;">C/C++ 環境向け大規模言語モデル推論ツール</td></tr>
    <tr><td style="text-align: center;">4</td><td style="text-align: center;">stackblitz/bolt.new</td><td style="text-align: center;">210.928</td><td style="text-align: center;">AI・フロントエンド・クラウドインフラ</td><td style="text-align: center;">TypeScript</td><td style="text-align: center;">フルスタック Web アプリを迅速に構築、実行、編集、デプロイ</td></tr>
    <tr><td style="text-align: center;">5</td><td style="text-align: center;">RooCodeInc/Roo-Code</td><td style="text-align: center;">191.1142</td><td style="text-align: center;">AI・プログラミング言語・開発</td><td style="text-align: center;">TypeScript</td><td style="text-align: center;">エディタ統合型 AI 自動コーディング支援</td></tr>
    <tr><td style="text-align: center;">6</td><td style="text-align: center;">elizaOS/eliza</td><td style="text-align: center;">158.6689</td><td style="text-align: center;">AI</td><td style="text-align: center;">TypeScript</td><td style="text-align: center;">一般利用者向け自律型エージェントツール</td></tr>
    <tr><td style="text-align: center;">7</td><td style="text-align: center;">cline/cline</td><td style="text-align: center;">122.1027</td><td style="text-align: center;">AI・プログラミング言語・開発</td><td style="text-align: center;">TypeScript</td><td style="text-align: center;">許可に基づきファイル作成・編集やコマンド実行を行う IDE 内エージェント</td></tr>
    <tr><td style="text-align: center;">8</td><td style="text-align: center;">Aider-AI/aider</td><td style="text-align: center;">116.6952</td><td style="text-align: center;">AI・プログラミング言語・開発</td><td style="text-align: center;">Python</td><td style="text-align: center;">ターミナル内の AI ペアプログラミングツール</td></tr>
    <tr><td style="text-align: center;">9</td><td style="text-align: center;">All-Hands-AI/OpenHands</td><td style="text-align: center;">115.2683</td><td style="text-align: center;">AI・プログラミング言語・開発</td><td style="text-align: center;">Python</td><td style="text-align: center;">「コードを減らし、創造を増やす」ためのツール</td></tr>
    <tr><td style="text-align: center;">10</td><td style="text-align: center;">erigontech/erigon</td><td style="text-align: center;">91.0026</td><td style="text-align: center;">ブロックチェーン・Web3</td><td style="text-align: center;">Go</td><td style="text-align: center;">GNU Lesser General Public License v3.0 を採用</td></tr>
    <tr><td style="text-align: center;">11</td><td style="text-align: center;">ohcnetwork/care_fe</td><td style="text-align: center;">90.0266</td><td style="text-align: center;">応用・ソリューション</td><td style="text-align: center;">TypeScript</td><td style="text-align: center;">地域を越えた医療資源の分散管理を支援する公益デジタルプロジェクト</td></tr>
    <tr><td style="text-align: center;">12</td><td style="text-align: center;">community-scripts/ProxmoxVE</td><td style="text-align: center;">89.9397</td><td style="text-align: center;">クラウドインフラ</td><td style="text-align: center;">Shell</td><td style="text-align: center;">Proxmox VE 補助スクリプト（コミュニティ版）</td></tr>
    <tr><td style="text-align: center;">13</td><td style="text-align: center;">browser-use/browser-use</td><td style="text-align: center;">87.7688</td><td style="text-align: center;">AI・フロントエンド</td><td style="text-align: center;">Python</td><td style="text-align: center;">Web サイトを AI エージェントから利用しやすくするツール</td></tr>
    <tr><td style="text-align: center;">14</td><td style="text-align: center;">modular/modular</td><td style="text-align: center;">85.5626</td><td style="text-align: center;">プログラミング言語・開発・AI</td><td style="text-align: center;">Mojo</td><td style="text-align: center;">Mojo プログラミング言語</td></tr>
    <tr><td style="text-align: center;">15</td><td style="text-align: center;">ghostty-org/ghostty</td><td style="text-align: center;">84.8664</td><td style="text-align: center;">OS</td><td style="text-align: center;">Zig</td><td style="text-align: center;">ネイティブ UI と GPU アクセラレーションを採用したクロスプラットフォーム端末</td></tr>
    <tr><td style="text-align: center;">16</td><td style="text-align: center;">pydantic/pydantic-ai</td><td style="text-align: center;">83.3799</td><td style="text-align: center;">AI・プログラミング言語・開発</td><td style="text-align: center;">Python</td><td style="text-align: center;">LLM と Pydantic を組み合わせるエージェントフレームワーク／アダプター</td></tr>
    <tr><td style="text-align: center;">17</td><td style="text-align: center;">iotaledger/iota</td><td style="text-align: center;">80.6274</td><td style="text-align: center;">ブロックチェーン・Web3</td><td style="text-align: center;">Rust</td><td style="text-align: center;">Web3 と現実世界をつなぐ分散型プログラマブル DLT インフラ</td></tr>
    <tr><td style="text-align: center;">18</td><td style="text-align: center;">volcengine/verl</td><td style="text-align: center;">80.1939</td><td style="text-align: center;">AI</td><td style="text-align: center;">Python</td><td style="text-align: center;">VolcEngine の大規模言語モデル強化学習ツール</td></tr>
    <tr><td style="text-align: center;">19</td><td style="text-align: center;">block/goose</td><td style="text-align: center;">79.8506</td><td style="text-align: center;">AI・プログラミング言語・開発</td><td style="text-align: center;">Rust</td><td style="text-align: center;">インストールや実行を行える拡張可能な AI エージェント</td></tr>
    <tr><td style="text-align: center;">20</td><td style="text-align: center;">modrinth/code</td><td style="text-align: center;">79.1998</td><td style="text-align: center;">応用・ソリューション</td><td style="text-align: center;">Rust</td><td style="text-align: center;">Modrinth の運用を支えるコードベース</td></tr>
    <tr><td style="text-align: center;">21</td><td style="text-align: center;">bloxstraplabs/bloxstrap</td><td style="text-align: center;">79.1061</td><td style="text-align: center;">応用・ソリューション</td><td style="text-align: center;">C#</td><td style="text-align: center;">追加機能を備えた Roblox 代替ランチャー</td></tr>
    <tr><td style="text-align: center;">22</td><td style="text-align: center;">apache/gravitino</td><td style="text-align: center;">78.9191</td><td style="text-align: center;">ビッグデータ・データ工学・データベース</td><td style="text-align: center;">Java</td><td style="text-align: center;">高性能な分散メタデータレイク向けオープンデータカタログ</td></tr>
    <tr><td style="text-align: center;">23</td><td style="text-align: center;">Cumulocity-IoT/c8y-docs</td><td style="text-align: center;">77.2667</td><td style="text-align: center;">IoT・エッジコンピューティング</td><td style="text-align: center;">SCSS</td><td style="text-align: center;">Cumulocity IoT のガイドと文書</td></tr>
    <tr><td style="text-align: center;">24</td><td style="text-align: center;">RSSNext/Folo</td><td style="text-align: center;">76.783</td><td style="text-align: center;">フロントエンド・ブロックチェーン・Web3</td><td style="text-align: center;">TypeScript</td><td style="text-align: center;">統合型情報収集ツール</td></tr>
    <tr><td style="text-align: center;">25</td><td style="text-align: center;">AstrBotDevs/AstrBot</td><td style="text-align: center;">76.5032</td><td style="text-align: center;">AI・応用・ソリューション</td><td style="text-align: center;">Python</td><td style="text-align: center;">ワークフローやコード実行に対応するマルチプラットフォーム LLM チャットボット／開発基盤</td></tr>
    <tr><td style="text-align: center;">26</td><td style="text-align: center;">stackblitz-labs/bolt.diy</td><td style="text-align: center;">76.2544</td><td style="text-align: center;">AI・フロントエンド</td><td style="text-align: center;">TypeScript</td><td style="text-align: center;">任意の LLM でフルスタック Web アプリを構築・デプロイ</td></tr>
    <tr><td style="text-align: center;">27</td><td style="text-align: center;">luanti-org/luanti</td><td style="text-align: center;">74.9987</td><td style="text-align: center;">応用・ソリューション</td><td style="text-align: center;">C++</td><td style="text-align: center;">オープンソースのボクセルゲーム制作基盤（旧 Minetest）</td></tr>
    <tr><td style="text-align: center;">28</td><td style="text-align: center;">Saghen/blink.cmp</td><td style="text-align: center;">72.125</td><td style="text-align: center;">プログラミング言語・開発</td><td style="text-align: center;">Lua</td><td style="text-align: center;">Neovim 向け高性能・多機能補完プラグイン</td></tr>
    <tr><td style="text-align: center;">29</td><td style="text-align: center;">modelcontextprotocol/servers</td><td style="text-align: center;">71.1212</td><td style="text-align: center;">AI</td><td style="text-align: center;">JavaScript</td><td style="text-align: center;">Model Context Protocol サーバー</td></tr>
    <tr><td style="text-align: center;">30</td><td style="text-align: center;">huggingface/smolagents</td><td style="text-align: center;">69.7365</td><td style="text-align: center;">AI</td><td style="text-align: center;">Python</td><td style="text-align: center;">Python コードでツールや他のエージェントを操作する軽量エージェントライブラリ</td></tr>
    </tbody>
  </table>
</div>

- AI 関連は 19 件で Top 30 の過半数を占める。
- プログラミング言語・開発関連は 11 件で、Mojo から C++、Python のツールまで幅広い。
- AI、フロントエンド、クラウド、Web3 など複数分野を横断するプロジェクトが増えている。

#### 3.4.2 技術分野分析：AI がイノベーションを主導し、複数分野へ拡大

表 3.12 世界の新興オープンソースプロジェクト Top 30 の技術分野

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;"><strong>技術分野</strong></th><th style="text-align: center;"><strong>件数</strong></th><th style="text-align: center;"><strong>割合</strong></th><th style="text-align: center;"><strong>月平均 OpenRank</strong></th><th style="text-align: center;"><strong>代表プロジェクト</strong></th><th style="text-align: center;"><strong>主な用途</strong></th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">AI 関連（分野横断を含む）</td><td style="text-align: center;">19</td><td style="text-align: center;">63.3%</td><td style="text-align: center;">138.7</td><td style="text-align: center;">CherryHQ/cherry-studio、ggml-org/llama.cpp</td><td style="text-align: center;">LLM 推論、AI コーディングエージェント、マルチモーダル操作</td></tr>
    <tr><td style="text-align: center;">応用・ソリューション</td><td style="text-align: center;">7</td><td style="text-align: center;">23.3%</td><td style="text-align: center;">226.5</td><td style="text-align: center;">DigitalPlatDev/FreeDomain、modrinth/code</td><td style="text-align: center;">ドメインサービス、ゲーム制作基盤、医療管理</td></tr>
    <tr><td style="text-align: center;">プログラミング言語・開発（AI 横断を除く）</td><td style="text-align: center;">2</td><td style="text-align: center;">6.7%</td><td style="text-align: center;">78.8</td><td style="text-align: center;">Saghen/blink.cmp、modular/modular</td><td style="text-align: center;">コード補完、新言語開発</td></tr>
    <tr><td style="text-align: center;">ブロックチェーン・Web3</td><td style="text-align: center;">3</td><td style="text-align: center;">10.0%</td><td style="text-align: center;">80.8</td><td style="text-align: center;">erigontech/erigon、iotaledger/iota</td><td style="text-align: center;">Ethereum ノード、分散台帳インフラ</td></tr>
    <tr><td style="text-align: center;">クラウドインフラ</td><td style="text-align: center;">2</td><td style="text-align: center;">6.7%</td><td style="text-align: center;">150.4</td><td style="text-align: center;">stackblitz/bolt.new、community-scripts/ProxmoxVE</td><td style="text-align: center;">フルスタックアプリのデプロイ、仮想化管理</td></tr>
    <tr><td style="text-align: center;">OS</td><td style="text-align: center;">1</td><td style="text-align: center;">3.3%</td><td style="text-align: center;">84.9</td><td style="text-align: center;">ghostty-org/ghostty</td><td style="text-align: center;">クロスプラットフォーム端末</td></tr>
    <tr><td style="text-align: center;">ビッグデータ・データ工学・データベース</td><td style="text-align: center;">1</td><td style="text-align: center;">3.3%</td><td style="text-align: center;">78.9</td><td style="text-align: center;">apache/gravitino</td><td style="text-align: center;">分散メタデータレイク</td></tr>
    <tr><td style="text-align: center;">IoT・エッジコンピューティング</td><td style="text-align: center;">1</td><td style="text-align: center;">3.3%</td><td style="text-align: center;">77.3</td><td style="text-align: center;">Cumulocity-IoT/c8y-docs</td><td style="text-align: center;">IoT 文書・分析支援</td></tr>
    </tbody>
  </table>
</div>

AI 関連は 6 割超を占め、ggml-org/llama.cpp や stackblitz/bolt.new など、AI を実用化するプロジェクトが先導している。応用・ソリューションは 7 件だが、DigitalPlatDev/FreeDomain によって月平均 OpenRank が高く、軽量で実用的なサービスが短期間で支持を得やすいことを示す。

#### 3.4.3 主要言語分析：TypeScript と Python が主導し、少数言語が用途に特化

表 3.13 世界の新興オープンソースプロジェクト Top 30 の主要言語

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;"><strong>主要言語</strong></th><th style="text-align: center;"><strong>件数</strong></th><th style="text-align: center;"><strong>割合</strong></th><th style="text-align: center;"><strong>月平均 OpenRank</strong></th><th style="text-align: center;"><strong>対応分野</strong></th><th style="text-align: center;"><strong>代表プロジェクト</strong></th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">TypeScript</td><td style="text-align: center;">10</td><td style="text-align: center;">33.3%</td><td style="text-align: center;">156.8</td><td style="text-align: center;">AI、フロントエンド、ブロックチェーン・Web3、応用・ソリューション</td><td style="text-align: center;">CherryHQ/cherry-studio、stackblitz/bolt.new</td></tr>
    <tr><td style="text-align: center;">Python</td><td style="text-align: center;">9</td><td style="text-align: center;">30.0%</td><td style="text-align: center;">105.3</td><td style="text-align: center;">AI、プログラミング言語・開発、応用・ソリューション</td><td style="text-align: center;">Aider-AI/aider、huggingface/smolagents</td></tr>
    <tr><td style="text-align: center;">Rust</td><td style="text-align: center;">4</td><td style="text-align: center;">13.3%</td><td style="text-align: center;">79.9</td><td style="text-align: center;">ブロックチェーン・Web3、応用・ソリューション、AI</td><td style="text-align: center;">iotaledger/iota、block/goose</td></tr>
    <tr><td style="text-align: center;">C++</td><td style="text-align: center;">2</td><td style="text-align: center;">6.7%</td><td style="text-align: center;">157.6</td><td style="text-align: center;">AI、応用・ソリューション</td><td style="text-align: center;">ggml-org/llama.cpp、luanti-org/luanti</td></tr>
    <tr><td style="text-align: center;">Go</td><td style="text-align: center;">1</td><td style="text-align: center;">3.3%</td><td style="text-align: center;">91.0</td><td style="text-align: center;">ブロックチェーン・Web3</td><td style="text-align: center;">erigontech/erigon</td></tr>
    <tr><td style="text-align: center;">Java</td><td style="text-align: center;">1</td><td style="text-align: center;">3.3%</td><td style="text-align: center;">78.9</td><td style="text-align: center;">ビッグデータ・データ工学・データベース</td><td style="text-align: center;">apache/gravitino</td></tr>
    <tr><td style="text-align: center;">Mojo</td><td style="text-align: center;">1</td><td style="text-align: center;">3.3%</td><td style="text-align: center;">85.6</td><td style="text-align: center;">プログラミング言語・開発、AI</td><td style="text-align: center;">modular/modular</td></tr>
    <tr><td style="text-align: center;">Zig</td><td style="text-align: center;">1</td><td style="text-align: center;">3.3%</td><td style="text-align: center;">84.9</td><td style="text-align: center;">OS</td><td style="text-align: center;">ghostty-org/ghostty</td></tr>
    <tr><td style="text-align: center;">Shell</td><td style="text-align: center;">1</td><td style="text-align: center;">3.3%</td><td style="text-align: center;">89.9</td><td style="text-align: center;">クラウドインフラ</td><td style="text-align: center;">community-scripts/ProxmoxVE</td></tr>
    <tr><td style="text-align: center;">SCSS</td><td style="text-align: center;">1</td><td style="text-align: center;">3.3%</td><td style="text-align: center;">77.3</td><td style="text-align: center;">IoT・エッジコンピューティング</td><td style="text-align: center;">Cumulocity-IoT/c8y-docs</td></tr>
    <tr><td style="text-align: center;">Lua</td><td style="text-align: center;">1</td><td style="text-align: center;">3.3%</td><td style="text-align: center;">72.1</td><td style="text-align: center;">プログラミング言語・開発</td><td style="text-align: center;">Saghen/blink.cmp</td></tr>
    <tr><td style="text-align: center;">C#</td><td style="text-align: center;">1</td><td style="text-align: center;">3.3%</td><td style="text-align: center;">79.1</td><td style="text-align: center;">応用・ソリューション</td><td style="text-align: center;">bloxstraplabs/bloxstrap</td></tr>
    <tr><td style="text-align: center;">HTML</td><td style="text-align: center;">1</td><td style="text-align: center;">3.3%</td><td style="text-align: center;">1,219.1</td><td style="text-align: center;">応用・ソリューション</td><td style="text-align: center;">DigitalPlatDev/FreeDomain</td></tr>
    </tbody>
  </table>
</div>

- TypeScript と Python は合計 6 割超で、前者はフロントエンド操作、後者は AI アルゴリズムを中心に利用される。
- Mojo、Zig、Rust などは件数こそ少ないが、AI、端末、ブロックチェーンなど特定用途に適合している。
- ブロックチェーン・Web3 では **75%**が Rust / Go、AI では **84%**が TypeScript / Python を使用する。応用分野では利用者要件に応じて言語が多様化している。

## 四、オープンソース特別分析

### 4.1 大規模モデルエコシステム分析

#### 4.1.1 大規模モデルエコシステムとは

Hugging Face は世界で最も影響力のあるオープンソース大規模モデルプラットフォームの一つであり、中国では ModelScope（魔搭コミュニティ）が同様の役割を持つ。開発者や研究機関はモデルを公開し、説明やライセンスを提示し、ダウンロード、Like、コメントを通じて継続的なフィードバックを得る。本節はコードの共同保守ではなく、公開後のモデルがどう利用・評価され、既存モデルを基に再開発されるかに注目する。

前半は **2022～2025 年の長期変化**として、モデル数、種類、派生関係、ライセンス、協働、中国のモデル・機関の位置を扱う。後半は **2025 年 3 月～2026 年 2 月の月別変化**として、継続利用、注目、重要な月の変化を分析する。

#### 4.1.2 主な発見

- **規模が拡大**：2025 年末時点で Hugging Face は 1,300 万人超のユーザーと 250 万件のモデル、ModelScope は 1,600 万人超のユーザーと 15 万件超のモデルを持つ。
- **成長は一様ではない**：テキスト生成への集中が進み、画像生成、音声認識、マルチモーダルも拡大している。
- **公開から再利用へ**：既存モデルのファインチューニング、適応、量子化が増え、基盤モデルを中心とする再利用・再開発へ重点が移った。
- **ライセンス情報の課題**：再利用経路が増える一方、ライセンス情報の欠落が後続利用の判断を難しくしている。
- **主要モデルがコミュニティ化**：高影響力モデルのリポジトリは、ダウンロードページから、議論と継続更新を行うコミュニティの入口へ変化している。
- **利用と注目は異なる**：ダウンロードは継続利用、Like は特定期間の注目と評価をより強く示す。
- **中国モデルの影響力が上昇**：Qwen、DeepSeek、GLM、Kimi などが Hugging Face の変化を支える主要な存在となった。

#### 4.1.3 2022～2025 年：Hugging Face のモデルエコシステムの変化

**1. モデルと公開者が継続的に増加**

<center><img src="/image/data/figure-4-1-new-models-and-publishers.png" width="700"></center>

<center>図 4.1 2022～2025 年の年間新規モデル数と新規モデル公開者数</center>

<center>出典：Hugging Face プラットフォームのデータを基に作成</center>

> 注：公開時期に基づく。「新規モデル」は当年に初めて公開されたモデル、「新規モデル公開者」は当年に初めてモデルを公開した異なる作者を指す。

年間新規モデルは 2022～2025 年に 10 万件台から **117 万件**へ、新規公開者は 3 万から **20 万超**へ増えた。ModelScope も同時期に拡大し、世界と中国国内の双方で、少数機関による集中公開から、多様な組織・個人が継続的に参加する供給へ移行している。2026 年 1～2 月だけでも **29.5 万件**のモデルと **3.6 万**の公開者が新たに加わった。

<center><img src="/image/data/figure-4-2-monthly-new-models.png" width="700"></center>

<center>図 4.2 月別新規モデル数（2022～2026 年、公開時期ベース）</center>

<center>出典：Hugging Face プラットフォームのデータを基に作成</center>

2022～2023 年は継続して増加し、2024 年後半に再加速、2025 年の大半は高水準を保った。初期の一時的な拡大から、安定した継続成長へ移行している。

**2. アクティブ協働者が増え、コミュニティ基盤が拡大**

<center><img src="/image/data/figure-4-3-hugging-face-active-collaborators-and-model-repos.png" width="700"></center>

<center>図 4.3 Hugging Face のアクティブ協働者とアクティブモデルリポジトリ（2022～2025 年）</center>

<center>出典：Hugging Face プラットフォームのデータを基に作成</center>

> **注：**「アクティブ協働者」は Discussion、PR、コメント、返信、編集、リアクションなどの記録がある利用者、「アクティブモデルリポジトリ」は集計期間中に協働行動があったリポジトリを指す。

2025 年末までに、累計 **168,179 人**のアクティブ協働者と **218,699 件**のアクティブモデルリポジトリが存在した。年間新規協働者は 2022 年の **6,768 人**から 2025 年の **62,805 人**へ増え、2025 年のアクティブリポジトリは **127,139 件**となった。

2024 年のアクティブリポジトリ数は 2023 年から一時的に減少したが、協働イベントは **24.68 万件**から **31.77 万件**へ、協働者は **2.17 万人**から **2.95 万人**へ増加した。リポジトリ当たりのイベント数も **4.37**から **8.04**へ増え、協働が少数の主要リポジトリに集中したと解釈できる。モデル供給とコミュニティ協働が同時に拡大している。

**3. 成長が主要なモデル種類へ集中**

Hugging Face の「モデル種類」はアルゴリズム構造ではなく、主な用途を表す。

- **text-generation（テキスト生成）**：文章やコードを生成する。
- **text-classification（テキスト分類）**：感情や問い合わせ種別などのラベルを付ける。
- **text-to-image（テキスト画像生成）**：文章から画像を生成する。
- **automatic-speech-recognition（音声認識）**：音声を文字へ変換する。
- **reinforcement-learning（強化学習）**：環境との反復的なやり取りと報酬から方策を学習する。
- **token-classification（トークン分類）**：文中の語や部分文字列へ個別にラベルを付ける。
- **image-classification（画像分類）**：画像全体のカテゴリを判定する。
- **feature-extraction（特徴抽出）**：入力を検索、クラスタリング、類似度計算に使うベクトルへ変換する。
- **image-text-to-text（画像・テキストからテキスト）**：画像と質問などを入力し、文章で回答する。
- **fill-mask（マスク補完）**：文中の欠落箇所を予測する。
- **text-to-video（テキスト動画生成）**：文章から動画を生成する。
- **image-to-video（画像動画生成）**：静止画から動画を生成する。
- **image-to-image（画像変換）**：画像を高画質化または別のスタイルへ変換する。
- **text-to-speech（音声合成）**：文章から自然な音声を生成する。
- **any-to-any（任意形式間変換）**：複数形式を入力し、文章、音声、動作指示など複数形式で出力する。
- **question-answering（質問応答）**：文脈や質問から回答を出力する。
- **robotics（ロボティクス）**：視覚、言語指示、ロボット状態から知覚・判断・動作を行う。Hugging Face の LeRobot が代表例である。

<center><img src="/image/data/figure-4-4-hugging-face-model-type-share.png" width="700"></center>

<center>図 4.4 Hugging Face のラベル付きモデルに占める主要種類の割合（Top 10＋その他）</center>

<center>出典：Hugging Face プラットフォームのデータを基に作成</center>

**text-generation** が最大で、**text-classification**、**text-to-image** が続く。上位 10 種類でラベル付きモデルの約 9 割を占める。一方、種類が未記入のモデルは約 **180.2 万件**、全体の約 **68.3%**であり、この分析はラベル付きモデルの主要傾向を示すもので、長尾を含む全体構造ではない。

<center><img src="/image/data/figure-4-5-model-type-new-share-over-time.png" width="700"></center>

<center>図 4.5 主要モデル種類の新規モデルに占める割合（ラベル付きモデルのみ）</center>

<center>出典：Hugging Face プラットフォームのデータを基に作成</center>

**text-generation** は 2022 年の約 15.6%から 2024～2025 年の約 45%～47%へ上昇した。**text-classification** や **token-classification** は存在するものの、新規モデルに占める割合は低下した。

**4. 主要モデル種類マップ：利用されるモデルと評価されるモデル**

ダウンロードを「利用」、Like を「評価」の目安として同じ座標上で比較する。対象は累計ダウンロード **1,000 回以上**または Like **1 件以上**の **267,328 件**で、全モデルの約 **8.8%**である。

<center><img src="/image/data/figure-4-6-core-model-types-downloads-vs-likes.png" width="700"></center>

<center>図 4.6 主要モデル種類：ダウンロードと Like の比較（バブル＝モデル数、色＝割合）</center>

<center>出典：Hugging Face プラットフォームのデータを基に作成</center>

**（1）注目すべき三種類のモデル**

第一は**インフラ型モデル**である。token-classification、image-classification、feature-extraction などは各種システムで頻繁に利用され、ダウンロード数は多いが Like は比較的少ない。話題性より安定した再利用を示している。

第二は**体験駆動型モデル**である。text-to-video、image-to-video、image-to-image、text-to-speech、any-to-any などは出力が直感的で、利用後に Like を付けやすい。

第三は**汎用性と可視性を兼ねる中間層モデル**である。text-generation、automatic-speech-recognition、feature-extraction は安定需要と用途拡張性を持ち、ダウンロードと Like の双方で存在感が大きい。

- **音声**：automatic-speech-recognition は平均累計ダウンロード約 3.1 万、Like 約 17 で、text-to-speech は Like がさらに活発である。
- **クロスモーダル**：any-to-any は対象モデルの 0.3%未満だが、平均累計 Like と Like 密度が特に高い。
- **robotics**：ダウンロードは多くないが Like 密度が高い。[Hugging Face に関する記事](https://aiworld.eu/story/from-the-bottom-to-the-top-robotics-datasets-lead-on-hugging-face)でも、ロボティクスデータセットは急成長するサブコミュニティの一つとされる。
- **質問応答と強化学習**：安定需要はあるが、画像・動画・音声生成より話題性と利用者の反応は弱い。

**5. モデル再利用が一般化し、派生関係が急増**

<center><img src="/image/data/figure-4-7-derivative-relationship-evolution.png" width="700"></center>

<center>図 4.7 派生関係の規模と種類構成の変化（2022～2025 年）</center>

<center>出典：Hugging Face プラットフォームのデータを基に作成</center>

- **finetune**：基盤モデルを特定データで追加学習し、分野や用途へ適応させる。
- **adapter**：基盤モデル全体を変更せず、小規模な学習可能モジュールを追加する。
- **quantized**：パラメーターを低精度化し、保存容量と計算負荷を減らす。
- **merge**：複数モデルのパラメーターや能力を統合する。

初期の finetune 中心から、finetune、adapter、quantized が並行して成長する構造へ変化した。特に 2024～2025 年は adapter と quantized が大きく伸び、軽量な適応とデプロイ最適化が進んだ。merge は小規模ながら継続している。

[Hugging Face の公式報告](https://huggingface.co/blog/huggingface/state-of-os-hf-spring-2026)によると、Alibaba の派生モデル数は Google と Meta の合計を上回り、Qwen 系だけで **11.3 万件超**、Qwen タグ付きリポジトリでは **20 万件超**に達した。

**6. 再利用の増加に対してライセンス情報が不足**

<center><img src="/image/data/figure-4-8-license-status-by-derivative-type.png" width="700"></center>

<center>図 4.8 派生種類別のライセンス情報の状態</center>

<center>出典：Hugging Face プラットフォームのデータを基に作成</center>

quantized と finetune では、子モデルと親モデルのライセンスが一致する割合が **61%**、**55%**である一方、Unknown は **33%**、**30%**だった。adapter と merge では Unknown が **58%**、**68%**に達し、再利用の増加にライセンス情報の開示が追いついていない。

**7. 上位モデルは Discussion を中心にコミュニティ化**

<center><img src="/image/data/figure-4-9-top20-model-collaboration-topics.png" width="700"></center>

<center>図 4.9 2025 年の協働活発度 Top 20 モデルと話題構成（Discussion / PR）</center>

<center>出典：Hugging Face プラットフォームのデータを基に作成</center>

> 注：Collaboration score は、参加者、Discussion、PR、返信、編集、リアクションなどから協働の活発度を測る。

Top 20 の多くは約 200 人、一部は 300 人超の協働者を持つ。Discussion の割合が PR より高く、モデル利用のフィードバック、効果の議論、問題調査、迅速な更新を中心とする運営型の協働が重要になっている。Grok、GLM、Qwen、DeepSeek などが上位に含まれる。

**8. 中国のオープンソースモデルが主要勢力へ**

<center><img src="/image/data/figure-4-11-institution-influence-downloads-vs-likes.png" width="700"></center>

<center>図 4.10 機関別影響力：累計ダウンロード Top 15 と Like Top 15</center>

<center>出典：Hugging Face プラットフォームのデータを基に作成</center>

ダウンロード上位には sentence-transformers、google-bert、openai、FacebookAI など長期利用される基盤モデルの機関が多く、Qwen と BAAI も Top 15 に入った。Like では Qwen が首位、deepseek-ai が上位 3 位、zai-org も上位となった。中国機関は、実際の再利用とコミュニティの注目の双方で存在感を高めている。

[Hugging Face の 2026 年 3 月の公式報告](https://huggingface.co/blog/huggingface/state-of-os-hf-spring-2026)によると、中国は月別・累計ダウンロードで米国を上回り、過去 1 年間の総ダウンロードの **41%**を占めた。Baidu のモデルリポジトリは 2024 年の 0 件から 2025 年の **100 件超**へ増え、ByteDance と Tencent の公開数も **8～9 倍**となった。

#### 4.1.4 2025 年 3 月～2026 年 2 月：ダウンロードと Like が示すもの

**1. 二つの指標を同時に見る理由**

<center><img src="/image/data/figure-4-10-monthly-model-downloads-and-likes-net-growth.png" width="700"></center>

<center>図 4.11 2025 年 3 月～2026 年 2 月の月別ダウンロード・Like 純増</center>

<center>出典：Hugging Face プラットフォームのデータを基に作成</center>

> 注：2026 年 1～2 月が大きいため断軸を使用する。純増は累計値ではなく前月からの増加分である。

ダウンロードは、モデルが製品、スクリプト、ワークフロー、ローカル環境へ継続的に組み込まれているかに近く、実際の再利用規模をよりよく表す。Like は、ある期間にモデルが集中的な評価を得たかに近く、新しいモデルや能力に対するコミュニティの関心をより強く反映する。

具体的には、2025 年 4～5 月に一度大きく増え、7 月に再び上昇した。11 月にはダウンロードと Like が同時に大きく伸び、ダウンロード純増は **42.76 億回**、Like 純増は **58.48 万件**となった。2026 年に入ると月間増加量はさらに拡大し、1 月は **507.07 億回**と **196.17 万件**、2 月は **2,049.69 億回**と **729.62 万件**へ急増した。プラットフォームへの関心は一定速度で高まるのではなく、主要モデルの集中公開、急速な普及、継続的な議論を軸として、段階的なピークを形成している。

[Hugging Face の公式報告](https://huggingface.co/blog/huggingface/state-of-os-hf-spring-2026)でも同様の傾向が示されている。オープンソースモデルは公開後すぐに注目のピークを迎えることが多く、関心が高い期間は平均約 **6 週間**で、その後は明確に減速する。そのため、Like と注目度は新しいモデルの公開や連続更新の際に集中しやすい一方、長期的なダウンロード実績は、モデルが継続的に再利用されているかをよりよく表す。

**2. 上位集中度：利用は集中し、評価は分散**

<center><img src="/image/data/figure-4-12-monthly-top20-concentration-downloads-vs-likes.png" width="700"></center>

<center>図 4.12 2025 年 3 月～2026 年 2 月の月別 Top 20 集中度（ダウンロード / Like）</center>

<center>出典：Hugging Face プラットフォームのデータを基に作成</center>

> 注：ここでいう **Top 20 集中度**とは、各月の全モデルにおけるダウンロードまたは Like の純増のうち、上位 20 モデルが占める割合を指す。割合が高いほど少数の上位モデルへ集中し、低いほど中位層やロングテールへ広く分散している。

月別に見ると、**ダウンロードの上位集中度は Like より明確に高い**。2025 年 3 月～2026 年 2 月のダウンロード Top 20 は、月間純増の **30%～49%**を占める。[Hugging Face の公式報告](https://huggingface.co/blog/huggingface/state-of-os-hf-spring-2026)でも、約半数のモデルの累計ダウンロードは **200 回未満**で、ダウンロード数上位 **200 件**が全体の **49.6%**を占めるとされる。プラットフォーム上の利用はもともと上位へ集中する傾向が強く、月別 Top 20 集中度の変化は、その長期的な構造の強弱を表している。

これに対し、Like Top 20 は **12%～24%**にとどまり、コミュニティの注目と評価はより多様なモデルへ分散している。

ダウンロード集中度は 2025 年 3～6 月に比較的高く、7 月以降は全体として低下し、2025 年 11 月と 2026 年 2 月には **30.7%**となった。上位モデルが利用増加の重要な源である一方、実際に利用されるモデルが増え、ダウンロードの純増がより広いモデル群へ分散しつつある。Like の集中度は一貫して低く、2025 年 7 月には **12.1%**まで低下した。利用者が評価を示す対象は最も人気のある少数モデルに限られず、さまざまな方向の「新しい能力」や「新しい体験」へ広がっている。

全体として、**継続的に利用される構造と、集中的に好まれる構造は同じではない**。ダウンロードは上位モデルに集中しやすく、プラットフォームの再利用構造を表す。Like はより多くのモデルへ広がり、コミュニティの関心と評価の分散を表す。長期的な再利用の基盤となるモデルが、その月に最も注目されたモデルとは限らず、イノベーションの方向や新しい体験は Like に先に表れやすい。

**3. 常時上位モデル：長期トラフィックを支える中間層能力**

月別ダウンロード Top 20 に長期間、繰り返し入るモデルを見ると、プラットフォーム上で長期的な再利用を実際に支えているモデルを把握できる。表 4.1 が示すように、継続的なトラフィックを支えるのは、その時々で最も話題になる対話モデルではなく、テキスト埋め込み、古典的なエンコーダー、画像 backbone、安全性検出など、繰り返し利用できる**中間層の能力**である。

> 注：「**登場月数**」は、2025 年 3 月～2026 年 2 月の月別 Top 20 に入った月数を指す。「**Top 20 登場月のダウンロード純増合計**」および「**Top 20 登場月の Like 純増合計**」は、そのモデルが Top 20 に入った月に寄与した純増の合計であり、プラットフォーム上の過去からの累計値ではない。

表 4.1 ダウンロード Top 20 への登場月数が多いモデル（Top 10）

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;">モデル</th><th style="text-align: center;">登場月数</th><th style="text-align: center;">Top 20 登場月のダウンロード純増合計（回）</th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">sentence-transformers/all-MiniLM-L6-v2</td><td style="text-align: center;">12</td><td style="text-align: center;">610,686,941</td></tr>
    <tr><td style="text-align: center;">sentence-transformers/all-mpnet-base-v2</td><td style="text-align: center;">12</td><td style="text-align: center;">118,761,995</td></tr>
    <tr><td style="text-align: center;">timm/mobilenetv3_small_100.lamb_in1k</td><td style="text-align: center;">12</td><td style="text-align: center;">96,084,260</td></tr>
    <tr><td style="text-align: center;">Falconsai/nsfw_image_detection</td><td style="text-align: center;">12</td><td style="text-align: center;">28,595,149,095</td></tr>
    <tr><td style="text-align: center;">google-bert/bert-base-uncased</td><td style="text-align: center;">12</td><td style="text-align: center;">284,177,818</td></tr>
    <tr><td style="text-align: center;">dima806/fairface_age_image_detection</td><td style="text-align: center;">12</td><td style="text-align: center;">120,792,157</td></tr>
    <tr><td style="text-align: center;">openai/clip-vit-large-patch14</td><td style="text-align: center;">9</td><td style="text-align: center;">80,970,480</td></tr>
    <tr><td style="text-align: center;">facebook/opt-125m</td><td style="text-align: center;">9</td><td style="text-align: center;">40,768,170</td></tr>
    <tr><td style="text-align: center;">openai/clip-vit-base-patch32</td><td style="text-align: center;">8</td><td style="text-align: center;">75,817,891</td></tr>
    <tr><td style="text-align: center;">FacebookAI/roberta-large</td><td style="text-align: center;">8</td><td style="text-align: center;">26,865,275</td></tr>
    </tbody>
  </table>
</div>

`sentence-transformers/all-MiniLM-L6-v2`、`sentence-transformers/all-mpnet-base-v2`、`google-bert/bert-base-uncased`、`timm/mobilenetv3_small_100.lamb_in1k` などは、直近 1 年間に繰り返し、あるいは継続して月別ダウンロード Top 20 に入り、一部は **12 カ月**連続で選出された。安定したダウンロード需要の多くは、検索、分類、認識、コンテンツ審査、ワークフローへ組み込まれる基盤的なコンポーネントから生じている。最も注目されるとは限らないが、長期的な再利用価値が高い。

ダウンロードの常時上位モデルに対し、Like の常時上位モデルは、継続的にコミュニティの注目と評価を得るモデルを表す。表 4.2 のとおり、画像生成、推論強化、音声対話など、利用体験への反応が生まれやすい分野が多い。

表 4.2 Like Top 20 への登場月数が多いモデル（Top 10）

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;">モデル</th><th style="text-align: center;">登場月数</th><th style="text-align: center;">Top 20 登場月の Like 純増合計（件）</th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">black-forest-labs/FLUX.1-dev</td><td style="text-align: center;">6</td><td style="text-align: center;">1,683</td></tr>
    <tr><td style="text-align: center;">Phr00t/Qwen-Image-Edit-Rapid-AIO</td><td style="text-align: center;">4</td><td style="text-align: center;">1,481</td></tr>
    <tr><td style="text-align: center;">hexgrad/Kokoro-82M</td><td style="text-align: center;">4</td><td style="text-align: center;">888</td></tr>
    <tr><td style="text-align: center;">Tongyi-MAI/Z-Image-Turbo</td><td style="text-align: center;">3</td><td style="text-align: center;">3,231</td></tr>
    <tr><td style="text-align: center;">deepseek-ai/DeepSeek-R1-0528</td><td style="text-align: center;">3</td><td style="text-align: center;">1,853</td></tr>
    <tr><td style="text-align: center;">google/gemma-3n-E4B-it-litert-preview</td><td style="text-align: center;">3</td><td style="text-align: center;">1,310</td></tr>
    <tr><td style="text-align: center;">ResembleAI/chatterbox</td><td style="text-align: center;">3</td><td style="text-align: center;">882</td></tr>
    <tr><td style="text-align: center;">lodestones/Chroma</td><td style="text-align: center;">3</td><td style="text-align: center;">836</td></tr>
    <tr><td style="text-align: center;">deepseek-ai/DeepSeek-R1</td><td style="text-align: center;">3</td><td style="text-align: center;">722</td></tr>
    <tr><td style="text-align: center;">deepseek-ai/DeepSeek-R1-0528-Qwen3-8B</td><td style="text-align: center;">3</td><td style="text-align: center;">614</td></tr>
    </tbody>
  </table>
</div>

`FLUX.1-dev`、`Qwen-Image-Edit-Rapid-AIO`、`Kokoro-82M`、`DeepSeek-R1` などは、特定の月に明確な評価のピークを形成した。ただし、継続して上位に入った月数は、ダウンロードの常時上位モデルより全体として少ない。Like は、少数の基盤的能力に長期間支えられるダウンロードとは異なり、その時々の話題を軸として集中的な反応を得やすい。

全体として、ダウンロードランキングは「どのモデルが継続的に使われているか」、Like ランキングは「どのモデルが継続的に目に留まり、議論され、評価されているか」を示す。前者はより安定し、基盤的な能力を反映する。後者は新しい体験や能力によって動きやすい。

#### 4.1.5 まとめと考察

2022～2025 年、Hugging Face ではモデル数とモデル公開者数が同時に増加した。プラットフォームは、少数の主要チームが集中的にモデルを公開するホスティング場所から、多様な個人・組織が継続的に参加する公開・配布・再利用プラットフォームへ変化した。

規模の拡大と同時に、モデルの構成は分散し続けたのではなく、少数の主要な種類へ徐々に集中した。テキスト生成、画像生成、音声認識など、生成、多モーダル、コンテンツ制作に関係する分野が、より明確な成長軸となっている。単にモデル数が増えただけでなく、プラットフォームの主要な能力の方向が明確になりつつある。

モデルエコシステムの発展は、「モデルを一つ公開する」ことだけにとどまらない。派生関係の増加、ライセンス情報の不足、上位モデルに見られるコミュニティ運営は、プラットフォームがモデルを継続的に開発し、フィードバックを得て、再利用するエコシステムへ進んだことを示す。

2025 年 3 月～2026 年 2 月の月別データでは、ダウンロードと Like が異なるが相互補完的なシグナルとなる。ダウンロードはモデルの継続的な組み込みと反復利用、Like は一定期間における集中的な注目と評価に近い。いくつかの重要な月に生じた大きな変動は、主要モデルの集中公開、急速な普及、継続的な議論を軸として、段階的なピークが生じることを示している。

機関、モデル、重要な月を総合すると、中国のモデルは単なる活発な参加者ではなく、機関別ランキング、協働活発度ランキング、重要月の代表モデルに入り、現在の Hugging Face エコシステムを変化させる主要な推進力の一つとなっている。

### 4.2 Open Source Promotion Plan（OSPP、開源之夏）年次分析

#### 4.2.1 背景と全体分析

[Open Source Promotion Plan（OSPP、開源之夏）](https://summer-ospp.ac.cn/)は、中国科学院ソフトウェア研究所が開始した「オープンソースソフトウェア・サプライチェーン活性化計画」の夏季プログラムである。大学生によるオープンソースソフトウェアの開発・保守への参加を促し、優れたコミュニティの発展を支援する。2020～2025 年に 6 回開催された。

OSPP のデータによると、2025 年は **565 件**の課題が公開され、学生が採択された課題は **517 件**、完了した課題は **436 件**、完了率は **77%**だった。公開数は 2024 年とほぼ同じだが、選考の厳格化により採択・完了数はやや減少し、参加大学数も減少した。

表 4.3 OSPP 2025 年の全体状況

<div style="display: flex; justify-content: center; width: 100%; overflow-x: auto;">
  <table style="display: table; margin: 0 auto; text-align: center;">
    <thead>
    <tr><th style="text-align: center;"><strong>課題総数</strong></th><th style="text-align: center;"><strong>採択課題数</strong></th><th style="text-align: center;"><strong>完了課題数</strong></th><th style="text-align: center;"><strong>完了率（%）</strong></th><th style="text-align: center;"><strong>大学数</strong></th></tr>
    </thead>
    <tbody>
    <tr><td style="text-align: center;">565(+3)</td><td style="text-align: center;">517(-2)</td><td style="text-align: center;">436(-19)</td><td style="text-align: center;">81(-4)</td><td style="text-align: center;">165(-21)</td></tr>
    </tbody>
  </table>
</div>

完了課題の大半は GitHub（307 件）、Gitee（86 件）、AtomGit（30 件）などに置かれている。OS カーネル関連の一部コミュニティは独自の Git リポジトリを使用した。AtomGit の利用が急増し、Gitee の件数が減少している。

<center><img src="/image/data/figure-4-13-completed-project-platform-distribution.png" width="700"></center>

<center>図 4.13 完了課題が使用したプラットフォームの分布</center>

<center>出典：OSPP コミュニティのデータを基に作成</center>

完了した **436 件**は **165 大学**の学生が担当し、University of Electronic Science and Technology of China が **23 件**で首位となった。

<center><img src="/image/data/figure-4-14-completed-project-university-distribution.png" width="700"></center>

<center>図 4.14 完了課題を担当した学生の所属大学分布</center>

<center>出典：OSPP コミュニティのデータを基に作成</center>

#### 4.2.2 年間貢献分布

完了課題数だけでなく、各大学の学生がコミュニティでどの程度貢献し、プロジェクトへ協働して参加したかを詳細に分析した。これは、学生が特定の課題を完了したかどうかだけでなく、全過程における参加の深さを把握するためである。

> _注：OpenDigger の基礎データの制約により、以下は GitHub と Gitee のデータのみを対象とする。_

2025 年の貢献度データとコミュニティ OpenRank を用いて、大学別の総貢献度 Top 20 を算出した。

<center><img src="/image/data/figure-4-15-ospp-university-contribution-ranking.png" width="700"></center>

<center>図 4.15 OSPP 2025 年大学別貢献度ランキング</center>

<center>出典：OSPP コミュニティと OpenDigger のデータを基に作成</center>

総貢献度と学生一人当たりの OpenRank 貢献度を併せて見ると、University of Electronic Science and Technology of China は学生数と貢献の深さの双方で伸び、2025 年の首位となった。Top 20 のうち 18 大学は前年も OSPP に参加していた。

学生の貢献状況をさらに見るため、OpenRank 貢献度による学生貢献者 Top 20 も算出した。

<center><img src="/image/data/figure-4-16-ospp-student-contribution-ranking.png" width="700"></center>

<center>図 4.16 OSPP 2025 年学生別貢献度ランキング</center>

<center>出典：OSPP コミュニティと OpenDigger のデータを基に作成</center>

2025 年は、過去のように一部の学生だけが極端に高い貢献度を示すのではなく、多くの学生が新規参加者として比較的安定した貢献水準を示した。

#### 4.2.3 全体での貢献分布

OSPP は多くの優秀な大学生が在学中からオープンソースコミュニティへ深く参加する機会となっている。これらの学生が他のコミュニティにも参加しているか、またオープンソース全体でどの程度貢献しているかを確認するため、OSPP 以外を含む全体での貢献度と主要な貢献先も集計した。

<center><img src="/image/data/figure-4-17-student-global-contribution-ranking.png" width="700"></center>

<center>図 4.17 学生のオープンソース全体での貢献度ランキング</center>

<center>出典：OSPP コミュニティと OpenDigger のデータを基に作成</center>

多くの学生が OSPP の対象コミュニティに加え、他のオープンソースコミュニティにも広く貢献している。
