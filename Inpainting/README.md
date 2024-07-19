# Inpainting
## Inpainting 模型需要三個基本的輸入參數
### 1. 原始圖片
### 2. 需要被 inpaint 的區域（mask image）
### 3. inpaint 內容(文字敘述)

## 程式碼流程
### 1. 設定原始圖片路徑(img_path) & yolo 輸出路徑(label_path) & 圖片座標範圍輸出路徑(pos_path) & inpainting輸出結果儲存路徑(save_path)
### 2. 透過 yolo ouput 計算每張圖片座標位置並輸出到 pos_path
### 3. 讀取 pos_path 創建 3 維 mask image
### 4. 原始圖片與 mask image 送進 Inpainting model 產生結果存入(save_path)

## 參考連結
### https://huggingface.co/docs/diffusers/using-diffusers/inpaint 