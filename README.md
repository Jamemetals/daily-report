# Power and BTU daily report dashboard

**1. Import Data from monthly and daily report in .csv file**

**2. Have 5 plotly graph in dash board with 5 function \n**
   2.1 def kW_each_power_meter_day(df): --> Area plot of kW from each power meter
   2.2 def compare_kW_TR_day(df): --> line plor of Total_kW and Total_Tr 
   2.3 def pie_plot_kW_TR_day(df): --> pie plot of kW from each power meter and BTU meter
   2.4 def create_box_plot_day(df): --> box plot of kW form each power meter 
   2.5 def summary_day(df): --> plotly table included kW_mean, kW_max and kW_total from each power meter

3. Create dashboard on dash 

4. Lay out of dash board is 
   Row1 : Col1 is Title
   Row2 : (Col1 is def kW_each_power_meter_day(df):, Col2 is def compare_kW_TR_day(df):)
   Row3 : (Col1 is def pie_plot_kW_TR_day(df):, Col2 is def create_box_plot_day(df):)
   Row4 : Col1 is def summary_day(df):


