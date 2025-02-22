# posting-map
## アプリケーション概要
* 町丁目ごとにポスティング状況を可視化できるシステムです。
* 2024年東京都知事選で活躍された安野たかひろさん陣営が作成・運用されていた、オープンソースのポスター貼付け状況管理システム(https://github.com/takahiroanno2024/poster-map)を流用し、改変しています。

## ライセンスについて
* このプロジェクトは[GPL-3.0 license](https://github.com/mori-yosuke-kokumin/posting-map/blob/main/LICENSE)にて公開されています。

## コントリビュートについて
* プロジェクトへのコントリビュートの際には、[コントリビューターライセンス契約（CLA）](https://github.com/mori-yosuke-kokumin/posting-map/blob/main/CLA.md)への同意が必須となります。ご了承ください。

## 動作サンプル
https://precious-florentine-d72ed6.netlify.app/

## 謝辞
本プロジェクトでは、以下のライブラリや公開データを使用させていただきました。この場を借りて開発者・コントリビューターの皆様に感謝申し上げます。
- [Leaflet](https://leafletjs.com/)
    - 地図上での可視化に使用
- [Bootstrap](https://getbootstrap.jp/)
    - トップページのメニューに使用 (CSSのみ)
- [Linked Open Addresses Japan](https://uedayou.net/loa/)
    - `/posting`ページで進捗を可視化する際に、各市区町村のポリゴンを利用
- [OpenStreetMap](https://www.openstreetmap.org/copyright)
    - ベースマップとして利用

