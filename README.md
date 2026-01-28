# WoundCare
**This project is for educational purposes only. **

<h1>Description</h1>
WoundCare ( Zhiyu ) is a AI model dataset and application which devlopped by Zhiyu WoundCare Team in Fong Chong School of Taipa. The purpose of this project is to assit users to detect the catagories of wounds by high precision and fast efficiency model. 

<h1>Model & Dataset Download</h1>
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
    <td class="tg-0lax">View in Releases</td>
  </tr>
</tbody>
</table>

<h1>Application Download</h1>
Download the application from the Releases section. Android and iOS version are available. Please note that the application is still in development and may not be fully functional.

<a href="https://testflight.apple.com/join/MyWKt6Wa">
  <img height=75 alt="Get the beta on TestFlight" src="https://askyourself.app/assets/testflight.png"/>
</a>

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

Our model's overall metrics are listed below:
<b>Model accuracy measured on validation set</b>
![圖片 1](https://github.com/user-attachments/assets/336727b9-e0b9-4ebd-87ff-842b14a44a90)
![pics2](https://github.com/user-attachments/assets/c7b8e003-6b92-4319-b0a2-7c39dc18a943)
![pics1](https://github.com/user-attachments/assets/c3edd810-0a9f-43c8-ac52-c9f433ae020f)
![pics](https://github.com/user-attachments/assets/10b6a157-c2d3-4e7d-84eb-30a20a472b55)


<h1>License</h1>
This dataset and model are licensed under two Licenses. During training process, please note that our model has used :


<ul>
  <li>WoundCare Dataset: <a href="https://github.com/fct200020/woundcare/blob/main/LICENSE-DATASET">BY-NC-SA 4.0</a></li>
  <li>WoundCare Model: <a href="https://github.com/fct200020/woundcare/blob/main/LICENSE-MODEL">AGPL-3.0 License</a></li>
</ul>

