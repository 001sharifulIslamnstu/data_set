## 3. Contents
| Component      | Description |
|----------------|-------------|
| **Train Set**  | `N` samples for training models. |
| **Test Set**   | `M` samples for evaluating performance. |
| **Metadata**   | Optional contextual information such as demographics, timestamps, environment variables. |
| **Labels**     | Ground-truth annotations for supervised tasks. |

## 4. File Formats
- Images: `.jpg`, `.png`, `.tiff`  
- Tabular: `.csv`, `.xlsx`, `.json`  
- Annotations: `.json`, `.txt`, `.xml`  
- Audio/Video (optional): `.wav`, `.mp4`

## 5. Features / Variables
| Feature Name | Type | Description | Example |
|--------------|------|-------------|---------|
| `feature_1`  | numeric/categorical | Explanation | `12.4`, `high` |
| `feature_2`  | numeric/categorical | Explanation | `0`, `1` |
| `label`      | class/continuous    | Target variable | `0–4` |

## 6. Data Collection
Describe how the dataset was collected: **[sensor, survey, device, scraping, simulation]**. Include ethical or licensing considerations if applicable.

## 7. Preprocessing
Optional steps:
- Normalization / Standardization  
- Missing value handling  
- Image resizing  
- Data augmentation  
- Metadata cleaning  

## 8. Usage Instructions
### Load Example (Python)
```python
import pandas as pd
import os

metadata = pd.read_csv("metadata/metadata.csv")
train_img_dir = "train/images/"
