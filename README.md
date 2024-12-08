# PMW3610 breakout board - SEIBOKU（青墨）

Boothから購入もできます https://booth.pm/ja/items/6363907

## 特徴

PMW3610用のコンパクトで低コストなブレイクアウトボードです。[PMW3360 breakout board \- SUMI（墨）](https://github.com/snize/BOB-PMW3360-SUMI)と同様の設計思想で設計され、自作キーボードや自作トラックボールの試作や流用・組み込みを意識しています。

- 3.3Vのみで動作に限定することで部品点数を削減し低コスト・コンパクト化
- 手はんだでの実装を前提とし手はんだ用のパッドサイズと間隔を採用
- 平面的には基板の中心とOptical Centerが一致するように配置
- 立体的にはレンズ部の厚みは約4.0mm(PMW3360は約3.4mm)で若干の違いあり

## 寸法図/Dimensions

![寸法図](img/BOB-PMW3610-SEIBOKU.png)

## 回路図/Schematic

![回路図](img/BOB-PMW3610-SEIBOKU.svg)

## 部品表/BOM

| Reference      | Value               | Qty |
| -------------- | ------------------- | --- |
| C1, C3, C6, C7 | 0.1uF X7R           | 4   |
| C2             | 1uF                 | 1   |
| C4, C8         | 0.01uF X7R          | 2   |
| C5             | 10uF X7R            | 1   |
| C9             | 3.3uF/16V           | 1   |
| R1             | 10k                 | 1   |
| U1             | TLV70019DDCR        | 1   |
| U2             | PMW3610DM-SUDU      | 1   |

## 使用フォント/Font

本プロジェクトでは、**Departure Mono** フォントを使用しています。[rektdeckard/departure-mono](https://github.com/rektdeckard/departure-mono)

## ライセンス/License

This project is licensed under the CERN OHL-P v2.
You may use, distribute, and modify this design under the terms of the CERN OHL-P v2.
Original design by snize.

### 本プロジェクトを利用する場合について

- 著作権表示とライセンスの表示を残してください
- issueなどで利用した旨を報告していただけると作者が喜びます
  - 作例にバックリンクさせていただきます

## 本プロジェクトを利用した作例

- 
