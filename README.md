
## Machine Learning Overview  

In machine learning, we can classify learning into three types:  

1. **Supervised Learning**: This approach uses labeled data.  
2. **Unsupervised Learning**: This method operates on data without labels.  
3. **Reinforcement Learning**: This technique learns from feedback based on the actions taken.  

## Project Overview  

In this project, we will employ **unsupervised learning** to identify various customer segments for marketing strategies based on purchasing behaviors, demographic characteristics. Key factors analysis include:  

- Buying frequency  
- Product types  
- Spending amounts
- Age
- Gender
- Anuual income

By examining this data, the brand can categorize customers into segments such as:  

- Eco-conscious buyers  
- Luxury shoppers  
- Budget-conscious consumers  

This segmentation enables the brand to customize its marketing messages and campaigns for each specific group.  

### Insights and Recommendations  

Focus on tailoring marketing strategies to each identified segment based on their unique purchasing behaviors.  

You can find the analysis of customer segmentation [here](https://www.kaggle.com/code/mahmoudakl7/customers-segmentation).  


## Data Structure and Methodology

- the database consists of one table with a total row count 200 Records
- before we begin the analysis we check the data for quality control and familiarization

 ## Executive summary

**overview of the findings**

The customer segmentation analysis identified four distinct groups based on income, spending behavior, and age dynamics. Segments C and D represent younger consumers with higher spending tendencies, though Segment C defies conventional patterns by maintaining high spending despite lower income, indicating strong brand loyalty or preference for premium experiences. In contrast, Segments A and B, consisting of older consumers, exhibit more conservative spending behaviors, likely driven by cost-consciousness or different lifestyle priorities. Additionally, a slight female majority exists across all segments, with Segment C standing out for its large female consumer base, presenting strategic opportunities for gender-specific marketing and targeted campaigns.



# Customer Segments Overview  

We applied KMeans clustering to analyze our customer data, leading to the identification of four distinct segments based on annual income, spending scores, and demographic patterns:  

## Segment A (Blue)  
- **Income/Spending**: Lower to moderate income; lower spending scores.  
- **Age Profile**: Primarily older customers, with about 70% aged 41–60.  
- **Gender Distribution**: Slightly more females (approx. 55%) than males.  

## Segment B (Orange)  
- **Income/Spending**: Moderate income with moderate spending scores.  
- **Age Profile**: Concentrated primarily in the 31–50 age range.  
- **Gender Distribution**: Slight female majority, overall balanced (around 52% female).  

## Segment C (Green)  
- **Income/Spending**: Lower income with higher spending scores (spending up to 40% more than expected for their income bracket).  
- **Age Profile**: Predominantly younger customers (21–30 years old, with some in the 31–40 range).  
- **Gender Distribution**: Largest segment overall, with a notable female majority (around 60% female).  

## Segment D (Red)  
- **Income/Spending**: Higher income and relatively high spending scores.  
- **Age Profile**: Mostly younger to middle-aged adults (21–40 years old).  
- **Gender Distribution**: Slightly more females than males (approx. 55%), fairly balanced overall.  



![image](https://github.com/user-attachments/assets/ea3b2d87-a1f5-4f28-9d0d-03b66c466ada)

# Spending vs. Income Patterns  

## Segment C  
- Shoppers in Segment C consistently spend **2× more** than Segment A.  
- They have similar or lower incomes, indicating:  
  - Strong brand loyalty  
  - Preference for premium experiences among younger consumers  

## Segment D  
- Segment D is the **top-spending group**.  
- **80%** of its members frequently purchase premium or luxury items.  
- Their monthly spending is about **1.5× more** than the average monthly spend of Segment B.  

![image](https://github.com/user-attachments/assets/fc4417b2-c6da-43e1-9835-35bfbac5e0c5)

# Age Dynamics  

## Younger Segments (C and D)  
- Comprise roughly **60%** of high spenders.  
- Showcase an appetite for discretionary spending across different income levels.  

## Older Segments (A and B)  
- Account for about **40%** of the customer base.  
- Display more cost-conscious behavior, possibly due to:  
  - Different lifestyle priorities  
  - Budgeting priorities
 

![image](https://github.com/user-attachments/assets/a95170ae-6e80-442e-bcd0-c06f905d8954)

# Gender Distribution  

## Overall Customer Base  
- **55%** of customers are female.  
- This highlights potential for gender-specific marketing or product strategies.  

## Segment C  
- Stands out with **60%** female consumers.  
- This makes Segment C particularly attractive for targeted campaigns focused on younger women's interests.  































