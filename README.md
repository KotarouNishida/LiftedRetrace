# AFM Lifted Retrace Control Software
## Overview (English)
This repository contains the software developed for controlling an Atomic Force Microscope (AFM) using a novel "Lifted Retrace" scanning method.  
It aims to improve quantitative nanoscale measurements of metal corrosion.  

**Key Features**
- LabVIEW-based FPGA control for real-time probe scanning
- Implementation of the lifted retrace method to separate topography and secondary signals
- Example scripts for data analysis and visualization

**Requirements**
- LabVIEW 2023 or later
- FPGA hardware compatible with the LabVIEW project
- Windows 10/11

**Usage**
⚠️ This software requires specific AFM hardware and cannot operate independently.  
For demonstration, see `/docs` for figures and analysis examples.

**Results / Documentation**
- Figures: `/docs/figures` (example AFM scans)
- Paper PDF: `/docs/AFM_study.pdf`

**Author Contribution**
I was responsible for FPGA programming, implementing the lifted retrace method, and creating data analysis scripts.

**License**
MIT License (for demonstration purposes)

---

## 概要 (日本語)
本リポジトリは、原子間力顕微鏡（AFM）の制御ソフトウェアをまとめたものです。  
定量性向上のため、新規走査手法「リフテッドリトレース」を実装しています。

**主な特徴**
- LabVIEW FPGA によるリアルタイム探針制御
- トポグラフィー情報と二次信号の分離を可能にするリフテッドリトレース手法の実装
- データ解析用スクリプトの提供

**動作環境**
- LabVIEW 2023 以降
- FPGA ボード（LabVIEW プロジェクトに対応）
- Windows 10/11

**使用方法**
⚠️ 特定の AFM ハードウェアが必要です。  
動作確認用に、図や解析例は `/docs` にまとめています。

**成果物**
- 図: `/docs/figures` （AFM走査例）
- 論文PDF: `/docs/AFM_study.pdf`

**担当部分**
FPGA プログラミング、リフテッドリトレースの実装、データ解析スクリプト作成を担当しました。

**ライセンス**
MIT ライセンス（デモンストレーション目的）
