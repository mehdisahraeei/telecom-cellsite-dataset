# 📡 Synthetic Telecom Cell Site Dataset (Iran)

This repository provides a **synthetic dataset** simulating telecom cell site configurations in Iran, designed for **machine learning**, **network modeling**, and **educational purposes**.

> ⚠️ All data is **fictitious** and does **not** represent any real-world or confidential information.

---

## 📁 Dataset Features

Includes over 30 fields such as:

- 📍 Site type, tower type, height  
- 📶 Technology counts (2G to 5G)  
- 📡 Antenna specs (per sector: angle, tilt, tip)  
- ⚡ Power metrics & phase codes  
- 🌐 Link type & load percentage  

📂 File: `dataset/dataset-tci.csv`

---

## 🔍 Sample Data Preview

| site code   | sharing | type     | tower type         | height | 2G | 3G | 4G | 5G | vendor   | angle1 | tilt1 | tip1   | link    | load |
|-------------|---------|----------|---------------------|--------|----|----|----|----|----------|--------|--------|--------|---------|------|
| MTR_f624pd0 | yes     | Outdoor  | Lattice             | 42     | 1  | 0  | 1  | 0  | Antenkar | 300    | 0      | 8X-pol | MW      | 87%  |
| MTR_t118ka1 | yes     | Outdoor  | NB Lattice Tower    | 42     | 3  | 3  | 4  | 2  | Antenkar | 350    | 0      | 12X-pol| MW      | 72%  |
| MTR_a155mz1 | no      | Indoor   | Lattice             | 36     | 2  | 2  | 2  | 1  | Takta    | 111    | 1      | 5X-Pol | BW-ETH  | 74%  |
| MTR_u836qu0 | yes     | Outdoor  | Lattice             | 54     | 2  | 2  | 2  | 1  | Huawei   | 111    | 2      | 4X-Pol | Fiber   | 54%  |
| MTR_e703lo1 | no      | Indoor   | Lattice             | 42     | 1  | 0  | 1  | 0  | Huawei   | 357    | 0      | 8X-pol | Fiber-TCX| 75%  |

---

## 💡 Use Cases

- ML & DL model testing (clustering, classification)  
- Educational notebooks 
- Data visualization practice 


## 👤 Author

**Mehdi Sahraei** – Ilam, Iran  
📧 mahdi_sahrai@yahoo.com | [🔗 LinkedIn](https://www.linkedin.com/in/mehdisahraei)


## 📝 License

Free for research and educational use
