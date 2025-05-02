
# Football Talent Identifier
![picture](https://github.com/user-attachments/assets/53c20951-34ca-4798-b2e7-1673817d12fc)

This project aims to identify young and high-potential football players using data analysis. FIFA 21 player data is used to discover and analyze promising talents.

## 📁 Project Structure

football-talent-identifier/
│
├── data/                     # Dataset and output files
├── analysis.ipynb            # Main analysis notebook
└── README.md                 # Project description


## 📊 Dataset Used

- **Dataset:** `players_21.csv` (FIFA 21 dataset)
- **Source:** [Kaggle - FIFA 21 complete player dataset](https://www.kaggle.com/datasets/stefanoleone992/fifa-21-complete-player-dataset)

## 🔍 Objective

- Identify young football players with high potential
- Rank clubs based on the number of such players
- Visualize the findings

## 📈 Analysis Steps

1. Load and filter the data
2. Sort by potential and age
3. Select players under age 21 with potential above 85
4. Visualize key insights
5. Export the final list to a `.csv` file

## 🧰 Libraries Used

- `pandas`
- `matplotlib`
- `seaborn`
- `os`

## 📦 Installation

```bash
pip install pandas matplotlib seaborn
```

## 🖼️ Sample Visualization

[YoungTalents](YoungTalents.png)

## 📁 Output

- List of young high-potential players
[genclik_yetenek_listesi.xlsx](https://github.com/user-attachments/files/20013120/genclik_yetenek_listesi.xlsx)


## ✍️ Contribution

Feel free to open a pull request if you'd like to contribute!
