💻 Laptop Prices Dataset  
The Laptop Prices Dataset provides a comprehensive collection of 1,275 laptop models, including their specifications and pricing details. This dataset is ideal for price prediction, trend analysis, and feature comparison across various brands and configurations.  

📂 Dataset Details  
- Total Records: 1,275  
- Total Features: 23  
- File Format: CSV  

📊 Features  
| Column Name          | Description                                      |
|----------------------|--------------------------------------------------|
| Company            | Brand of the laptop (e.g., Dell, Apple, HP)      |
| Product            | Model name                                       |
| TypeName          | Category (e.g., Ultrabook, Gaming, Notebook)     |
| Inches            | Screen size in inches                            |
| ScreenW, ScreenH | Screen resolution width and height (pixels)    |
| Touchscreen       | Indicates if the laptop has a touchscreen (Yes/No) |
| CPU_company       | Processor manufacturer (Intel, AMD)              |
| CPU_freq          | CPU clock speed in GHz                           |
| Ram              | RAM capacity in GB                                |
| GPU_company      | Graphics processor manufacturer                   |
| PrimaryStorage   | Storage capacity (GB)                             |
| PrimaryStorageType | Type of storage (SSD, HDD)                      |
| Weight           | Weight of the laptop (kg)                         |
| Price_euros      | Price in Euros                                    |

🔍 Exploratory Data Analysis  
This dataset has been analyzed using multivariate analysis to uncover trends and relationships between different laptop features. Key insights include:  
✔️ Correlation Analysis – Identifying feature dependencies.  
✔️ Price Distribution by Brand – Examining brand-wise pricing variations.  
✔️ Impact of CPU, GPU, RAM, and Storage on Price – Evaluating how specifications affect cost.  
✔️ Screen Features & Weight Analysis – Understanding their influence on pricing.  
 🚀 Usage Instructions  

### 📥 Download & Load the Dataset  
1. Clone the Repository:  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. Load in Python:  
   ```python
   import pandas as pd
   df = pd.read_csv("Laptop prices.csv")
   ```

