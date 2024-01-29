# Part 1 - Introduction
Skytrax is an International air transport rating organisation, was established in 1989, and is based in London, UK. This dataset includes airline reviews from 2013 to 2019 for popular airlines around the world with multiple choice and free text questions. Data is scraped at Spring 2019.

## Goals of the analysis:
Answer business questions :
Which airline has the highest recommended Ratio (%)?
Does the text review wording length have relationship with the overall review score (1-10)?
To understand what factors the customers care about the most when recommending the airline?
To build the predictive models that helps airline company to predict good feedback (willing to recommend others) as our marketing campaign target

# Part 2 - Exploratory Data Analysis

## 2.1 Dataset Preview
## 2.2 Data cleaning :
1.Deal with duplicated rows
2.Deal with missing values
3.Fix the date data
4.Deal with customer review column(free text column)

## 2.3 Analysis
### Findings:
#### 1,Garuda Indonisia is no.1 who got 90% of their customer say they will recommend the airline. The NO.2 airline is China Southern Airline from China which got 86.2% of their customer recommended review, and NO.3 is Eva Airline from Taiwan who got 85.5% of their customer's recommendation.
![image](https://github.com/rachelsu88/Skytrax-Airline-Reviews-Analysis/assets/157779213/6b03eca4-6820-423a-b424-3ea7d935671b)


#### 2,Score of 6 Service Categories
Among the 6 service categories, reviews show customer especially not satisfied with food_bev, entertainment, ground_service. These above 3 categories received a lot low score (1). And the cabin service got the most higest score (5).
![image](https://github.com/rachelsu88/Skytrax-Airline-Reviews-Analysis/assets/157779213/d6f07bb7-dfa7-4284-86e0-82f65679090c)


#### 3,The Overall Score (1-10):
The top 5 airline companies who received the best overall score are all from Asia airline companies.
And the top 5 overall rating airlines are generally aligned with the top 5 recommeded airlines, however the ranking are slightly different. China Southern Airline are NO.2 from top recommended airline but rank at NO.5 on overall rating airline.
![image](https://github.com/rachelsu88/Skytrax-Airline-Reviews-Analysis/assets/157779213/dd71987d-c6ad-41ec-9224-8e88f187f9b9)


#### 4,Customer text review in worldcould
The worldcloud from customer review column which is a free text column to see what the most common words customers concern. Obviously, we can see from the above word could that customers concern a lot with time/ on time (there are two words TIME, HOUR related to it). It makes sense to our understanding that on time is very cruial when talking about flights. delay is definitely will get big complaints. Other than time related words, we also see SEAT, FOOD, MEAL and STAFF ..
![image](https://github.com/rachelsu88/Skytrax-Airline-Reviews-Analysis/assets/157779213/e8dd1a65-d363-40c5-83ae-234d4910145a)
