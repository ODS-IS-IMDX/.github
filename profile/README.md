<img src="https://github.com/ODS-IS-IMDX/.github/blob/main/images/ODS_Logo.png" width="60%">

## Open Data Spaces インフラ管理DXデータ連携基盤 関連リポジトリ

独立行政法人情報処理推進機構（IPA）のデジタルアーキテクチャ・デザインセンター（[DADC](https://www.ipa.go.jp/dadc/index.html)）では、[経済産業省](https://www.meti.go.jp/policy/mono_info_service/digital_architecture/index.html)をはじめとした関係省庁、国立研究開発法人 新エネルギー・産業技術総合開発機構（NEDO）とともに、運用及び管理を行う者が異なる複数の情報処理システムの連携の仕組みに関して、アーキテクチャの設計、研究開発・実証、社会実装・普及の取組（[ウラノス・エコシステム](https://www.meti.go.jp/policy/mono_info_service/digital_architecture/ouranos.html)）を進めています。

[Open Data Spaces（ODS）](https://www.ipa.go.jp/digital/opendataspaces/)は、国や組織ごとの多様性を尊重する、オープンでスケーラブルな分散データマネジメントの技術コンセプトです。

ODSのリファレンスアーキテクチャモデル（ODS-RAM）において、「インダストリサービス（Industry Service）」は、それぞれの産業やドメインユースケースに特化したビジネスアプリケーションやビジネスプラットフォーム等を提供するバーティカルサービスとして位置付けられます。  
「Infrastructure Management DX（IMDX）（インフラ管理DXデータ連携基盤）」インダストリサービスでは、インフラ管理DXデータ連携基盤を実装するための各種ライブラリやツール類を共創しています。

インダストリサービスの関連リポジトリは、[こちら](https://github.com/orgs/ODS-IS-IMDX/repositories)から。

ODSの詳細な情報は[Open Data Spaces Organization](https://github.com/open-dataspaces)を参照してください。

# 問い合わせに関して
1. 本リポジトリは配布を目的としており、IssueやPull Requestを受け付けておりません。

# ライセンス
 1. 本リポジトリはMITライセンスで提供されています。
 2. ソースコードおよび関連ドキュメントの著作権はリポジトリごとに異なるため、各リポジトリのライセンス部分をご参照ください。

# 免責事項
 1. 本リポジトリの内容は予告なく変更・削除する可能性があります。
 2. 本リポジトリの利用により生じた損失及び損害等について、いかなる責任も負わないものとします。

# リポジトリ一覧
| 成果当初年度 | リポジトリ名 | リポジトリ説明 | 
|----|----|-----|
| 2025年度| repo_infradx_ap_PCM_0010 | 公益事業者情報削除用リポジトリ|
| 2025年度|  repo_infradx_ap_LIM_0010 | レイヤ情報登録用リポジトリ |
| 2025年度| repo_infradx_ap_LIM_0020 | レイヤ情報削除用リポジトリ 
| 2025年度| repo_infradx_ap_FDI_0010 | データ標準化用リポジトリ | 
| 2025年度| repo_infradx_ap_FDI_0020 | データ取込用リポジトリ | 
| 2025年度| repo_infradx_ap_FDI_0030 | データ登録用リポジトリ | 
| 2025年度| repo_infradx_ap_FDI_0040 | 品質チェック用リポジトリ | 
| 2025年度| repo_infradx_ap_FDI_0050 | データ公開用リポジトリ |
| 2025年度| repo_infradx_ap_FDI_0060 | 履歴管理用リポジトリ | 
| 2025年度| repo_infradx_ap_FDI_0070 | 差分管理用リポジトリ |
| 2025年度| repo_infradx_ap_FDI_0080 | TBL出力（一時DB→設備データ管理マスタDB）用リポジトリ | 
| 2025年度| repo_infradx_ap_FDI_0090 | TBL出力（設備データ管理マスタDB→2D用最終断面テーブル）用リポジトリ | 
| 2025年度| repo_infradx_ap_FDI_0100 | TBL出力（設備データ管理マスタDB→3D用最終断面テーブル）用リポジトリ | 
| 2025年度| repo_infradx_ap_AIM_0010 | 認可情報登録リポジトリ | 
| 2025年度| repo_infradx_ap_CIM_0010 | クライアント情報登録用リポジトリ | 
| 2025年度| repo_infradx_ap_BSC_0010 | オンライン処理共通用リポジトリ | 
| 2025年度| repo_infradx_ap_BSC_0020 | バッチ処理共通用リポジトリ | 
| 2025年度| repo_infradx_ap_CMN_0010 | 認証用リポジトリ | 
| 2025年度| repo_infradx_DDL | DDL用リポジトリ |
| 2025年度| repo_infradx_ap_GFV_0010 | ベクタデータ配信（可視化）用リポジトリ | 
| 2025年度| repo_infradx_ap_provider_shp_normalizer | データ変換ツール用リポジトリ |
| 2024年度| ap-infdx-repo-timeoutreload | タイムアウトデータ再読み込みバッチ用リポジトリ |
| 2024年度| ap-infdx-repo-adjustcomplete | 設備データ取込タスク登録/更新用リポジトリ |
| 2024年度| ap-infdx-repo-adjuststatuscreate | データ整備ツールステータス作成用リポジトリ |
| 2024年度| ap-infdx-repo-adjuststatusupdate | データ整備ツールステータス変更用リポジトリ |
| 2024年度| ap-infdx-repo-buried | 埋設物情報APIコンテナ用リポジトリ | 
| 2024年度| ap-infdx-repo-buried-batch | 埋設物情報取得バッチコンテナ用リポジトリ | 
| 2024年度| ap-infdx-repo-filestatus | ファイル作成状況確認APIコンテナ用リポジトリ | 
| 2024年度| ap-infdx-repo-event | イベント情報取得APIコンテナ用リポジトリ | 
| 2024年度| ap-infdx-repo-permission | API利用権限コンテナ用リポジトリ | 
| 2024年度| ap-infdx-repo-group | API利用者グループコンテナ用リポジトリ | 
| 2024年度| ap-infdx-repo-accesshistory | アクセス履歴管理コンテナ用リポジトリ | 
| 2024年度| ap-infdx-repo-3dlib | 3D空間ID共通ライブラリコンテナ用リポジトリ | 
| 2024年度| ap-infdx-repo-api-basic | 基本機能リポジトリ | 
| 2024年度| data-adjust-tool | データ整備ツール用リポジトリ | 
| 2024年度| 3d-viewer | 3Dビューア用リポジトリ |

# 詳細仕様
以下では、2025年度に作成した成果物について、ツールやシステム概要資料を示します。

## ツール一覧
|　工程名　| ツール名 | ツール概要 |
|--------|----------|----------|
| 取得 | INF様ツール | INF様ツール |
| 取得 | INF様ツール | INF様ツール |
| 変換 | データ変換ツール | シェープファイルのジオメトリ検証・修正、座標系変換（EPSG）、カラムマッピングを行う。|
| 標準化 | データ標準化機能のことを指すため、機能一覧を参照してください。 | データ標準化機能のことを指すため、機能一覧を参照してください。| 

## データ整備ツールの利用イメージ
![](https://github.com/ODS-IS-IMDX/.github/blob/main/images/data-adjust.png)
（本画像著作権者：国立研究開発法人 新エネルギー・産業技術総合開発機構、NTTインフラネット株式会社、株式会社NTTデータ）

## 機能一覧
| 機能名 | 機能概要 |
|--------|----------|
| 公益事業者情報削除 | 公益事業者の情報を削除する機能 |
| レイヤ情報登録 | レイヤ情報を登録する機能 |
| レイヤ情報削除 | レイヤ情報を削除する機能 |
| データ標準化 | 標準フォーマットを標準仕様3Dシェープファイルに変換する機能 |
| データ取込 | データ登録と品質チェックをラップする機能 |
| データ登録 | データ標準化後ストレージ(S3)の標準仕様3Dシェープファイルを読み込み、一時DBに登録する機能。<br>また、対象の設備データについて取込管理テーブルにレコードを追加する |
| 品質チェック | 設備データで使用されている属性コードと、それを管理するマスタのコード値を比較し、<br>一致しないコードやフィーチャの情報をログに出力する機能 |
| データ公開 | 履歴管理からTBL出力までをラップする機能 |
| 履歴管理 | 設備データ管理マスタDBから設備データのダンプファイルを取得し、<br>履歴管理用ストレージにアップロードする機能。<br>ストレージはS3を使用し、過去1世代分の履歴を保管する |
| 差分管理 | 一時DBと設備データ管理マスタDBとの差分を抽出し、差分管理テーブルに登録する機能 |
| TBL出力<br>（一時DB→設備データ管理マスタDB） | 一時DBから取得したデータに管理用ID等の属性を追加し、設備データ管理マスタDBに登録する機能。<br>一時DBのデータは削除する |
| TBL出力<br>（設備データ管理マスタDB→2D用最終断面テーブル） | 設備データ管理マスタDBから設備データを取得し、<br>データの編集を行ったものを2D用最終断面テーブルに登録する機能 |
| TBL出力<br>（設備データ管理マスタDB→3D用最終断面テーブル） | 設備データ管理マスタDBから設備データを取得し、<br>データの編集を行ったものを3D用最終断面テーブルに登録する機能 |
| 認可情報登録 | 認可情報を登録する機能 |

## システム構成図
![](https://github.com/ODS-IS-IMDX/.github/blob/main/images/system.png)
