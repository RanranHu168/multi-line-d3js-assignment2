# Assignment 2: Multi-Line Chart and Supply Chain Table using D3.js

This project is a solution to **Assignment 2** in the _Data Visualization with Python and JavaScript_ course at UMass Dartmouth. It involves creating a side-by-side dynamic HTML page with both a data table and a multi-line chart, all built using **D3.js**.

## 📋 Assignment Description

We visualize and analyze a supply chain dataset using the following:

- A **dynamic HTML table** with calculated fields:
  - `ActualCost = RawMaterial + Workmanship + StorageCost`
  - `SoldPrice = EstimatedCost × 1.1`
  - `MarginOfProfit = SoldPrice − ActualCost`

- A **multi-line chart** using D3.js with 4 lines:
  1. Estimated Cost
  2. Actual Cost
  3. Sold Price
  4. Margin of Profit

- Styling and formatting with responsiveness and layout structure.

## 📁 Project Structure
multi-line-d3js-assignment2/
├── index.html # The main visualization (table + multi-line chart)
├── Assignment 2.docx # The original assignment instructions
└── README.md # This project documentation
 
> ⚠️ Note: The data file `data_sample.csv` is fetched from a public GitHub URL in the script. You can change the data path if hosting locally.

## 🔧 Technologies Used

- **HTML5 + CSS3**
- **D3.js v7**
- **JavaScript (ES6)**

## 🌐 Live Data Link

The data is loaded from:
      https://raw.githubusercontent.com/RanranHu168/Data-of-assignment-2/main/data_sample.csv

## 📊 Features

- Custom table layout with calculated financial columns
- Interactive D3.js chart with transitions, color legends, and axis formatting
- Uses `d3.scaleTime`, `d3.scaleLinear`, and `d3.schemeCategory10`

## 📚 References

- [D3.js Documentation](https://d3js.org/)
- [ColorBrewer](https://colorbrewer2.org/#type=qualitative&scheme=Paired&n=4)
- [D3 in Depth](https://www.d3indepth.com/)
- [D3.js in Action (Book)](https://www.manning.com/books/d3-js-in-action)

---

💡 **Created by Ranran Hu** for academic submission at UMass Dartmouth.