# Xion
Stock Trading Analysis~by Muneeb Ahmad Dar
		
Languages Used:
Python
Packages/Library Used:
Pandas, Numpy, Collections, MS Excel
Solution Approach:
Q1: a) Each strategy had to mapped and kept track of, for calculation of pandl on their part. So we created a map of strategies with quantity and pandl. If strategies aren’t closed by the end (quantity>0) we close them at ‘settlepx’ for further calculation of pandl
b) Each position bought and sold had to be kept track of for each trade, so we create a map of map of quantity and profit and loss. If positions aren’t closed by the end (quantity>0) we close them at ‘settlepx’ for further calculation of pandl.
Q2: Outright positions at the end can be found by keeping track of buying and selling orders with the help of map.
Result Glimpse: 
  







	


                         (UP)PROFIT AND LOSS BY TRADER                                                      (UP)PROFIT AND LOSS BY STRATEGIES










    (UP)END OF PERIOD NET POSITIONS
Future Works Possible:
•	There might be some discrepancy because of missing data in settlepx.csv which is default taken as 0. This can be removed by further communication through ms teams, google meet etc.
•	To get a deeper insight of trends and nature of buying and selling (decision making) by each trader we can use data visualisation techniques after processing the raw data through Exploratory Data Analysis.
GitHub-Repo Link:
               https://github.com/Darmuneeb322/Xion/tree/main/2


 
