# [TV-Mira-Policy](https://takatakaooo.github.io/TV-Mira-Policy/)
下記のアプリケーションのマニュアルとプライバシーポリシーです。

**クローズテスター募集中**
 - 現在、本体アプリのGoogle Playに向けて作業中ですが、Google Playの公開条件であるクローズテストが必要人数の件でクリアーできません。
 ご協力いただける方を募集中です。下記のGoogleグループにアクセスいただけると、ダウンロードURLがありますので、そちらからテスト参加いただけると助かります。
 https://groups.google.com/g/tv-mira-close-tester




# 📺 TV-Mira

<p align="center">
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android"/>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin"/>
  <img src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white" alt="Jetpack Compose"/>
  <img src="https://img.shields.io/badge/LibVLC-FF8800?style=for-the-badge&logo=vlcmediaplayer&logoColor=white" alt="LibVLC"/>
</p>

**TV-Mira** は、Mirakurunサーバーと連携してテレビ放送（地上波/BS/CS）をストリーミング視聴できるAndroidアプリです。

## ✨ 機能
- 📡 **Mirakurun連携** - Mirakurunサーバーから放送波を受信
- 🎬 **高品質・MPEG-2対応** - **LibVLC** 採用により、デバイスを問わず安定したMPEG-2 TS再生を実現
- 📺 **チャンネル一覧** - 地上波/BS/CSをタブでスムーズに切り替え
- 🎮 **快適なプレイヤー** - チャンネル送り/戻し、音量調整、**没入モード（全画面）**対応
- 🔊 **音声遅延補正** - Bluetoothイヤホン等の音ズレを自動/手動で補正
- ⚙️ **柔軟な設定** - 不要チャンネルの非表示、デコーダー切替、サーバー設定

## 📚 ドキュメント
- [**操作マニュアル (MANUAL.md)**](MANUAL.md): アプリの使い方

## 📋 動作要件
- **Android**: 7.0 (API 24) 以上
- **Mirakurun**: バージョン 3.x 以上

## ⚠️ 開発上の注意点
- **API制限**: MirakurunのAPI仕様変更に追従する必要があります。
- **デコーダー**: 一部の機種や古い端末ではハードウェアデコーダーが正常に動作しない場合があります（設定で切り替え推奨）。

## 🙏 謝辞

- [Mirakurun](https://github.com/Chinachu/Mirakurun) - DVRチューナーサーバー
- [LibVLC](https://videolan.org) - メディアプレイヤーフレームワーク

---
Last Updated: 2026-01-06
