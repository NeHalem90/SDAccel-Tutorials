<p align="right">
<a href="https://github.com/Xilinx/SDAccel-Tutorials/tree/master/docs/aws-getting-started/CPP/README.md">English</a> | <a>日本語</a>
</p>

# SDAccel および C/C++ カーネルを使用した AWS F1 入門

この入門ガイドは、C/C++ または OpenCL™ 関数から作成したアクセラレーション カーネルを使用して AWS F1 で SDAccel アプリケーションを作成する開発者向けのものです。

## 必須条件

F1 インスタンスに接続できるようにするには、いくつかの準備段階があります。このモジュールでは、次の方法について説明します。

- AWS アカウントを作成
- S3 バケットを作成
- 秘密接続キーを準備
- AWS F1 インスタンスへのアクセスをリクエスト

[**詳細な手順**](../PREREQUISITES/README.md)

<hr/>

## 1\. AWS F1 インスタンスの作成、設定、テスト

このモジュールでは、次の方法について説明します。

- AWS F1 インスタンスを起動して設定
- インスタンスへ接続して単純なテストを実行
- セッションを閉じる

[**詳細な手順**](STEP1.md)

<hr/>

## 2\. AWS F1 で最初のプログラムを実行

このモジュールでは、次の方法について説明します。

- 新規 SDAccel プロジェクトを作成して設定
- テスト アプリケーションをコンパイル、プロファイル、アクセラレーション

[**詳細な手順**](STEP2.md)

<hr/>

## 3\. AWS F1 および SDAccel C/OpenCL フローを詳細に学ぶ

このモジュールでは、次のトピックに関するオンライン トレーニング ビデオを提供します。

- AWS F1 および SDAccel 開発環境の概要
- AWS F1 ハードウェア仕様および要件
- アプリケーション ホスト コードの基本概念
- OpenCL メモリ アーキテクチャ

[**詳細な手順**](STEP3.md)

<hr/>

## 4\. C/C++ カーネルを使用した演習

このモジュールでは、次の方法について説明します。

- F1 に関する追加演習および例を実行
- SDAccel についてさらに学ぶ
- サポートを利用して問題をトラブルシュート

[**詳細な手順**](STEP4.md)

<hr/>

## 5\. コンピューターに SDAccel をインストールして実行

FPGA Developer AMI に含まれる AWS F1 インスタンスには、アプリケーションを Amazon クラウドで開発、コンパイル、実行、デバッグするのに必要なツールがすべて含まれています。オプションで、アプリケーションを自分のマシンで開発およびコンパイルしてから、AWS にアップロードして、クラウドで実行およびデバッグすることもできます。

このオプションのモジュールでは、次の方法について説明します。

- SDAccel をローカル コンピューターにインストールして、ライセンス取得
- 単純な例をローカルでコンパイル
- AWS F1 にアップロードして実行

次のものが必要になります。

- ザイリンクス アカウント — [ここで作成](https://japan.xilinx.com/registration/create-account.html)
- 次のいずれかを実行する Linux コンピューター:
  - Ubuntu 16.04.5 LTS、18.04.1 LTS
  - CentOS 7.4、7.5、7.6
  - RHEL 7.4、7.5、7.6

[**詳細な手順** <br>](STEP5.md)

<hr/>
<p align="center"><sup>Copyright&copy; 2019 Xilinx</sup></p>

この資料は表記のバージョンの英語版を翻訳したもので、内容に相違が生じる場合には原文を優先します。資料によっては英語版の更新に対応していないものがあります。日本語版は参考用としてご使用の上、最新情報につきましては、必ず最新英語版をご参照ください。
