---
title: User Scripts, Chrome extensions
layout: template
filename: scripts
---

## 目次

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [便利なユーザスクリプト、拡張機能の紹介記事](#%E4%BE%BF%E5%88%A9%E3%81%AA%E3%83%A6%E3%83%BC%E3%82%B6%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%97%E3%83%88%E6%8B%A1%E5%BC%B5%E6%A9%9F%E8%83%BD%E3%81%AE%E7%B4%B9%E4%BB%8B%E8%A8%98%E4%BA%8B)
- [ユーザスクリプト](#%E3%83%A6%E3%83%BC%E3%82%B6%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%97%E3%83%88)
  - [レーティング、パフォーマンスなどを表示する](#%E3%83%AC%E3%83%BC%E3%83%86%E3%82%A3%E3%83%B3%E3%82%B0%E3%83%91%E3%83%95%E3%82%A9%E3%83%BC%E3%83%9E%E3%83%B3%E3%82%B9%E3%81%AA%E3%81%A9%E3%82%92%E8%A1%A8%E7%A4%BA%E3%81%99%E3%82%8B)
  - [自動的に通知する](#%E8%87%AA%E5%8B%95%E7%9A%84%E3%81%AB%E9%80%9A%E7%9F%A5%E3%81%99%E3%82%8B)
  - [ショートカットによる効率化](#%E3%82%B7%E3%83%A7%E3%83%BC%E3%83%88%E3%82%AB%E3%83%83%E3%83%88%E3%81%AB%E3%82%88%E3%82%8B%E5%8A%B9%E7%8E%87%E5%8C%96)
  - [UIを見やすく色付けする、表示を簡略化する](#ui%E3%82%92%E8%A6%8B%E3%82%84%E3%81%99%E3%81%8F%E8%89%B2%E4%BB%98%E3%81%91%E3%81%99%E3%82%8B%E8%A1%A8%E7%A4%BA%E3%82%92%E7%B0%A1%E7%95%A5%E5%8C%96%E3%81%99%E3%82%8B)
    - [AtCoder](#atcoder)
    - [非公式サービス、ツール、外部サービスなど](#%E9%9D%9E%E5%85%AC%E5%BC%8F%E3%82%B5%E3%83%BC%E3%83%93%E3%82%B9%E3%83%84%E3%83%BC%E3%83%AB%E5%A4%96%E9%83%A8%E3%82%B5%E3%83%BC%E3%83%93%E3%82%B9%E3%81%AA%E3%81%A9)
  - [便利な機能を手軽に実行できるボタン、リンクなどを設置する](#%E4%BE%BF%E5%88%A9%E3%81%AA%E6%A9%9F%E8%83%BD%E3%82%92%E6%89%8B%E8%BB%BD%E3%81%AB%E5%AE%9F%E8%A1%8C%E3%81%A7%E3%81%8D%E3%82%8B%E3%83%9C%E3%82%BF%E3%83%B3%E3%83%AA%E3%83%B3%E3%82%AF%E3%81%AA%E3%81%A9%E3%82%92%E8%A8%AD%E7%BD%AE%E3%81%99%E3%82%8B)
- [Google Chromeの拡張機能](#google-chrome%E3%81%AE%E6%8B%A1%E5%BC%B5%E6%A9%9F%E8%83%BD)
  - [サンプルケースの取得](#%E3%82%B5%E3%83%B3%E3%83%97%E3%83%AB%E3%82%B1%E3%83%BC%E3%82%B9%E3%81%AE%E5%8F%96%E5%BE%97)
  - [公式でサポートされている以外言語で問題を解く](#%E5%85%AC%E5%BC%8F%E3%81%A7%E3%82%B5%E3%83%9D%E3%83%BC%E3%83%88%E3%81%95%E3%82%8C%E3%81%A6%E3%81%84%E3%82%8B%E4%BB%A5%E5%A4%96%E8%A8%80%E8%AA%9E%E3%81%A7%E5%95%8F%E9%A1%8C%E3%82%92%E8%A7%A3%E3%81%8F)
  - [レーティング、パフォーマンスなどを表示する](#%E3%83%AC%E3%83%BC%E3%83%86%E3%82%A3%E3%83%B3%E3%82%B0%E3%83%91%E3%83%95%E3%82%A9%E3%83%BC%E3%83%9E%E3%83%B3%E3%82%B9%E3%81%AA%E3%81%A9%E3%82%92%E8%A1%A8%E7%A4%BA%E3%81%99%E3%82%8B-1)
  - [UIを見やすく色付けする、表示を簡略化する](#ui%E3%82%92%E8%A6%8B%E3%82%84%E3%81%99%E3%81%8F%E8%89%B2%E4%BB%98%E3%81%91%E3%81%99%E3%82%8B%E8%A1%A8%E7%A4%BA%E3%82%92%E7%B0%A1%E7%95%A5%E5%8C%96%E3%81%99%E3%82%8B-1)
  - [便利な機能を手軽に実行できるボタン、リンクなどを設置する](#%E4%BE%BF%E5%88%A9%E3%81%AA%E6%A9%9F%E8%83%BD%E3%82%92%E6%89%8B%E8%BB%BD%E3%81%AB%E5%AE%9F%E8%A1%8C%E3%81%A7%E3%81%8D%E3%82%8B%E3%83%9C%E3%82%BF%E3%83%B3%E3%83%AA%E3%83%B3%E3%82%AF%E3%81%AA%E3%81%A9%E3%82%92%E8%A8%AD%E7%BD%AE%E3%81%99%E3%82%8B-1)
    - [AtCoder](#atcoder-1)
    - [非公式サービス、ツール、外部サービスなど](#%E9%9D%9E%E5%85%AC%E5%BC%8F%E3%82%B5%E3%83%BC%E3%83%93%E3%82%B9%E3%83%84%E3%83%BC%E3%83%AB%E5%A4%96%E9%83%A8%E3%82%B5%E3%83%BC%E3%83%93%E3%82%B9%E3%81%AA%E3%81%A9-1)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## 便利なユーザスクリプト、拡張機能の紹介記事

- [AtCoderを120%楽しむために便利な拡張機能](https://dailylife.dev/posts/79#body) - 記事の作成者が便利だと感じたユーザスクリプトや拡張機能が紹介されている記事。初めて使う方にもおすすめ。

## ユーザスクリプト

主に[AtCoder](https://atcoder.jp/)のWebページにある機能を拡張することができます。

ユーザスクリプトを利用するときは、スクリプトマネージャと呼ばれるツールを導入する必要があります。[こちら](https://greasyfork.org/ja)を参照してください。

### レーティング、パフォーマンスなどを表示する

- [ac-predictor](https://greasyfork.org/ja/scripts/369954-ac-predictor) - コンテスト開催中に推定パフォーマンスとレーティングの推移を表示する。[Webページ版](https://ac-predictor.com/)もある。使用されている技術に興味がある方は、作者による[解説記事(2020年12月時点)](https://qiita.com/keymoon/items/e83259f882f26c8f10a1)を参照されたい。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_predictor.png" alt="ac predictor">
  </div>

- [ac-predictor-minimal](https://greasyfork.org/ja/scripts/386999-ac-predictor-minimal) - [ac-predictor](https://greasyfork.org/ja/scripts/369954-ac-predictor)の機能限定版。スクリプトの透明性を確保する観点から、パフォーマンスを表示するのは「順位表」ページに限定される。
- [ac-writers script](https://greasyfork.org/ja/scripts/369965-ac-writers-script) - ユーザの「コンテスト成績表」ページにコンテストのWriterを表示する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/ac_writers_script.png" alt="ac writers script">
  </div>

- [AtCoderColorStandings](https://greasyfork.org/ja/scripts/423713-atcodercolorstandings) - 「順位表」ページと「バーチャル順位表」ページで、コンテスト参加者のレーティング別正解率を表示する。注: コンテスト中にSNSでの言及や投稿は避ける。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_color_standings.png" alt="atcoder color standings">
  </div>

- [AtcoderDevotionGraph](https://greasyfork.org/ja/scripts/416588-atcoderdevotiongraph) - 「ユーザ」ページのレーティンググラフに、ACした問題の総得点の推移を上書き表示する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_devotion_graph.png" alt="atcoder devotion graph">
  </div>

- [AtCoder Difficulty Display](https://greasyfork.org/ja/scripts/397185-atcoder-difficulty-display) - AtCoderの「問題」のページに[AtCoder Problems](https://kenkoooo.com/atcoder/)の難易度を表示する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_difficulty_display.png" alt="atcoder difficulty display">
  </div>

- [AtCoder Rating Cumlative Distribution](https://greasyfork.org/ja/scripts/419055-atcoder-rating-cumlative-distribution) - 「ユーザ」ページにあるRating分布の累積人数および累積パーセントを表示する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_rating_cumlative_distribution.png" alt="atcoder rating cumlative distribution">
  </div>

- [AtCoderRecentGraph](https://greasyfork.org/ja/scripts/418562-atcoderrecentgraph) - 「ユーザ」ページにあるレーティンググラフのうち、最近（注: 詳細は要確認）の推移を表示する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_recent_graph.png" alt="atcoder recent graph">
  </div>

- [AtCoderStandingsAnalysis](https://greasyfork.org/ja/scripts/398439-atcoderstandingsanalysis) - 「順位表」ページから、自分の得点・正解者数 / 提出者数・正解率・平均ペナルティ数・ペナルティ率・内部レートの分布を集計する。注: コンテスト中にSNSでの言及や投稿は避ける。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_standings_analysis.png" alt="atcoder standings analysis">
  </div>

- [atcoder-standings-difficulty-analyzer](https://greasyfork.org/ja/scripts/419541-atcoder-standings-difficulty-analyzer) - 「順位表」ページに、問題別の推定難易度の推移・ACした人数の推移などを表示する。注: コンテスト中にSNSでの言及や投稿は避ける。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_standings_difficulty_analyzer.png" alt="atcoder standings difficulty analyzer">
  </div>

- [atcoder-standings-lang](https://greasyfork.org/ja/scripts/415894-atcoder-standings-lang) - 「順位表」ページおよび「バーチャル順位表」ページで、ユーザ名の横にAC数の多い言語を表示する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder-standings-lang.png" alt="atcoder standings lang">
  </div>

- [atcoder-submission-wo-ikki-ni-miiru](https://greasyfork.org/ja/scripts/403062-atcoder-submission-wo-ikki-ni-miiru) - 「提出結果」ページにソースコードを表示する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_submission_wo_ikki_ni_miiru.png" alt="atcoder submission wo ikki ni miiru">
  </div>

### 自動的に通知する

- [atcoder-bell](https://greasyfork.org/ja/scripts/377923-atcoder-bell) - ジャッジシステムでの正誤判定が終了すると、ベルが鳴る。
- [AtcoderColorNEWS](https://greasyfork.org/ja/scripts/387896-atcodercolornews) - お気に入りに登録した人の色の変化を通知する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_color_news.png" alt="atcoder color news">
  </div>

- [AtCoderResultNotifier](https://greasyfork.org/ja/scripts/371225-atcoderresultnotifier) - 提出結果を通知する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_result_notifier.gif" alt="atcoder result notifier">
  </div>

### ショートカットによる効率化

- [Add Shortest Tab](https://greasyfork.org/ja/scripts/391692-add-shortest-tab) - 開いている問題について、コード長に並べた提出ページのタブを追加する。コンテスト中の利用は非推奨。

  <div align="center">
    <img loading = "lazy" src="images/userscript/add_shortest_tab.jpeg" alt="add shortest tab">
  </div>

- [add-typical90-link](https://greasyfork.org/ja/scripts/427326-add-typical90-link) - 「[競プロ典型90問](https://atcoder.jp/contests/typical90)」に、「解説リンク」タブを追加する。このタブから[GitHub](https://github.com/E869120/kyopro_educational_90/tree/main/editorial)で公開されている解説に移動できる。

  <div align="center">
    <img loading = "lazy" src="images/userscript/add_typical90_link.png" alt="add typical90 link">
  </div>

- [atcoder_all_open](https://greasyfork.org/ja/scripts/387471-atcoder-all-open) - 「全ての問題をワンクリックで開く」タブを追加する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_all_open.png" alt="atcoder all open">
  </div>

- [AtCoder_CustomTest_Run_Shortcut](https://greasyfork.org/ja/scripts/418633-atcoder-customtest-run-shortcut) - 「コードテスト」ページで、Ctrl+Enterを押すと、標準入力の値を使用してソースコードを実行する。注: ショートカットを実行する前に、事前にソースコードと標準入力に入力を済ませておく必要がある。

- [AtCoderDevotionScript](https://greasyfork.org/en/scripts/415819-atcoderdevotionscript) - 「問題」ページで、Ctrl + Qを押すと、[atcoder-cli](https://github.com/Tatamo/atcoder-cli)の利用に必要なコンテストIDをクリップボードに書き込むことができる。使い方の詳細は、作者の[紹介記事](https://iiiimmmmo.hatenablog.com/entry/2020/11/15/170008)を参照されたい。注: macOSユーザは、ショートカットの干渉があるため、設定の変更が必要。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_devotion_script.png" alt="atcoder devotion script">
  </div>

- [AtCoder dos2unix UserScript](https://greasyfork.org/ja/scripts/372122-atcoder-dos2unix-userscript) - 改行コードをCRLFからLFに変換して、コードを提出する。

- [AtCoder Editorial New Tab](https://greasyfork.org/ja/scripts/424207-atcoder-editorial-new-tab) - 「問題」ページにある「解説」ボタンを押すと、該当する解説を新しいタブで開くことができる。

- [AtCoder Jump to Submissions from Standings](https://greasyfork.org/ja/scripts/397528-atcoder-jump-to-submissions-from-standings) - 「順位表」ページの得点をダブルクリックすると、該当するコンテスタントの実装を見ることができる。[Codeforces](https://codeforces.com/)の仕様を参考にしている。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_jump_to_submissions_from_standings.gif" alt="atcoder jump to submissions from standings">
  </div>

- [AtCoder Easy Test](https://greasyfork.org/ja/scripts/415946-atcoder-easy-test) - 「問題」ページで、入出力サンプルを使って素早くテストを実行できる。また、自分で作成したテストケースも実行できる。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_easy_test.png" alt="atcoder easy test">
  </div>

- [atcoder-keyboard-shortcuts](https://greasyfork.org/ja/scripts/397575-atcoder-keyboard-shortcuts) - Shift+[1-5]で、「問題」ページにあるサンプルの入力をクリップボードにコピーする。
- [AtCoderLinkCompletionForJOI](https://greasyfork.org/ja/scripts/382313-atcoderlinkcompletionforjoi) - JOIの問題ページにPDFへのリンクを追加する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_link_completion_for_joi.png" alt="atcoder link completion for joi">
  </div>

- [AtCoder_submit_keyboard_shortcut](https://greasyfork.org/ja/scripts/378760-atcoder-submit-keyboard-shortcut) - 問題の提出が、Ctrl+Enterでできる。
- [AtCoderSubmitSearchSettings](https://greasyfork.org/ja/scripts/390424-atcodersubmitsearchsettings) - 「すべての提出」ページで、古いバージョンで提出されたコードを検索できる。検索のデフォルト設定も指定できる。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_submit_search_settings.png" alt="atcoder submit search settings">
  </div>

- [AtCoderTags_Helper](https://greasyfork.org/ja/scripts/393121-atcodertags-helper) - 「問題」ページから[AtCoderTags](https://atcoder-tags.herokuapp.com/)に投票できる。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcodertags_helper.png" alt="atcodertags helper">
  </div>

### UIを見やすく色付けする、表示を簡略化する

#### AtCoder

- [ac-clar-shaper](https://greasyfork.org/ja/scripts/388211-ac-clar-shaper) - Clarから非本質な情報（アカウント名・全体公開の有無・投稿/更新日時）を消し、問題順にソートする。

  <div align="center">
    <img loading = "lazy" src="images/userscript/ac_clar_shaper.png" alt="ac clar shaper">
  </div>

- [ac-search-old-languages](https://greasyfork.org/ja/scripts/405745-ac-search-old-languages) - 「提出結果」ページで、judge-update-202004以前の言語による提出コードを検索できるようにする。

  <div align="center">
    <img loading = "lazy" src="images/userscript/ac_search_old_languages.png" alt="ac search old languages">
  </div>

- [AtCoder Anonymizer](https://greasyfork.org/ja/scripts/413425-atcoder-anonymizer) - 自分のIDを「Anonymous」で置き換える。スクリプト作成者による注: プロフィールページのURLやTwitter IDなどは変更されない。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_anonymizer.png" alt="atcoder anonymizer">
  </div>

- [AtCoderBackGroundColorizer](https://greasyfork.org/ja/scripts/377844-atcoderbackgroundcolorizer) - 各ページの背景を任意の色に変更する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_background_colorizer.png" alt="atcoder background colorizer">
  </div>

- [AtCoder Better Highlighter](https://greasyfork.org/ja/scripts/412865-atcoder-better-highlighter) - 「提出結果」ページのコードをハイライトして見やすくする。デフォルトで10種類以上の言語をサポートしており、対応言語の拡張や配色の変更も可能。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_better_highlighter.png" alt="atcoder background colorizer">
  </div>

- [AtCoderColouringDifference](https://greasyfork.org/ja/scripts/371703-atcodercolouringdifference) - ユーザの「コンテスト成績表」ページで"差分"の部分を色づけする。レポジトリ作成者注: スクリプトの実行対象URLがベータ版のため、修正が必要。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_colouring_difference.png" alt="atcoder colouring difference">
  </div>

- [AtCoder Custom Default Submissions](https://greasyfork.org/ja/scripts/393705-atcoder-custom-default-submissions) - 「すべての提出」ページにおける絞り込み、並び替え設定のデフォルト値を設定できる。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_custom_default_submissions.jpg" alt="atcoder custom default submissions">
  </div>

- [AtCoderDarkTheme](https://greasyfork.org/ja/scripts/388076-atcoderdarktheme) - ダークテーマに変更する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_dark_theme.png" alt="atcoder dark theme">
  </div>

- [AtCoder Difficulty Colorizer for Typical 90](https://greasyfork.org/ja/scripts/425463-atcoder-difficulty-colorizer-for-typical-90) - 「[競プロ典型90問](https://atcoder.jp/contests/typical90)」の問題名を、難易度に応じた色に変更する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_difficulty_colorizer_for_typical_90.png" alt="atcoder difficulty colorizer for typical 90">
  </div>

- [AtCoder Heuristic Rating coloring](https://greasyfork.org/ja/scripts/427070-atcoder-heuristic-rating-coloring) - [AtCoder Heuristic Contest](https://atcoder.jp/contests/archive?ratedType=0&category=1200&keyword=AtCoder+Heuristic+Contest)の「順位表」ページで、ユーザ名を同コンテストのレーティングに応じて色付けする。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_heuristic_rating_coloring.png" alt="atcoder heuristic rating coloring">
  </div>

- [AtCoder-ngtkanaResult](https://greasyfork.org/ja/scripts/416384-atcoder-ngtkanaresult) - 「提出結果」ページの「結果」を[ngtkana](https://atcoder.jp/users/ngtkana)さんの言葉に置き換える。作成者注: 不正解の詳細はマウスオーバーで表示される。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_ngtkanaresult.png" alt="atcoder ngtkanaresult">
  </div>

- [AtCoderPerformanceColorizer](https://greasyfork.org/ja/scripts/371693-atcoderperformancecolorizer) - ユーザの「コンテスト成績表」のパフォーマンス値、レーティング値に色付けする。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_performance_colorizer.png" alt="atcoder performance colorizer">
  </div>

- [AtCoder Print Task Copy](https://greasyfork.org/ja/scripts/394999-atcoder-print-task-copy) - 「問題」ページにある「印刷用問題文」にCopyボタンを追加する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_print_task_copy.png" alt="atcoder print task copy">
  </div>

- [AtCoderScoreHider](https://greasyfork.org/ja/scripts/371898-atcoderscorehider) - 「提出」ページなどの配点を隠す。日本語版のみ対応。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_score_hider.png" alt="atcoder score hider">
  </div>

- [AtCoder Submission Status](https://greasyfork.org/ja/scripts/383817-atcoder-submission-status) - 提出した解答について、テストケースの結果(AC、WA、…)が一目でわかるように表示する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_submission_status.png" alt="atcoder submission status">
  </div>

- [AtCoder Submission User Colorizer](https://greasyfork.org/ja/scripts/397710-atcoder-submission-user-colorizer) - [AtCoder](https://atcoder.jp/)の「提出結果」ページのユーザ名を色付けする。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_submission_user_colorizer.png" alt="atcoder submission user colorizer">
  </div>

- [atcoder-tasks-page-colorizer](https://greasyfork.org/ja/scripts/380404-atcoder-tasks-page-colorizer) - [AtCoder](https://atcoder.jp/)の「問題」ページで、提出した問題に色付けする。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_tasks_page_colorizer.jpg" alt="atcoder tasks page colorizer">
  </div>

- [AtCoder Theme: Solarized Dark](https://greasyfork.org/ja/scripts/423564-atcoder-theme-solarized-dark) - 背景のテーマを「Solarized Dark」に変更する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_theme_solarized_dark.png" alt="atcoder theme solarized dark">
  </div>

- [AtCoder TLE Police](https://greasyfork.org/ja/scripts/381104-atcoder-tle-police) - 提出したコードが'TLE'(Time Limit Exceeded)となった場合に'AR'(ArRested)に置き換える。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_tle_police.png" alt="atcoder tle police">
  </div>

- [AtCoder Traffic Light](https://greasyfork.org/ja/scripts/420136-atcoder-traffic-light) - 「問題」ページから、直接解説ページに移動できる。また、解説ボタンの色が読み込み状況に応じて変化する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_traffic_light.png" alt="snuke? smeke?">
  </div>

- [AtCoderタイマー削除](https://greasyfork.org/ja/scripts/393176-calmatcoder) - コンテストが開催されている間のみ、タイマーを非表示にする。

- [HighlightAtCoderContestNot2100](https://greasyfork.org/en/scripts/426911-highlightatcodercontestnot2100) - レーティングの変動があるコンテストのうち、開始時間が21時でない場合に赤字で強調する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/highlight_atcoder_contest_not_2100.png" alt="highlight atcoder contest not 2100">
  </div>

- [perf on standings](https://greasyfork.org/en/scripts/422106-perf-on-standings) - 「順位表」ページで、Rated対象者の順位をパフォーマンス値に対応した色で塗る。

  <div align="center">
    <img loading = "lazy" src="images/userscript/perf_on_standings.png" alt="perf on standings">
  </div>

- [Snuke? Smeke?](https://greasyfork.org/ja/scripts/377622-snuke-smeke) - 問題文の「すぬけ」と「すめけ」をハイライトする。

  <div align="center">
    <img loading = "lazy" src="images/userscript/snuke_smeke.png" alt="snuke? smeke?">
  </div>

- [Time Limit Emphasizer](https://greasyfork.org/ja/scripts/406381-time-limit-emphasizer) - 問題の実行時間制限が2secでない場合に赤大文字で強調する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/time_limit_emphasizer.png" alt="time limit emphasizer">
  </div>

- [View All Editorials](https://greasyfork.org/ja/scripts/416554-view-all-editorials) - 「解説」ページに、問題の解説を表示する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/view-all-editorials.png" alt="view all editorials">
  </div>

#### 非公式サービス、ツール、外部サービスなど

- [AtCoder Problems Marker](https://greasyfork.org/ja/scripts/395711-atcoder-problems-marker) - [AtCoder Problems](https://kenkoooo.com/atcoder/) で表示される問題に、ユーザが独自のマーカー(解説ACなど)を付けられるようにする。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_problems_marker.png" alt="atcoder problems marker">
  </div>

- [ICPC-Yokohama-2020-Username-and-AtCoder-Color](https://github.com/TumoiYorozu/ICPC-Yokohama-2020-Username-and-AtCoder-Color) - ICPC 2020 Yokohama Liveの[順位表](https://icpcsec.firebaseapp.com/standings/)に、ユーザ名とAtCoderのレーティングに対応した色を表示する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/icpc_yokohama_2020_username_and_atcoder_color.png" alt="icpc yokohama 2020 username and atcoder color">
  </div>

### 便利な機能を手軽に実行できるボタン、リンクなどを設置する

- [ac-favorite-manager](https://greasyfork.org/ja/scripts/387728-ac-favorite-manager) - ユーザ名のドロップダウンメニューに、お気に入りの管理画面のリンクを追加する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/ac_favorite_manager.png" alt="ac favorite manager">
  </div>

- [AtCoder Auto Pager](https://greasyfork.org/ja/scripts/421991-atcoder-auto-pager) - 「順位表」ページに、順位・得点・解答時間・パフォーマンスによる検索機能を追加する。注: パフォーマンスによる検索を行うためには、[ac-predictor](https://greasyfork.org/ja/scripts/369954-ac-predictor)を導入する必要がある。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_auto_pager.png" alt="atcoder auto pager">
  </div>

- [atcoder_collect_all_examples](https://greasyfork.org/ja/scripts/387240-atcoder-collect-all-examples) - 「問題」ページに入力例・出力例をまとめた項目を生成する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_collect_all_examples.png" alt="atcoder collect all examples">
  </div>

- [AtCoder Fav Rating](https://greasyfork.org/ja/scripts/406745-atcoder-fav-rating) - 「アカウント」ページにお気に入りの順位・レーティング(現在・最高)・参加回数を一覧で表示するボタンを設置する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_fav_rating.png" alt="atcoder fav rating">
  </div>

- [AtCoder-Google-Calender](https://greasyfork.org/ja/scripts/390758-atcoder-google-calender) - 予定されたコンテストの日時をGoogle Calenderに追加するリンクを設置する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_google_calender.png" alt="atcoder google calender">
  </div>

- [AtCoder HashTag Setter](https://greasyfork.org/ja/scripts/422324-atcoder-hashtag-setter) - 「コンテスト」「問題」「提出」の各ページにあるTwitter Shareボタンを利用するときに、ツイートに関連したハッシュタグを追加する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_hashtag_setter.png" alt="atcoder hashtag setter">
  </div>

- [AtCoder Hide Editorial](https://greasyfork.org/ja/scripts/425127-atcoder-hide-editorial) - 問題の「解説」に関するURLを取り除く。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_hide_editorial.png" alt="atcoder hide editorial">
  </div>

- [AtCoderLanguageButtons](https://greasyfork.org/ja/scripts/421663-atcoderlanguagebuttons) - 「問題」「提出」「コードテスト」の各ページに、提出する言語を簡単に切り替えられるボタンを設置する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_language_buttons.png" alt="atcoder language buttons">
  </div>

- [AtCoder Language Filter](https://greasyfork.org/ja/scripts/398148-atcoder-language-filter) - 「提出」ページで、提出する言語のフィルタリングと並び替えを行う。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_language_filter.png" alt="atcoder language filter">
  </div>

- [atcoder-problem-navigator](https://greasyfork.org/ja/scripts/383360-atcoder-problem-navigator) - 「問題」ページで、各問題のリンクに飛べるナビゲーションバーを追加。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_problem_navigator.png" alt="atcoder problem navigator">
  </div>

- [AtCoder Profile2Ranking Link](https://greasyfork.org/en/scripts/426219-atcoder-profile2ranking-link) - 「プロフィール」ページで、国と地域・誕生年・所属のいずれかのリンクをクリックすると、「ランキング」ページで指定した属性と一致するユーザが表示される。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_profile2ranking_link.png" alt="atcoder profile2ranking link">
  </div>

- [AtCoder_Result_Tweet_Button](https://greasyfork.org/ja/scripts/370227-atcoder-result-tweet-button) - [AtCoder](https://atcoder.jp/)のユーザページに、参加したコンテスト情報をツイートするボタンを追加する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_result_tweet_button.png" alt="atcoder result tweet button">
  </div>

- [AtCoder ResultsPage Tweaks](https://greasyfork.org/ja/scripts/424079-atcoder-resultspage-tweaks) - 「提出結果」ページの「すべての提出」で、検索条件を変更したときに自動で検索する。

- [AtCoder Sample Downloader](https://greasyfork.org/ja/scripts/425977-atcoder-sample-downloader) - 「問題」ページに、入出力のサンプルをダウンロードできるボタンを設置する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_sample_downloader.png" alt="atcoder sample downloader">
  </div>

- [AtCoderTags_Hint](https://greasyfork.org/ja/scripts/393337-atcodertags-hint) - 「問題」ページにカテゴリーを表すヒントボタンを設置する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcodertags_hint.png" alt="atcodertags hint">
  </div>

- [AtCoder TestCase Extension](https://greasyfork.org/ja/scripts/371832-atcoder-testcase-extension) - 公開されているテストケースのリンクを追加する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_testcase_extension.png" alt="atcoder testcase extension">
  </div>

- [AtCoderUsers](https://greasyfork.org/ja/scripts/420811-atcoderusers) - 「プロフィール」ページに、[AtCoder Problems](https://kenkoooo.com/atcoder/)、[AtCoder Performances](https://atcoderapps.herokuapp.com/atcoderperformances/)、[AtCoder Scores](http://atcoder-scores.herokuapp.com/)、[AtCoder Tags](https://atcoder-tags.herokuapp.com/)のリンクを追加する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_users.png" alt="atcoder users">
  </div>

- [AtCoderUserSearchForm](https://greasyfork.org/ja/scripts/382092-atcoderusersearchform) - 「ホーム」ページにユーザ検索のフォームを追加する。日本語版ページのみ有効。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_user_search_form.png" alt="atcoder user search form">
  </div>

- [AtCoder-Submission-RadioButton](https://greasyfork.org/ja/scripts/390828-atcoder-submission-radiobutton) - 「提出」ページに、各問題を選択するラジオボタンを設置する。[Chrome拡張版](https://chrome.google.com/webstore/detail/atcoder-submission-radiob/hkehpabdllmdfmflgjofmgcdbmjafcdd?hl=ja&gl=UA)もある。

  <div align="center">
    <img loading = "lazy" src="images/userscript/atcoder_submission_radiobutton.png" alt="atcoder submission radiobutton">
  </div>

- [AutoSubmissionsSettings.js](https://greasyfork.org/ja/scripts/390514-autosubmissionssettings-js) - 「すべての提出」画面で、指定した言語と結果で検索するボタンを追加する。

  <div align="center">
    <img loading = "lazy" src="images/userscript/auto_submissions_settings_js.png" alt="auto submissions settings js">
  </div>

- [Save_Paken_AtCoder_Account](https://greasyfork.org/ja/scripts/401642-save-paken-atcoder-account) - パ研の共有アカウントで誤ってコンテストに参加するのを防ぐ。

- [VirtualContestUpSolver](https://greasyfork.org/ja/scripts/421963-virtualcontestupsolver) - [AtCoder Problems](https://kenkoooo.com/atcoder/)のバーチャルコンテストで出題された問題のうち、復習したかどうかを管理できる。注: スクリプトを有効活用するためには、バーチャルコンテストに参加できる状態(GitHubアカウントを利用してユーザ認証を済ませた状態)にあり、少なくとも1回以上の参加が必要。

  <div align="center">
    <img loading = "lazy" src="images/userscript/virtual_contest_upsolver.png" alt="virtual contest upsolver">
  </div>

## Google Chromeの拡張機能

Google Chromeに機能を追加します。

使い方は、[こちら](https://www.google.com/search?sxsrf=ALeKk033ZO4VOoYJmsx9txWxx32vSveVQw%3A1594530427618&ei=e5oKX9GlJaSzmAXYjZ4Y&q=chrome+%E6%8B%A1%E5%BC%B5%E6%A9%9F%E8%83%BD+%E4%BD%BF%E3%81%84%E6%96%B9&oq=chrome%E6%8B%A1%E5%BC%B5%E6%A9%9F%E8%83%BD%E3%81%A8%E3%81%AF&gs_lcp=CgZwc3ktYWIQARgBMgcIABBHELADMgcIABBHELADMgcIABBHELADMgcIABBHELADMgcIABBHELADMgcIABBHELADMgcIABBHELADMgcIABBHELADUABYAGC7uwRoAXAAeACAAQCIAQCSAQCYAQCqAQdnd3Mtd2l6&sclient=psy-ab)を参照してください。

### サンプルケースの取得

- [Competitive Companion](https://github.com/jmerle/competitive-companion) - [AtCoder](https://atcoder.jp/)を含む複数のコンテストサイトのサンプルケースを取得することができるブラウザ拡張（[Chrome extension](https://chrome.google.com/webstore/detail/competitive-companion/cjnmckjndlpiamhfimnnjmnckgghkjbl)、[Firefox add-on](https://addons.mozilla.org/en-US/firefox/addon/competitive-companion/))。この結果を利用してテストするIDEプラグインが多数公開されており、例えば[CHelper](https://plugins.jetbrains.com/plugin/7091-chelper)、[JHelper](https://plugins.jetbrains.com/plugin/7541-jhelper)などがある。

  <div align="center">
    <img loading = "lazy" src="images/chrome_extension/competitive_companion.jpg" alt="competitive companion">
  </div>

### 公式でサポートされている以外言語で問題を解く

- [Scratcher's AtCoder](https://chrome.google.com/webstore/detail/scratchers-atcoder/hackndbjgkehhjinjjoldifbhnfddklh?hl=ja&gl=UA) - [Scratch](https://ja.wikipedia.org/wiki/Scratch_(%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9F%E3%83%B3%E3%82%B0%E8%A8%80%E8%AA%9E))で問題を解くことができる。

  <div align="center">
    <img loading = "lazy" src="images/chrome_extension/scratchers_atcoder.jpg" alt="scratchers atcoder">
  </div>

### レーティング、パフォーマンスなどを表示する

- [AtCoder ACer](https://chrome.google.com/webstore/detail/atcoder-acer/pmdfjdiiiacncpgmjmeicdoidkaadjde?hl=ja&gl=UA) - 「問題一覧」ページにコンテスト中にAC(Accepted)した人数を表示する。

  <div align="center">
    <img loading = "lazy" src="images/chrome_extension/atcoder_acer.png" alt="atcoder acer">
  </div>

### UIを見やすく色付けする、表示を簡略化する

- [AtCoder Color](https://chrome.google.com/webstore/detail/atcoder-color/mcefknoiablejellmicpmokcaelpdaec?hl=ja&gl=UA) - 「問題」ページで提出状況に応じて色付けする。

  <div align="center">
    <img loading = "lazy" src="images/chrome_extension/atcoder_color.png" alt="atcoder color">
  </div>

- [AtCoder Color Mark](https://chrome.google.com/webstore/detail/atcoder-color-mark/dogcmibkiolcdafifopmnghhlajpbmga?hl=ja&gl=UA) - 「順位表」や「コンテスト成績表」のページにレーティングを示す円を表示する。

  <div align="center">
    <img loading = "lazy" src="images/chrome_extension/atcoder_color_mark.png" alt="atcoder color mark">
  </div>

- [AtCoderのScoreを見やすくする](https://chrome.google.com/webstore/detail/atcoder-%E3%81%AE-score-%E3%82%92%E8%A6%8B%E3%82%84%E3%81%99%E3%81%8F%E3%81%99%E3%82%8B/ndnmjoimfdcpjbnnlkieikajbbcaockp?hl=ja&gl=UA) - マラソン形式のスコアをカンマ区切りやlogで表示する。

  <div align="center">
    <img loading = "lazy" src="images/chrome_extension/atcoder_marathon_score.png" alt="atcoder marathon score">
  </div>

### 便利な機能を手軽に実行できるボタン、リンクなどを設置する

#### AtCoder

- [AtCoder Calendar](https://chrome.google.com/webstore/detail/atcoder-calendar/dokfhaljgioiaeappgnmibgoipegbldf?hl=ja&gl=UA) - コンテストの「トップ」ページにGoogle Calendarのスケジュール作成リンクを生成する。

  <div align="center">
    <img loading = "lazy" src="images/chrome_extension/atcoder_google_calender.png" alt="atcoder calendar">
  </div>

- [AtCoder Opener](https://chrome.google.com/webstore/detail/atcoder-opener/fcfbcmhldmilebbhlapaekahjlcflinl) - コンテストの「トップ」ページで拡張機能のボタン(Aのマーク)をクリックすると、「印刷用問題文」と「提出」ページを新しいタブで開くことができる。

  <div align="center">
    <img loading = "lazy" src="images/chrome_extension/atcoder_opener.png" alt="atcoder opener">
  </div>

- [AtCoder-Submission-RadioButton](https://chrome.google.com/webstore/detail/atcoder-submission-radiob/hkehpabdllmdfmflgjofmgcdbmjafcdd?hl=ja&gl=UA) - 「提出」ページに、各問題を選択するラジオボタンを設置する。[ユーザスクリプト版](https://greasyfork.org/ja/scripts/390828-atcoder-submission-radiobutton)もある。

  <div align="center">
    <img loading = "lazy" src="images/chrome_extension/atcoder_submission_radiobutton.png" alt="atcoder submission radiobutton">
  </div>

- [AtCoder TestCase Extension](https://chrome.google.com/webstore/detail/atcoder-testcase-extensio/klmflnjcfalpmeldgkcinfilloihmbdh?hl=ja&gl=UA) - 公開されているテストケースへのリンクを追加する。ABC/ARC/AGC以外のコンテストは一部未対応の場合もある。

  <div align="center">
    <img loading = "lazy" src="images/chrome_extension/atcoder_testcase_extension.png" alt="atcoder testcase extension">
  </div>

- [AtCoder Unit Test](https://chrome.google.com/webstore/detail/atcoder-unit-test/lmahhninbclefepjbcdfbcjnancipfmi?hl=ja&gl=UA) - 「問題」ページから、単体(ユニット)テストを生成する。Java (JUnit)、Kotlin (JUnit)、C# (MS Test)、Python3 (unittest)に対応。デフォルトは、Java (JUnit)となっている。対応言語の切り替えは、「拡張機能 / アドオン」 → 「AC Unit Test」 のオプションで行うことができる。

  <div align="center">
    <img loading = "lazy" src="images/chrome_extension/atcoder_unit_test.png" alt="atcoder unit test">
  </div>

- [Coder's Calendar](https://chrome.google.com/webstore/detail/coders-calendar/bageaffklfkikjigoclfgengklfnidll?hl=ja&gl=UA) - 開催予定のコンテスト情報を表示する。[Codechef](https://www.codechef.com/)、 [HackerEarth](https://www.hackerearth.com/)、[Hackerrank](https://www.hackerrank.com/)、[Topcoder](https://www.topcoder.com/)、[Codeforces](https://codeforces.com/)、[CSAcademy](https://csacademy.com/)、 [LeetCode](https://leetcode.com/)、[Kaggle](https://www.kaggle.com/)などにも対応している。

  <div align="center">
    <img loading = "lazy" src="images/chrome_extension/coders_calendar.jpg" alt="coders calendar">
  </div>

- [Coding Schedule](https://chrome.google.com/webstore/detail/coding-schedule/jbekfkgidfgnjgnnaiklfjhepdbhclme?hl=ja&gl=UA) - 開催中・開催予定のコンテスト情報を表示する。[Codeforces](https://codeforces.com/)、[Codechef](https://www.codechef.com/)、[CSAcademy](https://csacademy.com/)、[HackerEarth](https://www.hackerearth.com/)、[Hackerrank](https://www.hackerrank.com/)、[Topcoder](https://www.topcoder.com/)、[Sphere online judge (Spoj)](https://www.spoj.com/)などにも対応している。

  <div align="center">
    <img loading = "lazy" src="images/chrome_extension/coding_schedule.jpg" alt="coding schedule">
  </div>

- [Comfortable Atcoder](https://chrome.google.com/webstore/detail/comfortable-atcoder/ipmmkccdccnephfilbjdnmnfcbopbpaj?hl=ja&gl=UA) - 提出結果の通知、問題をドロップダウンリストで表示、などを設定できる。

  <div align="center">
    <img loading = "lazy" src="images/chrome_extension/comfortable_atcoder.png" alt="comfortable atcoder">
  </div>

- [KONTESTS](https://chrome.google.com/webstore/detail/kontests/agpdemlkalmmeenclchlajdcmbcacoea?hl=ja&gl=UA) - コンテスト情報を表示する。[Codeforces](https://codeforces.com/)、Codeforces::Gym、[TopCoder](https://www.topcoder.com/)、[CSAcademy](https://csacademy.com/)にも対応している。

  <div align="center">
    <img loading = "lazy" src="images/chrome_extension/kontests.png" alt="kontests">
  </div>

- [NextPage](https://chrome.google.com/webstore/detail/nextpage/mhhmddcnnehdkpclpjpmidpeejohlmfb?hl=ja&gl=UA) - あるコンテストの次の回のページに移動できる。レポジトリ作成者注: 拡張機能のアイコンが表示されていない場合は、ピン止めをする必要がある。青矢印のマークをクリックすると動作する。

  <div align="center">
    <img loading = "lazy" src="images/chrome_extension/next_page.png" alt="next page">
  </div>

#### 非公式サービス、ツール、外部サービスなど

- [Solve Later Again](https://chrome.google.com/webstore/detail/solve-later-again/emndffmnlppiaelhdneheagpaancfahk?hl=ja&gl=UA) - [AtCoder Problems](https://kenkoooo.com/atcoder/)のTableページに、「Solve Later Again（またあとで解く）」テーブルを追加し、解き直したい問題を管理できる。

  <div align="center">
    <img loading = "lazy" src="images/chrome_extension/solve_later_again.jpg" alt="solve later again">
  </div>
