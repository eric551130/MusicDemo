# 評分指南
評分網址:https://forms.gle/o8tWFqqzEUQuDCds9
共有三種不同生成方式:
1. Unconditional Generation
2. Prompt-Based Generation: 模型輸入是一個測試資料集的樂句
2. Phrase-Based Generation: 模型輸入是一個測試資料集的樂句，且樂句結構和該測試資料集一樣，因此小節長度相等

有條件生成任務中，每個資料夾有三個midi檔案，包含專家、模型A、模型B；無條件任務中，只包含模型生成音樂。

# 其他論文的DEMO

## Theme Transformer: Symbolic Music Generation with Theme-Conditioned Transformer

https://atosystem.github.io/ThemeTransformer/

* 編碼REMI
* POP909三個音軌捨棄副旋律，只保留旋律和和弦兩個音軌
* 模型輸入是測試資料集

## Structure-Enhanced Pop Music Generation via Harmony-Aware Learning
https://www.zhangxueyao.com/data/HAT/demo.html

* 編碼CP
* POP909三個音軌都保留
* DEMO網站上面音樂是無條件生成，只有最後一個case study是輸入是一個測試資料集的樂句


## POP MUSIC GENERATION WITH CONTROLLABLE PHRASE LENGTHS
https://miltokyo.github.io/phrase-length-designated-music-generation/

* 編碼REMI和CP都有測試
* POP909三個音軌都保留
* 模型輸入只有用樂句標籤，並沒有使用測試資料當作音樂輸入，因此生成內容大多來自專家音樂