# 🐍 Vectorized String Operations and Time Series Analysis

## 📝 Description
This Python script demonstrates **vectorized string operations** and **time series analysis** using **Pandas**. It covers string manipulations, date/time operations, and time series visualization. The script also includes examples of resampling, rolling windows, and grouping data by time intervals.

## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/navidfalah/vectorized-string-time-series.git
   cd vectorized-string-time-series
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Install additional libraries:
   ```bash
   pip install pandas matplotlib numpy
   ```

## 🚀 Usage
1. Run the script:
   ```bash
   python vectorized_string_time_series.py
   ```
2. The script will:
   - Perform vectorized string operations on Pandas Series.
   - Manipulate and analyze date/time data.
   - Visualize time series data using Matplotlib.
   - Demonstrate resampling, rolling windows, and grouping by time intervals.

## 📂 File Structure
```
vectorized-string-time-series/
├── vectorized_string_time_series.py  # Main script
├── README.md                         # This file
├── requirements.txt                  # Dependencies
└── data/                             # (Optional) Data folder for local inputs
```

## 🧩 Key Features
- **Vectorized String Operations**:
  - Capitalize, lowercase, and split strings in Pandas Series.
  - Check if strings start with a specific character or substring.
- **Date/Time Operations**:
  - Parse and format date/time strings.
  - Create date ranges and perform time-based indexing.
- **Time Series Analysis**:
  - Resample time series data (e.g., daily to weekly).
  - Apply rolling windows and Gaussian smoothing.
  - Group data by time intervals (e.g., weekdays vs. weekends).
- **Visualization**:
  - Plot time series data using Matplotlib.
  - Visualize trends and patterns in time series data.

## 📊 Example Outputs
1. **String Operations**:
   - Capitalized names: `['Peter', 'Paul', 'Mary']`.
2. **Time Series Plot**:
   - Hourly bicycle count over time.
3. **Resampled Data**:
   - Weekly bicycle count with different line styles.
4. **Rolling Mean**:
   - 30-day rolling mean of hourly bicycle count.
5. **Grouped Data**:
   - Average bicycle count by weekday and weekend.

## 🤖 Libraries Used
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization.
- **NumPy**: For numerical computations.

## 📈 Performance Metrics
- **Efficiency**: Vectorized operations for fast string and date/time manipulations.
- **Flexibility**: Supports a wide range of time series analysis techniques.

## 🛠️ Dependencies
- Python 3.x
- Libraries:
  - `pandas`, `matplotlib`
  - `numpy`, `dateutil`

## 🤝 Contributing
1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -m "Add your feature"`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a pull request.

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 👤 Author
- **Name**: Navid Falah
- **GitHub**: [navidfalah](https://github.com/navidfalah)
- **Email**: navid.falah7@gmail.com
