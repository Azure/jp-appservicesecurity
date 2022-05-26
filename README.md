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
