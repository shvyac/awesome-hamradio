# Awesome Ham Radio

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[日本語版はこちら / Japanese](README.ja.md)

A curated list of useful **amateur / ham radio** resources — licensing & societies, band plans, SDR, digital modes, logging, antennas, contests, satellites, APRS, and the Japan (JARL) scene. Prefer durable official / project URLs. ⭐ badges show live GitHub star counts (via shields.io).

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
- [shvyac's awesome lists](#shvyacs-awesome-lists)

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

- [GNU Radio](https://www.gnuradio.org/) ![GitHub stars](https://img.shields.io/github/stars/gnuradio/gnuradio?style=flat&label=%E2%AD%90) - Free & open-source toolkit of signal-processing blocks for software radios. ([GitHub](https://github.com/gnuradio/gnuradio))
- [SDRangel](https://www.sdrangel.org/) ![GitHub stars](https://img.shields.io/github/stars/f4exb/sdrangel?style=flat&label=%E2%AD%90) - Multi-platform Rx/Tx SDR application (Airspy, BladeRF, HackRF, LimeSDR, PlutoSDR, RTL-SDR, and more). ([GitHub](https://github.com/f4exb/sdrangel))
- [SDR++](https://www.sdrpp.org/) ![GitHub stars](https://img.shields.io/github/stars/AlexandreRouma/SDRPlusPlus?style=flat&label=%E2%AD%90) - Lightweight, cross-platform open-source SDR receiver with broad hardware support. ([GitHub](https://github.com/AlexandreRouma/SDRPlusPlus))
- [Gqrx](https://www.gqrx.dk/) ![GitHub stars](https://img.shields.io/github/stars/gqrx-sdr/gqrx?style=flat&label=%E2%AD%90) - Open-source SDR receiver powered by GNU Radio and Qt. ([GitHub](https://github.com/gqrx-sdr/gqrx))
- [CubicSDR](https://cubicsdr.com/) ![GitHub stars](https://img.shields.io/github/stars/cjcliffe/CubicSDR?style=flat&label=%E2%AD%90) - Cross-platform SDR application. ([GitHub](https://github.com/cjcliffe/CubicSDR))
- [OpenWebRX+](https://fms.komkon.org/OWRX/) ![GitHub stars](https://img.shields.io/github/stars/luarvique/openwebrx?style=flat&label=%E2%AD%90) - Extended fork of OpenWebRX: browser-based multi-user SDR receiver with many built-in decoders. ([GitHub](https://github.com/luarvique/openwebrx))
- [SoapySDR](https://github.com/pothosware/SoapySDR) ![GitHub stars](https://img.shields.io/github/stars/pothosware/SoapySDR?style=flat&label=%E2%AD%90) - Vendor- and platform-neutral SDR support library (hardware abstraction).
- [RTL-SDR Blog](https://www.rtl-sdr.com/) - News, tutorials, and drivers around low-cost RTL2832U dongles.
- [Osmocom rtl-sdr](https://osmocom.org/projects/rtl-sdr/wiki) - Classic open-source RTL2832U SDR stack.

---

## Digital modes

Weak-signal and keyboard modes popular on HF and VHF.

- [WSJT-X](https://wsjtx.github.io/wsjtx/) ![GitHub stars](https://img.shields.io/github/stars/WSJTX/wsjtx?style=flat&label=%E2%AD%90) - Official home of FT8, FT4, WSPR, JT65, Q65, MSK144, and related modes (K1JT / WSJT Development Team); 3.x series (since 2026) adds parallel FT8 decoding and full-duplex operation. ([Downloads](https://wsjtx.github.io/wsjtx/downloads.html)) · ([GitHub](https://github.com/WSJTX/wsjtx))
- [FT4 / FT8 protocol paper (QEX)](https://wsjt.sourceforge.io/FT4_FT8_QEX.pdf) - Design notes for FT4 and FT8.
- [JS8Call](https://js8call.com/) ![GitHub stars](https://img.shields.io/github/stars/JS8Call-improved/JS8Call-improved?style=flat&label=%E2%AD%90) - Keyboard messaging built on a robust FSK layer inspired by FT8; now developed by the JS8Call-Improved team (original repo archived), 3.x series. ([GitHub](https://github.com/JS8Call-improved/JS8Call-improved))
- [fldigi](http://www.w1hkj.com/) - Multi-mode digital modem suite (PSK, RTTY, Olivia, CW, and more) by W1HKJ.
- [FreeDV](https://freedv.org/) ![GitHub stars](https://img.shields.io/github/stars/freedv/freedv-gui?style=flat&label=%E2%AD%90) - Open-source HF digital voice over ordinary SSB rigs, including the ML-based RADE mode. ([GitHub](https://github.com/freedv/freedv-gui))
- [GridTracker](https://gridtracker.org/) - Companion map, alerts, and logging bridge for WSJT-X / JTDX style apps. ([Docs](https://docs.gridtracker.org/latest/))
- [M17 Project](https://m17project.org/) - Open-source digital radio protocol for VHF/UHF voice and data (Codec 2), with open hardware and gateway software.
- [OpenRTX](https://openrtx.org/) ![GitHub stars](https://img.shields.io/github/stars/OpenRTX/OpenRTX?style=flat&label=%E2%AD%90) - Modular open-source firmware for handheld radios (e.g. TYT MD-380/390, Module17) with native M17 support. ([GitHub](https://github.com/OpenRTX/OpenRTX))
- [ft8_lib](https://github.com/kgoba/ft8_lib) ![GitHub stars](https://img.shields.io/github/stars/kgoba/ft8_lib?style=flat&label=%E2%AD%90) - Lightweight C library for FT8 encoding/decoding.
- [Morse Code World](https://morsecodeworld.com/) - Browser-based Morse encoder/decoder (text, audio, photos).
- [Online Morse Code](https://onlinemorsecode.com/) - Free browser-based Morse code translator with adjustable-speed CW audio, WAV download, audio decoding, printable chart and learning guides.

---

## Logging, QSL & awards

Station logs, electronic QSL, and award tracking.

- [Logbook of The World (LoTW)](https://www.arrl.org/logbook-of-the-world) - ARRL’s electronic QSO confirmation system (TQSL certificates; DXCC / WAS credit).
- [Club Log](https://clublog.org/) - Log analysis, DXCC tracking, and LoTW Trusted Partner uploads.
- [Wavelog](https://www.wavelog.org/) ![GitHub stars](https://img.shields.io/github/stars/wavelog/wavelog?style=flat&label=%E2%AD%90) - Modern open-source web logbook (Cloudlog lineage); LoTW / eQSL sync, club stations, contest logger. ([GitHub](https://github.com/wavelog/wavelog))
- [Cloudlog](https://github.com/magicbug/Cloudlog) ![GitHub stars](https://img.shields.io/github/stars/magicbug/Cloudlog?style=flat&label=%E2%AD%90) - Original PHP web logbook (still maintained); Wavelog is its community fork.
- [QLog](https://github.com/foldynl/QLog) ![GitHub stars](https://img.shields.io/github/stars/foldynl/QLog?style=flat&label=%E2%AD%90) - Open-source cross-platform desktop logger (Qt) with Hamlib rig control, LoTW / eQSL / Club Log sync, and WSJT-X integration.
- [Ham2K Portable Logger (PoLo)](https://polo.ham2k.com/) ![GitHub stars](https://img.shields.io/github/stars/ham2k/app-polo?style=flat&label=%E2%AD%90) - Free mobile logger for POTA / SOTA / WWFF and portable operation (iOS / Android). ([GitHub](https://github.com/ham2k/app-polo))
- [Swisslog](https://www.swisslogforwindows.com/) - Feature-rich Windows logging suite.
- [zLog](https://github.com/jr8ppg/zLog) ![GitHub stars](https://img.shields.io/github/stars/jr8ppg/zLog?style=flat&label=%E2%AD%90) - Popular Japanese contest / general logger for Windows (JR8PPG lineage).
- [eQSL.cc](https://www.eqsl.cc/) - Electronic QSL card exchange.
- [QRZ.com](https://www.qrz.com/) - Callsign lookup, bio pages, and logbook features.

---

## Radio control & CAT

- [Hamlib](https://hamlib.github.io/) ![GitHub stars](https://img.shields.io/github/stars/Hamlib/Hamlib?style=flat&label=%E2%AD%90) - Portable radio-control library and `rigctl` / `rigctld` daemons used by many apps. ([GitHub](https://github.com/Hamlib/Hamlib))
- [flrig](http://www.w1hkj.com/) - Rig-control companion to fldigi (XML-RPC / CAT).
- [qdmr](https://dm3mat.de/software/qdmr/) ![GitHub stars](https://img.shields.io/github/stars/hmatuschek/qdmr?style=flat&label=%E2%AD%90) - Open-source codeplug editor / programmer for many low-cost DMR (and M17) radios on Linux, macOS, and Windows. ([GitHub](https://github.com/hmatuschek/qdmr))

---

## APRS & packet

Automatic Packet Reporting System and related TNCs.

- [aprs.fi](https://aprs.fi/) - Classic APRS-IS tracking map (OH7LZB).
- [aprs.world](https://aprs.world/) - Live worldwide APRS map with messaging and multi-language UI.
- [Dire Wolf](https://github.com/wb2osz/direwolf) ![GitHub stars](https://img.shields.io/github/stars/wb2osz/direwolf?style=flat&label=%E2%AD%90) - Software TNC, APRS digipeater, and iGate.
- [Pat](https://getpat.io/) ![GitHub stars](https://img.shields.io/github/stars/la5nta/pat?style=flat&label=%E2%AD%90) - Cross-platform Winlink email client (Go) with web UI; supports AX.25 packet, ARDOP, VARA, and PACTOR; reached v1.0 in 2026. ([GitHub](https://github.com/la5nta/pat))
- [APRSdroid](https://github.com/ge0rg/aprsdroid) ![GitHub stars](https://img.shields.io/github/stars/ge0rg/aprsdroid?style=flat&label=%E2%AD%90) - APRS client for Android.
- [APRS Track Direct](https://github.com/qvarforth/trackdirect) ![GitHub stars](https://img.shields.io/github/stars/qvarforth/trackdirect?style=flat&label=%E2%AD%90) - Tools to run your own APRS website.

---

## Satellites

- [AMSAT](https://www.amsat.org/) - Radio Amateur Satellite Corporation — news, status, and educational resources.
- [SatNOGS](https://satnogs.org/) - Open global network of ground stations for observing satellites. ([Wiki](https://wiki.satnogs.org/))
- [Gpredict](https://github.com/csete/gpredict) ![GitHub stars](https://img.shields.io/github/stars/csete/gpredict?style=flat&label=%E2%AD%90) - Real-time satellite tracking and orbit prediction with Hamlib radio / rotator control (Doppler correction).
- [Look4Sat](https://github.com/rt-bishop/Look4Sat) ![GitHub stars](https://img.shields.io/github/stars/rt-bishop/Look4Sat?style=flat&label=%E2%AD%90) - Ad-free Android satellite tracker and pass predictor inspired by Gpredict (Celestrak / SatNOGS data, offline prediction; Google Play / F-Droid).
- [SatDump](https://www.satdump.org/) ![GitHub stars](https://img.shields.io/github/stars/SatDump/SatDump?style=flat&label=%E2%AD%90) - Generic satellite data processing software: live SDR reception and decoding of weather and other satellites (NOAA APT, Meteor LRPT, GOES, and more); 2.0 in development. ([GitHub](https://github.com/SatDump/SatDump))
- [CubeSatSim](https://github.com/alanbjohnston/CubeSatSim) ![GitHub stars](https://img.shields.io/github/stars/alanbjohnston/CubeSatSim?style=flat&label=%E2%AD%90) - AMSAT CubeSat Simulator: low-cost Raspberry Pi based satellite model that transmits real telemetry, for education and STEM demos.
- [IARU satellite frequency coordination](https://www.iaru.org/reference/satellites/) - How amateur satellite frequencies are coordinated.
- [JARL — Fuji / amateur satellites (English)](https://www.jarl.org/English/) - Japan amateur-satellite notes via JARL.

---

## Antennas & propagation

- [ARRL Antenna Book (shop / overview)](https://home.arrl.org/) - Long-running reference series on antenna theory and practice (editions sold via ARRL).
- [4nec2](https://www.qsl.net/4nec2/) - Free NEC-2 based antenna modeler / optimizer for Windows.
- [EZNEC](https://eznec.com/) - Graphical NEC antenna modeling; now a free download (EZNEC Pro/2 v6), no longer sold or supported since W7EL retired.
- [AntennaSim](https://ea1fuo.github.io/AntennaSim/) ![GitHub stars](https://img.shields.io/github/stars/EA1FUO/AntennaSim?style=flat&label=%E2%AD%90) - Free browser-based NEC2 antenna simulator (new in 2026): 3D radiation patterns, SWR / impedance / Smith charts, optimizer, NanoVNA .s1p overlay; runs fully in WebAssembly or via Docker. ([GitHub](https://github.com/EA1FUO/AntennaSim))
- [NanoVNA-Saver](https://github.com/NanoVNA-Saver/nanovna-saver) ![GitHub stars](https://img.shields.io/github/stars/NanoVNA-Saver/nanovna-saver?style=flat&label=%E2%AD%90) - Cross-platform desktop app for capturing, displaying, and saving NanoVNA sweeps (Smith chart, SWR, return loss, calibration, Touchstone export).
- [PSK Reporter](https://pskreporter.info/) - Near-real-time digimode reception reports — great for checking antennas and propagation.
- [VOACAP Online](https://www.voacap.com/hf/) - HF propagation prediction (Point-to-Point and coverage tools).
- [NOAA SWPC](https://www.swpc.noaa.gov/) - Official space-weather forecasts, alerts, and solar / geomagnetic indices relevant to HF.

---

## Contests

- [ARRL Contest Calendar](https://www.arrl.org/contest-calendar) - Official ARRL contest dates and links.
- [WA7BNM Contest Calendar](https://www.contestcalendar.com/) - Comprehensive worldwide contest calendar.
- [Perfect Clock – contest calendars](https://perfectclock.cc/ham-radio) - HF, VHF/UHF, RTTY/FT8 and weekly CW contests on a timeline.
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
- [OpenHamClock](https://github.com/accius/openhamclock) ![GitHub stars](https://img.shields.io/github/stars/accius/openhamclock?style=flat&label=%E2%AD%90) - Open-source, community-maintained successor to HamClock (the original stopped working in June 2026 after its creator WB0OEW became a Silent Key): real-time dashboard with DX cluster spots, propagation, space weather, and maps; runs in a browser, on a Raspberry Pi kiosk, via Docker, or as a Snap.

---

## DSP & developer libraries

Useful when building your own demodulators, SDR apps, or audio tools.

- [liquid-dsp](https://liquidsdr.org/) ![GitHub stars](https://img.shields.io/github/stars/jgaeddert/liquid-dsp?style=flat&label=%E2%AD%90) - Digital signal processing library aimed at SDRs. ([GitHub](https://github.com/jgaeddert/liquid-dsp))
- [FFTW](https://www.fftw.org/) ![GitHub stars](https://img.shields.io/github/stars/FFTW/fftw3?style=flat&label=%E2%AD%90) - Fast Fourier Transform library. ([GitHub](https://github.com/FFTW/fftw3))
- [Kiss FFT](https://github.com/mborgerding/kissfft) ![GitHub stars](https://img.shields.io/github/stars/mborgerding/kissfft?style=flat&label=%E2%AD%90) - Small, simple FFT implementation.
- [RtAudio](https://www.music.mcgill.ca/~gary/rtaudio/) ![GitHub stars](https://img.shields.io/github/stars/thestk/rtaudio?style=flat&label=%E2%AD%90) - Cross-platform realtime audio I/O API. ([GitHub](https://github.com/thestk/rtaudio))
- [morse-code-audio](https://github.com/bellemann/morse-code-audio) ![GitHub stars](https://img.shields.io/github/stars/bellemann/morse-code-audio?style=flat&label=%E2%AD%90) - Dependency-free JavaScript library to encode Morse, build ITU and Farnsworth timing, render WAV audio and decode CW from audio. ([Demo](https://morsecodefree.com/morse-code-audio-decoder/))

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

- [zLog](https://github.com/jr8ppg/zLog) ![GitHub stars](https://img.shields.io/github/stars/jr8ppg/zLog?style=flat&label=%E2%AD%90) - Contest / general logger popular in Japan.
- [nextzlog](https://github.com/nextzlog) - Related Japanese logging / contest tooling.
- [jr8ppg](https://github.com/jr8ppg) · [StudioZaigo](https://github.com/StudioZaigo) · [ji1udd](https://github.com/ji1udd) - Active Japanese amateur-radio developers on GitHub.

### ACARS & aviation data (JA references)

- [acarsdec](https://github.com/TLeconte/acarsdec) ![GitHub stars](https://img.shields.io/github/stars/TLeconte/acarsdec?style=flat&label=%E2%AD%90) - Multi-channel ACARS decoder (original repo archived; actively maintained fork: [f00b4r0/acarsdec](https://github.com/f00b4r0/acarsdec) ![GitHub stars](https://img.shields.io/github/stars/f00b4r0/acarsdec?style=flat&label=%E2%AD%90)).
- [JAERO](https://github.com/jontio/JAERO) ![GitHub stars](https://img.shields.io/github/stars/jontio/JAERO?style=flat&label=%E2%AD%90) - Aero satcom / ACARS related decoder.
- [Avicom — ACARS overview (Japanese)](https://www.avicom.co.jp/service/data-link/) - Industry notes on ACARS data-link use in Japan.

### Radio-specific tooling

- [FT-991A interoperability tools](https://github.com/j0ju/ft991a-interoperability-tools) ![GitHub stars](https://img.shields.io/github/stars/j0ju/ft991a-interoperability-tools?style=flat&label=%E2%AD%90) - Unofficial docs and tools for Yaesu FT-991A.
- [RALF FT-991A ExMenu Utils](https://github.com/AdotGdot/RALF.FT991A.ExMenu.Utils) ![GitHub stars](https://img.shields.io/github/stars/AdotGdot/RALF.FT991A.ExMenu.Utils?style=flat&label=%E2%AD%90) - Backup & restore for FT-991A extended menu.

---

## Related lists

- [sindresorhus/awesome](https://github.com/sindresorhus/awesome) ![GitHub stars](https://img.shields.io/github/stars/sindresorhus/awesome?style=flat&label=%E2%AD%90) - The Awesome meta-list.
- [kyleterry/awesome-radio](https://github.com/kyleterry/awesome-radio) ![GitHub stars](https://img.shields.io/github/stars/kyleterry/awesome-radio?style=flat&label=%E2%AD%90) - Broader radio / SDR awesome list.
- [Awesome Search](https://awesomelists.calvinjeng.io/) - Quick search across Awesome lists.

---

## Contributing

Contributions welcome — open a pull request to add a resource, fix a broken link, or suggest a category.

Prefer **durable official / docs URLs**, short blurbs, and actively maintained projects. Keep product and organization names; mark language or region when helpful. Update both `README.md` and `README.ja.md` when you can.

---

## shvyac's awesome lists

All curated lists maintained by [shvyac](https://github.com/shvyac):

- [awesome-AI-Powered-Executive-Dashboards](https://github.com/shvyac/awesome-AI-Powered-Executive-Dashboards) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-AI-Powered-Executive-Dashboards?style=flat&label=%E2%AD%90)
- [awesome-ai-tool-for-mechanical-engineering](https://github.com/shvyac/awesome-ai-tool-for-mechanical-engineering) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ai-tool-for-mechanical-engineering?style=flat&label=%E2%AD%90)
- [awesome-audio-softwares](https://github.com/shvyac/awesome-audio-softwares) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-audio-softwares?style=flat&label=%E2%AD%90)
- [awesome-azure-ai-dynamics365-security](https://github.com/shvyac/awesome-azure-ai-dynamics365-security) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-azure-ai-dynamics365-security?style=flat&label=%E2%AD%90)
- [awesome-ballroom-dance](https://github.com/shvyac/awesome-ballroom-dance) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ballroom-dance?style=flat&label=%E2%AD%90)
- [awesome-cad-cae](https://github.com/shvyac/awesome-cad-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cad-cae?style=flat&label=%E2%AD%90)
- [awesome-cms-ai](https://github.com/shvyac/awesome-cms-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cms-ai?style=flat&label=%E2%AD%90)
- [awesome-dashboards-visualization](https://github.com/shvyac/awesome-dashboards-visualization) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-dashboards-visualization?style=flat&label=%E2%AD%90)
- [awesome-ghost-artists](https://github.com/shvyac/awesome-ghost-artists) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ghost-artists?style=flat&label=%E2%AD%90)
- [awesome-hamradio](https://github.com/shvyac/awesome-hamradio) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-hamradio?style=flat&label=%E2%AD%90)
- [awesome-hpc](https://github.com/shvyac/awesome-hpc) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-hpc?style=flat&label=%E2%AD%90)
- [awesome-iso27001-isms-tools](https://github.com/shvyac/awesome-iso27001-isms-tools) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-iso27001-isms-tools?style=flat&label=%E2%AD%90)
- [awesome-local-llm](https://github.com/shvyac/awesome-local-llm) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-local-llm?style=flat&label=%E2%AD%90)
- [awesome-m5stack-arduino](https://github.com/shvyac/awesome-m5stack-arduino) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-m5stack-arduino?style=flat&label=%E2%AD%90)
- [awesome-map-gis](https://github.com/shvyac/awesome-map-gis) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-map-gis?style=flat&label=%E2%AD%90)
- [awesome-meshless-cae](https://github.com/shvyac/awesome-meshless-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-meshless-cae?style=flat&label=%E2%AD%90)
- [awesome-online-services](https://github.com/shvyac/awesome-online-services) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-online-services?style=flat&label=%E2%AD%90)
- [awesome-open-source-solvers](https://github.com/shvyac/awesome-open-source-solvers) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-open-source-solvers?style=flat&label=%E2%AD%90)
- [awesome-osint-ai](https://github.com/shvyac/awesome-osint-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-osint-ai?style=flat&label=%E2%AD%90)
- [awesome-redmine-ai](https://github.com/shvyac/awesome-redmine-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-redmine-ai?style=flat&label=%E2%AD%90)
- [awesome-requirements-system-ai](https://github.com/shvyac/awesome-requirements-system-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-requirements-system-ai?style=flat&label=%E2%AD%90)
- [awesome-trading-stock](https://github.com/shvyac/awesome-trading-stock) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-trading-stock?style=flat&label=%E2%AD%90)
