# Awesome Ham Radio（日本語）

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[English README](README.md)

**アマチュア無線（ハム）**向けの有用なリソースの厳選リストです。免許・団体、バンドプラン、SDR、デジタルモード、ログ、アンテナ、コンテスト、衛星、APRS、そして日本（JARL）の情報を中心にまとめています。できるだけ公式／プロジェクトの耐久性のある URL を優先しています。

## 目次

- [団体・免許](#団体免許)
- [バンドプラン・周波数](#バンドプラン周波数)
- [ソフトウェア無線（SDR）](#ソフトウェア無線sdr)
- [デジタルモード](#デジタルモード)
- [ログ・QSL・アワード](#ログqslアワード)
- [リグコントロール（CAT）](#リグコントロールcat)
- [APRS・パケット](#aprsパケット)
- [衛星](#衛星)
- [アンテナ・伝搬](#アンテナ伝搬)
- [コンテスト](#コンテスト)
- [スポット・アラート](#スポットアラート)
- [DSP・開発ライブラリ](#dsp開発ライブラリ)
- [日本](#日本)
- [関連リスト](#関連リスト)
- [コントリビューション](#コントリビューション)

---

## 団体・免許

規則・試験・政策の入口となる国内外の団体。

- [国際アマチュア無線連合（IARU）（英語）](https://www.iaru.org/) - アマチュア無線の国際的な声。周波数確保とリージョン連携。
- [IARU Region 1（英語）](https://www.iaru-r1.org/) - 欧州・アフリカ・中東・北アジア。
- [IARU Region 2（英語）](https://www.iaru-r2.org/en/) - 南北アメリカ。
- [IARU Region 3（英語）](https://www.iaru-r3.org/) - アジア太平洋（日本を含む）。
- [ARRL（英語）](https://www.arrl.org/) - 米国の全国団体。試験学習、LoTW、コンテスト、QST など。
- [JARL（日本アマチュア無線連盟）](https://www.jarl.org/) - 日本の全国団体（[English](https://www.jarl.org/English/)）。
- [ITU 地上業務関連（英語）](https://www.itu.int/en/ITU-R/terrestrial/Pages/default.aspx) - 国際無線通信規則におけるアマチュア業務の文脈。

---

## バンドプラン・周波数

- [IARU Region 1 バンドプラン（英語）](https://www.iaru-r1.org/spectrum/band-plans/) - Region 1 の HF／VHF／UHF バンドプラン文書。
- [IARU Region 2 バンドプラン（英語）](https://www.iaru-r2.org/en/resources/band-plans/) - 米州向けバンドプラン資料。
- [ARRL バンドプラン（英語）](https://www.arrl.org/band-plan) - 米国アマチュアの割当と注記。
- [JARL バンドプラン](https://www.jarl.org/Japanese/A_Shiryo/A-3_Band_Plan/A-3-0.htm) - 日本のアマチュア無線バンドプラン（現行版は令和7年7月17日施行、PDF あり）。

---

## ソフトウェア無線（SDR）

受信（および送受信）向けソフトウェアとハードウェア生態系。

- [GNU Radio（英語）](https://www.gnuradio.org/) - ソフトウェア無線向け信号処理ブロックのオープンソース・ツールキット。（[GitHub](https://github.com/gnuradio/gnuradio)）
- [SDRangel（英語）](https://www.sdrangel.org/) - マルチプラットフォームの Rx／Tx SDR アプリ（Airspy、BladeRF、HackRF、LimeSDR、PlutoSDR、RTL-SDR など）。（[GitHub](https://github.com/f4exb/sdrangel)）
- [SDR++（英語）](https://www.sdrpp.org/) - 軽量でシンプルなクロスプラットフォームのオープンソース SDR 受信ソフト。対応ハードウェアが豊富。（[GitHub](https://github.com/AlexandreRouma/SDRPlusPlus)）
- [Gqrx（英語）](https://www.gqrx.dk/) - GNU Radio と Qt ベースのオープンソース SDR 受信機。（[GitHub](https://github.com/gqrx-sdr/gqrx)）
- [CubicSDR（英語）](https://cubicsdr.com/) - クロスプラットフォーム SDR アプリ。（[GitHub](https://github.com/cjcliffe/CubicSDR)）
- [OpenWebRX+（英語）](https://fms.komkon.org/OWRX/) - OpenWebRX の拡張フォーク。ブラウザから使える複数ユーザー対応 SDR 受信機で、多数のデコーダを内蔵。（[GitHub](https://github.com/luarvique/openwebrx)）
- [SoapySDR（英語）](https://github.com/pothosware/SoapySDR) - ベンダー非依存の SDR サポートライブラリ（ハードウェア抽象化）。
- [RTL-SDR Blog（英語）](https://www.rtl-sdr.com/) - 安価な RTL2832U ドングル周辺のニュース・チュートリアル・ドライバ。
- [Osmocom rtl-sdr（英語）](https://osmocom.org/projects/rtl-sdr/wiki) - 定番の RTL2832U オープンソース SDR スタック。

---

## デジタルモード

HF／VHF で人気の弱信号・キーボード系モード。

- [WSJT-X（英語）](https://wsjtx.github.io/wsjtx/) - FT8、FT4、WSPR、JT65、Q65、MSK144 などの公式ホーム（K1JT／WSJT 開発チーム）。2026 年からの 3.x 系で FT8 並列デコードや全二重運用に対応。（[Downloads](https://wsjtx.github.io/wsjtx/downloads.html)）·（[GitHub](https://github.com/WSJTX/wsjtx)）
- [FT4／FT8 プロトコル解説（QEX）（英語）](https://wsjt.sourceforge.io/FT4_FT8_QEX.pdf) - FT4／FT8 の設計メモ。
- [JS8Call（英語）](https://js8call.com/) - FT8 系の堅牢な FSK 層をベースにしたキーボード・メッセージング。（[Improved／コミュニティビルド](https://github.com/JS8Call-improved)）
- [fldigi（英語）](http://www.w1hkj.com/) - PSK、RTTY、Olivia、CW など多モードのデジタルモデム群（W1HKJ）。
- [FreeDV（英語）](https://freedv.org/) - 一般的な SSB 機で使えるオープンソースの HF デジタル音声。機械学習ベースの RADE モードを含む。（[GitHub](https://github.com/drowe67/freedv-gui)）
- [GridTracker（英語）](https://gridtracker.org/) - WSJT-X／JTDX 系のマップ・アラート・ログ連携コンパニオン。（[Docs](https://docs.gridtracker.org/latest/)）
- [ft8_lib（英語）](https://github.com/kgoba/ft8_lib) - FT8 エンコード／デコード向け軽量 C ライブラリ。
- [Morse Code World（英語）](https://morsecodeworld.com/) - ブラウザ上のモールス符号化／復号（テキスト・音声・画像）。

---

## ログ・QSL・アワード

局ログ、電子 QSL、アワード管理。

- [Logbook of The World（LoTW）（英語）](https://www.arrl.org/logbook-of-the-world) - ARRL の電子 QSO 確認システム（TQSL。DXCC／WAS など）。
- [Club Log（英語）](https://clublog.org/) - ログ分析、DXCC 追跡、LoTW Trusted Partner 連携。
- [Wavelog（英語）](https://www.wavelog.org/) - モダンなオープンソース Web ログ（Cloudlog 系譜）。LoTW／eQSL 同期、クラブ局、コンテストロガー。（[GitHub](https://github.com/wavelog/wavelog)）
- [Cloudlog（英語）](https://github.com/magicbug/Cloudlog) - 先行する PHP Web ログ。多くの運用者は Wavelog へ移行中。
- [Swisslog（英語）](https://www.swisslogforwindows.com/) - 高機能な Windows ログソフト。
- [zLog](https://github.com/jr8ppg/zLog) - 日本で広く使われるコンテスト／一般用ロガー（JR8PPG 系譜）。
- [eQSL.cc（英語）](https://www.eqsl.cc/) - 電子 QSL カード交換。
- [QRZ.com（英語）](https://www.qrz.com/) - コールサイン検索、自己紹介ページ、ログ機能。

---

## リグコントロール（CAT）

- [Hamlib（英語）](https://hamlib.github.io/) - 多くのアプリが使うポータブルなリグ制御ライブラリと `rigctl`／`rigctld`。（[GitHub](https://github.com/Hamlib/Hamlib)）
- [flrig（英語）](http://www.w1hkj.com/) - fldigi 向けリグ制御コンパニオン（XML-RPC／CAT）。

---

## APRS・パケット

Automatic Packet Reporting System と関連 TNC。

- [aprs.fi（英語）](https://aprs.fi/) - 定番の APRS-IS トラッキング地図（OH7LZB）。
- [aprs.world（英語）](https://aprs.world/) - 世界地図ベースのライブ APRS。メッセージや多言語 UI。
- [Dire Wolf（英語）](https://github.com/wb2osz/direwolf) - ソフトウェア TNC、APRS デジピーター、iGate。
- [APRSdroid（英語）](https://github.com/ge0rg/aprsdroid) - Android 向け APRS クライアント。
- [APRS Track Direct（英語）](https://github.com/qvarforth/trackdirect) - 独自 APRS サイト構築用ツール。

---

## 衛星

- [AMSAT（英語）](https://www.amsat.org/) - アマチュア衛星のニュース・状態・教育リソース。
- [SatNOGS（英語）](https://satnogs.org/) - 衛星観測のためのオープンな地上局ネットワーク。（[Wiki](https://wiki.satnogs.org/)）
- [IARU 衛星周波数調整（英語）](https://www.iaru.org/reference/satellites/) - アマチュア衛星周波数の調整手順。
- [JARL — アマチュア衛星（English）](https://www.jarl.org/English/) - JARL 経由の日本アマチュア衛星情報。

---

## アンテナ・伝搬

- [ARRL Antenna Book（英語・概要）](https://home.arrl.org/) - アンテナ理論・実践の定番シリーズ（ARRL 経由で販売）。
- [4nec2（英語）](https://www.qsl.net/4nec2/) - Windows 向け無料 NEC-2 アンテナモデラー／最適化ツール。
- [EZNEC（英語）](https://eznec.com/) - グラフィカルな NEC アンテナモデリング。作者 W7EL の引退に伴い販売・サポートを終了し、現在は無料配布（EZNEC Pro/2 v6）。
- [PSK Reporter（英語）](https://pskreporter.info/) - デジタルモードのほぼリアルタイム受信レポート。アンテナ・伝搬の確認に便利。
- [VOACAP Online（英語）](https://www.voacap.com/hf/) - HF 伝搬予測（地点間・カバレッジ）。
- [SolarHam（英語）](https://www.solarham.net/) - HF に影響する太陽・地磁気コンディション。

---

## コンテスト

- [ARRL Contest Calendar（英語）](https://www.arrl.org/contest-calendar) - ARRL 公式コンテスト日程。
- [WA7BNM Contest Calendar（英語）](https://www.contestcalendar.com/) - 世界のコンテストを網羅したカレンダー。
- [IARU HF World Championship（英語）](https://www.arrl.org/iaru-hf-championship) - 年次 IARU HF コンテスト（ARRL ページ経由が多い）。
- [CQ World Wide DX Contest（英語）](https://www.cqww.com/) - 大型 DX コンテストシリーズ（CW／SSB／RTTY）。
- [N1MM Logger+（英語）](https://n1mmwp.hamdocs.com/) - CW・フォーン・デジタル対応で世界的に定番の無料 Windows コンテストロガー。
- [JARL コンテスト](https://www.jarl.org/) - 国内コンテストの日程・規約は JARL サイトを参照。

---

## スポット・アラート

- [HamAlert（英語）](https://hamalert.org/) - DX クラスタ、RBN、SOTA／POTA、WWFF、PSK Reporter などからの設定可能なアラート。
- [DX Summit（英語）](https://www.dxsummit.fi/) - 人気の Web DX クラスタ。
- [Reverse Beacon Network（RBN）（英語）](https://www.reversebeacon.net/) - スキマーベースの CW／RTTY スポット網。
- [SOTAWatch（英語）](https://sotawatch.sota.org.uk/) - Summits on the Air のスポット。
- [Parks on the Air（POTA）（英語）](https://parksontheair.com/) - 公園アクティベーションとスポットツール。

---

## DSP・開発ライブラリ

自作復調・SDR アプリ・オーディオ処理向け。

- [liquid-dsp（英語）](https://liquidsdr.org/) - SDR 向けデジタル信号処理ライブラリ。（[GitHub](https://github.com/jgaeddert/liquid-dsp)）
- [FFTW（英語）](https://www.fftw.org/) - 高速フーリエ変換ライブラリ。（[GitHub](https://github.com/FFTW/fftw3)）
- [Kiss FFT（英語）](https://github.com/mborgerding/kissfft) - 小さく単純な FFT 実装。
- [RtAudio（英語）](https://www.music.mcgill.ca/~gary/rtaudio/) - クロスプラットフォームのリアルタイム音声 I/O API。（[GitHub](https://github.com/thestk/rtaudio)）

---

## 日本

免許、連盟、ログ、国内で特に有用なソフトウェア。

### 免許・行政

- [総務省 電波利用ポータル — アマチュア無線](https://www.tele.soumu.go.jp/j/others/amateur/) - アマチュア無線の公式ポータル。
- [アマチュア局の申請・届出](https://www.tele.soumu.go.jp/j/others/amateur/shinsei/) - 開局・変更などの手続様式。
- [電波利用電子申請](https://www.denpa.soumu.go.jp/) - 無線局の電子申請システム。

### 連盟・イベント

- [JARL](https://www.jarl.org/) - 日本アマチュア無線連盟（ハムフェア、コンテスト、アワードなど）。
- [JARL English](https://www.jarl.org/English/) - 海外向け英語メニュー。

### ソフト・コミュニティ（JA）

- [zLog](https://github.com/jr8ppg/zLog) - 国内で定番のコンテスト／一般用ロガー。
- [nextzlog](https://github.com/nextzlog) - 関連する日本語ログ／コンテストツール群。
- [jr8ppg](https://github.com/jr8ppg) · [StudioZaigo](https://github.com/StudioZaigo) · [ji1udd](https://github.com/ji1udd) - GitHub 上で活発な日本人アマチュア無線開発者。

### ACARS・航空データ（参考）

- [acarsdec（英語）](https://github.com/TLeconte/acarsdec) - マルチチャネル ACARS デコーダ。
- [JAERO（英語）](https://github.com/jontio/JAERO) - 航空衛星／ACARS 関連デコーダ。
- [Avicom — ACARS 概要](https://www.avicom.co.jp/services/data_link/) - 国内における ACARS データリンクの解説。

### リグ固有ツール

- [FT-991A interoperability tools（英語）](https://github.com/j0ju/ft991a-interoperability-tools) - Yaesu FT-991A 向け非公式ドキュメント／ツール。
- [RALF FT-991A ExMenu Utils（英語）](https://github.com/AdotGdot/RALF.FT991A.ExMenu.Utils) - FT-991A 拡張メニューのバックアップ／復元。

---

## 関連リスト

- [sindresorhus/awesome（英語）](https://github.com/sindresorhus/awesome) - Awesome のメタリスト。
- [kyleterry/awesome-radio（英語）](https://github.com/kyleterry/awesome-radio) - より広い無線／SDR 向け Awesome リスト。
- [Awesome Search（英語）](https://awesomelists.top/) - Awesome リスト横断検索。

---

## コントリビューション

コントリビューション歓迎です。リソース追加、リンク切れ修正、カテゴリ提案はプルリクエストでどうぞ。

**公式／ドキュメントの耐久性のある URL**、短い説明、継続的にメンテナンスされているプロジェクトを優先してください。製品名・団体名はそのまま。言語や地域が分かるように書くと親切です。可能なら `README.md` と `README.ja.md` の両方を更新してください。
