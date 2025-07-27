## 📊 Google Search Trends Analysis

This project utilizes the **Google Trends API (Pytrends)** to analyze public interest over time for specific keywords. It visualizes how search interest changes over the past year using matplotlib, allowing quick insights into what people are searching for online.

---

### 📌 Features

* 📈 Retrieves search interest using `pytrends`
* 🗓️ Shows trends over the last 12 months
* 🧠 Plots data using `matplotlib`
* 🖱️ Customizable: Search any keyword you want
* 🛠️ Clean error handling for rate limits and multiple requests

---

### 🛠️ Tools & Technologies

* Python 3.13
* Pytrends (Google Trends API)
* Matplotlib
* Pandas

---

### 🚀 How to Run

1. **Clone the repo**:

   ```bash
   git clone https://github.com/your-username/google-search-analysis.git
   cd google-search-analysis
   ```

2. **Install requirements**:

   ```bash
   pip install pytrends pandas matplotlib
   ```

3. **Run the notebook**:
   Open `Google search analysis.ipynb` in Jupyter Notebook or VSCode and run the cells.

---

### 🖼️ Example Output

The project outputs a line chart like this:

```
Search Interest over time "cloud computing"
        |
    100 |         ●
     75 |       ●
     50 |     ●
     25 |  ●
      0 +-----------------> Time
```

---

### 🧩 Customization

You can modify the `keyword` in the notebook to analyze any other search term:

```python
keyword = "your topic"
```

---

### 🧠 Learning Outcome

This project helped me understand:

* How to use `pytrends` to connect with Google Trends data
* Working with time series data in Pandas
* Handling rate limits (HTTP 429)
* Building clean, reusable data analysis code

---

### 📜 License

This project is under the [MIT License](LICENSE).

---
