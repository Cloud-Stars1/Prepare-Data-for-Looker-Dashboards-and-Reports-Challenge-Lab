
# 🚀 Prepare Data for Looker Dashboards and Reports: Challenge Lab | GSP346

### 🔗 **Solution Video:** [Watch Here ]()

---

## 🌐 **Cloud Stars Guide:**

## **Task 1. Create looks**
## **Look #1: Most heliports by state**
In this section, you need to use the Airports dataset to build a visualization that answers the following question: *Which states and cities have the most airports with heliports?*
 
1. Click  **Explore > Airports**.
2. Click **City and State Dimensions**. Click **Count Measure**. Hover the cursor over the **Facility Type**, click the **Filter By Field** button (three lines), and set the **Airports Facility** type to is equal to ```HELIPORT```.
3. On the Data tab, change **Row limit** to <dynamic ASSIGNED LIMIT>.
4. In the data section, make sure the Airports Count column is in descending order. Clicking the column reorders it. For visualization, make sure the type is set to Table.
5. Click **RUN**.
6. Click the gear icon in the top right and save the visualization as a Look. Title it: <dynamic Look1 title>.

---

## **Look #2: Facility type breakdown**
In this section, you need to use the Airports dataset to build a visualization that answers the following question: *What is the facility type breakdown for the states with the most airports?*
 
1. Click Explore > Airports.
2. Click State and Facility Type Dimensions. Click Count Measure. Make sure the Airports Facility Type column is in descending sort order.
3. In the left pane, hover the cursor over the Facility Type, click the Pivot data button. Set the row limit to <dynamic ASSIGNED LIMIT>.
4. In the data section, make sure the Airports Count column is in descending order. Clicking the column reorders it. For visualization, make sure the type is set to Table.
5. Click RUN.
6. Save the visualization as a Look. Title it: <dynamic Look2 title>

---

Look #3: Percentage canceled
In this section, you need to use the Flights dataset to build a visualization that answers the following question: What are the airports and states with the highest percentage of flight cancellations with over 10,000 flights?
Click Explore >Flights.
Click Aircraft Origin > City and State Dimensions.
Under Flights Details, click Canceled Count Measure.
Under Flights, click the Count Measure. Next, hover the cursor over it and click the filter button.
Set the filter to: Flights Count is greater than 10,000.
Click Run.
Click the + Add button next to Custom Fields on the left toolbar. Select Table Calculation. For your table calculation, add the formula:
 
${flights.cancelled_count}/${flights.count}

 
rename it to Percentage of Flights Cancelled, Click Default Formatting to change the format to Percent (3), and click Save.

In the data section, make sure the Percentage of Flights Cancelled column is in descending order. Clicking the column reorders it. Click the gear icon next to the Flights Count column and select Hide from Visualization. Repeat this for the Cancelled Count Column. In the visualization pane, make sure you're using a table.
Click Run.
Save the visualization as a Look. Title it: States and Cities with Highest Percentage of Cancellations: Flights over 10,000

---

Look #4: Smallest average distance
In this section, you need to use the Flights dataset to build a visualization that answers the following question: What are the origin and destination airports with the smallest average distance between them?
Click Explore >Flights.
Click Flights > Origin and Destination Dimensions.
Click the + Add button next to Custom Fields on the left toolbar. Select Custom Measure. For Field to measure, select Average Distance from the dropdown.
Name The Custom Measure: Average Distance (Miles) and click Save.
Hover over the Average Distance (Miles) Custom field you just created (in the left pane), and click the gear icon that appears on the right side and click. Set the filter to: Average Distance (Miles) is greater than 0.
On the Data tab, change the Row limit to <LAB ASSIGNED LIMIT>. For visualization, make sure the type is set to Table.
Click Run.
Save this visualization as a Look and title it: <dynamic Look4 title>.

---

Task 2. Merge results
In this section, you need to use both the Flights and Airports datasets to build a visualization that answers the following question: Where are the busiest, joint-use major airports that have control towers and what are their associated codes?
Click Flights Explore.
Click Aircraft Origin > City , State, and Code Dimensions, and Flights > Count Measure. Set the Row Limit to 10. Click Run.
Click the gear icon next to Run, then click Merge Results. Choose the Airports explore. Select Airports > City, State, and Code.
Click the filter icon next to Control Tower (Yes / No). Set the filter to: is Yes.
Repeat this filter process for Is Major and Joint Use.
Click Run.
Click Save. Confirm the merge, then click Run. Click visualization and choose a Bar Chart.
Click the gear icon on the top right and then click Save to Dashboard. Title your visualization: Busiest, Major Joint-Use Airports with Control Towers.
Click New Dashboard.
New Dashboard named <dynamic Dashboard name>.
Click Save to Dashboard.

---

Task 3. Save looks to a dashboard
For this task, you need to add all of your created Looks to a Dashboard.
Click the Looker Navigation menu page in the top-left corner. On the left, click Folder and select My folder you should have the Looks you created.
To add each Look to the Dashboard, follow these steps:
Click the look (you created).
In the top right, next to Run / Edit, click the gear icon. Select Save > To an existing dashboard.
In the Shared tab, in Developer Student, click the dashboard you created (Plane and Helicopter Rental Hub Data) and click Save to Dashboard.
Complete this process for all of the Looks.

---

## 🎉 **Lab Completed!**

You've successfully demonstrated your skills and determination by completing the lab. **Well done!**

### 🌟 **Stay Connected!**

- 🔔 **Join our [Telegram Channel](https://t.me/cloudstars24)** for the latest updates.
- 🗣 **Participate in the [Discussion Group](https://t.me/cloudstarschat)** and engage with fellow learners.
- 💼 **Follow us on [LinkedIn](https://www.linkedin.com/company/cloudstars1)** to stay updated with the latest news and opportunities.


---

**Keep up the great work and continue your learning journey!**

# [CLOUD STARS](https://www.youtube.com/@cloud-stars) - Don't Forgot to Subscribe!

---

