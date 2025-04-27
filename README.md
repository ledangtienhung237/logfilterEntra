# Prepare the README.md content based on the proposed structure
readme_content = """# 📊 Log Viewer - JSON Log Analyzer

Welcome to **Log Viewer**, a simple and powerful web application developed by **Hunter Le** to upload, view, search, filter, and analyze JSON logs directly from your browser.

## 🌟 Features
- Upload and parse JSON log files.
- Search logs dynamically with debounce.
- Sort by any column by clicking on header.
- Pagination with customizable rows per page.
- Export filtered results to CSV.
- Analyze detailed log entry with:
  - MFA Authentication Analysis
  - Device & Compliance Analysis
  - Authentication Details
  - Conditional Access Policy Details
- Lightweight, responsive, and Bootstrap 5 styled.
- Visualize MFA usage statistics with a doughnut chart (powered by Chart.js).

## 🚀 How to Use
1. Open the `index.html` file in your browser.
2. Upload your JSON log file.
3. Use search box or click on column headers to sort/filter.
4. Click on a specific log to view detailed analysis in a popup.
5. Export the filtered data as a CSV file.

## 📁 Files
- `index.min.html` - Minified version ready for deployment.

## 🛡️ Credit
Created with ❤️ by **Hunter Le**.

## 📜 License
This project is licensed for educational and personal use only.  
Unauthorized copying, distribution, or commercial use without permission is prohibited.
"""

# Save the README.md
readme_file_path = '/mnt/data/README.md'
with open(readme_file_path, 'w', encoding='utf-8') as f:
    f.write(readme_content)

readme_file_path
