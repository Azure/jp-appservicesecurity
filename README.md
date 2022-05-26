# Azure App Service: セキュリティの脅威への対策ガイド

本ドキュメントは Azure App Service と関連するサービス（ Azure Storage / Azure Front Door ）に起こりうる脅威とそれらの対策についてまとめています。

ここで取り上げた製品・サービスの詳細および最新情報は[製品ドキュメント](https://docs.microsoft.com)をご参照ください。なお本ドキュメントは[株式会社ネクストスケープ](https://www.nextscape.net/)にて作成しております。

## [はじめに](./chapter00.md)

クラウドサービスを利用する上でのセキュリティ対策の必要性と、本ドキュメントの読者対象を記載しています。

## [1章 Web アプリケーションに対する脅威と対策](./chapter01.md)

クラウドに展開された Web アプリケーションに対してどのような脅威があるのか、またそれらの脅威から保護するための Azure のセキュリティ対策サービスについて取り上げています。

本ドキュメントでは下記の Azure リソースを題材とし、それぞれのセキュリティ対策について取り扱います。

- Azure App Service
- Azure Storage
- Azure Front Door + Web Application Firewall

## [2章 Web アプリケーションを保護する - Microsoft Defender for App Service](./chapter02.md)

Azure App Service に展開されている Web アプリケーションを保護する手段として、 Microsoft Defender for App Service が役立ちます。  
 Microsoft Defender for App Service の機能を体験するためのトライアルも記載しています。

## [3章 ストレージを保護する - Microsoft Defender for Storage](./chapter03.md)

Azure Storage を保護する手段として、Microsoft Defender for Storage が役立ちます。  
 Microsoft Defender for Storage の機能を体験するためのトライアルも記載しています。

## [4章 外部攻撃から保護する - Azure Front Door + Web Application Firewall](./chapter04.md)

Web アプリケーションを外部攻撃から保護する手段として、 Azure の Web Application Firewall が役立ちます。  
本ドキュメントでは Azure Front Door に付属されている Web Application Firewall 機能を題材とします。  
 Azure Front Door + Web Application Firewall の機能を体験するためのトライアルも記載します。

## [付録](./chapter05.md)

本ドキュメントで取り扱っている Azure のセキュリティ対策サービス以外にも、合わせて検討したい Azure セキュリティの関連事項等を記載します。

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
