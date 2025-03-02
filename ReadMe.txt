This Dash app creates an interactive dashboard for visualizing automobile sales statistics. It has two main report types: "Yearly Statistics" and "Recession Period Statistics."

Data Loading: The app loads historical automobile sales data using pandas.

Dropdown Menus: Users can choose between "Yearly Statistics" or "Recession Period Statistics" and select a year (1980-2023) for the yearly report.

Callbacks:
One callback controls enabling/disabling the year selection based on the report type.

Another callback updates the displayed charts based on the selected report type and year:

Recession Period Statistics: Displays charts on average sales, vehicle types, advertising expenditure, and the effect of unemployment during recession periods.

Yearly Statistics: Displays charts on yearly sales trends, monthly sales, vehicle sales by type, and advertising expenditure for the selected year.

Charts: The app uses plotly.express to generate line charts, bar charts, and pie charts dynamically.

Running the App: The app is run with app.run_server(debug=True), allowing interactive exploration of the data.

In short, the app enables interactive analysis of automobile sales trends and recession impacts through various visualizations.