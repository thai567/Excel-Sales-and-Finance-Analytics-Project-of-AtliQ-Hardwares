# Excel-Sales-and-Finance-Analytics-Project-of-AtliQ-Hardwares
#   𝐎𝐛𝐣𝐞𝐜𝐭𝐢𝐯𝐞: -
AtliQ, a company that sells hardware such as PCs, mice, printers, and other devices to various customers, serves two types of clients: physical stores known as brick-and-mortar establishments like Croma and Best Buy, and e-commerce platforms like Amazon and Flipkart. The business users at AtliQ have been provided with files containing over 1.5 million records to create sales and financial reports for the company.



#  𝐓𝐡𝐞 𝐑𝐞𝐩𝐨𝐫𝐭 𝐜𝐨𝐧𝐬𝐢𝐬𝐭𝐬 𝐨𝐟: -

# Sales Report
1. Customer Net Sales Performance Report 
2. Market Performance vs Target Report 
3. Top 10 Products 
4. Division Level Report
5. Top & Bottom 5 Products  
6. New Product - 2021     

# Finance Report
1. P&L yearly  
2. P&L Monthly   
3. P&L Market 
4. GM% Quartely

 
# ➡️ 𝐒𝐭𝐞𝐩𝐬 𝐢𝐧𝐯𝐨𝐥𝐯𝐞𝐝 𝐢𝐧 𝐦𝐚𝐤𝐢𝐧𝐠 𝐭𝐡𝐢𝐬 𝐑𝐞𝐩𝐨𝐫𝐭: -

1. 𝐄𝐓𝐋 (𝐄𝐱𝐭𝐫𝐚𝐜𝐭 𝐓𝐫𝐚𝐧𝐬𝐟𝐨𝐫𝐦 𝐚𝐧𝐝 𝐋𝐨𝐚𝐝)
Load all the CSV files that were provided, to Power Query. Ensured there were no missing values, all dimension tables contained a unique column, removed duplicate values, corrected the spelling errors, and in the end loaded the files in the Power Pivot.
 
 
2. 𝐃𝐚𝐭𝐚 𝐌𝐨𝐝𝐞𝐥𝐢𝐧𝐠
Connect all the tables using star schema. Create a new table dim_date using Power Query that includes the date, month, and year in a separate column. Add a new column for adding AtiliQ Hardware Fiscal year that runs from September to August and then connect the table with others.
 
3. 𝗣𝗶𝘃𝗼𝘁 𝗧𝗮𝗯𝗹𝗲 𝗮𝗻𝗱 𝗣𝗼𝘄𝗲𝗿 𝗣𝗶𝘃𝗼𝘁
Integrate the data model with a Pivot Table for quick data analysis. Utilize Power Pivot to create new measures and columns. Employ Power Query for seamless data transformation and connectivity, streamlining the entire process of preparing and analysing data efficiently.
 
 
4. 𝐃𝐀𝐗 (𝐃𝐚𝐭𝐚 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬 𝐄𝐱𝐩𝐫𝐞𝐬𝐬𝐢𝐨𝐧)
Create 10 + new Measures such as Net sales for each year, Gross Margin, GM %, and COGS using Formulas like Calculate, Sum, Divide, etc. Create new Columns using Functions like Related, Calculate, Format and extract quarterly months by adding 4 months to the calendar year for a fiscal year perspective.
 
 
5. 𝐂𝐨𝐧𝐝𝐢𝐭𝐢𝐨𝐧𝐚𝐥 𝐅𝐨𝐫𝐦𝐚𝐭𝐭𝐢𝐧𝐠
Applied Conditional Formatting to enhance data presentation by applying rules, and formatting numbers and text. This approach highlights important data, identifies trends, and improves overall data readability for more effective analysis.

# 💡 𝐈𝐧𝐬𝐢𝐠𝐡𝐭𝐬:-
1. In 2021, India emerged as the top-performing market with the highest net sales of $161.3 million, while Sweden recorded the lowest sales at $1.8 million.
2. The AQ Master Wired X1 MS proved to be the best-selling product, moving 4.2 million units, whereas the AQ Home Allin1 Gen2 had the lowest sales, with only 8.8 thousand units sold.  
3. The top 3 customers contributing to the highest net sales were Amazon, AtliQ Exclusive, and AtliQ e-store.
4. The introduction of 16 new products in 2021 showcased AQ's innovation, with the AQ Qwerty leading sales at 22 million units.



# Finance Knowledge
- A Profit and Loss (P&L) statement is a financial report that provides an overview of a company’s financial performance over a period of time, typically a month, quarter, or year.
- The Profit and loss (P&L) statement includes several metrics such as Net sales, cost of goods sold (COGS), Gross Margin and GM % etc, these metrics evaluate a company’s financial performance, profitability, and pricing tactics.
