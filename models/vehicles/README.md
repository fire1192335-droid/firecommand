# 車輛模型

此資料夾預留：

- `engine.glb`：11 車與 61 車
- `ladder.glb`：31 車
- `ambulance.glb`：救護車

缺少檔案時使用程式產生的簡易 Three.js 模型。模型路徑集中於 `src/map/vehicles.ts` 的 `modelPaths`。

GLB 採公尺單位、Y 軸向上、-Z 為車頭方向，原點置於地面車體中心。Loader 轉為地圖的 Z-up 座標。替換後重新載入頁面；尺寸、材質與模型授權需自行確認。
