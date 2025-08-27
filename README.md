<h1>🍕 Pizza Sales Dashboard</h1>

<h2>📌 <b>Project Overview</b></h2>
<p>
An <b>interactive Pizza Sales Dashboard</b> analyzing sales data for <b>2015</b>.
</p>

<p><b>Provides insights into:</b></p>
<ul>
  <li><b>Total Revenue</b></li>
  <li><b>Order Trends</b> (daily & monthly)</li>
  <li><b>Top & Bottom-Selling Pizzas</b></li>
  <li><b>Busiest Periods</b></li>
  <li><b>Sales by Category & Size</b></li>
</ul>

<p>👉 Helps in <b>data-driven decision-making</b> by identifying patterns, customer preferences, and performance gaps.</p>

<hr>

<h2>🔄 <b>Workflow</b></h2>

<h3>1. Data Preparation</h3>
<ul>
  <li>Imported Excel data into SQL database.</li>
  <li>Cleaned dataset (duplicates, missing values, formatting).</li>
</ul>

<h3>2. SQL Analysis</h3>
<ul>
  <li><b>KPIs</b>: Revenue, Orders, AOV, Pizzas Sold</li>
  <li><b>Trends</b>: Daily & Monthly orders</li>
  <li>Sales % by <b>Category & Size</b></li>
  <li>Top/Bottom 5 pizzas by <b>Revenue, Quantity, Orders</b></li>
</ul>

<h3>3. Power BI Visualization</h3>
<ul>
  <li>Connected SQL → Power BI</li>
  <li>Cleaned using Power Query</li>
  <li>Built <b>2 dashboards</b>:
    <ul>
      <li>📊 <b>Trends & Sales Performance</b></li>
      <li>📈 <b>Best & Worst Sellers</b></li>
    </ul>
  </li>
</ul>

<hr>

<h2>📷 <b>Sample Dashboards</b></h2>

<p><b>Trends & Sales Performance</b></p>
<img width="800" alt="Trends Dashboard" src="https://github.com/user-attachments/assets/9ee6e6d2-f246-4288-a495-b52e0ee91e29" />

<p><b>Best & Worst Sellers</b></p>
<img width="800" alt="Best Worst Dashboard" src="https://github.com/user-attachments/assets/1b2e30b1-997e-41ef-ba1a-6591800dd86f" />

<hr>

<h2>🛠️ <b>Tools & Technologies</b></h2>
<ul>
  <li><b>Excel</b> → Raw data source</li>
  <li><b>SQL</b> → KPIs, trends & queries</li>
  <li><b>Power Query</b> → Data cleaning</li>
  <li><b>Power BI</b> → Visualization</li>
</ul>

<hr>

<h2>🚀 <b>Key Insights</b></h2>
<ul>
  <li>Peak sales: <b>Friday & Saturday</b></li>
  <li><b>Classic pizzas</b> lead in sales</li>
  <li><b>Large pizzas</b> = ~46% of revenue</li>
  <li><b>Thai Chicken Pizza</b> = top revenue driver</li>
  <li><b>Brie Carre Pizza</b> = weakest performer</li>
  <li>Seasonal spikes in <b>July & January</b></li>
</ul>

<hr>

<h2>📂 <b>Project Structure</b></h2>
<pre>
📁 Pizza-Sales-Dashboard
 ┣ 📂 Data/       # Raw dataset (Excel/CSV)
 ┣ 📂 Queries/    # SQL scripts
 ┣ 📂 Output/     # SQL results & Power BI exports
 ┣ 📂 Images/     # Assets used in creating dashboard
 ┣ 📄 README.md   # Documentation
</pre>

<hr>

<h2>⚡ <b>How to Use</b></h2>

<h3>1. Clone Repository</h3>
<pre>
git clone https://github.com/varshabsamuel18/pizza-sales-excel-sql-powerbi-dashboard.git
cd Pizza-Sales-Dashboard
</pre>

<h3>2. Load Data into SQL</h3>
<ul>
  <li>Create DB (<code>pizza_sales_db</code>)</li>
  <li>Import dataset → <code>pizza_sales</code></li>
  <li>Run queries from <code>SQL QUERIES</code></li>
</ul>

<h3>3. Open Power BI</h3>
<ul>
  <li>Load <code>.pbix</code> file or connect to SQL</li>
  <li>Apply transformations in Power Query</li>
  <li>Explore dashboards with slicers</li>
</ul>

<hr>

<h2>🔮 <b>Future Enhancements</b></h2>
<ul>
  <li>Automate SQL → Power BI refresh</li>
  <li>Add <b>customer segmentation</b></li>
  <li>Apply <b>predictive analytics</b> for forecasting</li>
  <li>Build <b>mobile-friendly dashboards</b></li>
</ul>
