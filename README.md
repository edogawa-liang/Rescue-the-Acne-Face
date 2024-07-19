# Rescue the Acne Face
## Goal
我們的目標是通過深度學習技術實現臉部痘痘的去除。痘痘不僅影響美觀，還可能對人們的自信心造成影響。為了實現這一目標，我們探索並比較了多種圖像處理方法，包括 YOLO + Inpainting 和 Pix2Pix 等等。

## Contain
以下簡單說明每個資料夾內的方法與用途:
- **YOLO**: 含有YOLO v8我們的使用方式與說明

- **Inpainting**: 含有inpainting的使用方式與流程。

- **Filter**: 含有Filter的使用與說明

- **pix2pix**: 含有資料前處理與pix2pix模型。

- **Result**: 問卷分析的方式與過程。

- **RescueAcneFace_Report.pdf**: 書面報告。

- **RescueAcneFace_Oral.pdf**: 簡報。

## Method Overview
![Method Overview](./pix2pix/samples/method.png)

## Result
以下展示我們使用不同方法的結果對比：


<table>
    <tr>
        <th style="text-align:center">Original</th>
        <th style="text-align:center">Median Filter</th>
        <th style="text-align:center">Inpainting</th>
        <th style="text-align:center">Pix2Pix</th>
    </tr>
    <tr>
        <td style="text-align:center"><img src="./pix2pix/samples/origin-1.jpg" alt="Original" width="200"></td>
        <td style="text-align:center"><img src="./pix2pix/samples/m-filter-1.jpg" alt="Median Filter" width="200"></td>
        <td style="text-align:center"><img src="./pix2pix/samples/inpainting-1.jpg" alt="Inpainting" width="200"></td>
        <td style="text-align:center"><img src="./pix2pix/samples/pix2pix-1.png" alt="Pix2Pix" width="200"></td>
    </tr>
    <tr>
        <td style="text-align:center"><img src="./pix2pix/samples/origin-2.jpg" alt="Original" width="200"></td>
        <td style="text-align:center"><img src="./pix2pix/samples/m-filter-2.jpg" alt="Median Filter" width="200"></td>
        <td style="text-align:center"><img src="./pix2pix/samples/inpainting-2.jpg" alt="Inpainting" width="200"></td>
        <td style="text-align:center"><img src="./pix2pix/samples/pix2pix-2.png" alt="Pix2Pix" width="200"></td>
    </tr>
</table>
