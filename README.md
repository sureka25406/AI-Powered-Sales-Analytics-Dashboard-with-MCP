# AI-Powered Sales Analytics Dashboard with MCP

## Overview
This project is an AI-Powered Sales Analytics Dashboard that provides real-time sales insights, interactive visualizations, and natural language business queries. It integrates Python, MySQL, Streamlit, Pandas, and MCP (Model Context Protocol) to help users analyze sales performance and generate automated reports.

## Features
- Interactive sales dashboard using Streamlit
- Real-time sales analytics and insights
- MySQL database integration
- Data analysis with Pandas
- Natural language business queries using MCP
- Automated PDF report generation with ReportLab
- Revenue, profit, and sales trend analysis
- User-friendly interface for decision-making

## Technologies Used
- Python
- MySQL
- SQL
- Pandas
- Streamlit
- ReportLab
- MCP (Model Context Protocol)

## Project Structure

```text
AI-Sales-Analytics-Dashboard/
│
├── dashboard.py
├── mcp_server.py
├── mcp_connection.py
├── sales_report.pdf
└── README.md
```

## How It Works
1. Sales data is stored in MySQL.
2. Pandas processes and analyzes the data.
3. Streamlit displays interactive dashboards and charts.
4. MCP enables natural language business queries.
5. ReportLab generates PDF sales reports.
6. Users receive actionable insights for business decisions.

## Example Queries
- What is the total revenue this month?
- Which product generated the highest sales?
- Show the top-performing sales region.
- What are the monthly sales trends?

## Installation

Clone the repository:

```bash
git clone <repository-url>
cd AI-Sales-Analytics-Dashboard
```

Install dependencies:

```bash
pip install pandas streamlit mysql-connector-python reportlab
```

## Run the Project

Start the MCP server:

```bash
python mcp_server.py
```

Launch the dashboard:

```bash
streamlit run dashboard.py
```

## Business Value
- Provides real-time sales monitoring
- Supports data-driven decision-making
- Reduces manual reporting efforts
- Simplifies data analysis through natural language queries
- Improves business intelligence and reporting efficiency

## Author
Sureka
