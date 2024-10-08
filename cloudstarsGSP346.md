
# 🚀 Prepare Data for Looker Dashboards and Reports: Challenge Lab | GSP346

### 🔗 **Solution Video:** [Watch Here ](https://youtu.be/Cdh5T3JPQNs)

---

## 🌐 **Cloud Stars Guide:**

## **Task 1. Create looks**
## **Look #1: Most heliports by state**
In this section, you need to use the Airports dataset to build a visualization that answers the following question: *Which states and cities have the most airports with heliports?*
 
1. Click  **Explore > Airports**.
2. Click **City and State Dimensions**. Click **Count Measure**. Hover the cursor over the **Facility Type**, click the **Filter By Field** button (three lines), and set the **Airports Facility** type to is equal to ```HELIPORT```.
3. On the Data tab, change **Row limit** to **[dynamic ASSIGNED LIMIT]**.
4. In the data section, make sure the Airports Count column is in **descending order**. Clicking the column reorders it.
5. For visualization, make sure the type is set to **Table**.
6. Click **RUN**.
7. Click the gear icon in the top right and save the visualization as a Look. Title it: **[dynamic Look1 title]**.

---

## **Look #2: Facility type breakdown**
In this section, you need to use the Airports dataset to build a visualization that answers the following question: *What is the facility type breakdown for the states with the most airports?*
 
1. Click **Explore > Airports**.
2. Click **State** and **Facility Type Dimensions**. Click **Count Measure**. Make sure the Airports **Facility Type** column is in **descending** sort order.
3. In the left pane, hover the cursor over the **Facility Type**, click the **Pivot data** button.
4. Set the row limit to **[dynamic ASSIGNED LIMIT]**.
5. In the data section, make sure the Airports Count column is in **descending order**. Clicking the column reorders it.
6. For visualization, make sure the type is set to **Table**.
7. Click **RUN**.
8. Save the visualization as a Look. Title it: **[dynamic Look2 title]**

---

## **Look #3: Percentage canceled**
In this section, you need to use the Flights dataset to build a visualization that answers the following question: *What are the airports and states with the highest percentage of flight cancellations with over 10,000 flights?*

1. Click **Explore > Flights**.
2. Click **Aircraft Origin > City and State Dimensions**.
3. Under **Flights Details**, click **Canceled Count Measure**.
4. Under **Flights**, click the **Count Measure**. Next, hover the cursor over it and click the filter button.
5. Set the filter to: Flights Count **is greater than 10,000**.
6. Click **Run**.
7. Click the **+ Add** button next to Custom Fields on the left toolbar. Select **Table Calculation**. For your table calculation, add the formula:
```
${flights.cancelled_count}/${flights.count}
```
 rename it to ```Percentage of Flights Cancelled```, Click **Default Formatting** to change the format to **Percent (3)**, and click **Save**.

1. In the data section, make sure the **Percentage of Flights Cancelled** column is in **descending order**. Clicking the column reorders it.
2. Click the gear icon next to the Flights Count column and select **Hide from Visualization**. Repeat this for the **Cancelled Count Column**.
3. In the visualization pane, make sure you're using a **Table**.
4. Click **Run**.
5. Save the visualization as a Look. Title it:
``` States and Cities with Highest Percentage of Cancellations: Flights over 10,000 ```

---

## **Look #4: Smallest average distance**
In this section, you need to use the Flights dataset to build a visualization that answers the following question: *What are the origin and destination airports with the smallest average distance between them?*

1. Click **Explore > Flights**.
2. Click **Flights > Origin and Destination Dimensions**.
3. Click the **+ Add** button next to Custom Fields on the left toolbar. Select **Custom Measure**. For **Field to measure**, select ```Average Distance``` from the dropdown.
4. Name The Custom Measure: ```Average Distance (Miles)``` and click **Save**.
5. In the data section, make sure the Average Distance (Miles) column is in **ascending order**. Clicking twice the column reorders it.
6. Hover over the Average Distance (Miles) Custom field you just created (in the left pane), and click the gear icon that appears on the right side and click.
7. Set the filter to: Average Distance (Miles) **is greater than 0**.
8. On the Data tab, change the Row limit to **[LAB ASSIGNED LIMIT]**.
9. For visualization, make sure the type is set to **Table**.
10. Click **Run**.
11. Save this visualization as a Look and title it: **[dynamic Look4 title]**.

---

## **Task 2. Merge results**
In this section, you need to use both the Flights and Airports datasets to build a visualization that answers the following question: *Where are the busiest, joint-use major airports that have control towers and what are their associated codes?*

1. Click **Explore > Flights**.
2. Click **Aircraft Origin > City** , **State**, and **Code Dimensions**, and **Flights > Count Measure**.
3. Set the Row Limit to **10**. Click **Run**.
4. Click the gear icon next to Run, then click **Merge Results**.
5. Choose the **Explore > Airports**. Select **Airports > City**, **State**, and **Code**.
6. Click the filter icon next to **Control Tower (Yes / No)**. Set the filter to: is **Yes**.
7. Repeat this filter process for **Is Major** and **Joint Use**.
8. Click **Run**.
9. Click **Save**. Confirm the merge.
10. Click visualization and choose a **Bar Chart**.
11. Click **Run**.
12. Click the gear icon on the top right and then click **Save to Dashboard**. Title your visualization: ```Busiest, Major Joint-Use Airports with Control Towers```
13. Click **New Dashboard**.
14. New Dashboard named ```Plane and Helicopter Rental Hub Data```
15. Click **Save to Dashboard**.

---

## **Task 3. Save looks to a dashboard**
For this task, you need to add all of your created Looks to a Dashboard.

1. Click the **Looker Navigation menu** page in the top-left corner. On the left, click **Folder** and select **My folder** you should have the Looks you created.
2. To add each Look to the Dashboard, follow these steps:
   1. Click the look (you created).
   2. In the top right, next to **Run** / **Edit**, click the gear icon. Select **Save > To an existing dashboard**.
   3. In the Shared tab, in Developer Student, click the dashboard you created **Plane and Helicopter Rental Hub Data** and click **Save to Dashboard**.
3. Complete this process for all of the Looks.

---

## 🎉 **Lab completed with a 100% assessment score!**

You've successfully demonstrated your skills and determination by completing the lab. **Well done!**

### 🌟 **Stay Connected!**

- 🔔 **Join our [Telegram Channel](https://t.me/cloudstars24)** for the latest updates.
- 🗣 **Participate in the [Discussion Group](https://t.me/cloudstarschat)** and engage with fellow learners.
- 💼 **Follow us on [LinkedIn](https://www.linkedin.com/company/cloudstars1)** to stay updated with the latest news and opportunities.


---

**Keep up the great work and continue your learning journey!**

# [CLOUD STARS](https://www.youtube.com/@cloud-stars) - Don't Forgot to Subscribe!

---

