# Mass++/Mass++4: オープンソース・MSデータビューア

[Jump to English page](./)

This page provides …

## Mass++について

私たちは高速スペクトルビューア「Mass++」を開発し、これは全バージョン合計で今までおよそ2万回ダウンロードされてきました。現在開発中のバージョンはVer.4で、オープンソースソフトウェアとして、新たにJava言語で書き直し、複数のOSに対応できるようにしました。今回、これまで開発してきた様々な機能を整理し、Ver.4の正式リリース（Ver.4 Gold）として、基本的な機能、特にスペクトルやクロマトグラムの表示に関する機能（スペクトル／クロマトグラムのズーム、ピークのラベル付け、スペクトル／クロマトグラムの画像ファイルへのエクスポート、m/z値や保持時間値によるスペクトルの絞り込み機能など）を中心にパッケージを作成しました。このVer.4 Goldパッケージは4つのOS環境(Windows、MacOS、Linux Debian/Ubuntu、Linux RPM)でリリースされます。

なお、今後のバージョン管理およびVer.2.7系列との区別のために、「Mass++ Ver.4 Gold」は公開にあたって「Mass++4 Ver.1.0.0」と改称されました。今後はこちらの名称を主に使用していきます。

## 実行形式パッケージ（インストーラー）・ダウンロード

### 現行（最新）バージョン

 * **Mass++4 ver.1.0.0** （旧名 Mass++ ver.4 Gold（正式版））  **--> [ダウンロードページ](https://mspp.ninja/mass4-%e5%ae%9f%e8%a1%8c%e3%83%95%e3%82%a1%e3%82%a4%e3%83%ab%e3%83%80%e3%82%a6%e3%83%b3%e3%83%ad%e3%83%bc%e3%83%89/) （Windows, macOS, Linux RPM, Linux Debian/Ubuntu版）**
   * Mass++4は「Mass++ ver.4」として開発が進められてきたバージョンで、ver.2.7.4のユーザーがまだ多く混乱を避けるのが望ましいこと、機能的に大きく違いがあることなどから、ソフト名ごと改称したものです。「Mass++4 ver. 1.0.0」は、開発時に「Mass++ ver.4 Gold（正式版）」と呼んでいたバージョンと同一です。現在はこのバージョンのみ開発が行われています。


### 過去のバージョン

#### <ins>Ver.4（Mass++4）系列</ins>  -->  [ダウンロードページ](https://mspp.ninja/mass4-%e5%ae%9f%e8%a1%8c%e3%83%95%e3%82%a1%e3%82%a4%e3%83%ab%e3%83%80%e3%82%a6%e3%83%b3%e3%83%ad%e3%83%bc%e3%83%89/) （Windows, macOS, Linux RPM, Linux Debian/Ubuntu版）
* **Mass++4 ver.0.2.1** （旧名 Mass++ ver.4 beta2）
* **Mass++4 ver.0.2.0** （旧名 Mass++ ver.4 beta）
* **Mass++4 ver.0.1.0** （旧名 Mass++ ver.4 alpha）

#### <ins>Ver.2系列</ins>  --> [ダウンロードページ](https://mspp.ninja/mass-%e5%ae%9f%e8%a1%8c%e3%83%95%e3%82%a1%e3%82%a4%e3%83%ab%e3%83%80%e3%82%a6%e3%83%b3%e3%83%ad%e3%83%bc%e3%83%89/) （Windows版のみ）
* **Mass++ ver.2.7.5**
  * Mass++はver.2.7.4まではソースコードを公開せずに実行ファイルのみを公開してきました。ver.2.7.5は、ver.2.7.4から一部の機能を削除してオープンソース版に変更したものです。
* **Mass++ ver.2.7.4**
  * Mass++のver.2系列最終版であるver.2.7.4は解析機能などを多数含むもので、現在でも多くのユーザーがおられます。このファイルは、2025年3月31日まで島津製作所・田中耕一記念質量分析研究所のwebサイトで配布していたものと同一です。**本サイトでの配布には島津製作所は一切関わっておらず**、本バージョンのサポートも島津製作所は一切行いません。またこのバージョンは開発環境が古いため、**一切のサポートができません。ご使用は自己責任で**お願いします。


## ソースコード・リポジトリ

* 現行（最新）バージョン  
  * **Mass++4 ver.1.0.0** （旧名  ver. 4.0 Gold (正式版・安定版)  
    * [mspp4-core](https://github.com/masspp/mspp4-core)  
    * [mspp4-desktop](https://github.com/masspp/mspp4-desktop)
    * [api-sample](https://github.com/masspp/api-sample) （data processing APIについてのサンプルコード）

* 過去のバージョン  
  * [\~Mass++4 ver.0.2.1 (ver.4.0 beta2)](https://github.com/masspp/mspp4)  
  * [Mass++ ver.2.7.5](https://github.com/masspp/mspp2.7.5)
  * ver.2.7.4はクローズドソース（ソースコード非公開）です。

## リリースノート

* 2025/xx/xx: Mass++4 ver.1.0.0 (Mass++ ver.4.0 Gold) リリース  
  * Updated whole system to apply new concept  
  * 基本機能の書き直しと再実装  
* 2021/12/04: Mass++4 ver.0.2.1 (Mass++ ver.4.0 beta2) リリース  
  * [バグ修正](https://mspp.ninja/2021/12/ver-4-beta2%e3%82%a4%e3%83%b3%e3%82%b9%e3%83%88%e3%83%bc%e3%83%a9%e3%81%ae%e3%83%80%e3%82%a6%e3%83%b3%e3%83%ad%e3%83%bc%e3%83%89%e3%81%8c%e3%81%a7%e3%81%8d%e3%81%be%e3%81%99/) ベータ版に対する修正  
    * MS/MSスペクトルのプリカーサーイオン質量が、Raw data タブのSpectrumViewTableに表示されるようにした。
    * Projectタブを開いているときに、MS/MSスペクトルに対するペプチド同定処理が実行できるようにした。
    * macOS/Linux版で、Projectタブを開いて行うペプチド同定処理の過程で、ピークリストが生成されるようにした。
* 2020/06/08: Mass++4 ver.0.2.0 (Mass++ ver.4.0 beta) リリース  
  * アルファ版から [機能を追加]([https://mspp.ninja/2020/11/ver-4-alpha%e3%81%a8ver-4-beta%e3%81%ae%e6%a9%9f%e8%83%bd%e6%af%94%e8%bc%83/](https://mspp.ninja/2020/11/ver-4-alpha%e3%81%a8ver-4-beta%e3%81%ae%e6%a9%9f%e8%83%bd%e6%af%94%e8%bc%83/)  
    * 外部アプリケーション実行・データ交換
    * データ・アノテーション表示  
    * ピークピッキング
      * ProteoWizard ver. 3.0.20123の利用 (Windows環境のみ)  
    * ペプチドアノテーション（同定）用サーチエンジンのサポート
      * Comet ver. 2019.01 rev. 5 (Windows環境のみ)  
    * 対応ファイル  
      * mzML, MGF, pepXML (manual)
    * 対応OS
      * Windows, macOS, Linux Debian/Ubuntu, Linux RPM
* 2019/09/17: Mass++4 ver.0.1.0 (Mass++ ver.4.0 alpha) リリース  
  * 複数OS対応の新バージョンリリース開始
  * 実装した基本機能
    * スペクトル・クロマトグラム表示
      * TIC, XIC, MS1, MS/MS  
      * ミラープロット
      * オーバーラップ
    * ヒートマップ
      * 2D, 3D  
    * データ・アノテーション表示 (manual)  
    * 対応ファイル
      * mzML, MGF, pepXML (manual)  
    * 対応OS
      * Windows, macOS

## 開発者について

Mass++ユーザー会のweb ([https://mspp.ninja/](https://mspp.ninja/)) を参照してください。


