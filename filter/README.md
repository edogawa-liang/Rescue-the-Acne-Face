# filter
有兩個function，process_images()與apply_filter()
## apply_filter(image, bbox, filtertype)
第一個參數為傳入的圖片  
第二個參數為圖取文件獲得的bounding box  
第三個參數可以選擇使用的filter  

## process_images(image_folder, label_folder, output_folder, filter_type)
第一個參數為包含image的folder路徑  
第二個參數為label的txtfolder路徑  
第三個參數為output的folder路徑  
最後為選擇使用的filter  
此function會呼叫apply_filter()  

## 執行
設定image_folder, label_folder, output_folder, filter_type  
放入process_images()並執行即可獲得處理後的圖片

