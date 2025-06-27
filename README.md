# RISC-V Inst Viewer

[![Deploy static content to Pages](https://github.com/wipeseals/riscv-inst-viewer/actions/workflows/static.yml/badge.svg?branch=master)](https://github.com/wipeseals/riscv-inst-viewer/actions/workflows/static.yml)

RISC-V の開発・デバッグを支援する命令セット可視化・解析ツールです。RISC-V 命令の一覧表示と、数値からの命令デコード機能を提供し、プロセッサ開発やアセンブリプログラミングの効率化を図ります。

🚀 **デモサイト**: <https://wipeseals.github.io/riscv-inst-viewer/>

## 特徴

- **命令一覧表示**: RISC-V の各種拡張命令セット（RV32I/RV64I、M、A、F、D、C、Zicsr等）の詳細な一覧表示
- **命令デコード**: 32ビット数値から対応するRISC-V命令を逆引き・デコードする機能
- **アーキテクチャ対応**: RV32とRV64の両アーキテクチャに対応
- **フォーマット可視化**: 各命令のエンコーディングフォーマット（R型、I型、S型等）をビジュアル表示
- **スタンドアロン**: 単一HTMLファイルでの実行が可能で、外部依存関係なし
- **レスポンシブ対応**: デスクトップ・モバイルの両環境で利用可能
- **ダークモード**: ライト・ダークテーマの切り替え対応

## 使用方法

1. `index.html` をブラウザで開く
2. 「Search Instructions」セクションで命令名を検索、または「32-bit Instruction Decoder」で16進数値を入力
3. 命令の詳細情報とエンコーディングを確認

## RISC-V 仕様書・設計情報

- [RISC-V Instruction Set Manual](https://riscv.org/technical/specifications/) - 公式仕様書
- [RISC-V International](https://riscv.org/) - RISC-V 国際団体
- [RISC-V Assembly Programmer's Manual](https://github.com/riscv-non-isa/riscv-asm-manual) - アセンブリプログラミングマニュアル
- [RISC-V Green Card](https://www.cl.cam.ac.uk/teaching/1617/ECAD+Arch/files/docs/RISCVGreenCardv8-20151013.pdf) - 命令セット一覧
- [RISC-V Opcodes](https://github.com/riscv/riscv-opcodes) - 命令セット定義

## 対応拡張

- **RV32I/RV64I**: 基本整数命令セット
- **M**: 乗算・除算拡張
- **A**: アトミック操作拡張  
- **F**: 単精度浮動小数点拡張
- **D**: 倍精度浮動小数点拡張
- **C**: 圧縮命令拡張
- **Zicsr**: CSR 操作拡張
- **Zifencei**: 命令フェンス拡張

## 技術仕様

- **フロントエンド**: HTML5, CSS3, JavaScript (ES6+)
- **スタイリング**: Tailwind CSS
- **対応ブラウザ**: Chrome, Firefox, Safari, Edge (モダンブラウザ)

## 貢献

プルリクエストやイシューの投稿は歓迎します！新しい命令セットの追加や機能改善の提案をお待ちしています。

## インストール

`index.html`をブラウザで開くだけで使用可能です。

## ライセンス

このプロジェクトは MIT ライセンスの下で公開されています。詳細は `LICENSE` ファイルを参照してください。
