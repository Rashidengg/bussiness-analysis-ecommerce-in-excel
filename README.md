E-Commerce Sales Dashboard

E-commerce is rapidly becoming a mainstream way to conduct business, with more companies offering websites that allow customers to make purchases online. Shopping on the web is increasingly common.

**Objective**

An online e-commerce company aims to design a sales dashboard to analyze sales across different product categories. The dashboard will include user controls that allow users to select a product category and view sales trends by month and by specific products within that category.

**Domain:** E-Commerce

---

### Dataset Description

We will use the `E-Commerce Dashboard.xlsx` dataset for this project.

This dataset covers order data across various product categories. The fields included are:

| **Field**          | **Description**                                        |
|--------------------|--------------------------------------------------------|
| **Order ID**       | Unique identifier for each order                       |
| **Order Date**     | Date the order was placed                              |
| **Ship Date**      | Date the order was shipped                             |
| **Aging**          | Used to create a histogram of shipping days            |
| **Ship Mode**      | Method of shipment for the order                       |
| **Product Category** | Category of the product                              |
| **Product**        | Name of the product                                    |
| **Sales**          | Sales amount                                           |
| **Quantity**       | Number of units ordered                                |
| **Discount**       | Discount applied to the order                          |
| **Profit**         | Profit earned from the order                           |
| **Shipping Cost**  | Cost to ship the order                                 |
| **Order Priority** | Priority level of the order                            |
| **Customer ID**    | Unique identifier for each customer                    |
| **Customer Name**  | Name of the customer                                   |
| **Segment**        | Customer segment (e.g., Home Office, Corporate, Consumer) |
| **City**           | City where the order was placed                        |
| **State**          | State where the order was placed                       |
| **Country**        | Country where the order was placed                     |
| **Region**         | Specific region within the country                     |
| **Months**         | Month when the order was placed                        |

---

Analysis Tasks

Using the provided e-commerce data, complete the following tasks:

1. **Create a Histogram**: Analyze the number of shipping days (Aging) using a histogram.
2. **Monthly Sales and Profit Table**: Prepare a table showing sales and profit for each month. Place this in a sheet named "Working Sheet."
3. **Region-wise Sales Table**: Add a table to the "Working Sheet" showing sales by region.
4. **Create a Combo Box**: Add a user control combo box to allow selection of a product category.
5. **Create Column Charts**: Generate column charts based on the month-wise and region-wise sales tables.
6. **Link Combo Box to Tables**: Ensure the tables update based on the selected product category in the combo box.
7. **Create a Dashboard**: Compile the above elements into a comprehensive sales dashboard.

---

 Sample Step: Create a Histogram for Shipping Days (Aging)

To create a histogram:

1. Click the **Data** tab.
2. In the **Analysis** group (located on the right), click **Data Analysis**.
3. Select **Histogram** and click **OK**. A histogram dialog box will appear.

In the histogram dialog box:

- Check the **Labels** checkbox if your data includes labels.
- In the **Input Range** box, select the range for your data (e.g., `Sales Data!D1:D51291`).
- In the **Bin Range** box, select the range for your bin values (e.g., `Working!K3:K7`).
- In the **Output Range** box, select where you want the histogram to appear (e.g., `Working!N3`).
- Click the **Chart Output** checkbox and then click **OK**.

Note: Ensure your output matches the project requirements for accuracy and detail.
