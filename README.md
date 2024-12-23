## Amazon-Mechanical-Turk
Analyzes bar and coffee house visit patterns and behaviors based on Gender,Passengers,Temperature,occupation,age and other factors for accepting coupons. The analysis is mainly done to see different patterns in variables to see customer behavior in relation to coupon acceptance

## Introduction
This notebook explores customer behavior patterns to bars and coffee houses, with a focus on companion types (alone, friends, partner, kids) and factors like time of day, weather conditions, occupation and age group. The goal is to derive insights into when and with whom people visit bars, coffee houses the most, in order to enhance customer targeting and promotional strategies.

Compare the behaviors of customers who accepted coupons versus those who wont accept coupons.

## Preprocessing Data
- Cleaned the dataframes.
- Filtered columns for analysis, based on category group.
- Count occurrences of data by group by type.

## Visualizations
- **Scatter Plots**: Visualized the frequency of visits based on education, passenger, temperature, and age group.
- **Bar Plots**: Displayed counts of male and female visitors who accepted coupons..

## Observations for Bar with respect to Accepting Coupon
- **Age Factor**: Drivers above the age 25,shows the higher rate of acceptance of the bar coupons.
- **Passenger**:Drivers with no kids passenger and had occupations other than farming, fishing, or forestry had higher rate of acceptance of the coupons.
- **Frequent bar goers**: Frequent drivers visit more then one month is having high rate of acceptance of the coupons
- **Martial status**: Drivers who are not widowed have a higher acceptance rate for bar coupons.
- **Habits**: Drivers who goes to cheaper restaurants more than 4 times a month and income is less than 50K have a higher acceptance rate for bar coupons.

## Observations for Coffee House with respect to Accepting Coupons
- **Gender acceptance rate** : Females has high acceptance rate of the coupons more than males.
- **Temperature vs Acceptance rate** : Warmer temperature has high acceptance rate of the coupons,visit coffehouse for refreshing or for a break.
- **Education vs Acceptance rate** : Higher educated has high acceptance rate of the coupons,visited coffehouse for more
- Passenger with friends and patners has high acceptance rate of the coupons.

## Coupon Accepting and Non-Accepting Customers
- **Coupon Acceptance Behavior**: 
   - **Sunny days** Customers will accepted coupons are generally more likely to visit during **daytime hours** (10 AM and 2 PM), especially on **sunny days**.
   - Those who did not accept coupons tend to visit **later in the day** (6 PM onwards), with a slightly higher frequency during **rainy** and **snowy weather**.
   - The **companion type** also plays a role, with **friends** and **partners** more likely to accept coupons, while those visiting alone or with kids tend to decline the offer more frequently.
  
- **Age Group**:
   - **Above 25 age groups** (>25) are more likely to accept coupons compared to other age groups.
  
- **Temperature**:
   - **Warmer weather** Accepts coupon tend to favor most active.

## Conclusion
- **Key recommendation**: Promotions on **Sunny day** as the primary target group.
- **Temperature impact**: Consider coupon strategies based on weather conditions, as customers are more likely to accept coupons during sunny weather.

## Requirements
- Python 3.x
- Pandas
- Seaborn
- Matplotlib

## Usage
1. Clone this repository:  
   ```bash
   git clone https://github.com/sowmya-sadhu/Amazon_Mechanical_Turk.git
2. Install the necessary dependencies:
   ```bash
    pip install -r requirements.txt
3. Run the notebook:
Open the `prompt.ipynb` file in Jupyter or any compatible environment.
