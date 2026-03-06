# SQL Query Generator

This project converts natural language queries into SQL queries.

Example:
Input:
show users last month

Output:
SELECT * FROM users WHERE DATE(signup_date) >= DATE('now','-1 month') LIMIT 10;

Features
- Natural Language Input
- SQL Generation
- Query History
- PDF Export
- TXT Export
- WhatsApp Share

Technologies
- Python
- Gradio
