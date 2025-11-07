# Car Specifications Data Analysis with Python

**Project from:** *13 Python Data Analytics Real World Hands-on Projects* (Udemy)  
**Dataset:** `Cars Data.csv` – 432 car models with performance & pricing specs

---

## Project Overview
This project analyzes a **comprehensive dataset of car specifications** using **Pandas**. It includes **make, model, type, engine size, horsepower, fuel economy (MPG), pricing (MSRP & Invoice), weight, dimensions**, and more — ideal for automotive market analysis.

---

## Dataset Columns
| Column           | Description |
|------------------|-----------|
| `Make`           | Brand (e.g., Toyota, BMW) |
| `Model`          | Car model |
| `Type`           | Body style (Sedan, SUV, etc.) |
| `Origin`         | Asia, Europe, USA |
| `DriveTrain`     | Front, Rear, All |
| `MSRP`           | Manufacturer's Suggested Retail Price |
| `Invoice`        | Dealer invoice price |
| `EngineSize`     | Engine displacement (liters) |
| `Cylinders`      | Number of cylinders |
| `Horsepower`     | HP |
| `MPG_City`       | City fuel economy |
| `MPG_Highway`    | Highway fuel economy |
| `Weight`         | Curb weight (lbs) |
| `Wheelbase`      | Wheelbase length (inches) |
| `Length`         | Overall length (inches) |

---

## Key Analysis Performed
- Loaded and cleaned car dataset
- Handled **missing values** and **incorrect column names**
- Explored relationships between:
  - **Price vs Performance** (HP, MPG)
  - **Weight vs Fuel Economy**
  - **Engine Size vs Horsepower**
- Filtered by **origin**, **type**, and **drivetrain**

> **Sample Insight:**  
> Average MSRP by Origin:  
> - **Europe**: ~$45,000  
> - **Asia**: ~$28,000  
> - **USA**: ~$33,000

---

## Tools & Libraries
```python
pandas

```

### Insights Gained

- **European cars** have the **highest average MSRP**  
- **Horsepower strongly correlates** with **engine size and weight**  
- **Higher MPG** is common in **lighter, smaller-engine cars**  
- **SUVs dominate weight**, **sedans lead in fuel efficiency**  
- **Useful for car pricing models, consumer reports, and market segmentation**
