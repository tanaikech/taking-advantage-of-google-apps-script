# Google Apps Script を活用しよう

<a name="top"> </a>

ここでは、私の[Blog](https://tanaikech.github.io/)、[Gists](https://gist.github.com/tanaikech)や[GitHub](https://github.com/tanaikech), [Stackoverflow での私の回答](https://stackoverflow.com/users/7108653/tanaike?tab=answers)で公開している Google Apps Script を利用するための CLI ツール、ライブラリ、レポート、ベンチマーク、サンプルスクリプトなどを紹介します。これらのコンテンツから Google Apps Script の可能性を知るきっかけになれば幸いです。

（注意）オリジナルは[こちら（英語）](https://github.com/tanaikech/taking-advantage-of-google-apps-script)です。このリストのみを日本語に自動翻訳させています。リストにある各リンク先は英語です。

<br>

# 索引

- [ニュース](#news)
- [Google Apps Script のトレンド](#trend)
- [設定](#settings)
- [GAS 用の CLI ツール](#clitool)
- [Web アプリケーション](#webapps)
- [GAS ライブラリ](#gaslibraries)
- [GAS ライブラリデータベース](#gaslibrarydatabase)
- [ライブラリに移動](#golibraries)
- [Node.js モジュール](#nodemodules)
- [Python ライブラリ](#pythonlibrary)
- [Javascript ライブラリ](#javascriptlibrary)
- [アドオン](#addons)
- [レポート](#reports)
- [ベンチマーク](#benchmarks)
- [コミュニティ](#communities)
- [サンプルスクリプト](#samplescripts)
  - [Google ドライブ内のファイル](#filesingoogledrive)
  - [プロジェクト](#projects)
  - [スプレッドシート](#spreadsheets)
  - [ドキュメント](#documents)
  - [スライド](#slides)
  - [Gmail](#gmail)
  - [カレンダー](#calendar)
  - [フォーム](#form)
  - [YouTube](#youtube)
  - [チャート](#chart)
  - [分析](#analytics)
  - [Slack](#slack)
  - [仮想通貨](#virtualcurrency)
  - [Stackoverflow](#stackoverflow)
  - [Netatmo](#netatmo)
  - [Figma](#figma)
  - [Microsoft](#microsoft)
  - [その他](#etc)
  - [Node.js](#nodejs)
  - [Golang](#golang)
  - [Python](#python)
  - [Curl](#curl)
  - [Javascript](#javascript)
  - [PHP](#php)
  - [生成AI](#generativeai)
  - [モデルコンテキストプロトコル (MCP)](#mcp)
  - [Gemini CLI](#geminicli)

<br>
<br>

<a name="news"> </a>

# ニュース

- **2025 年 9 月 26 日:** [Recipient of the Outstanding Google Developer Expert Award](https://tanaikech.github.io/2025/10/12/recipient-of-the-outstanding-google-developer-expert-award/)
- **2024 年 6 月 3 日:** [私の投稿が、5 月 23 日の週の「Google Cloud に困惑している人のためのガイド」に掲載されました](https://tanaikech.github.io/2024/06/03/my-post-was-featured-in-the-overwhelmed-persons-guide-to-google-cloud-week-of-may-23/)
- **2023 年 12 月 13 日:** [高度な Google サービスに Drive API v3 がリリースされました](https://tanaikech.github.io/2023/12/13/drive-api-v3-has-been-release) -to-advanced-google-services/)
- **2023 年 8 月 12 日:** [私のレポートが 2023 年 7 月の Google Workspace デベロッパー ニュースレターに掲載されました](https://tanaikech.github.io/2023/08/12/my-report-has-been- 特集-google-workspace-developer-newsletter-on-july-2023/)
- **2023 年 6 月 11 日:** [私のレポートは、Champion Innovators Content Library および Google Cloud Medium Publication で公開されました](https://tanaikech.github.io/2023/06/11/my-report-has-been-published-at-champion-innovators-content-library-and-google-cloud-medium-publication/)
- **2023 年 5 月 21 日:** [私のレポートは、Champion Innovators Content Library および Google Cloud Medium Publication で公開されました](https://tanaikech.github.io/2023/05/21/my-report-has-been-published-at-champion-innovators-content-library-and-google-cloud-medium-publication/)
- **2023 年 5 月 16 日:** [私のレポートは、Champion Innovators Content Library および Google Cloud Medium Publication で公開されました](https://tanaikech.github.io/2023/05/16/my-report-has-been-published-at-champion-innovators-content-library-and-google-cloud-medium-publication/)
- **2023 年 4 月 20 日:** [私のレポート "Google Apps Script を使用した Google スプレッドシートのリッチテキスト管理の強化" が Champion Innovators Content Library で公開されました](https://cloud.google.com/innovators/champions/content#/?q=tanaike)
- **2023 年 1 月 31 日:** [レポートが Champion Innovators Content Library で公開されました](https://tanaikech.github.io/2023/01/31/my-report-has-been-published-at-champion-innovators-content-library/)
- **2022 年 11 月 15 日:** [レポートが Google Workspace Developer Newsletter で公開されました](https://tanaikech.github.io/2022/11/15/my-report-has-been-featured-by-google-workspace-developer-newsletter/)
- **2022 年 11 月 3 日:** [レポートが Champion Innovators Content Library で公開されました](https://tanaikech.github.io/2022/11/03/my-report-has-been-published-at-champion-innovators-content-library/)
- **2022 年 10 月 3 日:** [レポートが Google Clound の Blog で公開されました](https://tanaikech.github.io/2022/10/03/my-report-has-been-published-on-the-blog-of-google-cloud/)
- **2022 年 9 月 6 日:** [レポートが Champion Innovators Content Library で公開されました](https://tanaikech.github.io/2022/09/06/my-3-reports-have-been-published-at-champion-innovators-content-library/)
- **2022 年 8 月 17 日:** [レポートが Champion Innovators Content Library で公開されました](https://tanaikech.github.io/2022/08/24/my-report-has-been-published-at-champion-innovators-content-library/)
- **2022 年 6 月 2 日:** [Google サイトが新しくなり、ページ全体へのコンテンツの埋め込みが可能に](https://tanaikech.github.io/2022/06/02/embed-content-as-a-full-page-in-new-google-sites/)
- **2022 年 4 月 14 日:** [Google Apps Script の Script Editor が更新されます](https://tanaikech.github.io/2022/04/14/updating-script-editor-of-google-apps-script/)
- **2022 年 3 月 10 日:** [Google Forms API の Create メソッドのバグが解消されました](https://gist.github.com/tanaikech/dbabd43df594d27cdd1ecc69a7badb52)
- **2022 年 1 月 22 日:** [2022 年 1 月 19 日、「CellImageBuilder」と「CellImage」の 2 つのクラスがスプレッドシートサービスに追加されました。](https://tanaikech.github.io/2022/01/22/on-january-19-2022-2-classes-of-cellimagebuilder-and-cellimage-have-been-added-to-spreadsheet-service/)
- **2021 年 12 月 9 日：** [Google フォーム API がオープンベータ版で利用可能になりました](https://tanaikech.github.io/2021/12/09/google-forms-api-now-available-in-open-beta/)
- **2021 年 12 月 9 日** [(修正済み) Google Apps Script Web App HTML フォームファイル-入力フィールドが blob 互換形式ではない](https://tanaikech.github.io/2021/12/09/fixed-google-apps-script-web-app-html-form-file-input-fields-not-in-blob-compatible-format/)
- **2021 年 10 月 16 日：** [Google フォーム API の発表](https://tanaikech.github.io/2021/10/16/announcing-the-google-forms-api/)
- **2021 年 10 月 14 日：** [Google Cloud Innovators Champions](https://tanaikech.github.io/2021/10/14/google-cloud-innovators-champions/)
- **2021 年 4 月 6 日：** [Google Apps Script プロジェクトのタイムゾーンに関する新しい IDE のバグが削除されました](https://tanaikech.github.io/2021/04/06/a-bug-of-new-ide-about-time-zone-of-google-apps-script-project-was-removed/)
- **2020 年 12 月 15 日：** [Google Workspace Developer Experts に会う](https://tanaikech.github.io/2020/12/15/meet-the-google-workspace-developer-experts/)
- **2020 年 12 月 8 日：** [Google Apps Script 用の新しい IDE がついにリリースされました](https://tanaikech.github.io/2020/12/08/new-ide-for-google-apps-script-has-been-finally-released/)
- **2020 年 7 月 30 日：** [ドライブ API で GoogleApps Script プロジェクトを再度作成できるようになりました](https://gist.github.com/tanaikech/36821c7d70f9ce376d043c3d682d404e)
- **2020 年 7 月 10 日：** [ファイルの所有者の転送は、ドライブ API のバッチリクエストで実現できるようになりました](https://tanaikech.github.io/2020/07/10/transfer-of-owner-of-files-got-to-be-able-to-be-achived-with-batch-requests-of-drive-api/)
- **2020 年 7 月 9 日：** [ファイルの仕様：ドライブ API のコピーが変更されました](https://tanaikech.github.io/2020/07/09/specification-of-files-copy-in-drive-api-was-changed/)
- **2020 年 7 月 7 日：** [ファイルの所有者の転送は、ドライブ API のバッチリクエストでは使用できなくなりました](https://tanaikech.github.io/2020/07/07/transfer-of-owner-of-files-got-not-to-be-able-to-be-use-with-batch-requests-of-drive-api/)
- **2020 年 6 月 15 日：** [ファイルの所有者の転送は、ドライブ API のバッチリクエストで実現できるようになりました](https://tanaikech.github.io/2020/06/15/transfer-of-owner-of-files-got-to-be-able-to-be-achived-with-batch-requests-of-drive-api/)
- **2020 年 6 月 4 日：** [Google Apps Script のドライブサービスを使用した共有ドライブの管理](https://gist.github.com/tanaikech/ede1c9ea6eb6a27235df7d4cb16ef48d)
- **2020 年 3 月 11 日：** [DriveAPI は GoogleApps Script プロジェクトを作成できなくなりました](https://gist.github.com/tanaikech/0609f2cd989c28d6bd49d211b70b453d)
- **2020 年 2 月 7 日：** [V8 ランタイムは 2020 年 2 月 7 日に GoogleApps Script に追加されました](https://gist.github.com/tanaikech/8246f89540957b177f0e350f453ea2fb)
- **2019 年 4 月 8 日：** [Google Apps Script プロジェクトの仕様は 2019 年 4 月 8 日に変更されました](https://gist.github.com/tanaikech/558a5b6da0d9533017b1abe5815989c3)

<br>

<a name="trend"> </a>

# Google AppsScript のトレンド

> Stackoverflow では、多くの人が毎日質問と質問への回答を投稿しています。Stackoverflow にはさまざまなタグがあります。各タグで多くの議論が行われます。彼らの議論は重要な情報をもたらし、多くの人々にとって非常に役立ちます。タグの 1 つとして、「google-apps-script」があります。私は時々そのタグで質問で話し合います。ディスカッションを見ると、タグの原点である「Google Apps Script」が更新されているため、時間の経過とともにディスカッションが変化し、進行していることがわかります。このレポートでは、この変更を「google-apps-script」のタグのトレンドと考えています。この傾向には、「google-apps-script」のタグに追加される質問、質問者、回答者、タグの数が含まれます。「google-apps-script」のタグのトレンド Google AppsScript の進歩と GoogleAppsScript のさまざまなアプリケーションに深く関係しています。このレポートでは、いくつかのアプローチの 1 つとして、「google-apps-script」のタグが付いたすべての質問を統計的に分析することにより、Google AppsScript の傾向を調査しました。その結果、「google-apps-script」のタグを付けてすべての質問を調査したところ、このメインタグに追加されたタグが「google-apps-script」のタグの傾向に強く影響していることがわかりました。また、「google-apps-script」のタグに追加されたタグを調査することで、将来のトレンドを推定できる可能性が示されました。Google Apps Script の傾向は、「google-apps-script」のタグが付いたすべての質問を統計的に分析することによって調査されました。その結果、「google-apps-script」のタグを付けてすべての質問を調査したところ、このメインタグに追加されたタグが「google-apps-script」のタグの傾向に強く影響していることがわかりました。また、「google-apps-script」のタグに追加されたタグを調査することで、将来のトレンドを推定できる可能性が示されました。Google Apps Script の傾向は、「google-apps-script」のタグが付いたすべての質問を統計的に分析することによって調査されました。その結果、「google-apps-script」のタグを付けてすべての質問を調査したところ、このメインタグに追加されたタグが「google-apps-script」のタグの傾向に強く影響していることがわかりました。また、「google-apps-script」のタグに追加されたタグを調査することで、将来のトレンドを推定できる可能性が示されました。

- [Stackoverflow における 2019 年の google-apps-script タグの傾向](https://gist.github.com/tanaikech/4e4f1ca20b8dbce08f87289db415df7d)

- [Stackoverflow における 2020 年の google-apps-script タグの傾向](https://gist.github.com/tanaikech/fd7dbc6d630fd0550c32159635cecc96)

- [Stackoverflow における 2021 年の google-apps-script タグの傾向](https://gist.github.com/tanaikech/18519c3177e284638dce9113ec7ab5b1)

- [Stackoverflow における 2022 年の google-apps-script タグの傾向](https://gist.github.com/tanaikech/e258f30182fdd6609d94d87805914caa)

- [Stackoverflow における 2023 年の google-apps-script タグの傾向](https://gist.github.com/tanaikech/526e5aaed047ca54ece491a2f465f923)

- [Stackoverflow における 2024 年の google-apps-script タグの傾向](https://gist.github.com/tanaikech/7efec2c872fe2db57539a002d5d25875)
- [Stackoverflow における 2025 年の google-apps-script タグの傾向](https://gist.github.com/tanaikech/141bbe4e2ea4ad8ac926410063d10e1e)
<br>

<a name="settings"> </a>

# 設定

- [Cloud PlatformProject と GoogleApps Script Project のリンク](https://gist.github.com/tanaikech/e945c10917fac34a9d5d58cad768832c)：2019 年 4 月 8 日、Google Apps ScriptProject の仕様が変更されました。このレポートでは、Cloud PlatformProject を GAS プロジェクトにリンクするためのフローについて説明します。

- [Google CloudPlatform プロジェクトを新しい IDE 用の GoogleApps Script プロジェクトにリンクする](https://github.com/tanaikech/Linking-Google-Cloud-Platform-Project-to-Google-Apps-Script-Project-for-New-IDE)：これは、Google Cloud PlatformProject を新しい IDE 用の GoogleApps ScriptProject にリンクするためのドキュメントです。また、Google Apps ScriptAPI と GooglePhotosAPI を使用したいくつかのサンプルスクリプトが紹介されています。

- [新しい IDE の Web アプリの URL を変更せずに Web アプリを再デプロイする](https://gist.github.com/tanaikech/ebf92d8f427d02d53989d6c3464a9c43)：2021 年 3 月 15 日、1 つのデプロイメントに対して 1 つのエンドポイントが作成されます。[参照](https://developers.google.com/apps-script/releases/#march_15_2021)これにより、「Web Apps」を再デプロイすると、エンドポイントが変更されます。デプロイメント ID が変更されたため。これが新仕様のようです。このレポートでは、新しい IDE の Web アプリの URL を変更せずに Web アプリを再デプロイする方法を紹介します。

<br>

<a name="clitool"> </a>

# GAS 用の CLI ツール

- [ggsrun](https://github.com/tanaikech/ggsrun)：ローカル PC の独自の端末で Google Apps Script(GAS)を実行します。
- [gislack](https://github.com/tanaikech/gislack)：ファイルを Gist と Slack の両方に送信します。
- [goris](https://github.com/tanaikech/goris)：Google 逆画像検索(goris)で画像を検索します。
- [gogauth](https://github.com/tanaikech/gogauth)：Google で API を使用するためのアクセストークンを簡単に取得できます。
- [gorearrange](https://github.com/tanaikech/gorearrange)：端末上のテキストデータをインタラクティブに再配置します。
- [goodls](https://github.com/tanaikech/goodls)：Google ドライブから共有ファイルをダウンロードします。

<br>

<a name="webapps"> </a>

# Web アプリケーション

- [Google Apps Script ライブラリの検索](https://sites.google.com/view/sea​​rch-gas-libraries)：これは[the database](https://github.com/tanaikech/Google-Apps-Script-Library-Database)から GoogleApps スクリプトライブラリを検索するためのアプリケーションです。
- [Fields Builder For Google APIs](https://sites.google.com/view/fields-builder)：FieldsBuilderForGoogleAPIs は、GoogleAPI を使用するためのフィールド値を構築するための Web アプリケーションです。これは主に、GoogleAPI を使用するためのスクリプトを開発するために使用されます。[GitHub](https://github.com/tanaikech/FieldsBuilderForGoogleAPIs)

<br>

<a name="gaslibraries"> </a>

# GAS ライブラリ

GAS ライブラリは、[Google Apps Script ライブラリの検索](https://sites.google.com/view/sea​​rch-gas-libraries)で検索できます。

- [BatchRequest](https://github.com/tanaikech/BatchRequest)：これは Google Apps Script(GAS)を使用してバッチリクエストを実行するためのライブラリです。
- [ConvertNFDtoNFC](https://github.com/tanaikech/ConvertNFDtoNFC)：これは、Google Apps Script を使用して文字列を NFD(正規化フォーム分解)から NFC(正規化フォーム合成)に変換するためのスクリプトです。
- [FilesApp](https://github.com/tanaikech/FilesApp)：FilesApp は、Google Apps Script(GAS)を使用して Google ドライブのファイルとフォルダのリストを取得するための GAS ライブラリです。また、これにより、Google ドライブ内のすべてのファイルとフォルダからツリーを作成できます。
- [ImgApp](https://github.com/tanaikech/ImgApp)：これは Google AppsScript 用の画像ツールのライブラリです。
- [ManifestsApp](https://github.com/tanaikech/ManifestsApp)：これは Google AppsScripts のマニフェストライブラリです。
- [ProjectApp](https://github.com/tanaikech/ProjectApp)：これは Google Apps Script(GAS)用のプロジェクトライブラリです。
- [ProjectApp2](https://github.com/tanaikech/ProjectApp2)：これは Google Apps Script(GAS)用の GAS プロジェクトライブラリです。このライブラリは、スタンドアロンスクリプトタイプとコンテナバインドスクリプトタイプの両方のプロジェクトに使用できます。
- [OnedriveApp](https://github.com/tanaikech/OnedriveApp)：これは MicrosoftOneDrive を使用するための GoogleAppsScript のライブラリです。
- [Resumable_Upload_For_WebApps](https://github.com/tanaikech/Resumable_Upload_For_WebApps)：これは、Google Apps Script(GAS)を使用して Web Apps で大きなサイズ(> 50 MB)のファイルをアップロードするためのサンプルスクリプトです。再開可能なアップロード方法は、ファイルのアップロードに使用されます。このスクリプトは、javascript の gapi を使用してスクリプトに適用することもできます。
- [RunAll](https://github.com/tanaikech/RunAll)：これは、ネイティブの Google Apps Script(GAS)のみを使用して並行処理を実行するためのライブラリです。
- [SOUWA_GAS](https://github.com/tanaikech/SOUWA_GAS)：配列内の文字列要素を高速で合計するための GAS ライブラリ
- [ZipFolder](https://github.com/tanaikech/ZipFolder)：これは Google AppsScripts を使用してフォルダーを圧縮するためのライブラリです。
- [RangeListApp](https://github.com/tanaikech/RangeListApp)：RangeListApp は、Google Apps Script(GAS)を使用してスプレッドシートの値を a1Notation の範囲リストで取得、配置、置換するための GAS ライブラリです。
- [DownloadLargeFilesByUrl](https://github.com/tanaikech/DownloadLargeFilesByUrl)：DownloadLargeFilesByUrl は、Google Apps Script(GAS)を使用して URL から Google ドライブに大きなファイルをダウンロードするための GAS ライブラリです。
- [ArrangeStackingOrder](https://github.com/tanaikech/ArrangeStackingOrder)：ArrangeStackingOrder は、Google Apps Script(GAS)を使用して Google スライド上のページ要素のスタック順序を調整するための GAS ライブラリです。
- [ProcessApp](https://github.com/tanaikech/ProcessApp)：これは Google AppsScript のプロセスと情報を取得するためのライブラリです。たとえば、メソッドの 1 つは、所有者のアカウントで時間駆動型トリガーによって実行されたすべての関数の合計実行時間を取得します。
- [GistChecker](https://github.com/tanaikech/GistChecker)：これは、Google Apps Script を使用して、自分の Gists のコメント、スター、フォークの数の変更をメールで通知するための GAS ライブラリです。
- [FetchApp](https://github.com/tanaikech/FetchApp)：これは、Google AppsScript を使用して multipart / form-data のタイプを作成および要求するための GAS ライブラリです。このライブラリは、Google AppsScript のクラス UelFetchApp を拡張します。
- [GetEditType](https://github.com/tanaikech/GetEditType)：GetEditType は、Google Apps Script(GAS)を使用してスプレッドシートの OnEdit イベントトリガーの編集タイプを取得するための GAS ライブラリです。
- [UnzipGs](https://github.com/tanaikech/UnzipGs)：これは、Google AppsScript を使用してパスワードで保護された Zip ファイルを解凍するための GAS ライブラリです。
- [GmailToList](https://github.com/tanaikech/GmailToList)：これは、Google Apps Script(GAS)を使用して Gmail のすべてのメッセージをリストとしてエクスポートするためのライブラリです。
- [EncodeApp](https://github.com/tanaikech/EncodeApp)：EncodeApp は、エンコードセット(charset)を取得し、Google Apps Script(GAS)を使用して特定のエンコードセットで URL エンコードを行うための GAS ライブラリです。
- [DateFinder](https://github.com/tanaikech/DateFinder)：DateFinder は、スプレッドシートのシートのセル範囲から日付オブジェクトを検索し、GoogleApps を使用して検索範囲を RangeList オブジェクトとして取得するための GAS ライブラリです。スクリプト(GAS)。
- [RichTextApp](https://github.com/tanaikech/RichTextApp)：これは、テキストスタイルのリッチテキストを GoogleDocument から GoogleSpreadsheet に、または GoogleSpreadsheet から GoogleApps Script を使用して GoogleDocument にコピーするための GAS ライブラリです(ガス)。また、セル内のリッチテキストを HTML 形式に変換することもできます。
- [GPhotoApp](https://github.com/tanaikech/GPhotoApp)：これは、Google Apps Script(GAS)を使用して Google PhotoAPI を使用してアルバムとメディアアイテムを取得および作成するための GAS ライブラリです。
- [CopyFolder](https://github.com/tanaikech/CopyFolder)：これは Google ドライブ上のフォルダをコピーするための Google AppsScript ライブラリです。
- [OwnershipTransfer](https://github.com/tanaikech/OwnershipTransfer)：これは、ドライブ API を使用してファイルやサブフォルダーを含む特定のフォルダーの所有権の譲渡を実現するための Google AppsScript ライブラリです。
- [GASProjectApp](https://github.com/tanaikech/GASProjectApp)：これは、ドライブ API を使用してスタンドアロンタイプの Google Apps Script プロジェクトを作成、更新、エクスポートするための Google AppsScript ライブラリです。この場合、Apps ScriptAPI は使用されません。
- [DocsServiceApp](https://github.com/tanaikech/DocsServiceApp)：これは、ドキュメントサービス、ドキュメント API、スプレッドシートサービス、スプレッドシート API、スライドサービス、スライド API をサポートするための Google AppsScript ライブラリです。このライブラリの目的は、サービスが達成できないプロセスを補うことです。
- [HtmlFormApp](https://github.com/tanaikech/HtmlFormApp) : これは、HTML フォームからフォームオブジェクトを解析し、送信された値をスプレッドシートに追加するための Google AppsScript ライブラリです。
- [DocNamedRangeApp](https://github.com/tanaikech/DocNamedRangeApp) : これは、Google ドキュメントの名前付き範囲を管理するための Google Apps Script ライブラリです。
- [RichTextAssistant](https://github.com/tanaikech/RichTextAssistant) : これは、Google Apps Script を使用した Google スプレッドシートのリッチテキストの編集をサポートするためのライブラリです。
- [UtlApp](https://github.com/tanaikech/UtlApp) : Google Apps Scriptによるアプリケーション開発をサポートする便利なスクリプトを集めたGoogle Apps Scriptライブラリです。
- [TemplateApp](https://github.com/tanaikech/TemplateApp) : Google スプレッドシートをデータベースとして利用した Google ドキュメントや Google スライドのテンプレートを Google Apps Script で簡単に管理するための Google Apps Script ライブラリです。
- [TriggerApp](https://github.com/tanaikech/TriggerApp) : Google Apps Scriptを使用してGoogle Apps Scriptを実行するための時間駆動トリガーを効率的に管理するためのGoogle Apps Scriptライブラリです。
- [PDFApp](https://github.com/tanaikech/PDFApp) : PDF を管理するための Google Apps Script ライブラリです。
- [ScriptHistoryApp](https://github.com/tanaikech/ScriptHistoryApp) : Google Apps Script プロジェクトの履歴を管理するための Google Apps Script ライブラリです。
- [MicrosoftDocsApp](https://github.com/tanaikech/MicrosoftDocsApp) : これは、Goolge Apps Scriptの[Document service](https://developers.google.com/apps-script/reference/document), [Spreadsheet service](https://developers.google.com/apps-script/reference/spreadsheet), [Slides Service](https://developers.google.com/apps-script/reference/slides)を使用してMicrosoft Docs files (Word, Excel, and PowerPoint files)を使用するためのライブラリです。
- [CorporaApp](https://github.com/tanaikech/CorporaApp) : Gemini API のコーパスを管理するための Google Apps Script ライブラリです。
- [ImageBotApp](https://github.com/tanaikech/ImageBotApp) : これは、Gemini と Google Apps Script および Google Drive を使用した画像ボットです。
- [GoogleApiApp](https://github.com/tanaikech/GoogleApiApp) : Google Apps ScriptでGoogle APIを利用することをサポートするためのGoogle Apps Scriptライブラリです。
- [GeminiWithFiles](https://github.com/tanaikech/GeminiWithFiles) : GeminiWithFiles と呼ばれる新しい Google Apps Script ライブラリは、大規模な言語モデルである Gemini の使用を簡素化し、画像や PDF などの非構造化データを処理します。 GeminiWithFiles は、ファイルのアップロード、コンテンツの生成、複数の画像からの説明の作成を一度に行うことができます。 これにより、作業負荷が大幅に軽減され、Gemini の使用可能性が広がります。
- [MoveFolder](https://github.com/tanaikech/MoveFolder) : これは、Google ドライブ上のファイルとフォルダを含むフォルダを移動するための Google Apps Script ライブラリです。
- [MimeTypeApp](https://github.com/tanaikech/MimeTypeApp) : これは、さまざまな MIME タイプから指定されたターゲット MIME タイプにファイルを変換するための Google Apps Script ライブラリです。ライブラリは、ファイル ID と BLOB の両方を入力値として受け入れます。
- [MCPApp](https://github.com/tanaikech/MCPApp) : このテキストでは、AIインタラクションのためのモデルコンテキストプロトコル（MCP）を紹介し、Google Apps Script（GAS）をサーバーオプションとして検討します。サンプルコードを用いて実現可能性を示しますが、GAS SDKが存在しない点にも留意し、理解と開発を促進することを目的としています。
- [A2AApp](https://github.com/tanaikech/A2AApp) : これは、Google Apps Scriptを用いてAgent2Agent（A2A）サーバーを実装するためのライブラリです。これにより、AIエージェント間の通信と、AIを活用したワークフローにおける安全なサービスアクセスが可能になります。この成果は、Google Apps Scriptの潜在能力を浮き彫りにする可能性があります。
- [ToolsForMCPServer](https://github.com/tanaikech/ToolsForMCPServer): Gemini CLIは、MCPサーバーとして機能するGoogle Apps Scriptウェブアプリと統合され、Google Workspace APIの認証を簡素化します。これにより、GeminiはGoogleエコシステム内の複雑なタスクを自動化し、生産性を向上させることができます。設定手順とサンプルコードも提供されています。

<br>

<a name="gaslibrarydatabase"> </a>

# GAS ライブラリデータベース

- [Google Apps Script Library データベース](https://github.com/tanaikech/Google-Apps-Script-Library-Database)：これは GoogleApps スクリプトライブラリデータベース用です。

<br>

<a name="golibraries"> </a>

# Go ライブラリ

- [go-getfilelist](https://github.com/tanaikech/go-getfilelist)：これは、Google ドライブの特定のフォルダーからフォルダーツリーを含むファイルリストを取得するための Golang ライブラリです。
- [go-gettokenbyserviceaccount](https://github.com/tanaikech/go-gettokenbyserviceaccount)：これは、Google の OAuth2 パッケージを使用せずに Google のサービスアカウントからアクセストークンを取得するための Golang ライブラリです。
- [go-gdoctableapp](https://github.com/tanaikech/go-gdoctableapp)：これは、Google DocsAPI を使用して Google ドキュメントのテーブルを管理するための Golang ライブラリです。

<br>

<a name="nodemodules"> </a>
Node.js モジュール
=====

- [node-getfilelist](https://github.com/tanaikech/node-getfilelist)：これは、Google ドライブの特定のフォルダーからフォルダーツリーを含むファイルリストを取得するための Node.js モジュールです。
- [node-gdoctableapp](https://github.com/tanaikech/node-gdoctableapp)：これは、Google DocsAPI を使用して Google ドキュメントのテーブルを管理する Node.js モジュールです。

<br>

<a name="pythonlibrary"> </a>
Python ライブラリ
=====

- [getfilelistpy](https://github.com/tanaikech/getfilelistpy)：これは、Google ドライブの特定のフォルダーからフォルダーツリーを含むファイルリストを取得するための Python ライブラリです。
- [gdoctableapppy](https://github.com/tanaikech/gdoctableapppy)：これは、Google DocsAPI を使用して Google ドキュメントのテーブルを管理するための Python ライブラリです。

<br>

<a name="javascriptlibrary"> </a>
Javascript ライブラリ
=====

- [GetFileList_js](https://github.com/tanaikech/GetFileList_js)：これは、Google ドライブの特定のフォルダー(パブリック共有フォルダーと独自のフォルダー)からフォルダーツリーを含むファイルリストを取得するための Javascript ライブラリです。
- [syncGoogleScriptRun](https://github.com/tanaikech/syncGoogleScriptRun)：これは同期プロセスで「google.script.run」を使用するための Javascript ライブラリです。
- [ResumableUploadForGoogleDrive_js](https://github.com/tanaikech/ResumableUploadForGoogleDrive_js)：これは、Google ドライブの再開可能なアップロードを実現するための Javascript ライブラリです。
- [BatchRequest_js](https://github.com/tanaikech/BatchRequest_js)：これは、Javascript を使用して GoogleAPI のバッチリクエストを実行するためのライブラリです。
- [HtmlFormObjectParserForGoogleAppsScript_js](https://github.com/tanaikech/HtmlFormObjectParserForGoogleAppsScript_js)：これは、 `google.script.run`を使用して HTML フォームオブジェクトを GoogleAppsScript に送信するための Javascript ライブラリです。
- [GetAccessTokenFromServiceAccount_js](https://github.com/tanaikech/GetAccessTokenFromServiceAccount_js)：これは、Google サービスアカウントからアクセストークンを取得するための Javascript ライブラリです。
- [[画像を枠で切り抜く Javascript ライブラリ](https://github.com/tanaikech/CropImageByBorder_js) : 画像を枠で切り抜くための Javascript ライブラリです。

<br>

<a name="addons"> </a>

# アドオン

- [RearrangeScript](https://chrome.google.com/webstore/detail/rearrangescripts/ndaicidjkbcpajgejcclgfdcncpoekml)：スクリプトエディターで表示できるプロジェクトで Google Apps Scripts(GAS)を再配置します。[GitHub](https://github.com/tanaikech/RearrangeScripts)
- [ShapeApp](https://chrome.google.com/webstore/detail/shapeapp/nmbimbgfafgmkhioolneofjchigbpkhf)：Google スライドで図形を操作します。パラメータを入力して図形を作成・更新したり、図形を配置したりできます。これは、Google Apps Scripts(GAS)で構成されています。[GitHub](https://github.com/tanaikech/ShapeApp)

<br>

<a name="reports"> </a>

# レポート

### [配列の合計のための改善されたアルゴリズム](https://tanaikech.github.io/2016/10/13/improved-algorithms-for-summation-of-array-elements/)

> 配列要素を合計するための効率的なアルゴリズムを検討しました。配列内のすべての要素は文字列です。これらの要素をスクリプトを使用して合計する場合、標準的な方法は、各要素を順番に追加することです。スクリプトを最適化せずに実行すると、合計プロセス中のアクティブなデータの合計量が配列要素の数の 2 乗に比例するため、プロセスは徐々に遅くなります。これは、高いプロセスコストに直接つながります。このような現象は、特に Google Apps Script(GAS)で発生します。このレポートでは、ピラミッド法の新しいアルゴリズムを使用したこの問題の解決について説明しています。ピラミッド法では、アクティブなデータの総量が配列要素の数の線形に比例して増加します。これで、処理時間は、標準的な方法を使用するプロセスよりもはるかに短くなります。ピラミッド法は、GAS の標準法と比較して 99.7％のプロセスコスト削減を達成しました。身近な日常のシーンに新たな発見が隠されていることに改めて気づきました。

### [GAS ライブラリによるマニフェストの活用](https://gist.github.com/tanaikech/23ddf599a4155b66f1029978bba8153b)

> 最近の Google アップデート(2017 年 10 月 24 日の Google アップデート)によって、GAS 開発者にさまざまな新しい風が吹きました。新しい風の一つとして「マニフェスト」があります。「マニフェスト」を使用すると、JSON を使用してプロジェクトを管理できます。特に、OAuth2 プロセスを使用する必要がある特別なスコープは、マニフェストに設定するだけで使用できます。これが最大の変更だと思います。ただし、マニフェストを使用してスコープをプロジェクトに追加する場合、プロジェクトを使用するユーザーは、追加されたスコープのみを使用できます。つまり、ユーザーがプロジェクトでスクリプトを作成するときに、追加する必要のあるスコープがある場合、そのようなスコープを自動的に追加することはできません。そのため、「権限が不十分です」というエラーが発生します。このレポートでは、この問題を回避するための回避策を紹介します。

### [Google スライドの形状の指定された値と取得された値の違い](https://gist.github.com/tanaikech/953e630855e65de55d8e5bd448ad764f)

> これは、Google スライドの図形の特定の値と取得された値の違いを説明するためのドキュメントです。

### [Google Apps Script で Web アプリを活用する](https://github.com/tanaikech/taking-advantage-of-Web-Apps-with-google-apps-script)

> Google Apps Script(GAS)を使用するアプリケーションの 1 つとして WebApps があります。私は時々この Web アプリを使用します。しかし、私は Web アプリの仕様に関する情報を少ししか持っていません。そこで、Web アプリをさらに活用するために、これについて調査して要約しました。このレポートの目的は、GAS で Web アプリを使用してさまざまなアプリケーションを作成するための基本情報の 1 つになることです。

### [Google Apps Script を使用してスプレッドシートに挿入する画像の制限](https://gist.github.com/tanaikech/825f1ebfe7822780316d7c15f89dea11)

> ここでは、Google Apps Script(GAS)を使用してスプレッドシートに挿入するための画像の制限について紹介します。GAS を使用してスプレッドシートに画像を挿入する場合、通常、この状況ではクラス Sheet の insertImage()が使用されます。このとき、エラーが発生することがあります。これは、スプレッドシートへの画像の挿入に制限があることを示しています。そこで、制限を調べました。その結果、制限はファイルサイズではなく画像領域(pixels ^ 2)に依存することがわかりました。挿入できる画像の最大面積は 1,048,576 ピクセル^ 2 でした。

### [イベントトリガーを使用した非同期処理](https://gist.github.com/tanaikech/88f7fd5ed14da5e9afde18310da61cb5)

> これは、イベントトリガーを使用した非同期プロセスの可能性に関するレポートです。単純なトリガーである `onEdit()`は、スプレッドシートで値が変更されたときのトリガーとしてよく使用されます。ユーザーが onEdit イベントとして承認される必要があるいくつかのメソッドを含むスクリプトを使用したい場合、onEdit のインストール可能なトリガーが使用されます。`onEdit()`の機能のためにトリガーがインストールされている場合、イベントトリガーを実行すると、 `onEdit()`が 2 回実行されます。これを回避するために、単純なトリガーの機能以外の機能にインストール可能なトリガーをインストールします。同じイベントである単純なトリガーの機能は、プロジェクトでは使用されません。この状況を考えたとき、単純なトリガーで実行される `onEdit()`とインストール可能なトリガーで実行される関数の両方を同時に使用できるのではないかと思いました。そこで私はこの状況について調査しました。その結果、以下の単純なトリガーとインストール可能なトリガーが非同期プロセスとして機能することがわかりました。

### [Google Apps Script の V8 での Array.prototype.push.apply の制限](https://gist.github.com/tanaikech/3e3c16b58f6b30de366eba99de84c861)

> V8 が有効になっている場合、 `Array.apply`には要素数の制限があります。制限を超えると、「RangeError：最大呼び出しスタックサイズを超えました」などのエラーが発生しますが、V8 が無効になっている場合は問題は発生しませんでした。この場合、この問題は Google AppsScript と Javascript の両方で発生します。ですのでご注意ください。

### [//テンプレート内のリテラルがスクリプトエディタの HTML ファイルで使用される場合、コメントの開始として使用されます](https://gist.github.com/tanaikech/5a6b92f9fcce4046ae4c3c79c28fe958)

> テンプレートリテラルの `//`がスクリプトエディタの HTML ファイルで使用される場合、コメントの開始として使用されます。

### [onSelectionChange の応答の特性](https://gist.github.com/tanaikech/ca5812ed19dd6858879246bd2304266f)

> 「GoogleAppsScript で onSelectionChange イベントトリガーを使用した Google スプレッドシートでのタブの変更の検出」についてはすでに報告しました。[参照](https://tanaikech.github.io/2020/05/18/change-tab-detection-on-google-spreadsheet-using-onselectionchange-event-trigger-with-google-apps-script/)It `onSelectionChange`のイベントトリガーを使用する状況を考える場合、応答速度が重要であると考えられます。そこで、ここでは、 `onSelectionChange`のイベントトリガーに対する応答の特性を調査しました。

### [Google Apps Script を使用して Google スプレッドシートですばやくチェックされたチェックボックスを検出する](https://gist.github.com/tanaikech/7b1a18a5b768e4d69d519069f4aff440)

> これは、Google AppsScript を使用して Google スプレッドシートですばやくチェックされたチェックボックスを検出するためのレポートです。チェックボックスをオンにすると、イベントトリガーによって Google AppsScript の機能が実行されると想定しています。この場合、Google スプレッドシートの複数のチェックボックスをすばやくオンにすると、イベントトリガーの応答速度が原因で、チェックしたすべてのチェックボックスに対してスクリプトを実行できません。イベントトリガーの応答を理解することは、スプレッドシートのアプリケーションを作成するのに役立つと考えられます。このレポートでは、Google AppsScript を使用して Google スプレッドシートですばやくチェックされたチェックボックスの検出について調査しました。この結果から、イベントトリガーの応答を理解することができました。

### [レポート：ドライブ API を使用して特定のフォルダーに新しいファイルを作成する処理](https://gist.github.com/tanaikech/d034e38169503c2c22eb0c3352ae30b6)

> このレポートでは、DriveAPI を使用して特定のフォルダーに新しいファイルを作成するための処理についてレポートします。Drive API を使用して特定のフォルダに新しいファイルを作成すると、フォルダ ID の値を持つ `parents`のプロパティが、メソッド「Files：create」のリクエスト本文に含まれます。このプロセスについて、私はファイルが特定のフォルダに直接作成されると思っていました。しかし、次のプロセスで新しいファイルが作成されていることを確認できました。
>
> 1。ルートフォルダに新しいファイルを作成します。
> 2。作成したファイルを特定のフォルダに移動します。
>
> これらのプロセスは 1 回の API 呼び出しで実行されます。本報告では、上記の過程を確認するための実験結果を紹介したいと思います。この場合、Drive APIv3 は GoogleAppsScript で使用されます。

### [Stackoverflow の `google-apps-script`タグの重複した質問の統計分析](https://gist.github.com/tanaikech/fa8e7002678a377748ae35a33fa5b6eb)

> Stackoverflow では、多くの人が毎日質問を投稿して回答しています。これにより、Stackoverflow には多くの重要な情報があります。Stackoverflow から取得したデータを使用して、「Stackoverflow での google-apps-script タグの傾向」をすでに報告しました。[参照](https://github.com/tanaikech/taking-advantage-of-google-apps-script#trend-of-google-apps-script)重要な統計結果は、 Stackoverflow のデータ。このレポートでは、Stackoverflow の google-apps-script タグの重複した質問の統計分析を紹介します。重複した質問を分析すると、ユーザーにとって重要な問題を知ることができると考えられます。その結果、Javascript に関連する質問が重複する傾向があることがわかりました。

### [Google AppsScript を使用した外部サーバーでの HTML による Google ドライブの安全なアップロード](https://github.com/tanaikech/Safe-Uploading-for-Google-Drive-by-HTML-in-External-Server -using-Google-Apps-Script)

> これは、Google AppsScript を使用して外部サーバーに配置された HTML によってファイルを Google ドライブに安全にアップロードするためのレポートです。

> ユーザーに Google 側の外部サーバーに配置された HTML を使用して自分の Google ドライブにファイルをアップロードさせたい場合、ファイルサイズが 50 MB 未満の場合、アクセストークンを使用せずにこれを実現できます。[参照](https://tanaikech.github.io/2020/08/13/uploading-file-to-google-drive-from-external-html-without-authorization/)(HTML が内部に配置されている場合 Google 側のサーバーでは、[`google.script.run`](https://tanaikech.github.io/2020/02/18/uploading-file-to-google-drive-using-html-and-google-apps-script/)。)ただし、ファイルサイズが 50 MB を超える場合は、再開可能なアップロードでファイルをアップロードする必要があります。この場合、アクセストークンを使用する必要があります。この場合、ユーザーが自分の Google ドライブにアップロードする場合、アップロードでアクセストークンが使用されると、これがセキュリティの弱点と考えられます。このレポートでは、Google Apps Script を使用して外部サーバーに配置された HTML によってファイルを Google ドライブに安全にアップロードする方法を提案したいと思います。これをいくつかの方法の 1 つと考えてください。

### [ドライブ API のファイルリストメソッドの検索クエリの仕様](https://gist.github.com/tanaikech/268baf07f92f3b3962c86c6ea75b786a)

> このレポートでは、Drive API のファイルリストメソッドの検索クエリの現在の仕様について報告したいと思います。

> 最近、Drive API のファイルリストメソッドの検索クエリの仕様が変更されている可能性があることに気付きました。Drive API を使用してアプリケーションを作成するには、検索クエリの仕様の変更を知ることが重要だと思いました。このレポートでは、検索クエリの現在の仕様を紹介します。

### [フォームを使用した Google スプレッドシートへの同時書き込み](https://gist.github.com/tanaikech/c2f3fccabbf4906a18fdc38463982f31)

> ユーザーがフォームを使用してスプレッドシートに書き込もうとする場合、開発者はフォームからの同時送信を考慮する必要があります。たとえば、複数のユーザーがフォームを使用してデータを同時に送信した場合、すべてのデータがスプレッドシートに保存されない可能性があります。そのため、フォームを使用した Google スプレッドシートへの同時書き込みに関する情報を知ることが重要であると考えられます。このレポートでは、そのような状況を調査しました。

> その結果、Google Spreadsheet への同時書き込みの成功率を調査したところ、Google AppsScript で作成した WebApps よりも GoogleForm との同時書き込みの方が適していることがわかりました。スプレッドシートへのすべてのデータの書き込みに成功するためのユーザーのしきい値数は、Google フォームでそれぞれ 35、Web アプリで 26 でした。また、Web Apps を使用する場合、複数の送信には必ず LockService を使用する必要があることがわかりました。

### [Google スプレッドシートの大きな 10 進数と指数表記](https://gist.github.com/tanaikech/a1b32bdace0ebdd6c92a547b6f4dfbeb)

> このレポートでは、Google スプレッドシートの大きな 10 進数と指数表記を調査しました。大きな 10 進数がスプレッドシートに入力されると、スプレッドシートは指数表記を使用して表示値を自動的に設定します。このレポートでは、Spreadsheet サービスと Sheets API によって値が取得されたときの結果が示されています。

### [レポート：Google スプレッドシートに IMAGE 関数を使用して配置された画像](https://gist.github.com/tanaikech/10c55451caab9e291d5a571b157e8020)

> これは、Google スプレッドシートに「`=IMAGE(IMAGE_URL)`」関数を使用して配置された画像に関するレポートです。

> スプレッドシートのセル「A1」に「`=IMAGE(IMAGE_URL)`」を付けると、そのセルに画像が表示されます。この場合、セル「A1」を「`range.copyTo(range、{contentsOnly：true})`」でコピーすると、数式が削除され、画像が表示されます。URL の画像を削除すると、それらの画像はどうなるのかと思いました。このレポートでは、そのような状況を調査しました。

### [Google Apps Script を使用した Google スプレッドシートでの無限ループの発生と解決]（https://gist.github.com/tanaikech/c385bed8f037d67b154d9c0c8ff7a341）

> ここでは、Google AppsScript を使用して Google スプレッドシートで無限ループが発生して解決するためのレポートを紹介します。 これを Google の課題追跡システムに報告しました。

### [Google Apps Script を使用した Google スプレッドシートへのスプレッド構文と分割代入の適用]（https://gist.github.com/tanaikech/d0c60aa54fb55fc61a06593e311fa623）

> このレポートでは、GoogleAppsScript を使用してスプレッド構文と分割代入を GoogleSpreadsheet に適用する方法を紹介します。 最近、Stackoverflow でそれらを使用しているスクリプトをよく見ました。 また、スプレッド構文と破壊的代入に関連する質問を時々受けます。 ということで、ブログで紹介したいと思いました。

### [レポート：Google Apps Script を使用した Google スプレッドシートの 10,000,000 個のセルの処理](https://gist.github.com/tanaikech/cc4380692790150cc090114553e38a0e)

> 2022 年 3 月 14 日、「Google スプレッドシートがセル制限を 2 倍にする」と報告しました。 [参照]（https://workspaceupdates.googleblog.com/2022/03/ten-million-cells-google-sheets.html）この更新により、ユーザーはGoogleスプレッドシートで10,000,000個のセルを使用できるようになりました。 これは私たちにとって素晴らしいニュースです。 Google Apps Script を使用して Google スプレッドシートで 10,000,000 個のセルを処理しようとすると、さまざまな重要なポイントがあることがわかりました。 このレポートでは、GoogleAppsScript を使用して Google スプレッドシートで 10,000,000 個のセルを処理するための重要なポイントを紹介します。

### [レポート：Google Apps Script を使用して GOOGLEFINANCE から値を取得する](https://gist.github.com/tanaikech/7bebb7c6d8ed6ddfdd825153ef71c47e)

> これは、GoogleAppsScript を使用して GOOGLEFINANCE から値を取得するためのレポートです。 Google AppsScript を使用して GoogleSpreadsheet の`GOOGLEFINANCE`関数から値を取得するためにテストしたところ、値を取得できることに気付きました。

### [レポート：Google Apps Script を使用して同じ URL でさまざまな Google ドキュメントを公開する](https://gist.github.com/tanaikech/94810f7947361bef398ac9f301b9afde)

> これは、GoogleAppsScript を使用して同じ URL でさまざまな Google ドキュメントファイルを公開するためのサンプルメソッドです。

> 2022 年 5 月 25 日に更新することにより、コンテンツを新しい Google サイトにフルページとして埋め込むことができるようになりました。 [Ref](https://tanaikech.github.io/2022/06/02/embed-content-as-a-full-page-in-new-google-sites/) このメソッドでは、これが使用されます。

### [レポート：Google Apps Script での ScriptApp.getService（）。getUrl（）の最近の値](https://tanaikech.github.io/2022/06/11/report-recent-value-of-scriptapp.getservice.geturl-in-google-apps-script/)

### [Report: Google Apps Script の機能に関する JsDoc を含むドキュメントコメント](https://gist.github.com/tanaikech/5615cfc34e1d41659e934a7bcbaa27cf)

> これは、GoogleAppsScript の機能に関するドキュメントコメントのレポートです。

> Google Apps Script の機能に関するドキュメントのコメントを検討すると、JsDoc を思い浮かべます。 Google Apps Script では、JsDoc の一部を使用できます。 しかし、このレポートでは、JsDoc を含むドキュメントコメントを紹介したいと思います。

### [Report: Google Apps Script を使用した Google スプレッドシート上の画像の管理](https://gist.github.com/tanaikech/7ecb785ab9d4418d0c48ea853df8d1c8)

> これは、Google Apps Script を使用した Google スプレッドシート上の画像の管理に関するレポートです。

> 2018 年 10 月 30 日、Cass OverGridImage と inserImage のメソッドが Spreadsheet Service に追加されました。 2022 年 1 月 19 日、Class CellImageBuilder と Class CellImage がスプレッドシートサービスに追加されました。 これらのクラスとメソッドにより、画像を Google スプレッドシートで管理できるようになりました。 しかし、さまざまな状況で画像を使用する場合、画像の管理には工夫が必要な場合があります。 そこで、このレポートでは、Google Apps Script のサンプルスクリプトを使用した Google Spreadsheet での画像の管理について紹介します。

### [Report: Google Apps Script と Javascript を使用して、スプレッドシートで選択したセルを画像としてエクスポートすることに挑戦](https://gist.github.com/tanaikech/fbf47fe7b8e3e57ee49f24563550c113)

> スプレッドシートで選択したセルを Google Apps Script と Javascript を使って画像としてエクスポートすることに挑戦したレポートです。

### [Report: Google Apps Script ライブラリを使用して Web アプリを効率的に作成する](https://gist.github.com/tanaikech/90ac88cf1a74989e649a4e49a5ed1ab9)

> これは、Google Apps Script ライブラリを使用して Web アプリを効率的に作成するためのサンプル スクリプトです。

> Google Apps Script ライブラリを使用して Web Apps を作成すると、次の利点が得られます。

> - クライアント側のスクリプトをよりシンプルにできます。 Web Apps を構築するためのほとんどのスクリプトは、Google Apps Script ライブラリに含まれているためです。
> - Web Apps のスクリプト (この場合は、Google Apps Script ライブラリのスクリプトを変更します) を変更すると、最新のスクリプトがすぐに Web Apps に反映されます。ライブラリのスクリプトを変更する際に、Google Apps Script ライブラリを最新バージョンとして使用すると、クライアントはライブラリの最新のスクリプトをすぐに使用できるためです。そのため、Web Apps のダウンタイムを減らすことができます。
>   ・これにより、手動で最新バージョンのスクリプトを Web Apps に反映させる必要がなくなります。
> - ライブラリのデプロイ バージョンを変更することで Web Apps のスクリプトを変更できる場合。

### [Report: Google スプレッドシートの数式による大規模な計算中の Google Apps Script の処理コスト](https://gist.github.com/tanaikech/455ae803fae6a9aba31a928ce5a16c1d)

### [Report: Googleフォームの各質問のアイテムIDのルール](https://gist.github.com/tanaikech/f391fd4d596d45bb846d374ff0ded695)

### [Report: Google Apps Script を使用して Web Apps に疑似 2FA を実装する](https://gist.github.com/tanaikech/7a15164b1227e2ec2231fce24ae9daf2)

> Google Apps Script には Web Apps があります。 Web Apps を使用すると、ユーザーは HTML と Javascript を使用して Google Apps Script を実行できます。 これは、さまざまなアプリケーションに適用できます。 「誰でも」で Web アプリをデプロイすると、誰でも Web アプリにアクセスできます。 また、「誰でも」で展開したWebアプリを利用する必要がある場合があります。 このような状況下で、2 要素認証 (2FA) を実装できれば、より高いセキュリティを実現できると考えられ、Web Apps を使用したアプリケーションにさまざまな方向性を与えることにつながります。 本レポートでは、Google Apps Script を使用して、「誰でも」でデプロイした Web Apps に疑似 2FA を実装する方法を紹介したいと思います。

### [Google Apps Script による Google スプレッドシート上の不連続セルのベスト プラクティス](https://gist.github.com/tanaikech/dba916ae25f7351819e062b42bb5be10)

> Google Apps Script が Google スプレッドシートを管理するための強力なツールであることは既に知られています。 値を取得したり、Google スプレッドシートに配置したりする場合、不連続なセルを使用する必要がある場合があります。 このレポートは、Google スプレッドシートで不連続なセルを処理するためのベスト プラクティスを提案します。 処理コストの結果から、Google Apps Script で Sheets API とスプレッドシート サービスの Class RangeList を使用して低コストで不連続セルを使用することの有用性が理解できました。

### [レポート: Google Apps Script のプロパティサービスの仕様](https://gist.github.com/tanaikech/8b057d10fb5f2af014794e57b021c6aa)

> このレポートでは、PropertiesService の詳細な仕様を調査しました。 この仕様を知っておくと、Google Apps Scriptでアプリケーションを開発する際に役立つと考えられます。 その結果、キーと値の最大サイズは、キーが 1 バイトの場合は 524,287 バイト、値は 8,066 バイトであることがわかりました。 また、PropertiesService の最大サイズは、キーと値の両方のサイズを考慮する必要があることがわかりました。

### [レポート: Google Apps Script を使用して Google スプレッドシートをデータベースとして使用する HTML フォームを簡単に実装](https://gist.github.com/tanaikech/7dcadf189d9bdfd7dc0ae330ab0d84f5)

> 本レポートでは、Google スプレッドシートをデータベースとした HTML フォームを Google Apps Script を使って簡単に実装する方法を紹介します。 Google Apps Scriptを使用したHTMLフォームには2パターンあります。 1 つは、HTML フォームが同じ Google Apps Script プロジェクトに配置されることです。 もう 1 つは、HTML フォームが Google Apps Script プロジェクトとは別のサーバーに配置されることです。 本レポートでは、両方のパターンを簡単に実装する方法をサンプルスクリプトを用いて紹介します。

### [2023 年上半期の Stackoverflow の google-apps-script タグの傾向](https://gist.github.com/tanaikech/ef5a26a092a0e3b47aced170ead74be9)

> 最近、Stackoverflow での質問にこれまでにない変化を感じました。 これを裏付けるために、本レポートでは2023年上半期（1月1日～6月1日）のStackoverflowにおける「google-apps-script」タグの動向を調査した。 このレポートから、新型コロナウイルス感染症の影響が社会的に薄れた2023年において、「google-apps-script」のタグを含む質問に顕著な傾向が確認された。 この顕著な傾向の起源は、AI チャットボットによるものと推測されます。 AIチャットボットの登場は、オンラインサイトから得られる統計データの把握方法に大きな変化をもたらすかもしれません。

### [Google Apps Scriptで作成したWebアプリへのリクエストの流れを理解する](https://gist.github.com/tanaikech/131ba814a1f6012fd6a5ffe11789971f)

> ここでは、Google Apps Scriptで作成したWeb Appsへのリクエストの流れを理解するためのレポートを紹介したいと思います。 Web Appsを利用した様々なアプリケーションを作成し、Web AppsをWebhookとして利用する場合があります。 その場合、Web Appsへのリクエストの流れを理解しておけば、スムーズに目的を達成できるのではないかと考えられます。 本稿ではその情報を紹介したい。

### [レポート: google.script.run を使用して Javascript と Google Apps Script の間で転送する値](https://gist.github.com/tanaikech/9927dc5c12ebca118ff8f3f4d539c95d)

> このレポートでは、google.script.run を使用して HTML と Google Apps Script の間で転送するために使用できる値を紹介します。

### [Google Apps Script のスクリプト エディターの自動補完を活用する](https://gist.github.com/tanaikech/b2f0461c1060b54d2edbd43733708f52)

> Google Apps Scriptのスクリプトエディタのオートコンプリートを利用するためのレポートです。

### [レポート: Google Apps Script の実行方法](https://gist.github.com/tanaikech/f03ab0d9eff7182a57e699fb3fbb32b8)

> Google Apps Script はクラウドコンピューティングの強力なツールの 1 つであり、さまざまな場面で非常に役立ちます。 Google Apps Script はさまざまな方法で実行できます。 本レポートでは、Google Apps Scriptの実行方法を紹介します。
> 最近、生成 AI により、多くの新規ユーザーに Google Apps Script を使用する機会が与えられました。 このレポートがユーザーの皆様の Google Apps Script を使用したアプリケーション開発の一助になれば幸いです。

### [Google Apps Scriptを利用した飲食予約システム](https://github.com/tanaikech/RegistrationApp)

> Google Apps Scriptを利用した飲食予約システムです。

### [2024-01-01 - 2024-12-31 の Stackoverflow での私のアクティビティの統計](https://tanaikech.github.io/2025/03/02/statistics-of-my-activities-from-2024-01-01-2024-12-31-on-stackoverflow/)

> これは、2024-01-01 - 2024-12-31 の Stackoverflow での私のアクティビティの統計です。

### [Geminiによる包括的なビッグデータ処理](https://gist.github.com/tanaikech/92e16484ddfd8e8966673fdf92165ff9)

> 生成AIは、コンテキストウィンドウの制約により、大規模データセットの処理に限界に直面しています。既存の手法では、データレイク全体を分析することはできません。本レポートでは、一般的なモデルの限界を超えた包括的なビッグデータ分析を実現するGemini APIアプローチを紹介します。

### [Stackoverflow からの Google Apps Script の分析](https://gist.github.com/tanaikech/dc6bf3578bed965aaf3bf62abe81e822)

> このレポートでは、AI コンテキストウィンドウの制限を超えてビッグデータを分析するための新しい Gemini API メソッドについて詳しく説明します。このメソッドは Stack Overflow データで検証され、Google Apps Script の可能性についての洞察が得られました。

<br>

<a name="benchmarks"> </a>

# ベンチマーク

### [Google Apps Script のイベントオブジェクト](https://gist.github.com/tanaikech/4892c97df7ac0504ffd715c2dd6cd546)

> - `e.range.getA1Notation()`のプロセスコストは、`e.source.getActiveCell().getA1Notation()` や`SpreadsheetApp.getActiveSheet().getActiveCell().getA1Notation()`のプロセスコストの 20％と 10％程度であることがわかりました。

### [V8 なしで Google Apps Script を使用した配列処理のループ](https://gist.github.com/tanaikech/848aeafaac1ec676900bb78e3ce220b6)

> - 配列から 5 の倍数を取得するためのサンプルスクリプトの場合、「map、filter」を使用したループが最適な方法です。各メソッドのコストの昇順は、「map、filter」、「Comprehension」、「forEach」、「for in」、「for loop」、「while」です。
> - 「forEach」、「Comprehension」、「map、filter」のコストは、「for in」、「for loop」、「while」のコストよりも低くなります。
> - push()と new Array()のコストはほぼ同じです。 -配列を 1 次元配列から 2 次元配列に変更すると、「Comprehension」、「forEach」、「map、filter」のコストの増加率は、「for in」、「forloop」のコストの増加率よりもはるかに低くなります。 "と" while "。
> - 「for ループ」を使用する従来の方法については、このレポートの結果を使用して新しい方法を提案できます。
> - 「reduce」の場合、1 次元配列と 2 次元配列の間のプロセスコストはほぼ同じです。

### [Google Apps Script 用の UrlFetch サービスの fetchAll メソッド](https://gist.github.com/tanaikech/c0f383034045ab63c19604139ecb0728)

> - fetchAll メソッドが非同期処理によって機能することがわかりました。 -非同期処理で機能した後、戻り値はリクエストの順序で並べ替えられます。 -複数の URL からデータを取得する場合、 `UrlFetchApp.fetchAll()`のプロセスコストは、for ループを使用する `UrlFetchApp.fetch()`のプロセスコストよりもはるかに低いことがわかりました。

### [Google Apps Script を使用して配列処理を検索](https://gist.github.com/tanaikech/eda9234822b5dec80549216a43c52652)

> - indexOf()による検索のプロセスコストは、すべてのメソッドの中で最低でした。
> - 2 番目と最後の 1 つは、それぞれ for ループによる検索とハッシュによる検索でした。 -ハッシュによる検索については、オブジェクトからのハッシュによる検索のコストは非常に低いですが、ハッシュを検索するためのオブジェクトを作成するためのコストはすべての中で最も高かったです。これにより、ハッシュによる検索が最低ランクになりました。検索対象が既に作成されている場合は、ハッシュによる検索のコストが最も低くなります。
> - indexOf を使用した検索は、線形検索およびハッシュを使用した検索から 99％以上のプロセスコストを削減できます。 -これらの結果から、indexOf()のスキャンは一般的な for ループとは異なる可能性があると考えられます。

### [Google Apps Script を使用した条件分岐](https://gist.github.com/tanaikech/cef47530a58f2d8692cdb1a9d257907b)

> - 「三項演算子」のコストは、すべての方法と条件の中で最も低いことがわかりました。 -単一の条件分岐の場合、2 番目は「If」でした。ただし、複数の条件分岐の場合、「スイッチ」は 2 番目の分岐でした。これは、「If」と「Switch」がそれぞれ単一および複数の条件付きブランチ(2 つ以上のブランチ)に適していることを示しています。 -複数の条件分岐の場合、「真」の可能性が高い条件を前面に出すことで、処理コストを削減できます。 -「論理演算子」は、単一および複数の条件分岐の最低ランクでした。「論理演算子」は、コストが高く、読みやすさが低いため、一般的な用途には適さないと考えられます。

### [Google Apps Script を使用した配列処理のループの減少](https://gist.github.com/tanaikech/fdd8462a46179efb156cfa0550695c6e)

> - 「逆配列を使用したフィルター」により、「for ループの減少」と比較してプロセスコストが 43％低くなります。 -「逆配列」は、作成されたサンプル配列の「Array.prototype.reverse()」を使用して取得されました。 -「for ループの減少」は「for ループの増加」とほぼ同じです。 -「reverse()」のコストは、「for ループ」と「フィルター」に対して十分に小さいです。

### [Google Apps Script を使用したスプレッドシートの読み取りと書き込み](https://gist.github.com/tanaikech/d102c9600ba12a162c667287d2f20fe4)

> このレポートでは、スプレッドシートの読み取りと書き込みのプロセスコストを調査しました。この調査から、以下の結果が得られました。

> - スプレッドシートから値を読み取るためのプロセスコスト
>
> 1. Spreadsheet Service の getValues()と getSheetValues()の処理コストはほぼ同じです。
> 1. SheetsAPI の values.get と values.batchGet のプロセスコストはほぼ同じです。
> 1. Sheets API のメソッドは、Spreadsheet Service のプロセスコストから約 35％のプロセスコストを削減できます。 -スプレッドシートから値を書き込むためのプロセスコスト
> 1. Sheets API の values.update、values.batchUpdate、values.append のプロセスコストはほぼ同じです。
> 1. Sheets API のメソッドは、Spreadsheet Service のプロセスコストから約 19％のプロセスコストを削減できます。
> 1. Spreadsheet Service の setValues()と SheetsAPI のメソッドの間には反転点があります。 -データサイズが小さい場合、setValues()は値の書き込みに適しています。 -データサイズが大きくなると、SheetsAPI のメソッドが値の書き込みに適しています。

> これらの結果から、Spreadsheet of Sheets API の読み取りと書き込みの方法は、Spreadsheet サービスの方法とは異なるアルゴリズムやプロセスを使用していると考えられます。

### [Google Apps Script を使用したスプレッドシートへの CSV データのインポート](https://gist.github.com/tanaikech/030203c695b308606041587e6da269e7)

> このレポートでは、GAS を使用して CSV データをスプレッドシートにインポートするためのプロセスコストを調査しました。その結果、以下の結果が得られました。

> - SheetsAPI の `pasteData`を使用する pattern4 が、すべての中で最も低コストであることがわかりました。
> - CSV データをスプレッドシートにインポートするために pattern4 を使用すると、値の解析と書き込みの方法を使用する pattern1 と pattern2 からコストを 56％削減できます。
> - CSV データをスプレッドシートにインポートするために pattern4 を使用すると、mimeType を CSV からスプレッドシートに変換するメソッドを使用する pattern3 からコストを 72％削減できます。

### [ベンチマーク：V8 で Google Apps Script を使用した配列処理のループ](https://gist.github.com/tanaikech/3331e1e631d619abef8f32c4be14ba3a)

> このレポートでは、GAS と V8 ランタイムを使用したアレイ処理の「ループ」のプロセスコストを調査しました。その結果、V8 を搭載した GAS の以下の重要な機能が見つかりました。

> - 配列から 5 の倍数を取得するためのサンプルスクリプトの場合、「for loop」、「while」、「forEach」、「map、filter」、「reduce」を使用したループコストはほぼ同じです。 -「forin」の場合、プロセスコストは「for loop」、「while」、「forEach」、「map、filter」、「reduce」よりも高くなります。しかし、それを V8 なしの条件と比較すると、V8 を使用した場合の「forin」のコストは、V8 を使用しない場合よりもはるかに低くなります。 -`push() `と`new Array()`のコストはほぼ同じです。 -ループプロセスに v8 ランタイムを使用する場合、V8 を使用しないスクリプトと比較すると、プロセスコストを大幅に削減できます。 -「forloop」、「for in」、「while」、「forEach」、「map、filter」、「reduce」のすべてのメソッドで、1D 配列の場合は 97.0％、2D 配列の場合は 98.4％のプロセスコストが発生する可能性があります。削減されます。

### [ベンチマーク：Google Apps Script を使用した V8 でのプロセスコスト](https://gist.github.com/tanaikech/7198bc9019202f4080de8fd2e1b278fb)

> このレポートでは、V8 での 7 つの状況のプロセスコストが測定されました。その結果、以下の結果が得られた。

> 1. 矢印機能がある場合とない場合のプロセスコストはほぼ同じでした。
> 2. プロセスコスト「includes」と「indexOf」はほぼ同じでした。
> 3. 破壊的割り当てを使用した場合、コストは破壊的割り当てを使用しない場合よりも約 15％高くなりました。
> 4. Map オブジェクトがある場合とない場合のプロセスコストはほぼ同じでした。 -しかし、この場合、結果をオブジェクトとして取得するために、 `Object.fromEntries`のコストが追加されます。また、 `Object.fromEntries`を使用しない場合、Map オブジェクトを使用した場合のコストは Map オブジェクトを使用しない場合よりも約 20％低くなりました。
> 5. `Array.prototype.push`のプロセスコストは、` Array.prototype.push.apply`、Spread 構文、および `concat`の中で最も低かった。Spread 構文と `concat`のコストは、` Array.prototype.push`よりもそれぞれ約 3,040％と 36,666％高かった。
> 6. `reduce`のみのプロセスコストは、` reduce`、 `Object.assign`、および Spread 構文のみの中で最も低かった。`Object.assign`と Spread 構文のコストは、` reduce`のみのコストよりもそれぞれ約 265％と 448,063％高かった。
> 7. `Array.from`とマップのみの処理コストはほぼ同じでした。`Object.entries`のコストは` Array.from`のコストよりも約 131％高かった。

### [ベンチマーク：Google Apps Script を使用してスプレッドシートで値を検索するためのプロセスコスト](https://gist.github.com/tanaikech/0a6f03970b471ffa286f1dac0b79359e)

> ここでは、Google Apps Script(GAS)を使用してスプレッドシートで値を検索するためのプロセスコストを報告したいと思います。Google スプレッドシートで値を検索すると、次の 3 つのパターンが考えられます。[参照](https://stackoverflow.com/a/56663884)
>
> 1. getValues を使用してすべての値を取得し、取得した配列から値を検索します。
> 2. TextFinder を使用します。
> 3. クエリ言語を使用します。
>
> これらの場合、最も低いプロセスコストはクエリ言語を使用することであることがすでにわかっています。そして、配列から値を見つけることについて、私はすでに「[ベンチマーク：Google Apps Script を使用した配列処理の検索](https://gist.github.com/tanaikech/eda9234822b5dec80549216a43c52652)」として報告されています。しかし、TextFinder のプロセスコストを要約して、配列から値を見つけることは一度もありませんでした。そこで、このレポートでは、これを紹介したいと思います。その結果、値を検索して行番号と行値を取得するための TextFinder の重要性を理解することができました。

### [ベンチマーク：Google Apps Script を使用してスプレッドシートの配列から値を取得するためのプロセスコスト](https://gist.github.com/tanaikech/6333d797149ab9d69382d1b368f96e80)

> ここでは、Google Apps Script(GAS)を使用してスプレッドシートの配列から値を取得するためのプロセスコストを報告します。Spreadsheet を GoogleApps Script で使用すると、次のような状況になります。

> 1. 列の複数の行から値を取得します。
> 2. 行の複数の列から値を取得します。

> 上記の状況から値を取得する場合、2 次元配列の 1 次元配列から値を取得する必要があります。このレポートでは、上記の状況の 2 次元配列から値を取得するためのプロセスコストが測定されています。

> その結果、1 列に n 行、1 行に n 列の配列から値を取得する場合、破壊代入を使用する場合とインデックスを使用する場合がそれぞれ適切であることがわかりました。

### [ベンチマーク：Google Apps Script を使用した Google スプレッドシート上のセル内の数式のプロセスコストの測定](https://gist.github.com/tanaikech/b00be25a02ec283689480ac8138cbfeb)

> Google スプレッドシートを使用する場合、セル内の組み込み関数とカスタム関数が使用される場合があります。Google Apps Script の機能には、プロセスコストを測定する方法があります。[参照](https://github.com/tanaikech/taking-advantage-of-google-apps-script#benchmarks)ただし、組み込み関数の場合は、そのスクリプトを作成する必要があります。このレポートでは、セルに配置された関数を測定するためのスクリプトを提案し、組み込み関数のプロセスコストを測定しました。提案されたスクリプトは、Google スプレッドシートの組み込み関数とカスタム関数のプロセスコストを測定できます。スクリプトは、Google AppsScript を使用して作成されます。組み込み関数とカスタム関数のプロセスコストがわかる場合、

### [ベンチマーク：Google Apps Script を使用して Google スプレッドシートの特定の列の最初の空のセルと最初の空でないセルを取得するためのプロセスコスト](https://gist.github.com/tanaikech/61cbda29436795f199a9e4244e0bf5fe)

> ここでは、Google Apps Script(GAS)を使用して、GoogleSpreadsheet の特定の列の最初の空のセルまたは最初の空でないセルを取得するためのプロセスコストを報告します。この場合、次の 2 つのパターンが考えられます。

> 1. シートの**TOP**から検索して、特定の列の最初の空のセルを取得します

> 2. シートの**BOTTOM**から検索して、特定の列の最初の非空のセルを取得します

> 実際、GAS を使用してアプリケーションを作成する場合、特定の列の最初の空のセルまたは最初の空でないセルを取得する必要がある場合があります。ただし、その場合は、アプリケーションの他の部分と比較して、このプロセスコストを可能な限り低くしたいと思います。このような経験から、この処理コストを削減できれば、他のユーザーにも役立つと思いました。そこで、このレポートでは、この状況のプロセスコストを紹介したいと思います。そして、以下の結果が得られた。

> - シートの**TOP **から検索して特定の列の最初の空のセルを取得するには、 `getNextDataCell`を使用するメソッドのプロセスコストがすべてのメソッドの中で最も低くなります。

> - シートの**BOTTOM **から検索して、特定の列の最初の非空のセルを取得するには、 `TextFinder`を使用するメソッドのプロセスコストがすべてのメソッドの中で最も低くなります。

### [ベンチマーク：フォームを使用した Google スプレッドシートへの同時書き込み](https://gist.github.com/tanaikech/c2f3fccabbf4906a18fdc38463982f31)

### [ベンチマーク： Google Apps Script を使用した HTML テンプレートの処理コスト](https://gist.github.com/tanaikech/f1436d88423077115d2c249862f12f17)

709 / 5,000
翻訳結果

> Google Apps Script プロジェクトで HTML を使用する場合、Google Apps Script 側からの値を表示するために、HTML テンプレートが使用されます。 大きな値の HTML テンプレートを使用したところ、スクリプトを工夫することでプロセスコストを削減できることがわかりました。 このレポートでは、ベンチマークを使用した HTML テンプレートのプロセスコストを紹介します。

> その結果、Google Apps Script で HTML テーブルを作成し、HTML テンプレートで HTML テーブルを表示すると、処理コストが低くなることが明らかになりました。 また、HTML テンプレートを使用するためのプロセスコストを削減するために、GoogleAppsScript 側で HTML データを準備する必要があることがわかりました。

### [ベンチマーク： Google Apps Script を使用して XML データを解析するためのプロセスコスト](https://gist.github.com/tanaikech/d09fb02c93635c53312aff58a047eb13)

> XML データから値を取得するために、Google Apps Script を使用して XML データを解析する場合、データを解析する方法はいくつかあります。 XML データを管理するための組み込みクラスであるクラス XmlService は、それを思い付く最初の方法かもしれません。 Stackoverflow では、XML データがクラス XmlService を使用して解析されることが多いという質問が投稿されています。 クラス XmlService は XML データの管理に適していると考えられています。

> しかし、以前に Google Apps Script で XML データを使用してアプリケーションを作成したことがあると、クラス XmlService のプロセスが高い可能性があると感じました。 そのため、このレポートでは、GoogleAppsScript を使用して XML データを解析するためのプロセスコストを示しています。 その結果、V8 ランタイムがリリースされた後、XML データを解析するためのクラス XmlService 以外のメソッドも使用できることがわかりました。

### [Benchmark: High-Efficiency Finding and Replacing Many Values in Google Spreadsheet with Low Process Cost using Google Apps Script](https://gist.github.com/tanaikech/6fc2f3ea6d09ce2906e7922c76c0b238)

> これは、Google Apps Script を使用して、Google スプレッドシートの多くの値を低処理コストで高効率に検索および置換するためのサンプル スクリプトです。

> Google Apps Script を使って Google スプレッドシートで各種値を置き換える場合、処理コストが気になります。 そこで本レポートでは、これを高効率で実現するためのサンプルスクリプトを紹介したいと思います。

> その結果、サンプルシチュエーションを用いて、Sheets API を利用したサンプルスクリプトとスプレッドシートサービス（SpreadsheetApp）を利用したサンプルスクリプトの処理コストを比較したところ、Sheets API を利用した上記スクリプトの方が処理コストを削減できることがわかりました。 スプレッドシート サービスを使用したスクリプトより約 70% 短縮されました。

### [Benchmark: Google Apps Script を使用して配列の値をチェックするための処理コスト](https://gist.github.com/tanaikech/b7df3cd77a933dba247670f5eda15e4b)

> Google Apps Script (GAS) には最大実行時間があります。 つまり6分です。 また、カスタム機能や簡易トリガーの場合は30秒です。 そのため、ユーザーはスクリプトの処理コストを削減することに常に注意を払う必要があります。 特に、配列処理はスプレッドシートや Google API などでよく使われるため、配列処理の処理コストを把握しておくことは非常に重要です。 配列処理については「ベンチマーク：V8でGoogle Apps Scriptを使った配列処理のループ」と「Google Apps Scriptを使った配列処理の検索」で報告済みです。 このレポートでは、Google Apps Script を使用して 1 次元配列の値をチェックするプロセス コストを調査しました。

### [ベンチマーク: Google Apps Script でオブジェクトを使用して値を検索するためのプロセス コスト](https://gist.github.com/tanaikech/e4fcca733a78f7211d80967ac4a35adb)

> 1 次元配列と 2 次元配列から値を検索する場合、V8 ランタイムが使用できるようになった後、JSON オブジェクト、Set オブジェクト、Map オブジェクトを使用します。 しかし、私はこの状況のプロセス コストを測定したことがありませんでした。 この投稿では、JSON オブジェクト、Set オブジェクト、および 1 次元配列と 2 次元配列から変換された Map オブジェクトを使用して値を検索する場合の処理コストを紹介します。

<br>

<a name="communities"> </a>

# コミュニティ

### [Google Apps Script のコミュニティ](https://gist.github.com/tanaikech/6b42d86414c5529fee56367d6bf67516)

> Google+のコンシューマー(パーソナル)バージョンは 2019 年 4 月 2 日に閉鎖されます。これにより、[Google+の Apps Script コミュニティ](https://plus.google.com/communities/102471985047225101769/)も閉鎖されます。これは、議論するための重要なコミュニティの 1 つです。そこで、この投稿では、Google AppsScript に関連する他のコミュニティを紹介したいと思います。

<br>

<a name="samplescripts"> </a>

# サンプルスクリプト

<a name="filesingoogledrive"> </a>

#### Google ドライブのファイル

- [Google Web Apps で doPost を使用してファイルをアップロード](https://tanaikech.github.io/2017/02/05/file-upload-using-dopost-on-google-web-apps/)
- [GAS を使用した Google ドライブ API のアクセストークンの取得](https://gist.github.com/tanaikech/64175178489d1d72a6090b79be901c23)
- [Google ドライブにフォルダツリーを作成](https://tanaikech.github.io/2017/03/13/create-folder-tree-on-google-drive/)
- [Google ドライブから許可なくファイルをダウンロード](https://tanaikech.github.io/2017/03/20/download-files-without-authorization-from-google-drive/)
- [ドライブ API の「フィールド」の使用方法](https://tanaikech.github.io/2017/03/30/how-to-use-fields-of-drive-apis/)
- [承認なしの Google ドライブのファイル転送](https://github.com/tanaikech/FileTransfer)
- [PDF を TXT に変換](https://gist.github.com/tanaikech/825f4b848a8cbff7018f71d33399e99b)
- [Google API のアクセストークンの取得](https://gist.github.com/tanaikech/247e4db66098e94f9e7da1b857f0a9be)
- [ブラウザを使用して許可なく Google ドライブからファイルをダウンロードする](https://gist.github.com/tanaikech/c5b2811bce01cbcc26ffa357df496379)
- [(NEW)Google ドライブから古いリビジョンファイルを取得する](https://gist.github.com/tanaikech/9ab6683e78de0044b4f670ff3761af19)
- [Google ドライブのフォルダの下にあるファイルリストを取得](https://gist.github.com/tanaikech/8e9b6fd667efcb483c9c742da9cd4e19)
- [Google Apps Script を使用して OneDrive からアクセストークンを取得する](https://gist.github.com/tanaikech/d9674f0ead7e3320c5e3184f5d1b05cc)
- [Google ドキュメントと Microsoft ドキュメント間の相互変換](https://gist.github.com/tanaikech/8d639542577a594f6104b7f6fb753064)
- [Google Apps Script を使用したファイル名に含まれる特殊文字を含むファイルの取得](https://gist.github.com/tanaikech/e74ead2537b7b3718fc824b6ca60a531)
- [Google Apps Script の選択ボックスを使用した Google ドライブ内のファイルの選択](https://gist.github.com/tanaikech/96166a32e7781fee22da9e498b2289d0)
- [HTML フォームを使用して許可なくローカルファイルを Google ドライブにアップロードする](https://gist.github.com/tanaikech/2f16f467c94612dc83920a3158614d95)
- [Google ドライブ上の PDF ファイルから最新の作成ファイルを取得する](https://gist.github.com/tanaikech/0f452b2f951dddb57363dbb816487c33)
- [Google ドキュメントのダイアログボックスのボタンを使用してファイルをダウンロードする](https://gist.github.com/tanaikech/0f1fd11b7e4d45b016d45bbeeb06aa46)
- [DriveApp.searchFiles()に使用される Drive API v2 または v3 はどれですか？](https://gist.github.com/tanaikech/242f644026837dd071f0ce95b2fd107a)
- [ファイルを分割することにより、大きなサイズ(> 50 MB)の CSV ファイルから複数のスプレッドシートへの再開可能な変換](https://gist.github.com/tanaikech/3e44c779f05374d19333444c9a4dd5ba)
- [Javascript を使用してファイルを Google ドライブにアップロード](https://gist.github.com/tanaikech/bd53b366aedef70e35a35f449c51eced)
- [Google Apps Script を使用した拡張 makeCopy()](https://gist.github.com/tanaikech/ac1b0d50fe1ffaa40e95bbe9faf908b9)
- [Google ドライブの特定のフォルダの下にあるフォルダ構造のファイルリストを取得しています](https://gist.github.com/tanaikech/4fca197b8ec45c8ac6300b1531c2489d)
- [Google Apps Script を使用してローカルから Google ドライブに複数のファイルをアップロードする](https://gist.github.com/tanaikech/88fcae255abb4aac5bec81ad5ca213ef)
- [Google Apps Script 用の tarUnarchiver](https://github.com/tanaikech/tarUnarchiver-for-Google-Apps-Script)
- [Google Apps Script を使用して多くのファイルを Google ドキュメントに変換する](https://gist.github.com/tanaikech/d60700b523af7aaf89b9e7c92e35c3c2)
- [Google Apps Script を使用して OCR で PDF および画像ファイルを変換して Google ドキュメントを作成する](https://gist.github.com/tanaikech/b73396314254f7a5bf571af6b65eac07)
- [Google Apps Script を使用して複数の Google ドキュメントを 2 つのテキストファイルで上書きする](https://gist.github.com/tanaikech/55f0a57ed98ff11e7d8780cc773b6dce)
- [Google Apps Script を使用した Google ドライブ上のファイルのリビジョンの変更](https://gist.github.com/tanaikech/9508a9007c1a5196e4b234ea40528f96)
- [Google ドライブのワンタイムダウンロード](https://github.com/tanaikech/One_Time_Download_for_Google_Drive)
- [Google ドライブの非同期プロセスを使用した複数のファイルの再開可能なアップロード](https://github.com/tanaikech/AsynchronousResumableUploadForGoogleDrive)
- [Google Apps Script を使用してファイルを特定のフォルダに移動する](https://gist.github.com/tanaikech/84dd9e9f79cad87bedb45e21342c0121)
- [HTML および GoogleApps Script を使用してファイルを Google ドライブにアップロードする](https://gist.github.com/tanaikech/280b782ee0518aa083a4fe0d71384823)
- [Google ドライブで親なしでファイルとフォルダを取得する](https://gist.github.com/tanaikech/459089e678bad943f0f33e497e04c36f)
- [Google Apps Script を使用して Google ドライブにショートカットを作成する](https://gist.github.com/tanaikech/4639cccc8130cea10d753fee9f900041)
- [Google Apps Script を使用したドライブ API のバッチリクエスト](https://github.com/tanaikech/Batch-Requests-for-Drive-API-using-Google-Apps-Script)
- [Google Apps Script を使用して SVG 形式を PNG 形式に変換する](https://gist.github.com/tanaikech/8a6d46ca43665aa7e62965ed32336598)
- [認証なしで外部 HTML から Google ドライブにファイルをアップロードする](https://gist.github.com/tanaikech/d3e62002e522f9e3f2b35bc56c64b2c9)
- [Google Apps Script を使用して HTML フォームから送信された値を使用する](https://gist.github.com/tanaikech/58d96c023468fc1922d67764251b25e0)
- [Google Apps Script を使用して 'is：unorganized owner：me'でファイルを検索する](https://gist.github.com/tanaikech/ec6aa9f2967d2f837df7c87276a0c168)
- [Google AppsScript を使用した外部サーバーでの HTML による Google ドライブの安全なアップロード](https://github.com/tanaikech/Safe-Uploading-for-Google-Drive-by-HTML-in-External-Server-using-Google-Apps-Script)
- [Google Apps Script を使用して特定のフォルダにある「共有アイテム」のファイルを取得する](https://gist.github.com/tanaikech/ddebdc6c32937cbe2a525991398f066c)
- [回避策: Google Apps ScriptのDriveApp.searchFiles()でcreatedDateを使用できない](https://gist.github.com/tanaikech/2b9d86a7db01f72e88090116cb5fee1f)
- [回避策: アクセス トークンと API キーを使用せずに Google ドライブ内のファイル ID の存在を確認する](https://gist.github.com/tanaikech/ef51e36e53c5e49d2a8dc3736e8a9386)
- [Google Apps Script を使用して Google ドライブから特定のフォルダを取得する](https://gist.github.com/tanaikech/5be73060a7941d73ce7179c6fa77206a)
- [Google Apps Script を使用してファイルの所有者を他のユーザーに譲渡する](https://gist.github.com/tanaikech/685929fd4e739c943ab0b4c53348a4af)
- [Google Apps Script を使用して Google ドライブの特定のフォルダにある合計ファイル サイズを取得する](https://gist.github.com/tanaikech/bbf37f05f5f5a98d346295f6e4aa3c48)
- [Google Apps Script と Javascript で jsTree を使用したフォルダ ピッカー](https://gist.github.com/tanaikech/10edba76a0273c71368b3699d5f64b62)
- [Google Apps Scriptを使用してGoogleドライブ上のファイルのファイル内容を比較する](https://gist.github.com/tanaikech/ed64668e23c155138baa300a31d7f16f)
- [Google Apps Script を使用して Google ドライブ内のファイルとフォルダを含むフォルダを移動する](https://gist.github.com/tanaikech/5e79afbc50be824e02c6ba138f905e5c)
- [Google Apps Script によるフォルダ構造の分析](https://gist.github.com/tanaikech/aa654883775702d02bc3e40fdc3af69e)
- [Google Apps Script を使用して Gemini に大きなファイルをアップロードする: 50 MB 制限を克服する](https://gist.github.com/tanaikech/ad5b87df2842ecd2f9864784ac6bbecb)
- [Google スプレッドシートで分割非同期プロセスと再開可能なアップロードを使用して複数のファイルをアップロードする](https://gist.github.com/tanaikech/42925de7efc497b5e8eb21f9dae6260d)

<a name="projects"> </a>

#### Projects

- [Google Apps Script を使用して ClientId を取得する](https://gist.github.com/tanaikech/4656b1b01128d27f291cee317553ea6d)
- [GAS プロジェクトのコピーと上書き](https://gist.github.com/tanaikech/3e7608bd8ba87dd6019aedbd09224bd3)
- [Google Apps Script を使用してアカウントアクセスでサードパーティのアプリを削除する](https://gist.github.com/tanaikech/608e65fee105989df1a7b645c20572c2)
- [Google Apps Script を使用したプロジェクトでコメントなしで再フォーマットされたスクリプトを取得する](https://gist.github.com/tanaikech/61f69fd2ce181865d3430c260c6a5d0b)
- [Google Apps Script を使用してプロジェクトを zip ファイルとしてバックアップ](https://gist.github.com/tanaikech/035aa9f6603e7a8698c1cc67ab43e132)
- [Google Apps Script を使用した Google Apps Script プロジェクトの全文検索](https://gist.github.com/tanaikech/d557d3e239189877e595ed622ce2cb88)
- [Google Apps Scriptの履歴管理](https://gist.github.com/tanaikech/2453685e8e6b272e357b1f5935ca6e53)

<a name="spreadsheets"> </a>

#### Spreadsheets

- [Google HTML サービスを使用してスプレッドシートから CSV ファイルをダウンロード](https://tanaikech.github.io/2017/02/16/download-a-csv-file-from-spreadsheet-using-google-html-service/)。
- [スプレッドシートから変換された Excel ファイルを使用して電子メールを送信](https://tanaikech.github.io/2017/02/16/send-e-mail-with-excel-file-converted-from-spreadsheet/)
- [スプレッドシートから CSV ファイルをエクスポートしてダウンロードボタンを作成](https://tanaikech.github.io/2017/02/20/export-csv-file-from-spreadsheet-and-make-download-button/)
- [ダウンロードした Excel ファイルをスプレッドシートとして作成](https://tanaikech.github.io/2017/04/14/creating-downloaded-excel-file-as-spreadsheet/)
- [Excel ファイルからスプレッドシートを作成する](https://tanaikech.github.io/2017/04/15/creating-spreadsheet-from-excel-file/)
- [スプレッドシートを PDF に変換](https://tanaikech.github.io/2017/04/20/converting-spreadsheet-to-pdf/)
- [スプレッドシートを既存の Excel ファイルに上書きする](https://tanaikech.github.io/2017/04/21/overwriting-spreadsheet-to-existing-excel-file/)
- [共有スプレッドシートを使用したユーザー情報の取得](https://gist.github.com/tanaikech/a4a23d66134a900ddcb1652a4d420a58)
- [スプレッドシートのカスタム関数を使用してセルにマップを埋め込む](https://gist.github.com/tanaikech/408f0eb58b18b08c4aa3783e5ee7463e)
- [スプレッドシートのセルにアニメーション GIF を埋め込む](https://gist.github.com/tanaikech/9b540220a9f408c05213c82e085c891a)
- [スプレッドシートのカスタム関数を使用してルートと埋め込みマップを検索](https://gist.github.com/tanaikech/e2d49b88b5d45cf2f26e6aaa14eafe91)
- [Google スプレッドシートを使用した疑似ブラウザ](https://gist.github.com/tanaikech/a290509e3d3f6997d248b88763fc69b9)
- [スプレッドシートでの画像の取得](https://gist.github.com/tanaikech/d6594dc5c6c49a015c7d408c90e58bdc)
- [Google Sheets API の a1Notation を GridRange に変換](https://gist.github.com/tanaikech/95c7cd650837f33a564babcaf013cae0)
- [スプレッドシートのヘッダータイトルによる値の取得](https://gist.github.com/tanaikech/3036ee0199e2261f377aacbd7e458d1c)
- [Google Apps Script を使用して範囲からスプレッドシート ID を取得する](https://gist.github.com/tanaikech/d4b033014c36c3506ad3ec38ce1eae4f)
- [Google Apps Script を使用して onEdit(e)を拡張](https://gist.github.com/tanaikech/73edaed1268a6d07118aed538aa5608d)
- [Google スプレッドシートの組み込み関数の実行時間の測定](https://gist.github.com/tanaikech/1e7df0d6991d4e39330cd2b353573e72)
- [ユーザーインターフェイス環境のインスタンスの取得](https://gist.github.com/tanaikech/f05e7d82b754b0348463b8dec1c741ad)
- [スプレッドシートパート 1 のカスタム関数の自動再計算](https://gist.github.com/tanaikech/b8ea7bd7fd87bcd7bb28ddede1781889)
- [Google Apps Script を使用して新しいウィンドウでサイトを開く](https://gist.github.com/tanaikech/9115c70eb83558d3af2eea656e4d9c67)
- [Google Sheets API を使用して行を挿入して値を追加](https://gist.github.com/tanaikech/7846ebcafbab8318ff74c9955a99e06b)
- [スプレッドシート内のすべての名前付き範囲を a1Notation として取得](https://gist.github.com/tanaikech/aa744c9a15​​818c002d90eaea6b4efd03)
- [Google Apps Script の CLEAN メソッド](https://gist.github.com/tanaikech/585597adda7954ba1cde3e724582bac5)
- [特定の行と列の最後を取得](https://gist.github.com/tanaikech/044d8651aed41c886f3379fdf5165aa2)
- [Google Apps Script を使用した A1Notations の解析](https://gist.github.com/tanaikech/c59b90324c90935b13f9e7b26cbf436a)
- [Google Apps Script を使用して既存のサイドバーを閉じる](https://gist.github.com/tanaikech/c1b5fb20342dae623139ca0f48c8c12c)
- [計算中にダイアログボックスを開き、Google Apps Script を使用して計算結果を取得する](https://gist.github.com/tanaikech/3a4837d4ef0d31522cd9ff29c085c786)
- [Google Apps Script を使用したワンタイムライティングセルの作成](https://gist.github.com/tanaikech/4ba859167a84ed625fcbab392c8d34cd)
- [Google ドキュメントへの画像挿入の制限](https://gist.github.com/tanaikech/9414d22de2ff30216269ca7be4bce462)
- [Google Apps Script を使用したスプレッドシート上のセル内のリアルタイムプロセスの可能性](https://gist.github.com/tanaikech/52e7bbdabf8bfc34ac16d5f27fd8cb80)
- [Google Apps Script を使用したスプレッドシートのカスタム関数による値付けの修正](https://gist.github.com/tanaikech/6ebf4bafbdc35116470bd197d00fe614)
- [ユーザーが GoogleApps スクリプトを使用して Google ドライブからユーザーの Google ドライブにコピーしたスプレッドシートのセルを保護する](https://gist.github.com/tanaikech/847ea7e3e27a4a22004faa88d7b4dedb)
- [Google Apps Script を使用してスプレッドシートのフィルター処理されたシートから値を取得する](https://gist.github.com/tanaikech/053d3ebbe76fa7c0b5e80ea9d6396011)
- [スプレッドシートパート 2 のカスタム関数の自動再計算](https://gist.github.com/tanaikech/cb5447616bfc6a01de8a49131c0d2db0)
- [Google Apps Script を使用してスプレッドシートでスライサーによってフィルタリングされたシートから値を取得する](https://gist.github.com/tanaikech/7cc9efb29ba6063da04f81e50d858f52)
- [Google Apps Script を使用して Google スプレッドシートのカスタムメニューを動的に更新する](https://gist.github.com/tanaikech/1232a8fd1ffbd84c96ebbb97051c5b59)
- [Google Apps Script を使用した Google スプレッドシートの列の再配置](https://gist.github.com/tanaikech/59dc1398785803d188393fb04673f1bc)
- [Google Apps Script を使用して Google スプレッドシートの 2 つの範囲の間でオーバーラップされたセルを取得する](https://gist.github.com/tanaikech/492cc2bb0b978fdb344aa821962baf53)
- [更新：Google Apps Script を使用した A1Notations の拡張](https://gist.github.com/tanaikech/4fd7d66771d552ed83166df314cb0024)
- [2PACX の URL からすべてのシートの直接リンクを取得するための回避策-Web で公開された Google スプレッドシートの###](https://gist.github.com/tanaikech/e6251657d425d2827fee6dd3daf47976)
- [Google Apps Script を使用した Google スプレッドシートの行と列の非表示と削除](https://gist.github.com/tanaikech/a1e6c0b49043cbf92f8b3c25d18ebeed)
- [Google Apps Script で onSelectionChange イベントトリガーを使用した Google スプレッドシートのタブ検出の変更](https://gist.github.com/tanaikech/524c16dbef722763f80312357d0e4368)
- [Web アプリをラッパーとして使用する Google スプレッドシートの拡張カスタム関数](https://github.com/tanaikech/Enhanced-Custom-Function-for-Google-Spreadsheet-using-Web-Apps-as-Wrapper)
- [Google Apps Script を使用して Google スプレッドシートに配置されたボタンを無効にする](https://gist.github.com/tanaikech/28102d28b929e102f6fe88e7d42e2d64)
- [Google Apps Script を使用して選択したセルの行と列を強調表示](https://gist.github.com/tanaikech/3e6b6bbc13cd9814aa918c9933fb862f)
- [回避策：Sheets API を使用してセルに複数のハイパーリンクを配置する](https://gist.github.com/tanaikech/b18c0189a5d0266a849090fdbe6750a5)
- [Google Apps Script で TextFinder を使用した検索ダイアログサンプル](https://gist.github.com/tanaikech/64ab751e8fd8727d23e5f159c00e1579)
- [Google Apps Script を使用して Google スプレッドシートのセル幅に収まるようにテキストの長さを調整する](https://gist.github.com/tanaikech/784bae8c41b7d9bcba5b581920dda3f4)
- [Google Apps Script を使用した Google スプレッドシートのボタンの切り替え](https://gist.github.com/tanaikech/2e6cadc1f65d42aa161bcbd24e6cadb7)
- [Google Apps Script を使用して Google スプレッドシートの範囲を画像として変換](https://gist.github.com/tanaikech/6ec4f2278510311ea06b838c69828692)
- [Google Apps Script を使用したカスタムヘッダーとフッターを使用したスプレッドシートの作成](https://gist.github.com/tanaikech/0430c7a8cf28508aa3cb80c22136f7f9)
- [Google Apps Script：Google スプレッドシートで特定のシートを編集したときに特定の機能を実行する](https://gist.github.com/tanaikech/bc09d1e03a0ebed3af894a6ed61cf12d)
- [Google Apps Script を使用した Google スプレッドシートの行の代替背景色の設定](https://gist.github.com/tanaikech/89aaa3adcd3a1fc37187ca61f389cbe9)
- [Google Apps Script を使用して背景色で Google スプレッドシートにセルを並べ替える](https://gist.github.com/tanaikech/8e531fdb4125c843b58cf7bef6165786)
- [Google Apps Script と Javascript を使用して Web で公開された Google スプレッドシートの 2PACX-の URL からすべてのシートからすべての値を取得する](https://gist.github.com/tanaikech/1876f19638e329253cf352225bd180cd)
- [Google Apps Script を使用して Google スプレッドシートに複数のボタンを作成する](https://gist.github.com/tanaikech/17d48dbcf4c1a39663424cae658e50cb)
- [ユーザーが GoogleApps Script を使用して所有者によって保護された範囲のスクリプトを実行する](https://gist.github.com/tanaikech/5ebf492b53de40fe254dba63c8520391)
- [ボタンをクリックして Google スプレッドシートを XLSX および PDF ファイルとしてダウンロード](https://gist.github.com/tanaikech/61dea338dfba386f87c592d4ee6c68af)
- [Google Apps Script を使用して Google スプレッドシートの複数の値を低いプロセスコストで置き換える](https://gist.github.com/tanaikech/3030603299d1e302821611c834420258)
- [ボタンをクリックして Google スプレッドシートのアクティブシートを CSV および PDF ファイルとしてダウンロード](https://gist.github.com/tanaikech/114dad7d31dde402b4892787e9cceaad)
- [Google Apps Script を使用したスプレッドシートの保護のコピー](https://gist.github.com/tanaikech/b22a76d419a6bdbfa064f5b31f6eae8e)
- [Google Apps Script を使用して Google スプレッドシートにカラフルなボタンを作成する](https://gist.github.com/tanaikech/5eedf04fa0f7727570b8e4c45b84a1f1)
- [Google Apps Script を使用した Google スプレッドシートのフィルタービューによる非表示の行の取得と行の表示](https://gist.github.com/tanaikech/43eee17899a3d0a99817f3a2032ae937)
- [Google Apps Script を使用した連続数値のコンパイル](https://gist.github.com/tanaikech/5a43281964b739ead2b7ae2401400630)
- [Google スプレッドシートで TextFinder を活用する](https://gist.github.com/tanaikech/39f719bd10ccbb27edd694c33242e496)
- [Google Apps Script を使用して Google スプレッドシートの値をオブジェクトに変換する](https://gist.github.com/tanaikech/39d6402846c21502d41ecc7f78708e71)
- [Google Apps Script を使用してシート A の値をシート B の値で更新する](https://gist.github.com/tanaikech/bd1e9de7cc22f89d3c8c7f90bf07e943)
- [スコープの承認とスクリプトの表示の両方を行わずにユーザーに GoogleSpreadsheet で GoogleApps Script を実行させる](https://gist.github.com/tanaikech/82089f55e9e647bbe965a563ab1ce657)
- [Google Apps Script を使用して範囲 ID を Google スプレッドシート上の範囲オブジェクトに変換する](https://gist.github.com/tanaikech/3aa69f1a8e2a944c7df926879fa0f34e)
- [Javascript と GoogleAppsScript を使用した「text / event-stream」のコンテンツタイプからのデータの取得](https://gist.github.com/tanaikech/2ba5f847ae6032d1611875d60cdf79b2)
- [Google Apps Script を使用したシンプルでインストール可能なトリガーを使用しない Google スプレッドシート用の疑似 OnEdit トリガー](https://gist.github.com/tanaikech/05d9922a947232dbda5143b6ac6dc71f)
- [Google Apps Script を使用して Google スプレッドシートのセルにチェックボックスがあるかどうかを確認する](https://gist.github.com/tanaikech/763ac2328d60805a3f971537e8b6e7c3)
- [Google AppsScript を使用して Google スプレッドシートで選択した範囲を反転する](https://gist.github.com/tanaikech/c08b9ea7a0f54b3e6074bba510e1efb4)
- [Google Apps Script を使用した所有者、特定のユーザー、匿名ユーザーによる GoogleSpreadsheet への操作の検出](https://gist.github.com/tanaikech/4c0067b5faec34e4c8a4b8d24a9350e5)
- [Google Apps Script を使って Google Spreadsheet のセルのフォーマットを維持しつつ CSV データをインポートする](https://gist.github.com/tanaikech/909863d8807c9143f4814aa270afe02e)
- [Google AppsScript を使用して Google スプレッドシートのセルに IMAGE 関数を使用して Google ドライブの非公開画像を挿入するための回避策](https://gist.github.com/tanaikech/80c1cd268c303edcbd5483211a1b9ea4)
- [GoogleApps スクリプトで無限ループを使用して Google スプレッドシートのセルでカウンター](https://gist.github.com/tanaikech/efffc9233aba43922aae6cc93329075d)
- [Google Apps Script を使用して、Google スプレッドシートで同じヘッダータイトルの列をマージする](https://gist.github.com/tanaikech/41e62d17ca48a5b2f3f57e5e06ea8da0)
- [Google Apps Script を使用して、Google スプレッドシートで同じヘッダータイトルの行をマージする](https://gist.github.com/tanaikech/89e8825f31f65621332634dcbe9cf503)
- [GoogleAppsScript を使用して列文字を 1 つずつ増やす](https://gist.github.com/tanaikech/13fc8683114c5ff62b8144c338a1d574)
- [GoogleAppsScript を使用したスプレッドシート API のリクエスト数](https://gist.github.com/tanaikech/dad5df2403b551f6bdd99221be115bef)
- [GoogleAppsScript を使用して Google スプレッドシートの行を拡張する](https://gist.github.com/tanaikech/d5d96ce34846110d67f82147b396b2b7)
- [Google Workspace Update ブログから XML データを取得して解析し、Google Apps Script を使用して Google スプレッドシートに配置する](https://gist.github.com/tanaikech/0ba501fecdfd1ac9b0f6997b370586b4)
- [Google Apps Script を使用したテキストデータ内のテキスト位置の取得](https://gist.github.com/tanaikech/77fbac03f26e1c1688f54130a683f8c0)
- [Parsing JSON Data Array by Expanding Header Row using Google Apps Script](https://gist.github.com/tanaikech/d905b75175bd297733f807e7bddd33d4)
- [Google Apps Script を使用して Google スプレッドシートのセルの値を置き換える](https://gist.github.com/tanaikech/cedc350cf36865b7a84e260c78762db9)
- [IMPORTXML を使用した GoogleAppsScript での XML データの解析](https://gist.github.com/tanaikech/f4e6091c1de4873695783471e410f07a)
- [Google Apps Script を使用してチェックボックスをクリックしてスプレッドシートのセルを保護する](https://gist.github.com/tanaikech/1da4d8e8ebb2cdc62e6c42c6e71f14d7)
- [スコープなしで Google Apps Script を使用して A1Notation を GridRange に、またはその逆に変換する](https://gist.github.com/tanaikech/457b5545a48890ed6dce66d67324ec47)
- [Google Apps Script を使用して Google スプレッドシートから#REF の無効な名前付き範囲を削除する](https://gist.github.com/tanaikech/f9b993c4a178291324e03eeb5c161c1d)
- [Google Apps Script で GOOGLEFINANCE を使用して為替レートを確認する](https://gist.github.com/tanaikech/67e0cd1f5ba4946aa050963a0720ed5f)
- [Google Apps Script で作成した Web アプリを使用して、名前とパスワードを入力してユーザーのダッシュボードを作成する](https://gist.github.com/tanaikech/ac2537711bfcf19348b66b454da33196)
- [Google Apps Script を使用して複数のシートの個別のセル値をクリアする](https://gist.github.com/tanaikech/6b1ce61475e35416ce0e728a7fd3018c)
- [Google スプレッドシートのカスタム関数で RichTextValues を使用する](https://gist.github.com/tanaikech/1d63fcd5152688da68e9974167ca744f)
- [Google Apps Script を使用した Google スプレッドシートでのセル移動の検出](https://gist.github.com/tanaikech/5939e3de5e24ce389beade94158bdb7d)
- [Google Apps Script を使用して Google スプレッドシートのソース シートごとに宛先シートを更新する](https://gist.github.com/tanaikech/9970ebf1bd3c7475df57126f5d544f89)
- [Google Apps Script を使用して Google スプレッドシートで引用符付きのセルを検出する](https://gist.github.com/tanaikech/a17d291c9d3da8fbce0d100139d3c872)
- [Google Apps Script を使用して Google スプレッドシートに特定の行と列を表示する](https://gist.github.com/tanaikech/7573fe1aa0bd4fb3d0a1ff9740496ccc)
- [Google Apps Script を使用して 引用符プレフィックス (一重引用符) を使用してセルのセル座標を取得する](https://gist.github.com/tanaikech/89fb802a5ac04bc627c9b6f77476edd9)
- [Google Apps Script を使用して Google スプレッドシートから名前付き関数を取得する](https://gist.github.com/tanaikech/9a9e571ed662e35eec0aa747bb4e025a)
- [Google Apps Script を使用して Array1 を Array2 で更新する](https://gist.github.com/tanaikech/fb7149425069ad1138f36162698385df)
- [Google Apps Script と Node.js で Sheets API を使用してセルに複数のハイパーリンクを配置する](https://gist.github.com/tanaikech/4c27bf8d1948a5dfa5b0e53ce88c6d30)
- [回避策: サービスアカウントでSheets APIを使用し Googleスプレッドシートを編集したことを検出する](https://gist.github.com/tanaikech/5388797761cb92cf1fe325e939c10b25)
- [Google Apps Script を使用した Google スプレッドシートのディメンション グループのコピーと削除](https://gist.github.com/tanaikech/bb50f2e188327afd616bd2678ab0b40f)
- [Google Apps Script を使用した Google スプレッドシートの列の並べ替え](https://gist.github.com/tanaikech/5ca3ed56c36cb7b947e14d5b1dbab6a2)
- [Google Apps スクリプトを他のユーザーから非表示にして OnEdit トリガーを Google スプレッドシートに使用する](https://gist.github.com/tanaikech/848fea29875d5034a2347a5a16306215)
- [サービス アカウントで作成した Google スプレッドシートで OnEdit トリガーを使用](https://gist.github.com/tanaikech/58891b5caaf49ebfdb5f8dde4637d8e6)
- [回避策: Google Apps Script を使用して数値のセルからハイパーリンクを取得する](https://gist.github.com/tanaikech/82a74e64abcacabd51be8ff92c73691a)
- [Google Apps Script を使用して、フォルダ内のすべてのスプレッドシートの値を低いプロセス コストでマスター スプレッドシートに入れる](https://gist.github.com/tanaikech/e65100d2f13c9c6903e1a6c86184d663)
- [Google Apps Scriptを使用してGoogleスプレッドシートの列で同じ値の開始および終了の行番号を取得](https://gist.github.com/tanaikech/eca18c3ccff32065dbe60d5385dd51ab)
- [Google Apps Script を使用したセル値の引用符のプレフィックスの削除 (単一引用符)](https://gist.github.com/tanaikech/ec156204f3a2d96873dce5f6ba4674d6)
- [Google Apps Script でカスタム関数を使用して Microsoft Excel を Google スプレッドシートにインポートする](https://gist.github.com/tanaikech/742c9f8baf488503a66582b985b9d4e5)
- [Google Apps Script を使用した Google スプレッドシートのリッチ テキスト管理の強化](https://gist.github.com/tanaikech/8082e2bb265d2ad4bd61f9d418504811)
- [Google Apps Script を使用して TOTP を Google スプレッドシートに入れる](https://gist.github.com/tanaikech/4de7448903389e0884e2a21cd27abc86)
- [回避策: Google Apps Script を使用して、コピーした Google スプレッドシートに OnEdit トリガーを自動的にインストールする](https://gist.github.com/tanaikech/76bab12742174976d87e2473ae7975f8)
- [Google Apps Script を使用してスプレッドシートのセルに画像を挿入する](https://gist.github.com/tanaikech/c18715b68a81a8492a13140d9cd3bb6f)
- [Google Apps Script を使用した Google スプレッドシートのピボット解除](https://gist.github.com/tanaikech/05e5fd84561080e484bd4df799862f01)
- [Google Apps Script を使用して Google スプレッドシートを HTML テーブルに変換する](https://gist.github.com/tanaikech/61932a6acfe02e53ce9d5bca9078c536)
- [Google Apps Script を使用した Google スプレッドシート上の A1Notation の相対参照から絶対参照への変換、およびその逆の変換](https://gist.github.com/tanaikech/d9ae71d8736e168e47c56adb203b7e87)
- [Google Apps Script を使用してコンテナ バインド スクリプトを削除して Google スプレッドシートをコピーする](https://gist.github.com/tanaikech/d5f7b0ddd8c8746c4dff67040a436c5f)
- [Google Apps Scriptを使用してGoogleスプレッドシートの基本フィルタを自動更新](https://gist.github.com/tanaikech/03308f87b6c9568dd277e43eb646a75e)
- [Google Apps Scriptを使用したGoogleスプレッドシート上のセルの重なりをチェック](https://gist.github.com/tanaikech/b56e12dd1f2f15997b113b4738cf7f8b)
- [ベンチマーク: Google Apps Scriptを使用してGoogleスプレッドシート上の条件による行を効率的に削除する](https://gist.github.com/tanaikech/ef8969755f4a00275be7e8fc93dfc00e)
- [Google Apps Script を使用して Google スプレッドシートで選択したセルを左上にフォーカスする](https://gist.github.com/tanaikech/9f613d6fec34892dc211f30644e0a5ea)
- [Google Apps Scriptを使用してタイムゾーンが異なるGoogleスプレッドシート間で日付オブジェクトをコピー](https://gist.github.com/tanaikech/fd525434b51b8b0df3293c0067f071ca)
- [回避策: Google Apps Script で OnEdit トリガーを使用して IMPORTRANGE の変更を検出する](https://gist.github.com/tanaikech/0cf57b2684c2ac2c2562b1ec229c9ace)
- [Google Apps Scriptを使用したGoogleスプレッドシート上のダイアログによる共有ユーザーによるスコープの承認なしのファイルのアップロード](https://gist.github.com/tanaikech/dbcf9ba8674b898ee61baf5c33825a0b)
- [結合セルを含むGoogleスプレッドシートをGoogle Apps Scriptで処理するテクニック](https://gist.github.com/tanaikech/a03b0bb4218a19b41d507a5b649e3802)
- [Google Apps Scriptを使ったGoogleスプレッドシート上のカスタム関数の配列処理のテクニック](https://gist.github.com/tanaikech/e3f0bf29aad48d6e2e4ca096269e5a9d)
- [回避策: ユーザーが Google Apps Script を使用して保護されたセルを編集できるようにする](https://gist.github.com/tanaikech/a36770c4609fdb73ed1b8ed43c0612fd)
- [Google Apps Scriptを使用してGoogleスプレッドシート上のリッチテキストを管理するテクニック](https://gist.github.com/tanaikech/f3aa85e41287e329353ec062e8b64483)
- [Google Apps Scriptを使用したGoogleスプレッドシートへのIMPORTHTML、IMPORTDATA、IMPORTFEED、IMPORTXML、IMPORTRANGEによるアクセスを許可する](https://gist.github.com/tanaikech/627d86bdea4028c301431443f82f0ac1)
- [Google Apps Scriptを使用してGoogleスプレッドシートを保護するテクニック](https://gist.github.com/tanaikech/3f207ffee7bf64fa79c99118e2979e55)
- [Google Apps Scriptを使用してGoogleスプレッドシートから別のGoogleスプレッドシートにグラフを含むシートをコピー](https://gist.github.com/tanaikech/63f59cee0f2c0c8f24e418ca6b3f868b)
- [Google Apps Scriptを使用してGoogleスプレッドシートの特定の列に値を追加するテクニック](https://gist.github.com/tanaikech/434bef051c136bc87e724b033a478bd2)
- [Google Apps Script を使用して Google スプレッドシートの色付きセル領域を識別する](https://gist.github.com/tanaikech/15198f6c6872385b4ed6e85498b82733)
- [Google Apps Script を使用して、Google スプレッドシート上の散在する A1Notations を連続範囲に統合する](https://gist.github.com/tanaikech/1241411538d5b4d90e23a8c5f30d0ea6)
- [Google Apps Script を使用して Google スプレッドシートのセルにアニメーション GIF を挿入](https://gist.github.com/tanaikech/fe3a0fd36ee47685b07ce6db2fbae1ce)
- [スプレッドシート管理の簡素化: Google Apps Script 自動化の導入](https://gist.github.com/tanaikech/ccfa7da120aae62e33b2b11ea7eafa42)
- [Google Apps Script の新しい JavaScript メソッドを使用して、シートの行を Google スプレッドシートの複数のシートに配置する](https://gist.github.com/tanaikech/641d9ff0989951b98eaeca10559932d8)
- [回避策: Google Apps Script で Google スプレッドシートのテーブルを使用する](https://gist.github.com/tanaikech/2e6b1fa2d8f16464dffba070376c458d)
- [Google Apps Script を使用して Google スプレッドシートの表を PDF としてエクスポートする](https://gist.github.com/tanaikech/599f47550bd694a7264e24cea795b9bc)
- [Google スプレッドシートのスライドパズル](https://gist.github.com/tanaikech/d9a76ea9fad4eb49fcd5b02c677ac293)
- [Google Apps Script を使用して Google スプレッドシートのテーブルを管理する](https://gist.github.com/tanaikech/fe567e1f397dc4a8d88212f91e779dbd)
- [Sheets API を使用して Google スプレッドシートでスマートチップを管理する](https://gist.github.com/tanaikech/682d77c3e3fb4aade4e816801a26ca21)

<a name="documents"> </a>

#### Documents

- [Google ドキュメントの行数を取得しています](https://gist.github.com/tanaikech/37def8eeeaf7780bb99d3289ee32385e)
- [Google Apps Script を使用して Google ドキュメントのテキストを画像に置き換える](https://gist.github.com/tanaikech/f84831455dea5c394e48caaee0058b26)
- [Google Apps Script を使用して Google ドキュメントの段落の陰影の色を変更する](https://gist.github.com/tanaikech/aadeca550943d07ee25d90d3bda3c9b9)
- [Google Apps Script を使用して検索テキストを小文字に変更](https://gist.github.com/tanaikech/30e8c778eb1102f651550b2345b6f3c0)
- [Google Apps Script を使用して Google ドキュメント上の配置された画像を削除する](https://gist.github.com/tanaikech/02c4c4ec7cb0ac83771e4306afcd422c)
- [Google ドキュメントへの画像挿入の制限](https://gist.github.com/tanaikech/9414d22de2ff30216269ca7be4bce462)
- [Google Apps Script を使用して Google ドキュメントの全ページを取得する](https://gist.github.com/tanaikech/c78087c647dc9b5547b580ccd3629974)
- [Google Apps Script を使用した Google ドキュメントのページの削除](https://gist.github.com/tanaikech/6d33c3ce00cd46e45d3551a587b2ae17)
- [Google AppsScript で GoogleDocs API を使用して新しいテーブルを作成し、セルに値を設定する](https://gist.github.com/tanaikech/3b5ac06747c8771f70afd3496278b04b)
- [Google Apps Script を使用して Google ドキュメントの最後の空のページを削除する](https://gist.github.com/tanaikech/8e018892ebb417779e9a7fedfc6a4a7d)
- [Google スプレッドシートの更新された仕様：セルへの複数のハイパーリンク](https://gist.github.com/tanaikech/d39b4b5ccc5a1d50f5b8b75febd807a6)
- [Google Apps Script を使用した Google ドキュメントの 1 ページ目のヘッダーの変更](https://gist.github.com/tanaikech/d430543089cc687e5d9c2bc96d3178ff)
- [Google Apps Script を使用して Google ドキュメント内のすべての URL を取得する](https://gist.github.com/tanaikech/d3ce0c2186885ee27d23e02ddd2696b7)
- [Google Apps Script を使用して選択したテキストのフォントを Google ドキュメントの「GoogleSans」に変更する](https://gist.github.com/tanaikech/4700361cc060ae4333672da905d272c7)
- [Google アプリのスクリプトを使用して Google ドキュメントのテンプレートテキストを配列に置き換える](https://gist.github.com/tanaikech/7fc15c4e8ecccbedd469d8d778880834)
- [Google Apps Script を使用して Google ドキュメントのリストアイテムからグリフ値を取得する](https://gist.github.com/tanaikech/5f186b006c4803790318a75e65900c36)
- [Google Apps Script を使用した Google ドキュメントの疑似 OnEdit トリガー](https://gist.github.com/tanaikech/f27d427f07b20ca9fedec21e643c4a3e)
- [レポート：Google Docs API を使用して複数の段落を Google ドキュメントに順番に挿入](https://gist.github.com/tanaikech/6aa646691f6c2224202fa6fb756e3862)
- [GoogleAppsScript を使用して Google ドキュメントの概要を取得する](https://gist.github.com/tanaikech/b61ec85a5f0fb4f5a9157fb9f7bd0e84)
- [Google Apps Script を使用して、Google ドキュメントの複数の段落を正規表現に置き換える](https://gist.github.com/tanaikech/f32f878c6cc005bbbdec2d9c635fae7b)
- [Google Apps Script を使用した Google ドキュメントのスマートチップのドロップダウンリストの値の取得](https://gist.github.com/tanaikech/37a8498ecb392e8b23041ce238287e27)
- [Google Apps Script を使用して Google ドキュメントの画像を順番に置き換える](https://gist.github.com/tanaikech/1f3407674aafcba906a3528e7ec3463d)
- [Google Apps Script を使用して Google ドキュメントの同じ位置を更新する](https://gist.github.com/tanaikech/36a2a9d393f42274a833e5660bfe4ce0)
- [Google Apps Script を使用した OCR による大きな画像の Google ドキュメントへの変換](https://gist.github.com/tanaikech/d4efe1c07b99807f63fe7d5c058c0628)
- [Google Apps Script を使用して Google ドキュメントのテーブルの垂直方向の境界線を削除する](https://gist.github.com/tanaikech/811c4f6965346b95b3c507e1feb83177)
- [Google Apps Script を使用して Google ドキュメントでスマート チップのカレンダー イベントの値を取得する](https://gist.github.com/tanaikech/a130a87830ffbde46f160401787e1dff)
- [Google Apps Script を使用して Google ドキュメントの段落の行間を設定する](https://gist.github.com/tanaikech/ea68371c1f212d316a8713946e9d8385)
- [Google Apps Script を使用して Google ドキュメントにチェックボックスを含む段落を挿入する](https://gist.github.com/tanaikech/dec8cf3755e3c2cf294655c605fd6840)
- [回避策: 画像ハイパーリンクを含む HTML として Google ドキュメントをエクスポートする](https://gist.github.com/tanaikech/e6bbb3bf341d7ac021f3bcfa523c4ca3)
- [Google Apps Script を使用した Google ドキュメントの脚注の管理](https://gist.github.com/tanaikech/cd7bf2ca7b9109e081bd64ec50db54fc)
- [Google Apps Script を使用して Google ドキュメントのソフト ブレークをハード ブレークに変換する](https://gist.github.com/tanaikech/7de3ed734ac9b103631c3a20452dca74)
- [Google Docs APIを使用してGoogleドキュメント上にネストされたリストを作成するテクニック](https://gist.github.com/tanaikech/c3d409c44579a9c23382e20400f51d4c)
- [Google Apps Script を使用して Google Document を Markdown に変換したり、その逆を行ったりする](https://gist.github.com/tanaikech/0deba74c2003d997f67fb2b04dedb1d0)
- [パワーを解き放つ: Apps Script のドキュメント サービスを超えて Google Docs API を活用する](https://gist.github.com/tanaikech/c53f3280642119c3b187234c03e2adb0)
- [回避策: Google Apps Script を使用して、Web に公開された Google ドキュメントを PDF としてエクスポートする](https://gist.github.com/tanaikech/2f91c211cc6332c84db7b4697ccc4cb6)
- [Google Apps Script を使用して Google ドキュメントの箇条書きのグリフの色を変更するテクニック](https://gist.github.com/tanaikech/37f64e848cb8bafa4beb639bca6e0a41)
- [Google Apps Script を使用して Google ドキュメントの見出しからツリー構造を作成する](https://gist.github.com/tanaikech/0779fec840d06cbc545d07cb0209bd3d)
- [Google ドキュメントで引用符をスマート引用符に変換する自動化](https://gist.github.com/tanaikech/80a69b4a5bbd0420c525681088dc30bf)

<a name="slides"> </a>

#### Slides

- [Google Apps Script を使用して Google スライドのテーブルのサイズを取得する](https://gist.github.com/tanaikech/3143be7e7df8cc595d73427d22ae2e0e)
- [サムネイルとしてのスライドの要約](https://gist.github.com/tanaikech/79749b9fc411da91f932608b5c01ea5b)
- [Google ドキュメントへの画像挿入の制限](https://gist.github.com/tanaikech/9414d22de2ff30216269ca7be4bce462)
- [Google Apps Script を使用した Google スライド上のテキストの管理](https://gist.github.com/tanaikech/04e7b7657f97ddd7c68b6a9ddc3cdf98)
- [Google Apps Script を使用して Google スライドで画像を切り抜く](https://gist.github.com/tanaikech/a86781b425fe3f14edd5058ca8d46fe7)
- [Google Apps Script を使用して Google スライドの QR コードからデータを取得する](https://gist.github.com/tanaikech/4fc0b33493d375e589d61312d2f028b7)
- [Google Apps Script を使用した Shape へのスライドページリンクの追加](https://gist.github.com/tanaikech/444379309f1d0f69287c5a8becdc271d)
- [Google Apps Script を使用して Google スライドのカスタムグリッドビューを画像およびスプレッドシートとして作成する](https://gist.github.com/tanaikech/c94b79819167e96f6d9268d066989112)
- [Google AppsScript を使用して Google スライドと Web アプリによって作成されたシンプルなフォトギャラリー](https://github.com/tanaikech/SimplePhotoGalleryUsingGoogleAppsScript)
- [Google Apps Script を使用して Google スライドのテキストボックスのテキストを編集するだけ](https://gist.github.com/tanaikech/aa0a03ba3c440ca72fc1d7e02f038f7c)
- [Google Apps Script を使用して Google スプレッドシートから Google スライドに挿入されたテーブルのテーブルの高さを減らす](https://gist.github.com/tanaikech/659f3687f4ea5282f39ebf9b6d5ae54c)
- [Google Apps Script を使用して Google スライドから取得したすべてのサムネイル画像を Zip ファイルとしてエクスポート](https://gist.github.com/tanaikech/66a83c01e1f99829a85f909f8facb834)
- [Google Apps Scriptを使用してGoogleスライド上の表の行の高さと列の幅を管理する](https://gist.github.com/tanaikech/f24abc8e19f525fd4078bdb9762f431b)
- [Google Apps Script を使用した Google スライドの強化されたテキスト操作](https://gist.github.com/tanaikech/c7f8adb32d595b9e27b6a43f0910569e)

<a name="gmail"> </a>

#### Gmail

- [Gmail の返信メールを取得する方法](https://gist.github.com/tanaikech/a047e5f67f30b93482986039daa16dbc)
- [Gmail のメッセージ ID を使用してメッセージにラベルを追加する](https://gist.github.com/tanaikech/69c7daf910fdad0d6a296ea19f612089)
- [Google Apps Script を使用して絵文字を含むタイトルと本文を含む Gmail を送信する](https://gist.github.com/tanaikech/187863d97d2b5e60938d8316574a2850)
- [Google AppsScript を使用した GmailAPI でバッチリクエストを使用して複数のメールを送信する](https://gist.github.com/tanaikech/44e055214ab470c9b3143a469d7a7d21)
- [Google Apps Script を使用した Gmail メッセージの画像への変換](https://gist.github.com/tanaikech/12a61cb7e4516acc95ecf15287b3f0f3)
- [Google Apps Script を使用して Gmail フィルタで Gmail メッセージを検索する](https://gist.github.com/tanaikech/bc8788c65afeba42ec2e560bfa5eb8b2)
- [Gemini Pro API と Google Apps Script を使用した Gmail の柔軟なラベル付け](https://gist.github.com/tanaikech/cdfa63b670b223e482e457703b9cdeb6)

<a name="calendar"> </a>

#### Calendar

- [Google カレンダーからのイベント通知による GoogleApps Script の実行](https://gist.github.com/tanaikech/fbbfaa8f2a8a770424974aa16b9b6f3b)
- [Google Apps Script を使用して Google カレンダーのイベント URL からイベント ID を取得する](https://gist.github.com/tanaikech/b366be5995be04f689c3d80b18363f5e)
- [Google Apps Script でバッチリクエストを使用して多数の Google カレンダーイベントを管理する](https://github.com/tanaikech/Managing-A-Lot-Of-Google-Calendar-Events-using-Batch-Requests-with-Google-Apps-Script)
- [さまざまな言語を使用して GoogleMeet で新しいイベントを作成するためのサンプルスクリプト Google カレンダーへのリンク](https://gist.github.com/tanaikech/94791d48823e9659aa376cf7f0161d9b)

<a name="form"> </a>

#### Form

- [Google Apps Script を使用して Google フォームに回答を直接送信する](https://gist.github.com/tanaikech/b4a31a51cbb0ef84c871e6fb96e1502e)
- [Google Apps Script を使用して Google フォームから Google スプレッドシートにすべての回答値を入力する](https://gist.github.com/tanaikech/42ac2d72f62f2107b965f53239c2f398)
- [Google AppsScript での GoogleForms API の使用](https://gist.github.com/tanaikech/bac38226e863a398f55b5c3d817d86ed)
- [GoogleAppsScript で GoogleFormsAPI を使用して GoogleForm でクイズを作成する](https://gist.github.com/tanaikech/eebcb2d71eed1aab5decff64287bcc9a)
- [GoogleAppsScript で Google フォームサービスを使用して Google フォームでクイズを作成する](https://gist.github.com/tanaikech/3e131b55c7947ced19a3dd99410367eb)
- [GoogleAppsScript を使用した Google フォームのグリッドアイテムからの応答の分析](https://gist.github.com/tanaikech/97c3cfd5c6e393de6a16ff6465300e4d)
- [Google Apps Script を使用して時間通りに Google フォームを開閉する](https://gist.github.com/tanaikech/84bd91f2927d8c8463b494f712eb1800)

<a name="youtube"> </a>

#### YouTube

- [Google Apps Script を使用して Google ドライブ上のムービーファイルを YouTube にアップロードする](https://gist.github.com/tanaikech/dc62aeb9a363513d6d27baf119ecfc2d)
- [Google Apps Script を使用して YouTube のビデオ URL からチャンネルの subscriberCount を取得する](https://gist.github.com/tanaikech/e3b4ac87437a3f358e0577c5854e00a6)
- [YouTube API を使用した再開可能なアップロードで YouTube にビデオ ファイルをアップロードする Curl コマンド](https://gist.github.com/tanaikech/5f3ce2d002e1b8e5916821ecc1dacbdc)
- [Google Apps Script を使用した再開可能なアップロードで Google ドライブの動画ファイルを YouTube にアップロード](https://gist.github.com/tanaikech/e41b1a674f0c3912aa7c29aac28a57cd)

<a name="chart"> </a>

#### Chart

- [スプレッドシートでグラフを作成する](https://tanaikech.github.io/2017/02/13/making-charts-at-spreadsheet/)
- [スプレッドシートのカスタム関数を使用してセルにグラフを埋め込む](https://gist.github.com/tanaikech/52da88484851ce2e0dea9881bf49f6fa)
- [GAS を使用したコンボチャートのバーへのラインの変更](https://gist.github.com/tanaikech/bff89176cd269e392c45500274b40810)
- [Google Apps Script を使用してスプレッドシートの埋め込みグラフに vAxis のタイトルを追加する](https://gist.github.com/tanaikech/4125cc280e15c0fc726cb2fe4f35a3f7)

<a name="analytics"> </a>

#### Analytics

- [Google Apps Script を使用して GoogleAnalytics からユーザー概要レポートのユーザー、セッション、PageView を取得する](https://gist.github.com/tanaikech/dc3e9c8dfec9403ed0b1935605ea1476)

<a name="slack"> </a>

#### Slack

- [Google Apps Script を使用した Slack ステータスの変更](https://tanaikech.github.io/2017/05/09/changing-slack-status-using-google-apps-script/)
- [Google Apps Script による着信 Webhook を使用した Slack への画像ファイルのアップロード](https://gist.github.com/tanaikech/159cec05583c6f206e144f33b4042559)
- [Google Apps Script による Slack のダイアログボックスの使用](https://gist.github.com/tanaikech/c111f5560d21a07529e0da870af06a7d)

<a name="virtualcurrency"> </a>

#### 仮想通貨

- [Google AppsScript 用の BitfinexAPI](https://gist.github.com/tanaikech/1104d039341f198f95eee66af57c0abf)
- [Google AppsScript 用の BinanceAPI](https://gist.github.com/tanaikech/175067567819577fd8eba9b82eabd1a6)
- [Google AppsScript 用の BittrexAPI](https://gist.github.com/tanaikech/07fb768cf6d8256b3a72716a72e99f91)
- [Zaif API for Google Apps Script](https://gist.github.com/tanaikech/77481c2621dc7429449194c0f1dbd58c)
- [Google AppsScript 用 CryptopiaAPI](https://gist.github.com/tanaikech/58f092a544eb1cfbb19bc0252f36e4cb)

<a name="stackoverflow"> </a>

#### Stackoverflow

- [Google Apps Script を使用したメールによる Stackoverflow でのコメントの通知](https://github.com/tanaikech/Notifying-Comments-at-Stackoverflow-by-Email)

<a name="netatmo"> </a>

#### Netatmo

- [Netatmo がダウンしたときにメールで通知](https://github.com/tanaikech/Notifying-with-email-when-Netatmo-was-down)

<a name="figma"> </a>

#### Figma

- [Google Apps Script を使用した Figma から Google スライドへ](https://gist.github.com/tanaikech/6aeb3ff13765cfba465862e2e2c3dd3b)

<a name="microsoft"> </a>

#### Microsoft

この場合、Microsoft の API とリソースは Google AppsScript で使用されます。

- [OnedriveApp](https://github.com/tanaikech/OnedriveApp)：これは MicrosoftOneDrive を使用するための GoogleAppsScript のライブラリです。
- [Google Apps Script を使用して Microsoft アカウントのすべてのメールのリストを取得する](https://gist.github.com/tanaikech/45a5511cf2a4a42660b52b3409f7b537)
- [Google Apps Script で Microsoft アカウントを使用して Outlook メールを送信する](https://gist.github.com/tanaikech/0745889227e43c385d190385fff91598)

<a name="etc"> </a>

#### その他

- [Google ドライブ API を使用した OCR](https://gist.github.com/tanaikech/8c808bf8c060455fe5401ecacad07b94)
- [Google Apps Script を使用したマルチパート POST リクエスト](https://gist.github.com/tanaikech/d595d30a592979bbf0c692d1193d260c)
- [JSON for Javascript の重複値をチェックして値を変更する](https://gist.github.com/tanaikech/4c659fbb7cf8df0bc2c063dafa10e36c)
- [Google Apps Script を使用した 2 次元配列の要素の矯正](https://gist.github.com/tanaikech/6a8b169cdcbda5a84f19964b81e447d9)
- [Google Apps Script のバッチリクエスト](https://gist.github.com/tanaikech/f167b9280a8e710804e4061571b53fb9)
- [Google Apps Script を使用した JSON オブジェクトの変換](https://gist.github.com/tanaikech/806fe728f8cf964078ef1354307a433d)
- [Google Apps Script を使用して 2 次元配列の違いを取得する](https://gist.github.com/tanaikech/2abf57eefc667d6c71310db6aa95a44d)
- [更新された Utilities.computeHmacSignature()について](https://gist.github.com/tanaikech/9e9ab42ad225e127c59ae8ae598aacac)
- [オブジェクトから最大値のキーを取得する](https://gist.github.com/tanaikech/fcbc0204e92d8f1cdde74dc5ac820753)
- [Google Apps Script を使用して URL にクエリパラメータを追加する](https://gist.github.com/tanaikech/70503e0ea6998083fcb05c6d2a857107)
- [Google Apps Script を使用したサイトのスクリーンショットの取得](https://gist.github.com/tanaikech/a434b4ed50d91fe5f56fffcf6bcb3f78)
- [Google Apps Script を使用したサービスアカウントのアクセストークンの取得](https://gist.github.com/tanaikech/20ea127a8e23a7c609f8d764c8b7ed7c)
- [Google Apps Script を使用して URL からクエリパラメータを解析する](https://gist.github.com/tanaikech/34437522f3ce777bd060458b9cc02bdf)
- [Google Apps Script を使用して配列を n 個の要素で分割](https://gist.github.com/tanaikech/c1fd2b4bce19597abc609b72818c1d8e)
- [Google Apps Script を使用した 2 次元配列の重複行の処理](https://gist.github.com/tanaikech/5c2d6187c08b2d7b2f7a561de0c75c5e)
- [Google Apps Script を使用して JSON オブジェクトから複製する場合としない場合の値を取得する](https://gist.github.com/tanaikech/16ba2c77cdc8caa6a02958c9a4006e8a)
- [Google Apps Script を使用した HTML の解析](https://gist.github.com/tanaikech/e85193a89d041fed6122583739309786)
- [Google Apps Script の署名バージョン 4(AWS)の署名キーを取得する方法の例](https://gist.github.com/tanaikech/97a2787db7be94180a64e1f4c194d415)
- [Google Apps Script 用の Web アプリで関数名を指定して関数を実行する](https://gist.github.com/tanaikech/b2e0325a28efe7c609e4688ec22ee22c)
- [Google Apps Script を使用した Shift-JIS による URL エンコード](https://gist.github.com/tanaikech/f23755d7e024fea9c0f0e036853484d4)
- [Google Apps Script を使用して 2 つのアレイの違いを取得する](https://gist.github.com/tanaikech/cc7bdfe67c3b72c48c290fc11c231e72)
- [さまざまな言語で Web アプリにリクエストするためのサンプルスクリプト](https://gist.github.com/tanaikech/a72aab0242012362c46ec69031c720d5)
- [Google Apps Script 用の Web アプリにログイン](https://gist.github.com/tanaikech/3ccb4dd8ce43de21fdb764a68c14a4d7)
- [回避策：Javascript を使用してログイン Web アプリを Apps Script Dashboard に表示する](https://gist.github.com/tanaikech/e27581278f8cb464dff1dd83d6f887a7)
- [重要：Google Apps Script の v8 ランタイムがある場合とない場合の reduceRight](https://gist.github.com/tanaikech/7f13f4297d7307a47ad78f0254ce3353)
- [Google Apps Script を使用して画像にテキストを挿入](https://gist.github.com/tanaikech/835642df109731a559e52d831bd3342d)
- [Google AppsScript を使用した SimpleRequestBody を使用した multipart / form-data のリクエスト](https://gist.github.com/tanaikech/5cd0dc9ea7d75e4a2ff65049ed3d78c3)
- [Google Apps Script を使用してテキストを太字、斜体、太字-斜体の Unicode に変換する](https://gist.github.com/tanaikech/39797ccd1b9280f967fe62b3328d782a)
- [Google Apps Script によって作成された Web アプリを使用する Xpath テスター](https://gist.github.com/tanaikech/8a596d235205ba443452aeb510220477)
- [Google Apps Script を使用して画像にポイントをプロット](https://gist.github.com/tanaikech/fbb16f1eb43b3bafa93323461a500640)
- [Google Apps Script を使用してアルファチャネルで PNG 画像を作成する](https://github.com/tanaikech/Creating-PNG-Image-with-Alpha-Channel-using-Google-Apps-Script)
- [Google Apps Script を使用して特定の時間に分タイマーで関数を実行する](https://gist.github.com/tanaikech/6608e901272077cbc3738366ec5fe0b3)
- [Google Apps Script を使用した文字列から 16 進数への変換、16 進数からバイトへの変換、バイトから文字列への変換](https://gist.github.com/tanaikech/707b2cd2705f665a11b1ceb2febae91e)
- [ggsrun を簡単な設定で使用する方法](https://gist.github.com/tanaikech/695f7016b04e4c4156ad928e9482ead9)
- [Google Apps Script を使用して HTML をプレーンテキストに変換する](https://gist.github.com/tanaikech/2779ee59a199011e3f48a1fa92879a68)
- [Google Apps Script を使用して画像データサイズを縮小する](https://gist.github.com/tanaikech/14c863e225162ec86894d604709d8b35)
- [Google Apps Script を使用して n 個の長さごとに配列を分割して処理する](https://gist.github.com/tanaikech/9e6276edb67d0ebde80ea378b6f79e20)
- [Google Apps Script を使用した GateAPIv4 へのリクエスト](https://gist.github.com/tanaikech/d0ea117b1c0e54cf713a8027f6b2fb08)
- [Google Apps Script を使用した Tabulator データの Google ドライブへのエクスポート](https://gist.github.com/tanaikech/b0d83cd2f0a27f9cd778f3a1f167503e)
- [Google Apps Script で FirebaseDynamicLinks API を使用して長い URL を短縮する](https://gist.github.com/tanaikech/e439cbaadf363380fe026b380dd4de42)
- [Google Apps Script を使用して月と曜日の名前を取得する](https://gist.github.com/tanaikech/be6ef51a402aacb9fa24277dffed63bc)
- [Google Apps Script を使用して Google ドライブの各 mimeType のアイコンを取得する](https://gist.github.com/tanaikech/1c0bd1e88b67f19b77d79c9f631b001d)
- [Google Apps Script を使用したCookieを保持てHTTPリクエストを行う (SessionFetch)](https://gist.github.com/tanaikech/6202470a2bb4d22d1b195bb20bf8390c)
- [Google Apps Script を使用したエラー時にUrlFetchAppを再試行する (RetryFetch)](https://gist.github.com/tanaikech/ff431dacecc9af58d5e3c1b2aee53d5a)
- [Google Apps Script を使用したバッチ リクエストのバッチパスの取得](https://gist.github.com/tanaikech/a970943f91c0dd0955d1722743e560df)
- [Google Apps Script でPeople APIのgetBatchGet, batchCreateContacts, batchDeleteContacts, batchUpdateContactsを使用するサンプルスクリプト](https://gist.github.com/tanaikech/70e08b966e2f8095462dffa5760100c9)
- [回避策: Google Apps Script で作成したデプロイ済み Web アプリに再デプロイせずに最新のスクリプトを反映する](https://gist.github.com/tanaikech/e46def22cf106b012dfa5ad359b93d24)
- [Google Apps Script で crypto-js を使用した AES による暗号化と復号化](https://gist.github.com/tanaikech/1038c73f028b7595f4e070a0e7d48ff1)
- [Google Apps Script を使用して finance.yahoo.com の Salted Base64 を復号化](https://gist.github.com/tanaikech/2c13c70e932e84adcf658ca8334f25ab)
- [Google Apps Script を使用した JSON オブジェクトのフィルタリング](https://gist.github.com/tanaikech/d80131e89ed5025bbd40fe19b9e43beb)
- [Google Apps Script と Javascript を使用して年の月初と月末を取得する](https://gist.github.com/tanaikech/1153792b17ce29ae86c865e53c999375)
- [Google Apps Script を使用して複数の PDF ファイルを 1 つの PDF ファイルとしてマージする](https://gist.github.com/tanaikech/449ff906b85be18977e47e0d5ea173d5)
- [Google Apps Script を使用して PDF ファイル内のすべてのページを PNG 画像に変換する](https://gist.github.com/tanaikech/94ff0713a7bfe2d3e43afbfe54611190)
- [Google Apps Script を使用して U+00A0 を Unicode として U+0020 に置き換える](https://gist.github.com/tanaikech/cc470a3b6c49b32e06d908e6d3f96f66)
- [2023 年 1 月 27 日: Google Apps Script を使用して、finance.yahoo.com の Salted Base64 を復号化](https://gist.github.com/tanaikech/2b1c008d7f8e873cc738d75c7fefaf71)
- [2023 年 2 月 15 日: Google Apps Script を使用して、finance.yahoo.com の Salted Base64 を復号化](https://gist.github.com/tanaikech/84213e047bc64b50deb7295758e0d971)
- [google.script.run での Type File の入力タブ付き HTML フォームの問題](https://gist.github.com/tanaikech/9590b01e4d363d724c458b5cbc87d041)
- [Google Apps Script を使用したバッチ リクエストで Google Docs ファイルを PDF 形式でエクスポートする](https://gist.github.com/tanaikech/d65d9608e6dd108a0fed31604e7556e7)
- [Google Apps Script を使用してバイナリ データを検索データで分割](https://gist.github.com/tanaikech/1d406d997090888cfacdb8e9d295ba34)
- [Google Apps Script で SheetJS を使用して XLSX データから値を直接取得する](https://gist.github.com/tanaikech/7647ac0d4faa8fffb78ff2324be8435c)
- [回避策: Google Slide をクリックしてアニメーション GIF を開始する](https://gist.github.com/tanaikech/3a34928e74009f9c26a40c121de76d6a)
- [Google Apps Scriptを使用してGoogle Apps ScriptおよびGoogle APIのリリースノートをRSSから取得する](https://gist.github.com/tanaikech/fc54bb2c640e3c7ee8b168a7aa1431a8)
- [Google Apps Scriptを使用したGoogle APIおよびGoogle Apps Scriptの新規リリースをメールで通知](https://gist.github.com/tanaikech/79a40abcc70ca3f57db5b4a739bfa849)
- [Google Apps Scriptを使用してさまざまな形式の画像をPNG形式とJPEG形式に変換する](https://gist.github.com/tanaikech/7ef9536ff3f788238509d9c366ed9aed)
- [Google Apps Scriptを使用してPDFから特定のページを新しいPDFとしてエクスポート](https://gist.github.com/tanaikech/9d77f7d634d2d31914396d7dc84b79c3)
- [Google Apps Scriptを使用したPDFメタデータの管理Google Apps Scriptを使用したPDFメタデータの管理](https://gist.github.com/tanaikech/9ee06b508624e252dd0e32efc348a59a)
- [Google Apps Scriptを使用してPDFファイルのページ順序を変更する](https://gist.github.com/tanaikech/9de62573049e72b44a069fc31348524b)
- [Google Apps Script を使用した PDF フォームへの値の取得と設定](https://gist.github.com/tanaikech/a8a387614410b8c6c2c1addbce4dd23c)
- [Google Apps Script を使用して Google スライド テンプレートから PDF フォームを作成する](https://gist.github.com/tanaikech/682dec95002f8cc25f1c5f2349966b8c)
- [Google Apps Script を使用した PDF へのオブジェクトの埋め込み](https://gist.github.com/tanaikech/b085cb08d573afa2294e2a8f887cdbd2)
- [Google Apps Script 上で PDF をクッキング](https://gist.github.com/tanaikech/42ad6a83322364d0b99ad11260862f04)
- [Google Apps Script を使用して Google スプレッドシートからエクスポートされた PDF にヘッダーとフッターを追加](https://gist.github.com/tanaikech/1aac9139666963cb9268082763494218)
- [サービスアカウントでGoogle Apps Scriptを実行する](https://gist.github.com/tanaikech/304fea821ca36b8e9ccebe9814eaed82)
- [Google Apps Scriptで作成したWebアプリにJavaScriptを含むHTMLを挿入する](https://gist.github.com/tanaikech/a5b5b5646b97934578fbb22ee503e6aa)
- [Google Apps Script を使用して Google ドキュメント、Google スライド、Google スプレッドシートから絵文字リアクション付きコメントを取得](https://gist.github.com/tanaikech/7713944094af5643fcf13b8d362d0c68)
- [Gemini Pro API と Google Apps Script を使用して Google ドライブ上のファイルの説明を自動作成する](https://gist.github.com/tanaikech/87dcf5a2ab90bbef983a140ec79f7396)
- [JSDocでGoogle Apps Scriptのクラスオブジェクトを返す](https://gist.github.com/tanaikech/a42e060d0c049d981ea7a4a5e9da3892)
- [Microsoft Docs ファイル (Word、Excel、PowerPoint) を Google Apps Script のドキュメント サービス、スプレッドシート サービス、スライド サービスで使用する](https://gist.github.com/tanaikech/288b56aa47f4270f3b96d1421ea3eb36)
- [Google Apps Script を使用して連絡先 URL を People API のリソース名に変換](https://gist.github.com/tanaikech/41e71610f03617e131183faac5cf9ad7)
- [Google Apps Script を使用して誰もがさまざまな Google API を活用できるようにする](https://gist.github.com/tanaikech/88c180fa4bb35b74b73203f754db2d3c)
- [Google Apps Script を使用して PDF にページ番号を追加する](https://gist.github.com/tanaikech/05834ac8e605922637af9a4cfdecc152)
- [Google Apps Scriptを使用した高度なGoogleサービスで有効なAPIの確認](https://gist.github.com/tanaikech/3f03dac24179f750c013abc39703c4d2)
- [Google Apps Script のスクリプト エディターでの HTML および Javascript 開発の強化: 書式設定の課題の克服](https://gist.github.com/tanaikech/be52daa21ccf07873ad2a2e43e566676)
- [Google Apps Script の Web アプリ ログの可視性](https://gist.github.com/tanaikech/20a015b8112dad53253a508c4d8675fd)
- [MimeTypeApp: Google Apps Script を使用した柔軟な MimeType コンバーター](https://gist.github.com/tanaikech/9742675d8f2e971e4c6b7fe1d34b254a)
- [回避策: Google Apps Script を使用したスマートチップ](https://gist.github.com/tanaikech/d41f696a9931e5c931bff4eb5627f854)

<a name="nodejs"> </a>

#### Node.js

- [Node.js を使用して特定のフォルダーの下にファイルをダウンロードする](https://gist.github.com/tanaikech/38b536923b1765da052c21aab093649d)
- [Nodemailer を使用して Gmail からメールを送信する](https://gist.github.com/tanaikech/d225c7adab818a6dc1dfd7783f8c8e4d)
- [Node.js を使用して Google ドライブのフォルダツリーを作成](https://gist.github.com/tanaikech/97b336f04c739ae0181a606eab3dff42)
- [Node.js 用の googleapis によるアクセストークンを直接使用する](https://gist.github.com/tanaikech/ca11c53356c5466e60109f79d9e4d9c9)
- [googleapis を使用せずに Node.js を使用してテキストで新しい Google ドキュメントを作成し、既存の Google ドキュメントを上書きする](https://gist.github.com/tanaikech/915f1034749b8b2f451556167663ea19)
- [googleapis を使用せずに Node.js のサービスアカウントを使用してアクセストークンを取得する](https://gist.github.com/tanaikech/7aaf2276e4e6104b89802e85957e75ae)
- [Node.js の Google スプレッドシートから値を取得して Google ドキュメントにテーブルを作成する](https://gist.github.com/tanaikech/e64342de7011228f5fb639d7d1123ebb)
- [Node.js を使用した Google ドライブとの不和のための音楽ストリーミングプレーヤー](https://gist.github.com/tanaikech/6029cb2422dd58fe24c3a16a43ce7c35)
- [Node.js 用の Google ドライブ API を使用した再開可能なアップロードの簡単なスクリプト](https://gist.github.com/tanaikech/ae451679e8220f3b2d48edb3f8c1a8d3)
- [Node.js でドライブ API を使用して multipart / form-data のファイルを Google ドライブにアップロードする](https://gist.github.com/tanaikech/33563b6754e5054f3a5832667100fe91)
- [Node.js を使用して Web で公開された Google スプレッドシートの 2PACX-の URL からすべてのシートからすべての値を取得する](https://gist.github.com/tanaikech/49e1e6515225d810e849b3487142a90d)
- [Node.js を使用してストリームと再開可能なアップロードでファイルを保存せずにファイルをダウンロードして Google ドライブにアップロード](https://gist.github.com/tanaikech/99187753ceb5fd55d343b52dcbe176a5)
- [Axios 用の Google ドライブ API を使用した再開可能なアップロードの簡単なスクリプト](https://gist.github.com/tanaikech/0e33b7a850e8c56d111ed0f32df0b485)
- [Node.js で Axios を使用した Google Drive への再開可能なアップロードのサンプルスクリプト](https://gist.github.com/tanaikech/5212f2a8127e1c0a70c8642e298ae661)
- [Node.js で Calendar API を使用したバッチ リクエストによる Google カレンダーでの複数のイベントの作成と削除](https://gist.github.com/tanaikech/33544a8f56cb5b4c2f96ceb29d6b2855)
- [Google Apps Script と Node.js で Sheets API を使用してセルに複数のハイパーリンクを配置する](https://gist.github.com/tanaikech/4c27bf8d1948a5dfa5b0e53ce88c6d30)
- [Node.js でファイルをアップロードするための多目的なアプローチ: Gemini、Drive、YouTube、その他の API の統合](https://gist.github.com/tanaikech/7340cc7c87ec0f701dfb2f0351e02031)

<a name="golang"> </a>

#### Golang

- [Golang を使用した spreadsheets.values.batchUpdate](https://gist.github.com/tanaikech/0f5b15fec7f409cdb568b0c2904fccb2)
- [スプレッドシートとして CSV ファイルをアップロードし、Golang を使用して権限を変更する](https://gist.github.com/tanaikech/7ee103c80759a8297da198a5d1e92fc8)
- [文字列値を使用して Golang の[] googleapi.Field](https://gist.github.com/tanaikech/27d27a1ac7fa99503e0737c28db53056)
- [Golang 用の Google の OAuth2 パッケージによるサービスアカウントを使用したアクセストークンの取得](https://gist.github.com/tanaikech/4b4cb27ece27573b3f4df0e050b52330)
- [Golang を使用したスライスの並べ替え](https://gist.github.com/tanaikech/4d0075dc21b643245be03d661e8d5f54)
- [Golang の Google スプレッドシートから値を取得して Google ドキュメントにテーブルを作成する](https://gist.github.com/tanaikech/0589a673cae9569181def8ccd10793cf)
- [Golang を使用した Google ドライブへのファイルのアップロードの再開](https://gist.github.com/tanaikech/19655a8130bac1ba510b29c9c44bbd97)
- [Golang を使用した SheetsAPI の batchUpdate を使用した Google スプレッドシートのセルの数値形式の設定](https://gist.github.com/tanaikech/76cde17cecba38f44398c3effe2aedf2)
- [golang の googleapis を使用した GoogleAPI の文字列 JSON のリクエスト本文の使用](https://gist.github.com/tanaikech/3f1c8e9f40e78263ec1ade2cb9461dcc)

<a name="python"> </a>

#### Python

- [Python を使用して Google ドライブ上のファイルのサムネイルを更新する](https://gist.github.com/tanaikech/731c412c271828276bf3e24a25235aab)
- [クイックスタートなしで Python によってローカルから Google ドライブにファイルをアップロードする](https://gist.github.com/tanaikech/8cdfd23807372657dc63d81e25e35153)
- [Python 用 Google スプレッドシートから値を取得して Google ドキュメントにテーブルを作成する](https://gist.github.com/tanaikech/305e413696bcdf3a2ee3e86cebf3c7dc)
- [Python 用 Google ドライブ API を使用した再開可能なアップロードの簡単なスクリプト](https://gist.github.com/tanaikech/f709a952ff6e286027950d0484f6c03e)
- [Python を使用して Web で公開された Google スプレッドシートの 2PACX-の URL からすべてのシートからすべての値を取得する](https://gist.github.com/tanaikech/51628e5e0a2c017329457afdb1936912)
- [Python で DocsAPI を使用して Google ドキュメントのテンプレートテキストを配列に置き換える](https://gist.github.com/tanaikech/f1f9fb91d3432362670c810ae05ba53b)
- [Python を使用した非同期プロセスでの Google ドライブへのファイルのアップロード](https://gist.github.com/tanaikech/a4cfbea4935b8c281d1f6abb91016705)
- [Python で oauth2client と google-auth を使用してサービス アカウントからアクセス トークンを取得する](https://gist.github.com/tanaikech/5196ed237812192539c4369000bc131b)
- [googleapisで取得したアクセストークンの有効期限までPythonで利用する](https://gist.github.com/tanaikech/b2d877e4e4d274b17876191d48204882)
- [PythonでDrive APIを利用してGoogleドライブからファイルを再開可能でダウンロードする](https://gist.github.com/tanaikech/dfdad37859d591526b2fba8fb4390cf5)

<a name="curl"> </a>

#### Curl

- [ドライブ API を使用した curl のファイル変換によるファイルのアップロードとダウンロード](https://tanaikech.github.io/2017/02/08/file-upload-and-download-with-file-convert-for-curl-using-drive-api/)
- [Curl を使用して Google ドライブに共有ファイルをダウンロードする](https://gist.github.com/tanaikech/f0f2d122e05bf5f971611258c22c110f)
- [ドライブ API を使用して再開可能なアップロードでファイルを更新する](https://gist.github.com/tanaikech/bc33a83ac648911d00b43c59a24268fc)

<a name="javascript"> </a>

#### Javascript

- [axios を使用して Google フォトに画像ファイルをアップロードする](https://gist.github.com/tanaikech/426345c24e46da3ac7268f31b76bb3e4)
- [Javascript を使用したサービスアカウントのアクセストークンの取得](https://gist.github.com/tanaikech/3c7f208cb352a807b3d30b9c1dcf0c82)
- [サービスアカウントで JavaScript に GoogleAPI クライアントライブラリ(gapi)を使用する](https://gist.github.com/tanaikech/603102a64587cb9bff2e165994f6b6a1)
- [Javascript で API キーを使用して、公開されている Google スプレッドシートから値を取得する](https://gist.github.com/tanaikech/aeb1a21e1e51a902f903e6363cd1a5db)

<a name="php"> </a>

#### PHP

- [googleapis を使用せずに PHP のサービスアカウントを使用してアクセストークンを取得する](https://gist.github.com/tanaikech/1b47cfec588454963ee40c5a50943194)

<a name="generativeai"></a>

#### 生成AI

- [Gemini Pro API と Google Apps Script を使用して Google ドライブ上のファイルの説明を自動作成する](https://gist.github.com/tanaikech/87dcf5a2ab90bbef983a140ec79f7396)
- [Gemini Pro API と Google Apps Script を使用した Gmail の柔軟なラベル付け](https://gist.github.com/tanaikech/cdfa63b670b223e482e457703b9cdeb6)
- [Google Apps Script で Gemini Pro API を使用した Google Apps Script のエラー メッセージの拡張](https://gist.github.com/tanaikech/b86db4d574474cbb079b185271f679ce)
- [Gemini Pro API と Google Apps Script を使用して生成されたテキストを Google ドキュメント、Google スプレッドシート、Google スライドに挿入する](https://gist.github.com/tanaikech/f1a6042c62e207d22eb5a38140d8484e)
- [Gemini Pro API と Google Apps Script を使用したセマンティック検索](https://gist.github.com/tanaikech/c6556dc08ae3dcb013d8909c1f42b16d)
- [Gemini Pro API と Google Apps Script を使用した分類](https://gist.github.com/tanaikech/28061e3d5404b4fba23368bbae4611d2)
- [Gemini Pro API と Google Apps Script を使用した Gmail の柔軟なラベル付けパート 2](https://gist.github.com/tanaikech/811e5c92cf96e8b387ffa9f29da08ec3)
- [Google Apps ScriptでGemini APIのコーパスを使用したセマンティック検索](https://gist.github.com/tanaikech/02415a0056099229525f894ae59dacb5)
- [Google Apps Script を使用して Gemini Pro API を柔軟なテンプレートに適用する](https://gist.github.com/tanaikech/ad5bd7eee50c2b9f05995d56679610f7)
- [Gemini と Google Apps Script を使用した関数呼び出しガイド](https://gist.github.com/tanaikech/061cca4b9af67abe8c4244c03750ea30)
- [Google Apps Script で Gemini を使用した画像ボットの作成](https://gist.github.com/tanaikech/cf29216cf4b1c127d9213db6079894c7)
- [Gemini API と Google スプレッドシートおよび Google Apps Script を使用した類似性ビューアー](https://gist.github.com/tanaikech/6a7afe7b145170265ee3cb2d6cb4be58)
- [Gemini API を使用した拡張検索](https://gist.github.com/tanaikech/70c28ddff49e8a0cf474f7f48d996b8a)
- [Gemini API と Google Apps Script を使用したリバース エンジニアリングの試み](https://gist.github.com/tanaikech/b0cab68b99137de21339d717d8ea1b25)
- [Gemini API を使用したオーダーメイドの出力形式の作成](https://gist.github.com/tanaikech/3a659a87673e3e582c880934c8f19e01)
- [Gemini 1.5 API によってアップロードされたファイルを使用したテキストの生成](https://gist.github.com/tanaikech/0ad317503e3a066d715430e7e875abfb)
- [Gemini 1.5 APIを使用したStackoverflowの質問からGoogle Apps Scriptの傾向を分析](https://gist.github.com/tanaikech/8621c3b799685fd2db1204d1372e1d73)
- [Gemini 1.5 API と Google Apps Script を使用した請求書の解析](https://gist.github.com/tanaikech/165a6a76244a81312f9d398e88c4730d)
- [Google Apps Script を使用した Gemini API の出力タイプの指定](https://gist.github.com/tanaikech/f7e627a286058229aeaaed776743564d)
- [バッチ処理の強力なハウス: Gemini 1.5 API と Google Apps Script を活用して効率的なコンテンツ ワークフローを実現](https://gist.github.com/tanaikech/f3dbba02a620cfd7a729e13b012ea66f)
- [野生の出力を飼いならす: response_mime_type を使用した Gemini API 応答形式の効果的な制御](https://gist.github.com/tanaikech/0a55011d3e8b8fadebb71b624bb9a8af)
- [JSON スキーマを使用した Gemini API](https://gist.github.com/tanaikech/45b1a738b9e27236545a3cbcc1479a58)
- [Google Apps Script リバース エンジニアリングでの自動テスト ケース生成のための Gemini 1.5 API の活用](https://gist.github.com/tanaikech/fc51414e16faa2a26aa39eea487d64a5)
- [野生の出力を飼いならす: response_schema を使用した Gemini API 応答形式の効果的な制御](https://gist.github.com/tanaikech/c99089b7b82562bfc5bf5c4bd8306c07)
- [Gemini 1.5 Flash を使用した Google Apps Script のエラー メッセージの拡張](https://gist.github.com/tanaikech/d068afd87fb990fbe0f38c192306a139)
- [スマート請求書管理のロックを解除: Gemini、Gmail、Google Apps Script の統合](https://gist.github.com/tanaikech/9c8fca16c2de5ee943f39adbd67c34db)
- [Google Apps Script を使用して Gemini に大きなファイルをアップロードする: 50 MB 制限を克服する](https://gist.github.com/tanaikech/ad5b87df2842ecd2f9864784ac6bbecb)
- [Gemini API: 直接 PDF 入力によるコンテンツ生成の革命](https://gist.github.com/tanaikech/b932e8b52b098c600c160988e48a5cd6)
- [学習への新しいアプローチ: Gemini と Google Apps Script を組み合わせて Q&A を自動化](https://gist.github.com/tanaikech/5b472baa500ced516a85e2a24628a03d)
- [Gemini API を使用したシームレスな Google Apps Script ログのエクスポートと分析のために GCP を活用する](https://gist.github.com/tanaikech/68aa1dfbe041606d0d1df9cbd0079bcd)
- [Gemini API の機能拡張: Web コンテンツ要約の実用的なソリューション](https://gist.github.com/tanaikech/ba6ae7972838e5a8f0adbec62a722f75)
- [Node.js でファイルをアップロードするための多目的なアプローチ: Gemini、Drive、YouTube、その他の API の統合](https://gist.github.com/tanaikech/7340cc7c87ec0f701dfb2f0351e02031)
- [効率的なスクリプト生成のための Gemini 搭載の動的疑似 RAG](https://gist.github.com/tanaikech/7ce4cfebd06cc527cc7107987cdbd15f)
- [Google Apps Script で Gemini API を使用して Gmail に柔軟なラベルを付けるパート 3](https://gist.github.com/tanaikech/ed3fdd463b5965503c7b6f3b7db0d4f5)
- [Gemini のパワーを活用する: 構造化データからコンテンツを生成するためのガイド](https://gist.github.com/tanaikech/395ec09f4ddc9ffdb4c8fafdb39d69ff)
- [プロンプトエンジニアリングによる Gemini API の疑似関数呼び出し](https://gist.github.com/tanaikech/65c720a1fdc56d99c35b24aeaaa57f7e)
- [Google スプレッドシートで管理されたコーパスを RAG として使用して Gemini のテキスト生成精度を向上させる](https://gist.github.com/tanaikech/bed216a816ba19b99618cf7902103a59)
- [Gemini と Google Apps Script を使用して添付ファイルを含む Gmail 処理を効率化する](https://gist.github.com/tanaikech/f2161b110257e282b71ce1e6d0082a51)
- [Google Apps Script を使用して Gemini API で画像を生成する](https://gist.github.com/tanaikech/6cfeded96e440a9f722a23bed4992948)
- [Google Apps Script を使用して Gemini で視覚化されたレシピの説明を作成する](https://gist.github.com/tanaikech/ec9ec5946a0f28f715b6824f69790cf5)
- [Gemini API を使用して成長する画像を生成する](https://gist.github.com/tanaikech/369c2ea717c27dbde04a2ad13133535a)
- [Gemini としてのロードマップ ジェネレーター](https://gist.github.com/tanaikech/723c153d0e7ccb415d68fb4f42a326b1)
- [Gemini を使用した積載計画の自動化: 実現可能性調査とプロンプトベースのアプローチ](https://gist.github.com/tanaikech/9ef17c48c485891e7b873408c7fec82a)
- [Gemini と Google Apps Script を統合して Google スライドのプレゼンテーションを自動化する](https://gist.github.com/tanaikech/063bbecb2d3beaddc17fc3bf59722f13)
- [Gemini における時間情報の重要性と現在の時刻処理](https://gist.github.com/tanaikech/e5114194e059153de2b0511ca18ba4bd)
- [Google Apps Script で Gemini API を使用したテキスト読み上げ (TTS)](https://gist.github.com/tanaikech/bcdecc89f71d421a2de405d675e722b1)
- [Gemini API による画像生成の拡大: Python と Node.js のサポートを開始](https://gist.github.com/tanaikech/d3057587c22228503d313cea74a33e56)
- [Gemini APIのURLコンテキストツールの実践分析](https://gist.github.com/tanaikech/6cd666838572f478d69ec8ae660968d9)

<a name="mcp"></a>

#### モデルコンテキストプロトコル (MCP)

- [Google Apps Script を使用したモデルコンテキストプロトコル (MCP) サーバーの構築](https://gist.github.com/tanaikech/dc74ef2035391bb82d1c1d51ef489e74)
- [画像転送: MCP サーバー (Web アプリ/Google Apps Script) から MCP クライアント (Gemini/Python)](https://gist.github.com/tanaikech/8dc35b2e331ec99b0bdbc74b73eab821)
- [Google Apps Script を利用した MCP ネットワークによる Gmail 処理](https://gist.github.com/tanaikech/c2b9ef63039510762a1c50a23170b922)

<a name="a2a"></a>

#### Agent2Agent プロトコル (A2A)

- [Google Apps Script を使用した Agent2Agent (A2A) サーバーの構築](https://gist.github.com/tanaikech/85c4762a8b8c6c7d8bee1d7ed32ade34)
- [Google Apps Script ベースの Agent2Agent (A2A) ネットワークによる協調型エージェント システムの実現](https://gist.github.com/tanaikech/0dcee0009d8037262b60c8723283e9a5)
- [生成AIプロトコルの統合：MCPとA2Aのための単一サーバーソリューション](https://gist.github.com/tanaikech/f6e92df66a3a4f057f9bcae7c9d8a339)

<a name="geminicli"></a>

#### Gemini CLI

- [Google Apps Script の Web アプリで構築した MCP サーバーを備えた Gemini CLI](https://gist.github.com/tanaikech/4052c4dd938c845618746be420c5cc9c)
- [Gemini を使用した API のリクエストボディの生成](https://gist.github.com/tanaikech/5c5903553f3fa6f1640229dc88e57901)
- [Google Apps Script の偽サンドボックス: Gemini CLI で生成されたコードを安全に実行するための実現可能性調査](https://gist.github.com/tanaikech/0896697c24cf4b9e1b1038303cf734ae)
- [自然言語対応Googleマップ：Gemini CLIとMCPによる統合型コラボレーション機能](https://gist.github.com/tanaikech/09db6dd910b458b6d0d97d43cc60209f)
- [Gemini CLI の高速化: Google Apps Script MCP サーバー用の Node.js ラッパー](https://gist.github.com/tanaikech/1d7f0090834431d03194e58ebffdb660)
- [MCP サーバーを使用した Gemini CLI: Google Apps Script で可能性を広げる](https://gist.github.com/tanaikech/39b887f108b4896e34fea58df0695abd)
- [Google Apps Script で構築した MCP サーバーで Gemini CLI を使用してファイル コンテンツを処理する](https://gist.github.com/tanaikech/d16449e35d0a5d78299ca8028f414765)
- [Gemini CLI: 強化された ToolsForMCPServer を搭載](https://gist.github.com/tanaikech/f56d5c555a46acb6539ac2926b468f62)
- [次世代のデータ自動化: Gemini CLI、Google Sheets、MCP](https://gist.github.com/tanaikech/9d5a2ebf69781ac37f9b1338949278de)
- [Gemini CLI と MCP を使用して自然言語で Google ドキュメント、スプレッドシート、スライドを管理する](https://gist.github.com/tanaikech/07058ee7cefeae8e360be01cd99c6ebc)
- [次世代のデータ自動化: Gemini CLI、Google カレンダー、MCP](https://gist.github.com/tanaikech/f27e5a6633093b9cf929cb4fb569021f)
- [Gemini CLI でのプロンプトの使用に関する拡張ガイド](https://gist.github.com/tanaikech/68d72654c8b7ca9879388051230a17ae)
- [次世代の授業自動化: Gemini CLI、Google Classroom、MCP](https://gist.github.com/tanaikech/be36c5f544a5e6e1a25c0cff3db04ba6)
- [Google Workspace と自然言語の統合: Gemini CLI と MC による統合コラボレーション](https://gist.github.com/tanaikech/625e26dd9cf002311731ce5194b9e810)
- [Gemini CLI、Google Analytics、MCP を使用した自然言語による Web ページ分析の効率化](https://gist.github.com/tanaikech/1960fb03a38a13363f86966b4fcebbb5)
- [コンテンツ作成の効率化: Gemini CLI、MCP Server、VSCode の使用ガイド](https://gist.github.com/tanaikech/4d2c8418bb8b576aa9c560dde0f54a2f)
- [安全で会話型の Google Workspace 自動化: Gemini CLI と gas-fakes MCP サーバーの統合](https://gist.github.com/tanaikech/e995c03ff066f38a208fa473ac47132b)
- [MCP を介した Gemini CLI と Copilot CLI 間の共同対話](https://gist.github.com/tanaikech/e6c41eec8b1fac74979af45ab86c7e7e)
- [Gemini CLI を使用した Google Workspace 自動化のための動的ツール作成](https://gist.github.com/tanaikech/91321df429b3e94f6a71176bd4ecafbb)
- [Gemini CLI 拡張機能による Google Workspace 自動化の簡素化](https://gist.github.com/tanaikech/8693efc439bac83b3aea38317fb7724f)
- [Gemini CLI 拡張機能を構築するための開発者ガイド](https://gist.github.com/tanaikech/0a1426535ab3af0c68cf8d79bca770a0)

[TOP](#top)
