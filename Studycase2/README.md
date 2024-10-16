# Study Case 2: MixITup Business Expansion and Marketing Strategy

## The Case

**MixITup** is a startup driven by young entrepreneurs, operating in the Ice Cream, Boba Drinks, and Desserts (snacks) business. Currently, MixITup has three branches located in **Jakarta**, **Depok**, and **Tangerang**. With a positive reception from the public, both dine-in and delivery orders for MixITup products have exceeded service capacity. 

Last month, MixITup successfully raised **Rp. 33 billion** in Series B funding. They plan to scale their business to other cities and initiate massive marketing campaigns. By offering a 5% discount on selected items and distributing promotional vouchers, MixITup managed to collect customer data through its loyalty program.

As a junior Data Analyst at MixITup, your task is to perform Data Mining to uncover valuable insights and provide recommendations and strategies for business expansion and marketing efforts.

## Data Understanding

The dataset contains the following fields:

- **ID**: Unique customer identifier, assigned incrementally based on the order of sign-up to the loyalty program.
- **Jenis Kelamin**: Gender of the customer (Pria/Wanita).
- **Umur**: Age of the customer (in years).
- **Pendapatan-per-bulan**: Monthly income of the customer (in Rupiah).
- **Skor-pengeluaran**: A score given by MixITup to measure the customer’s spending, ranging from 0 to 100.
- **Menikah**: Marital status of the customer (0: Not Married, 1: Married).
- **Kota**: The city where the customer registered for the loyalty program.
- **Promo**: Frequency of promotional usage by the customer:
  - 0: Never
  - 1: Rarely
  - 2: Occasionally
  - 3: Frequently
- **HariFav**: The day of the week when the customer most often uses their loyalty card.
- **FavFlavor**: The customer’s favorite ice cream flavor:
  - 0: Vanilla
  - 1: Strawberry
  - 2: Chocolate
  - 3: Blueberry
  - 4: Bubblegum/Cotton Candy
  - 5: Coconut
  - 6: Caramel Pecan
  - 7: Mix of 2 Flavors
  - 8: Mix of 3 Flavors

## Instructions

To solve this case, follow these steps:

1. **Data Preprocessing**:
   - Load the dataset into your environment (e.g., Pandas in Python).
   - Check for missing values, and clean or impute data as necessary.
   - Normalize or scale numerical columns if required for analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Generate summary statistics to understand the dataset.
   - Visualize demographic and spending patterns using histograms, boxplots, and bar charts.
   - Analyze the frequency of promotional usage and favorite ice cream flavors.

3. **Clustering**:
   - Apply clustering techniques (e.g., K-Means, K-Modes, or K-Prototypes) to segment customers based on their spending behavior and preferences.
   - Interpret the clusters to identify key customer groups.

4. **Recommendations**:
   - Based on the insights from EDA and clustering, provide recommendations on:
     - Potential cities for business expansion.
     - Effective marketing strategies (e.g., promotions targeted at specific customer segments).
     - Opportunities for product development based on customer preferences.
