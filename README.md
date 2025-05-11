### 📊 Page View Time Series Visualizer  
Visualized time series data using a line chart, bar chart, and box plots. The dataset includes the number of daily page views on the freeCodeCamp.org forum from 2016-05-09 to 2019-12-03. The goal was to understand traffic trends and identify yearly and monthly growth patterns.

**Tasks Completed:**
- Imported and indexed data from `fcc-forum-pageviews.csv` using Pandas.
- Cleaned outliers by filtering the top and bottom 2.5% of daily page views.
- Created:
  - 📈 `draw_line_plot`: Line chart showing daily page views with appropriate labels and title.
  - 📊 `draw_bar_plot`: Bar chart displaying average monthly page views grouped by year.
  - 📦 `draw_box_plot`: Two box plots to show distribution by year (trend) and by month (seasonality).
- Used a separate copy of the DataFrame for each visualization.
- Saved each plot as an image file.

**Development & Testing:**
- All code written in `time_series_visualizer.py`.
- Used `main.py` to run and test functions.
- Unit tests provided in `test_module.py`.
