This is the read me file for the Project Youtube Data Harvesting and Data WareHousing. 

Work Flow: 
Step-1 : The user has to enter the Youtube Channel ID. 
Step-2 : Then the user should click the button Collect and Store Data.
Step-3 : After few seconds of running, the data will be stored in the Data base. You can see the success message in the UI.
Step-4 : You can choose any questions from the give drop down and you can view the results on the UI. Note: These analysis are completely based on the youtube channels stored in the Database.
Step-5 : The user can visualize in the form of bar graph and as well as Pie Chart.

################################################################################################################################################

Necessary Libraries
1) pandas - For viewing the data sets 
2) streamlit - Python UI application runner(Front-End)
3) datetime - Used for viewing the date and time of the contents which is stored.
4) googleapiclient.discovery - For accessing the Youtube API and to act as a bridge connection.
5) sqlalchemy or mysql connector - To communicate and to establish the connection between the code and the Database.
6) urllib.parse - for storing the Database password
7) matplotlib.pyplot - to visualize the fetched data in the form of plots
8) Seaborn - to visualize the fetched data in the form of Charts.



