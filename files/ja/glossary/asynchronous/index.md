---
title: Asynchronous （非同期）
slug: Glossary/Asynchronous
---
**非同期**とは、 2 つ以上の事象が同時に発生したり、関連する複数の事象が互いの完了を待たずに発生したりする概念を指します（前のものが完了するのを待たずに複数の関連するものが発生することもあります）。コンピュータの世界では、「非同期」という言葉は主に 2 つの文脈で使われています。

- ネットワークと通信

  - : 非同期通信とは、 2 人以上の通信者の間で、それぞれが都合の良いタイミングでメッセージを受信し処理する通信方式です。受信者は、受信直後に処理をする必要はありません。また、問題発生時には受信者が訂正をリクエストしたり問題を処理したりするという了解の下で、メッセージは受信者の確認を待たずに送信されるかもしれません。

    人の場合、電子メールは非同期通信の 1 つです。送信者がメールを送信すると、受信者は受信直後ではなく都合の良いタイミングでメッセージを読んで返信します。両者ともに、好きなときに送信や受信を継続でき、お互いにスケジュールを調整する必要はありません。

    ソフトウェアが非同期に通信する場合、プログラムは別のソフトウェア（サーバーなど）から情報を要求し、応答を待っている間、他のことをし続けることができます。例えば、 [AJAX](/ja/docs/Web/Guide/AJAX) プログラミングテクニック - 現代のアプリケーションでは XML ではなく {{Glossary("JSON")}} が通常使用されていますが、現在では単に "Ajax" と呼ばれています - は、 {{Glossary("HTTP")}} を使用してサーバーに比較的少量のデータを要求し、その結果はすぐにではなく利用可能なときに返される仕組みです。

- ソフトウェア設計

  - : 非同期ソフトウェアの設計は、プログラム中で元のタスクを止めることなく、別のタスクを同時に実行させることを可能にするものです。 2 つ目のタスクが完了した時、合意された仕組みを使い、その情報が元のタスクに通知されます。それにより、元のタスクは、処理が完了し結果が利用可能になったことを把握できるのです。

    非同期ソフトウェアを実装するプログラミング・テクニックは数多くあります。学んでみたければ、[非同期 JavaScript](/ja/docs/Learn/JavaScript/Asynchronous) の記事をご覧下さい。

## 関連情報

- [サーバーからのデータの取得](/ja/docs/Learn/JavaScript/Client-side_web_APIs/Fetching_data) （学習領域）
- {{glossary("Synchronous", "同期")}}
