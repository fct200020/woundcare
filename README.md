# WoundCare
**This project is for educational purposes only. **

<h1>Description</h1>
WoundCare ( Zhiyu ) is a AI model dataset which devlopped by Fong Chong School of Taipa. The purpose of this project is to assit users to detect the catagories of wounds by high precision and fast efficiency model.

<h1>Download</h1>
<table class="tg"><thead>
  <tr>
    <th class="tg-0lax">Dataset</th>
    <th class="tg-0lax">
        <a href="https://universe.roboflow.com/fct-wound-ai/woundcare-opensource-dataset">
    <img src="https://app.roboflow.com/images/download-dataset-badge.svg"></img>
</a>
    </th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-0lax">Model ( YOLO11I )</td>
    <td class="tg-0lax">Not Available</td>
  </tr>
</tbody>
</table>


<h1>Model</h1>
WoundCare Model (Zhiyu) was trained using the YOLO11I architecture on an Nvidia A100 GPU. The training process involved 7,686 annotated images over 100 epochs to optimize detection accuracy. To enhance model robustness and generalization, data preprocessing and augmentation techniques were rigorously applied, including:

 <ul>  
            <li><strong>Auto-orientation correction</strong> <em>(standardized image alignment)</em></li>  
            <li><strong>Resizing</strong> <em>(input dimensionality consistency)</em></li>  
            <li><strong>Spatial augmentations:</strong>  
                <ul>  
                    <li style="margin-left: 20px;">- Horizontal/vertical flipping</li>  
                    <li style="margin-left: 20px;">- Rotation</li>  
                </ul>  
            </li>  
            <li><strong>Photometric adjustments:</strong>  
                <ul>  
                    <li style="margin-left: 20px;">- Brightness variation</li>  
                </ul>  
            </li>  
            <li><strong>Noise injection</strong> <em>(artifact resilience enhancement)</em></li>  
  </ul>  
  

<h1>License</h1>
This dataset and model are licensed under two Licenses. During training process, please note that our model has used :

<ul>
  <li>WoundCare Dataset: BY-NC-SA 4.0</li>
  <li>WoundCare Model: AGPL-3.0 License</li>
</ul>

