# Awesome Ham Radio

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[日本語版はこちら / Japanese](README.ja.md)

A curated list of useful **amateur / ham radio** resources — licensing & societies, band plans, SDR, digital modes, logging, antennas, contests, satellites, APRS, and the Japan (JARL) scene. Prefer durable official / project URLs.

## Contents

- [Organizations & licensing](#organizations--licensing)
- [Band plans & spectrum](#band-plans--spectrum)
- [Software-defined radio (SDR)](#software-defined-radio-sdr)
- [Digital modes](#digital-modes)
- [Logging, QSL & awards](#logging-qsl--awards)
- [Radio control & CAT](#radio-control--cat)
- [APRS & packet](#aprs--packet)
- [Satellites](#satellites)
- [Antennas & propagation](#antennas--propagation)
- [Contests](#contests)
- [Spotting & alerts](#spotting--alerts)
- [DSP & developer libraries](#dsp--developer-libraries)
- [Japan](#japan)
- [Related lists](#related-lists)
- [Contributing](#contributing)

---

## Organizations & licensing

National and international bodies; start here for rules, exams, and advocacy.

- [International Amateur Radio Union (IARU)](https://www.iaru.org/) - Worldwide voice of amateur radio; spectrum advocacy and Region coordination.
- [IARU Region 1](https://www.iaru-r1.org/) - Europe, Africa, Middle East, northern Asia.
- [IARU Region 2](https://www.iaru-r2.org/en/) - The Americas.
- [IARU Region 3](https://www.iaru-r3.org/) - Asia-Pacific (includes Japan).
- [ARRL](https://www.arrl.org/) - US national association; licensing study, LoTW, contests, QST.
- [JARL (Japan Amateur Radio League)](https://www.jarl.org/) - Japan’s national society ([English](https://www.jarl.org/English/)).
- [ITU Amateur Service](https://www.itu.int/en/ITU-R/terrestrial/Pages/default.aspx) - International Radio Regulations context for the amateur service.

---

## Band plans & spectrum

- [IARU Region 1 band plan](https://www.iaru-r1.org/spectrum/band-plans/) - HF / VHF / UHF band-plan documents for Region 1.
- [IARU Region 2 band plan](https://www.iaru-r2.org/en/resources/band-plans/) - Band-plan resources for the Americas.
- [ARRL band plan / frequency allocations](https://www.arrl.org/band-plan) - US amateur allocations and notes.
- [JARL band plan (Japanese)](https://www.jarl.org/Japanese/A_Shiryo/A-3_Band_Plan/A-3-0.htm) - Japan amateur band plan (current edition effective 2025-07-17, PDF).

---

## Software-defined radio (SDR)

Receive (and often transmit) software and hardware ecosystems.

- [GNU Radio](https://www.gnuradio.org/) - Free & open-source toolkit of signal-processing blocks for software radios. ([GitHub](https://github.com/gnuradio/gnuradio))
- [SDRangel](https://www.sdrangel.org/) - Multi-platform Rx/Tx SDR application (Airspy, BladeRF, HackRF, LimeSDR, PlutoSDR, RTL-SDR, and more). ([GitHub](https://github.com/f4exb/sdrangel))
- [SDR++](https://www.sdrpp.org/) - Lightweight, cross-platform open-source SDR receiver with broad hardware support. ([GitHub](https://github.com/AlexandreRouma/SDRPlusPlus))
- [Gqrx](https://www.gqrx.dk/) - Open-source SDR receiver powered by GNU Radio and Qt. ([GitHub](https://github.com/gqrx-sdr/gqrx))
- [CubicSDR](https://cubicsdr.com/) - Cross-platform SDR application. ([GitHub](https://github.com/cjcliffe/CubicSDR))
- [OpenWebRX+](https://fms.komkon.org/OWRX/) - Extended fork of OpenWebRX: browser-based multi-user SDR receiver with many built-in decoders. ([GitHub](https://github.com/luarvique/openwebrx))
- [SoapySDR](https://github.com/pothosware/SoapySDR) - Vendor- and platform-neutral SDR support library (hardware abstraction).
- [RTL-SDR Blog](https://www.rtl-sdr.com/) - News, tutorials, and drivers around low-cost RTL2832U dongles.
- [Osmocom rtl-sdr](https://osmocom.org/projects/rtl-sdr/wiki) - Classic open-source RTL2832U SDR stack.

---

## Digital modes

Weak-signal and keyboard modes popular on HF and VHF.

- [WSJT-X](https://wsjtx.github.io/wsjtx/) - Official home of FT8, FT4, WSPR, JT65, Q65, MSK144, and related modes (K1JT / WSJT Development Team); 3.x series (since 2026) adds parallel FT8 decoding and full-duplex operation. ([Downloads](https://wsjtx.github.io/wsjtx/downloads.html)) · ([GitHub](https://github.com/WSJTX/wsjtx))
- [FT4 / FT8 protocol paper (QEX)](https://wsjt.sourceforge.io/FT4_FT8_QEX.pdf) - Design notes for FT4 and FT8.
- [JS8Call](https://js8call.com/) - Keyboard messaging built on a robust FSK layer inspired by FT8. ([Improved / community builds](https://github.com/JS8Call-improved))
- [fldigi](http://www.w1hkj.com/) - Multi-mode digital modem suite (PSK, RTTY, Olivia, CW, and more) by W1HKJ.
- [FreeDV](https://freedv.org/) - Open-source HF digital voice over ordinary SSB rigs, including the ML-based RADE mode. ([GitHub](https://github.com/drowe67/freedv-gui))
- [GridTracker](https://gridtracker.org/) - Companion map, alerts, and logging bridge for WSJT-X / JTDX style apps. ([Docs](https://docs.gridtracker.org/latest/))
- [ft8_lib](https://github.com/kgoba/ft8_lib) - Lightweight C library for FT8 encoding/decoding.
- [Morse Code World](https://morsecodeworld.com/) - Browser-based Morse encoder/decoder (text, audio, photos).

---

## Logging, QSL & awards

Station logs, electronic QSL, and award tracking.

- [Logbook of The World (LoTW)](https://www.arrl.org/logbook-of-the-world) - ARRL’s electronic QSO confirmation system (TQSL certificates; DXCC / WAS credit).
- [Club Log](https://clublog.org/) - Log analysis, DXCC tracking, and LoTW Trusted Partner uploads.
- [Wavelog](https://www.wavelog.org/) - Modern open-source web logbook (Cloudlog lineage); LoTW / eQSL sync, club stations, contest logger. ([GitHub](https://github.com/wavelog/wavelog))
- [Cloudlog](https://github.com/magicbug/Cloudlog) - Earlier PHP web logbook; many operators have moved to Wavelog.
- [Swisslog](https://www.swisslogforwindows.com/) - Feature-rich Windows logging suite.
- [zLog](https://github.com/jr8ppg/zLog) - Popular Japanese contest / general logger for Windows (JR8PPG lineage).
- [eQSL.cc](https://www.eqsl.cc/) - Electronic QSL card exchange.
- [QRZ.com](https://www.qrz.com/) - Callsign lookup, bio pages, and logbook features.

---

## Radio control & CAT

- [Hamlib](https://hamlib.github.io/) - Portable radio-control library and `rigctl` / `rigctld` daemons used by many apps. ([GitHub](https://github.com/Hamlib/Hamlib))
- [flrig](http://www.w1hkj.com/) - Rig-control companion to fldigi (XML-RPC / CAT).

---

## APRS & packet

Automatic Packet Reporting System and related TNCs.

- [aprs.fi](https://aprs.fi/) - Classic APRS-IS tracking map (OH7LZB).
- [aprs.world](https://aprs.world/) - Live worldwide APRS map with messaging and multi-language UI.
- [Dire Wolf](https://github.com/wb2osz/direwolf) - Software TNC, APRS digipeater, and iGate.
- [APRSdroid](https://github.com/ge0rg/aprsdroid) - APRS client for Android.
- [APRS Track Direct](https://github.com/qvarforth/trackdirect) - Tools to run your own APRS website.

---

## Satellites

- [AMSAT](https://www.amsat.org/) - Radio Amateur Satellite Corporation — news, status, and educational resources.
- [SatNOGS](https://satnogs.org/) - Open global network of ground stations for observing satellites. ([Wiki](https://wiki.satnogs.org/))
- [IARU satellite frequency coordination](https://www.iaru.org/reference/satellites/) - How amateur satellite frequencies are coordinated.
- [JARL — Fuji / amateur satellites (English)](https://www.jarl.org/English/) - Japan amateur-satellite notes via JARL.

---

## Antennas & propagation

- [ARRL Antenna Book (shop / overview)](https://home.arrl.org/) - Long-running reference series on antenna theory and practice (editions sold via ARRL).
- [4nec2](https://www.qsl.net/4nec2/) - Free NEC-2 based antenna modeler / optimizer for Windows.
- [EZNEC](https://eznec.com/) - Graphical NEC antenna modeling; now a free download (EZNEC Pro/2 v6), no longer sold or supported since W7EL retired.
- [PSK Reporter](https://pskreporter.info/) - Near-real-time digimode reception reports — great for checking antennas and propagation.
- [VOACAP Online](https://www.voacap.com/hf/) - HF propagation prediction (Point-to-Point and coverage tools).
- [SolarHam](https://www.solarham.net/) - Solar / geomagnetic conditions relevant to HF.

---

## Contests

- [ARRL Contest Calendar](https://www.arrl.org/contest-calendar) - Official ARRL contest dates and links.
- [WA7BNM Contest Calendar](https://www.contestcalendar.com/) - Comprehensive worldwide contest calendar.
- [IARU HF World Championship](https://www.arrl.org/iaru-hf-championship) - Annual IARU HF event (often hosted via ARRL pages).
- [CQ World Wide DX Contest](https://www.cqww.com/) - Major DX contest series (CW / SSB / RTTY).
- [N1MM Logger+](https://n1mmwp.hamdocs.com/) - Widely used free Windows contest logger for CW, phone, and digital modes.
- [JARL contests (Japanese)](https://www.jarl.org/) - National contest calendar and rules via JARL.

---

## Spotting & alerts

- [HamAlert](https://hamalert.org/) - Configurable alerts from DX cluster, RBN, SOTA/POTA, WWFF, PSK Reporter, and more.
- [DX Summit](https://www.dxsummit.fi/) - Popular web DX cluster.
- [Reverse Beacon Network (RBN)](https://www.reversebeacon.net/) - Skimmer-based CW / RTTY spotting network.
- [SOTAWatch](https://sotawatch.sota.org.uk/) - Summits on the Air spotting.
- [Parks on the Air (POTA)](https://parksontheair.com/) - Parks activation program and spotting tools.

---

## DSP & developer libraries

Useful when building your own demodulators, SDR apps, or audio tools.

- [liquid-dsp](https://liquidsdr.org/) - Digital signal processing library aimed at SDRs. ([GitHub](https://github.com/jgaeddert/liquid-dsp))
- [FFTW](https://www.fftw.org/) - Fast Fourier Transform library. ([GitHub](https://github.com/FFTW/fftw3))
- [Kiss FFT](https://github.com/mborgerding/kissfft) - Small, simple FFT implementation.
- [RtAudio](https://www.music.mcgill.ca/~gary/rtaudio/) - Cross-platform realtime audio I/O API. ([GitHub](https://github.com/thestk/rtaudio))

---

## Japan

Licensing, society, logging, and local software of particular interest to JA operators.

### Licensing & administration

- [総務省 電波利用ポータル — アマチュア無線](https://www.tele.soumu.go.jp/j/others/amateur/) - Official MIC portal for amateur radio.
- [アマチュア局の申請・届出](https://www.tele.soumu.go.jp/j/others/amateur/shinsei/) - Application / notification forms for amateur stations.
- [電波利用電子申請](https://www.denpa.soumu.go.jp/) - Electronic radio-station application system.

### Society & events

- [JARL](https://www.jarl.org/) - 日本アマチュア無線連盟（ハムフェア、コンテスト、アワードなど）.
- [JARL English](https://www.jarl.org/English/) - English menu for international visitors.

### Software & community (JA)

- [zLog](https://github.com/jr8ppg/zLog) - Contest / general logger popular in Japan.
- [nextzlog](https://github.com/nextzlog) - Related Japanese logging / contest tooling.
- [jr8ppg](https://github.com/jr8ppg) · [StudioZaigo](https://github.com/StudioZaigo) · [ji1udd](https://github.com/ji1udd) - Active Japanese amateur-radio developers on GitHub.

### ACARS & aviation data (JA references)

- [acarsdec](https://github.com/TLeconte/acarsdec) - Multi-channel ACARS decoder.
- [JAERO](https://github.com/jontio/JAERO) - Aero satcom / ACARS related decoder.
- [Avicom — ACARS overview (Japanese)](https://www.avicom.co.jp/services/data_link/) - Industry notes on ACARS data-link use in Japan.

### Radio-specific tooling

- [FT-991A interoperability tools](https://github.com/j0ju/ft991a-interoperability-tools) - Unofficial docs and tools for Yaesu FT-991A.
- [RALF FT-991A ExMenu Utils](https://github.com/AdotGdot/RALF.FT991A.ExMenu.Utils) - Backup & restore for FT-991A extended menu.

---

## Related lists

- [sindresorhus/awesome](https://github.com/sindresorhus/awesome) - The Awesome meta-list.
- [kyleterry/awesome-radio](https://github.com/kyleterry/awesome-radio) - Broader radio / SDR awesome list.
- [Awesome Search](https://awesomelists.top/) - Quick search across Awesome lists.

---

## Contributing

Contributions welcome — open a pull request to add a resource, fix a broken link, or suggest a category.

Prefer **durable official / docs URLs**, short blurbs, and actively maintained projects. Keep product and organization names; mark language or region when helpful. Update both `README.md` and `README.ja.md` when you can.
