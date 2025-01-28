# WoundCare  
**本項目僅用於教育用途**  

<h1>項目描述</h1>
WoundCare（智愈）是由氹仔坊眾學校開發的AI模型與數據集。該項目旨在通過高精度、高效率的模型，協助用戶識別不同類別的傷口。

<h1>資源下載</h1>
<table class="tg"><thead>
  <tr>
    <th class="tg-0lax">數據集</th>
    <th class="tg-0lax">
        <a href="https://universe.roboflow.com/fct-wound-ai/woundcare-opensource-dataset">
    <img src="https://app.roboflow.com/images/download-dataset-badge.svg"></img>
</a>
    </th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-0lax">模型（YOLO11I）</td>
    <td class="tg-0lax">請於版本發布頁面查看</td>
  </tr>
</tbody>
</table>

<h1>模型架構</h1>
WoundCare模型（智愈）基於YOLO11I架構，使用Nvidia A100 GPU進行訓練。訓練過程涵蓋7,686張標註圖像，歷經100個訓練周期以優化檢測精度。為提升模型的魯棒性和泛化能力，採用以下數據預處理與增強技術：

 <ul>  
            <li><strong>自動方向校正</strong> <em>（標準化圖像方位）</em></li>  
            <li><strong>尺寸歸一化</strong> <em>（確保輸入維度一致性）</em></li>  
            <li><strong>空間增強技術：</strong>  
                <ul>  
                    <li style="margin-left: 20px;">- 水平/垂直翻轉</li>  
                    <li style="margin-left: 20px;">- 旋轉</li>  
                </ul>  
            </li>  
            <li><strong>光度調整：</strong>  
                <ul>  
                    <li style="margin-left: 20px;">- 亮度變化</li>  
                </ul>  
            </li>  
            <li><strong>噪聲注入</strong> <em>（增強抗成像偽影能力）</em></li>  
  </ul>  

<h1>許可協議</h1>
本數據集與模型遵循雙許可協議。請注意，模型訓練過程中使用了以下授權資源：

<ul>
  <li>WoundCare數據集：採用 CC BY-NC-SA 4.0 協議</li>
  <li>WoundCare模型：採用 AGPL-3.0 協議</li>
</ul>
