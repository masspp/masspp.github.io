# Mass++: オープンソース・MSデータビューア

This page provides …

## Mass++について

私たちは高速スペクトルビューア「Mass++」を開発し、これは全バージョン合計で今までおよそ2万回ダウンロードされてきました。現在開発中のバージョンはVer.4で、オープンソースソフトウェアとして、新たにJava言語で書き直し、複数のOSに対応できるようにしました。今回、これまで開発してきた様々な機能を整理し、Ver.4の正式リリース（Ver.4 Gold）として、基本的な機能、特にスペクトルやクロマトグラムの表示に関する機能（スペクトル／クロマトグラムのズーム、ピークのラベル付け、スペクトル／クロマトグラムの画像ファイルへのエクスポート、m/z値や保持時間値によるスペクトルの絞り込み機能など）を中心にパッケージを作成しました。このVer.4 Goldパッケージは4つのOS環境(Windows、MacOS、Linux Debian/Ubuntu、Linux RPM)でリリースされます。

なお、今後のバージョン管理とVer.2.7系列との区別のために、公開と同時に「Mass++ Ver.4 Gold」は「Mass++4 Ver.1.0.0」と改称しました。今後はこちらの名称を主に使用してきます。

## 実行形式パッケージ（インストーラー）・ダウンロード

### 現行（最新）バージョン

* Mass++4 ver.1.0.0 （旧名 Mass++ ver.4 Gold (正式版)）

### 過去のバージョン

* Mass++4 ver.0.2.1 （旧名 Mass++ ver.4 beta2）
* Mass++4 ver.0.2.0 （旧名 Mass++ ver.4 beta）
* Mass++4 ver.0.1.0 （旧名 Mass++ ver.4 alpha）  
* Mass++ ver.2.7.5

## リリースノート

* 2025/xx/xx: Mass++4 ver.1.0.0 (Mass++ ver.4.0 Gold) リリース  
  * Updated whole system to apply new concept  
  * Re-implemented basic functions  
* 2021/12/04: Mass++4 ver.0.2.1 (Mass++ ver.4.0 beta2) リリース  
  * [バグ修正](https://mspp.ninja/2021/12/installers-of-mass-ver-4-beta-2-are-released/) ベータ版に対する修正  
    * To display precursor ion in MS/MS spectra properly  
    * To execute peptide identification process from Project tab properly  
    * To generate peak list of peptide identification properly for macOS/Linux  
* 2020/06/08: Mass++4 ver.0.2.0 (Mass++ ver.4.0 beta) リリース  
  * Added [some features from alpha version](https://mspp.ninja/2020/11/feature-comparison-of-ver-4-alpha-and-ver-4-beta/)  
    * Run external applications / Data exchange  
    * Data annotation view  
    * Peak picking  
      * Using ProteoWizard ver. 3.0.20123 (only for Windows)  
    * Search engine for peptide annotations  
      * Using Comet ver. 2019.01 rev. 5 (only for Windows)  
    * File support  
      * mzML, MGF, pepXML (manual)  
* 2019/09/17: Mass++4 ver.1.0.0 (Mass++ ver.4.0 alpha) リリース  
  * Released new version for multi platform  
  * Implemented basic functions  
    * Spectrum/Chromatograms view  
      * TIC, XIC, MS1, MS/MS  
      * Mirror view  
      * Overwrap  
    * Heatmap  
      * 2D, 3D  
    * Data annotation view (manual)  
    * File support  
      * mzML, MGF, pepXML (manual)  
    * OS support  
      * Windows, macOS

## ソースコード・リポジトリ

* 現行（最新）バージョン  
  * Mass++4 ver.1.0.0 （旧名  ver. 4.0 Gold (正式版・安定版)  
    * [mspp4-core](https://github.com/masspp/mspp4-core)  
    * [mspp4-desktop](https://github.com/masspp/mspp4-desktop)
    * [api-sample](https://github.com/masspp/api-sample) （data processing APIについてのサンプルコード）

* 過去のバージョン  
  * [\~Mass++4 ver.0.2.1 (ver.4.0 beta2)](https://github.com/masspp/mspp4)  
  * [Mass++ ver.2.7.5](https://github.com/masspp/mspp2.7.5)  

## 開発者について

Mass++ユーザー会のweb ([https://mspp.ninja/](https://mspp.ninja/)) を参照してください。


