# 政府相互運用性フレームワーク(Government Interoperability Framework) for Dataverse

本テンプレートはデジタル庁が提供しているデータモデル「政府相互運用性フレームワーク(Government Interoperability Framework)」(以下　GIF)を Microsoft Dataverse に展開するためのテンプレートです。
Microsoft Dataverse上にテンプレートを展開すると、モデル駆動型アプリとコアデータモデル(主要なテーブル)が作成され、取捨選択しながら拡張を行うことができます。 

![image](https://user-images.githubusercontent.com/123050871/214772063-25f861a9-f66a-454f-b0b9-c6e06bb4dd1e.png)

政府相互運用性フレームワーク（GIF）｜デジタル庁
https://www.digital.go.jp/policies/data_strategy_government_interoperability_framework/

補足
|       Microsoft Power Platform              　　　　　| Description                                              |
|------------------------------------------|----------------------------------------------------------|
| Power Apps   　　　　　|視覚的操作で実用的なアプリケーションを開発                       |
| Power Automate                              | 各サービスとの連携を可能とし、ルール・処理を自動化|
| Power BI                           | あらゆるデータをグラフ化し、傾向を分析                                        |
| Power Virtual Agents                                | 視覚的操作でチャットボットを作成                              |
| Power Pages                              | 視覚的操作でWebサイトを構築                            |

## コンテンツ
本レポジトリには下記のコンテンツが含まれています。

| File/folder                     　　　　　| Description                                              |
|------------------------------------------|----------------------------------------------------------|
| `GovernmentCommonCDMJapan_1_0_0_1.zip`   |Power Apps Unmanaged Solution File                        |
| `documents`                              | 導入手順書、テーブル一覧・テーブル定義書、管理者ガイド等|
| `README.md`                              | This README file.                                        |
| `LICENSE`                                | The license for the sample.                              |

## 前提条件
本サンプルは、Microsoft Power Platform の Dataverse 上で動作します。
Dataverse 環境への展開が可能な有償 Power Apps ライセンスが必要となります。

## セットアップ
本サンプルでは、Power Apps のセットアップが必要になります。
Zip ファイルをアンマネージドソリューションとして登録しています。こちらのアンマネージソリューションをソリューションのインポートでPower Appsの環境に登録をしてご利用ください。
詳細なセットアップ手順は同梱の「ソリューションのインポート」をご参照下さい。

## 構成内容
本テンプレートは下記の要素にて構成されています。

Power Apps ソリューションファイル  
Power Apps ソリューションファイルには次の内容が含まれています。
 - テーブル
 - モデル駆動型アプリ
 - サイトマップ

## 準備されている言語
本テンプレートは日本語で準備されており、日本語にのみ対応します。

## FAQ
 - Q.テンプレート導入後に拡張することは可能ですか？
   - A.可能です。新しいソリューションやカスタムテーブルの作成・編集に関しては「管理者ガイド」をご参照ください。
 - Q.サポートはありますか？
    - A.いいえ、ありません。
 - Q.Dataverse版を評価版にて利用することができますか？
    - A.Power Apps及びPower Automateは、双方とも30日の無償評価版があります。評価版にてご利用、機能の確認を行う事が可能です。

## 免責事項
本テンプレートはフレームワークを提供するものであり、恒久的なアプリケーション使用を意図したものではありません。
日本マイクロソフトはそのような目的で本テンプレートおよび関連サービスを使用するライセンスや権利を本テンプレート利用組織に付与していません。 
本テンプレートおよび関連サービスは、各企業のニーズを全て含めるように設計されたものではなく、そのような用途で使用されるものではありません。
実際の利用や必要な追加のカスタマイズは別途導入支援パートナーに確認・依頼してください。 本テンプレートおよび関連サービスのいかなる使用においても、利用者がすべてリスクと責任を負うものとします。
また、実装した本テンプレートおよび関連マイクロソフト サービスの使用に関して、適切な警告や情報をエンドユーザーに提供することについても、利用者が責任を負うものとします。 
本テンプレートは、日本国内での使用のみを目的とし、欠陥などがある可能性を含んだままの状態で提供されており、いかなる種類の保証も適用されません。

## Contributing
本プロジェクトは政府相互運用性フレームワーク(GIF)に依存しているため、GIFに変更が生じない限り原則アップデートはいたしません。
This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
