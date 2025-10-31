# 3LC Cottom Weed Detection (YOLOv8n only)
This competition is an object detection task aimed at identifying and classifying weeds (Carpetweed, Morning Glory, and Palmer Amaranth) in cotton fields. Due to real-world operational constraints, the model is limited to YOLOv8n, among other restrictions. The main objective is to achieve maximum performance within these real-world constraints using 3LC (Three Line Code).

<figure style="text-align: center;">
  <a href="https://www.youtube.com/watch?v=j2wSE3h9N7o" target="_blank">
    <img src="http://img.youtube.com/vi/j2wSE3h9N7o/0.jpg" alt="3LC" width="400" style="border-radius: 8px;">
  </a>
  <figcaption style="font-size: 14px; color: gray; margin-top: 6px;">
    🎥 3LC (Three Line Code)
  </figcaption>
</figure>

## Rule
✅ ALLOWED:
- YOLOv8n model only (REQUIRED)
- Hyperparameter tuning
- Data augmentation (training-time)
- Label corrections and improvements
- Confidence threshold adjustment

❌ PROHIBITED:
- Larger models (YOLOv8s, YOLOv8m, etc.)
- Model ensembles / stacking
- Different architectures
- Post-processing beyond standard NMS
- External data sources
- Test-Time Augmentation (TTA) 

## Dataset
Dataset: 542 training + 133 validation + 170 test images
| Class | Details |
| --- | --- | 
|0: carpetweed | |
|1: morningglory  | |
|2: palmer_amaranth |  |

## Links
| Source | Link | Details | 
| --- | --- | --- | 
| Doc | [3LC](https://docs.3lc.ai/3lc/latest/user-guide/index.html) | Documentation for 3LC |

## Log


