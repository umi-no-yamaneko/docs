+++
date = '2025-02-21T22:20:15+09:00'
title = '導入方法'
+++
## 前提条件
- ダウンロードしたzipファイルが解凍済みであること
- VCCがインストールされていること
- VRCに対応したUnity(2022.3.22f1)がインストールされていること
- VCCで以下パッケージが追加されていること
    - [lilToon](https://lilxyzw.github.io/lilToon/)
    - [FaceEmo](https://suzuryg.github.io/face-emo/)
    - [Modular Avatar](https://modular-avatar.nadena.dev/)

## 手順
1. VCCでAvatarプロジェクトを作成する際に，以下のパッケージを追加します。
    - Gesture Manager
    - lilToon
    - FaceEmo
    - Modular Avatar
    - Non-Destructive Modular Framework
![追加するパッケージ](https://storage.umi-no-yamaneko.jp/docs_assets/avatar/amami-tone/install/amami-tone-install-001.png)
2. 作成したUnityプロジェクトを開き，"アセット">"パッケージをインポート">"カスタムパッケージ..."をクリックします。
![パッケージインポート](https://storage.umi-no-yamaneko.jp/docs_assets/avatar/amami-tone/install/amami-tone-install-002.png)
3. Boothからダウンロードし，解凍したフォルダからUnitypackageをインポートします。
![パッケージインポート詳細](https://storage.umi-no-yamaneko.jp/docs_assets/avatar/amami-tone/install/amami-tone-install-003.png)

4. プロジェクトタブのSceneフォルダ内のamami-toneをダブルクリックします。
![シーンの展開](https://storage.umi-no-yamaneko.jp/docs_assets/avatar/amami-tone/install/amami-tone-install-004.png)

5. ヒエラルキーのamami-toneシーンを右クリックし，"シーンを別名で保存"をクリックし，Assetsフォルダの直下に任意の名前でシーンを保存します。
![シーンを別名で保存](https://storage.umi-no-yamaneko.jp/docs_assets/avatar/amami-tone/install/amami-tone-install-005.png)

6. 別名で保存したシーンのヒエラルキーから，"amami-tone"プレハブの"Emo"アイコンをクリックし，"アバターに適用"をクリックします。
![フェイシャルの適用](https://storage.umi-no-yamaneko.jp/docs_assets/avatar/amami-tone/install/amami-tone-install-006.png)

7. "表情メニューをアバターに適用しますか?"の画面で"適用"をクリックします。
![フェイシャルの適用](https://storage.umi-no-yamaneko.jp/docs_assets/avatar/amami-tone/install/amami-tone-install-007.png)

以上でアバターのセットアップは完了です。
