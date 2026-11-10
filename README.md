# 會考自然 知識大挑戰

國中教育會考自然科必背考點的計時競賽遊戲。線上遊玩：https://bgjd315-cloud.github.io/cap-science-game/

- 題庫：整理自[會考自然考點地圖](https://bgjd315-cloud.github.io/cap-science-map/)與南一版自然七上～九下課本，共 2404 題；再逐題比對 103～115 年歷屆會考自然科試題，只保留考過的 1302 題，並標示考過的年份。
- 模式：極速 60 秒、生存挑戰、單元特訓、雙人對決、錯題特訓、排行榜、考點圖鑑。
- 學習紀錄與排行榜只存在各自的裝置（瀏覽器 localStorage）。

## 維護
- `src/bank*.js`：題庫原檔；`src/exam_match.json`：歷屆會考比對結果（keep／考過年份）
- `src/template.html`：遊戲本體
- `node build.js`：組合出 `index.html`
- 圖片：Gemini 畫好的圖放 `img_raw/`（檔名見 `Gemini生圖提示詞.md`），執行 `python tools/process_images.py` 去背縮圖到 `img/`，再 `node build.js`
