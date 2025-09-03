\# ✈️ Airlines Data Analysis using SQL \& Python



An end-to-end project analyzing \*\*airline booking, flights, and aircraft data\*\* using \*\*SQL \& Python\*\* to provide actionable insights for \*\*occupancy rate optimization\*\* and \*\*profitability improvement\*\*.



---



\## 📑 Table of Contents

\- <a href="#overview">Overview</a>

\- <a href="#problem-statement">Problem Statement</a>

\- <a href="#dataset">Dataset</a>

\- <a href="#project-structure">Project Structure</a>

\- <a href="#tools--technologies">Tools \& Technologies</a>

\- <a href="#methods">Methods</a>

\- <a href="#key-insights">Key Insights</a>

\- <a href="#visualizations--outputs">Visualizations \& Outputs</a>

\- <a href="#how-to-run-this-project">How to Run This Project</a>

\- <a href="#results--conclusion">Results \& Conclusion</a>

\- <a href="#author--contact">Author \& Contact</a> 



---

<h2><a class="anchor" id="overview"></a>📖 Overview</h2>



The project analyzes \*\*airline operations data\*\* to identify factors affecting profitability.  

It focuses on \*\*occupancy rates, pricing strategies, and revenue analysis\*\*, ultimately helping airlines improve profitability by \*\*optimizing seat usage\*\* and \*\*pricing models\*\*.



---

<h2><a class="anchor" id="problem-statement"></a>❓ Problem Statement</h2>



Airlines face challenges such as:

\- Stricter environmental regulations  

\- Higher flight taxes  

\- Rising fuel prices  

\- Tight labor market → higher labor costs  



👉 To address this, the company needs to \*\*increase occupancy rates\*\* and optimize pricing strategies.



---

<h2><a class="anchor" id="dataset"></a>📊 Dataset</h2>



\*\*Dataset:\*\*  

\- Source: SQLite database (`travel.sqlite`)  

\- Tables: `aircrafts\_data`, `airports\_data`, `boarding\_passes`, `bookings`, `flights`, `seats`, `ticket\_flights`, `tickets`  



---

<h2><a class="anchor" id="project-structure"></a>📂 Project Structure</h2>



```

airlines-data-analysis-sql-python/

│── Notebooks/

│ └── airlines\_analysis.ipynb

│── Scripts/

│ └── airlines\_analysis.py

│── Outputs/

│ ├── tickets\_over\_time.png

│ ├── revenue\_over\_time.png

│ ├── avg\_fare\_conditions.png

│ ├── occupancy\_rate.png

│── Images/

│ └── dashboard\_screenshots.png

│── README.md

│── Requirements.txt

│── travel.sqlite (Database file)

```

---

<h2><a class="anchor" id="tools--technologies"></a>🛠 Tools \& Technologies</h2>



\- \*\*Languages:\*\* Python, SQL  

\- \*\*Libraries:\*\* Pandas, Matplotlib, Seaborn, SQLite3  

\- \*\*Database:\*\* SQLite  

\- \*\*Version Control:\*\* Git \& GitHub  



---

<h2><a class="anchor" id="methods"></a>🔎 Methods</h2>



1\. \*\*Understanding Business Problem\*\* 

&nbsp;  – identifying challenges in profitability \& occupancy.

&nbsp; 

2\. \*\*Database Connection \& Exploration\*\* 

&nbsp;  – extracting tables and metadata from SQLite. 

&nbsp;

3\. \*\*Data Cleaning \& Preparation\*\* 

&nbsp;  – handling nulls, checking data types.

&nbsp; 

4\. \*\*Revenue \& Ticket Trend Analysis\*\* 

&nbsp;  – line plots for bookings \& revenue over time.

&nbsp; 

5\. \*\*Fare Condition Analysis\*\* 

&nbsp;  – average ticket prices across classes (Economy, Business, Comfort). 

&nbsp; 

6\. \*\*Occupancy Rate Analysis\*\* 

&nbsp;  – seats booked vs total available seats.  



7\. \*\*Scenario Simulation\*\* 

&nbsp;  – impact of +10% occupancy rate on annual turnover.  



8\. \*\*Visualization \& Reporting\*\* 

&nbsp;  – business-friendly insights for decision-making.  



---

<h2><a class="anchor" id="key-insights"></a>📈 Key Insights</h2>



\- \*\*Occupancy Rate\*\* is directly linked with profitability.  

\- \*\*SU9 Aircraft\*\* generated the highest total revenue, mainly due to competitive pricing.  

\- \*\*CN1 Aircraft\*\* had the lowest revenue (limited to economy class, fewer facilities).  

\- \*\*Business fares are consistently higher than economy\*\*, across all aircrafts.  

\- Increasing occupancy rate by \*\*10% leads to a proportional revenue increase\*\*.  



---

<h2><a class="anchor" id="visualizations--outputs"></a>📊 Visualizations \& Outputs</h2>



\- \*\*Tickets Over Time (Line Chart):\*\* Shows peak in bookings between June 22 – July 7.

&nbsp; !\[Tickets Bookings](Outputs/tickets\_over\_time.png)



\- \*\*Revenue Over Time:\*\* Revenue trend mirrors ticket sales trend.

&nbsp; !\[Revenue Trends](Outputs/revenue\_over\_time.png)



\- \*\*Fare Condition Comparison (Bar Chart):\*\* Pricing across Economy, Business, Comfort.

&nbsp; !\[Fare Condition](Outputs/avg\_fare\_conditions.png)



\- \*\*Occupancy Rate Analysis:\*\* Seats booked vs total seats per aircraft.

&nbsp; !\[Booked Vs Total Seats](Outputs/occupancy\_rate.png)



\- \*\*Revenue Simulation (+10% Occupancy):\*\* Demonstrates potential revenue growth.  

&nbsp; !\[Revenue Growth/revenue\_growth\_by 10%\_occupancy.png)

---

<h2><a class="anchor" id="how-to-run-this-project"></a>🚀 How to Run This Project</h2>





\### 🔧 Step 1: Clone Repository



```bash

git clone https://github.com/yourusername/airlines-data-analysis-sql-python.git

cd airlines-data-analysis-sql-python

```



\### 🔧 Step 2: Install Dependencies



```bash

pip install -r Requirements.txt

```



\### 🔧 Step 3: Run Jupyter Notebook



```bash

jupyter notebook Notebooks/airlines\_analysis.ipynb

```

--- 

<h2><a class="anchor" id="results--conclusion"></a>✅ Results \& Conclusion</h2>



\- Identified key aircraft performance gaps.

\- Demonstrated how occupancy rate optimization directly improves revenue.

\- Suggested pricing adjustments for underperforming aircraft.

\- Provided a framework for ongoing airline data analysis.



---

<h2><a class="anchor" id="author--contact"></a>👨‍💻 Author \& Contact</h2>



\*\*Golla Sai Deep\*\*



📧 Email: saideepcct@gmail.com



🔗 LinkedIn: Your LinkedIn Profile



🔗 GitHub: Your GitHub Profile

