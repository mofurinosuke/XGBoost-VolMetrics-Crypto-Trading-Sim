# XGBoost-VolMetrics-Crypto-Trading-Sim
クリプト自動取引AIの説明とプログラム
# 🚀 ETH-JPY Hybrid Trading AI Portfolio
XGBoostとGARCHモデルを組み合わせた、イーサリアム（ETH-JPY）の自動取引アルゴリズムです。

## 📝 プロジェクト概要
このプロジェクトは、AIによるパターン認識（XGBoost）と、統計的な市場分析（GARCH、ADX）を統合し、
市場の「ボラティリティ」と「トレンドの質」に基づいた意思決定を行う自律型トレードシステムの構築を目的としています。

## 📈 バックテスト結果 (2025/12 最終検証)
データリーケージ（未来情報の漏洩）を完全に排除した厳密な検証結果です。

| 指標 | 🤖 本戦略 | 📉 Buy & Hold |
| :--- | :---: | :---: |
| **CAGR (年率リターン)** | **37.08%** | 23.12% |
| **Sharpe Ratio** | **0.88** | 0.65 |
| **Max Drawdown** | **40.02%** | 67.10% |

## 🛠 使用技術・モデル
- **XGBoost**: 機械学習による「下落・停滞」局面の高度な予測
- **GARCH(1,1)**: 条件付き分散を用いたボラティリティ予測とエントリー制限
- **ADX (Average Directional Index)**: 相場環境認識によるダマシの回避
- **Walk-Forward Validation**: 時系列データの特性を考慮した厳密な検証

## 🚀 使い方
1. 上部の `Open in Colab` ボタンをクリック。
2. 必要なライブラリ (`arch`, `xgboost`, `japanize-matplotlib`) をインストール。
3. データをロードして実行。

## ✍️ 開発者
mofurinosuke
