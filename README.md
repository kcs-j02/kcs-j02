# 小林 智輝 / Tomoki Kobayashi

北陸先端科学技術大学院大学（JAIST） 情報科学系 修士1年。

**GPUによるAI・計算処理の高速化**をテーマに、
タスクの依存関係とGPU資源を考慮した**スケジューリング・資源割当てアルゴリズム**を研究しています。

また、**サイバーセキュリティ**の学習や、身近な課題を解決する**アプリ・システムの自主開発**にも取り組んでいます。

---

## Research

### GPUタスクスケジューリング・資源割当て

依存関係を持つ複数のタスクを対象に、単一GPU上での全体実行時間を短縮するスケジューリング手法を研究しています。

主に以下を組み合わせた手法を検討・実装しています。

* タスク依存グラフ（DFG / STG）の解析
* Critical Path / bottom level に基づくタスク重要度評価
* CUDA Streamへのタスク割当て
* Streaming Multiprocessor（SM）の資源配分
* CUDA Green ContextによるGPU資源分離
* 予測makespanに基づく実行構成の選択

既存手法、Green Contextを用いた既存手法、提案手法を実装し、

* 実行時間
* Speedup
* SMs Active
* GPU実行状況

などから比較・評価しています。

**Tech:** C++, CUDA, CUDA Stream, CUDA Green Context, Taskflow, cudaFlow, CMake, Nsight Systems / Compute

Repository: [master_study](https://github.com/kcs-j02/master_study)

---

## Bachelor Research

### Q-learningとDQNの性能比較

強化学習アルゴリズムである **Q-learning** と **Deep Q-Network（DQN）** を実装し、同一条件で性能を比較しました。

以下の2種類の環境を用いて評価しています。

* 迷路課題：離散的な状態空間
* CartPole：連続値を含む状態空間

収束速度や学習の安定性を比較し、状態空間の性質による各アルゴリズムの特徴を分析しました。

**Tech:** Python, Q-learning, DQN, Reinforcement Learning

Repository: [my-Bachelor-study](https://github.com/kcs-j02/my-Bachelor-study)

---

## Personal Development

### エアコン遠隔操作アプリ

自宅のエアコンを遠隔操作するためのシステムを自主開発しています。

身近な課題を自分で分析し、必要な機能を設計して、サーバー側の処理やデバイスとの連携を実装しました。

検証しやすいように、実機だけでなく**擬似デバイス（fake device）**を用いた動作確認環境も構築しています。

* エアコン操作用サーバーの実装
* デバイスとの通信・制御
* 擬似デバイスを利用した動作検証
* 実環境を想定したシステム構築

Repository: [my_app](https://github.com/kcs-j02/my_app)

---

## Cybersecurity

将来、CSIRTやインシデント対応に関わることを目標に、サイバーセキュリティを自主的に学習しています。

現在は主に以下を学んでいます。

* Linux / Shell
* Web Security
* Network Security
* Cryptography
* Binary Analysis
* Digital Forensics
* CTF
* AI / Machine Learning × Security

単に攻撃手法を知るだけでなく、

**「何が起きたか → 原因は何か → どこまで影響しているか → どう防ぐか」**

まで分析できることを目標にしています。

Repository: [security](https://github.com/kcs-j02/security)

---

## Projects

### master_study

GPUタスクスケジューリングとGPU資源割当てに関する修士研究。

C++ / CUDAで複数方式を実装し、実行時間・Speedup・GPU利用状況を比較しています。

[Repository](https://github.com/kcs-j02/master_study)

### my_app

自宅のエアコンを遠隔操作するために自主開発したアプリケーション。

サーバー・デバイス間の連携や、擬似デバイスを用いた動作検証を実装しています。

[Repository](https://github.com/kcs-j02/my_app)

### my-Bachelor-study

Q-learningとDQNを実装し、離散・連続状態空間における性能を比較した学士研究。

[Repository](https://github.com/kcs-j02/my-Bachelor-study)

### security

CSIRT・インシデント対応を意識したサイバーセキュリティの自主学習記録。

[Repository](https://github.com/kcs-j02/security)

### entrance-exam

大学院入試のプログラミング問題をCで再現・実装。

[Repository](https://github.com/kcs-j02/entrance-exam)

---

## Tech Stack

**Languages**

`C++` `C` `CUDA` `Python` `JavaScript`

**GPU / Parallel Computing**

`CUDA` `CUDA Stream` `CUDA Green Context` `Taskflow` `cudaFlow`

**Analysis / Profiling**

`Nsight Systems` `Nsight Compute`

**Tools / Environment**

`Git` `GitHub` `Linux` `CMake`

**Machine Learning**

`Q-learning` `DQN` `Reinforcement Learning`

**Security**

`Web Security` `Network Security` `Binary Analysis` `Digital Forensics` `CTF`

---

## Interests

* GPU Computing / Parallel Processing
* Task Scheduling / Resource Allocation
* AI Acceleration
* Machine Learning / Reinforcement Learning
* Cybersecurity / CSIRT / Incident Response
* Application Development / IoT

---

## Contact

GitHub: [kcs-j02](https://github.com/kcs-j02)
