# タイピング速度と正確率の評価システム / Typing Evaluation System

Pythonで開発した、タイピング速度と正確率を評価するコンソールアプリケーションです。  
複数プレイヤーの入力データをもとに、入力文字の正確性・反応速度・編集距離などを計算します。

A simple console-based Python program to evaluate typing speed and accuracy.  
It measures input correctness, reaction time, and edit distance for multiple players.

## 使用技術 / Technologies

- Python 3.x
- 標準ライブラリ（`time`, `difflib`, `statistics` など）
- エディット距離（編集距離）アルゴリズム
- CSV ファイルによるデータ読み込み

## 機能 / Features

- 段落の読み込みとランダム出題
- タイピング速度（WPM）計算
- 正確率（Accuracy）計算
- 編集距離の計算（difflib 使用）
- 複数プレイヤーのスコア記録

## 製作目的 / Purpose

このプロジェクトは、Pythonの学習の一環として開発したものです。
プログラムの構造・ロジック設計・評価指標の実装などを総合的に経験することを目的としています。

This project was built as part of my learning journey with Python.
It helped me understand program structure, evaluation logic, and data handling.
