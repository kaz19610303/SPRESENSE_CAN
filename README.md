# SPRESENSE_CAN
Sony Spresense用の***CANインターフェースボード***です。

このボードに使用しているCANインタフェースICは***Microchip***社の***MCP2515T-E_ST***です。
MCP2515は、第2世代のスタンドアロンCANコントローラです。MCP2510とピンおよび機能の互換性があり、より高速なスループット、データバイト・フィルタリング、タイムトリガー・プロトコルのサポートなどのアップグレードされた機能が含まれています。
詳しくは以下のデータシートをご覧下さい。
[MCP2515 データシート](https://www.mouser.jp/datasheet/2/268/MCP2515-Stand-Alone-CAN-Controller-with-SPI-200018-708845.pdf)

回路図とEagle用のデータはGithubにて公開しています。
[kaz19610303/SPRESENSE_CAN](https://github.com/kaz19610303/SPRESENSE_CAN)

ジャンパー設定
SJ1　INTピン選択　1: EMMC_DATA2　3:I2S_LRCK
SJ2　csピン選択　 1: I2S_DIN　   3:SPI_CS
SJ3　ショートで終端抵抗有効
