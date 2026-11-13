# 飛機互動展間

以 Three.js 顯示 FBX 飛機模型的互動式網頁。可拖曳旋轉、滾輪縮放，並切換正面、側面與俯視角度。

## 本機預覽

請在專案根目錄啟動靜態伺服器：

```powershell
python -m http.server 8000
```

再用瀏覽器開啟 <http://localhost:8000>。3D 程式庫由 jsDelivr 載入，預覽時需要網路連線。

## 專案檔案

- `index.html`：網頁與互動控制
- `assets/aircraft.fbx`：飛機模型
