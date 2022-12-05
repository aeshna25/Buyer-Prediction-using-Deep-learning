1. Audiobooks_data: 

| Column name | Description |
| ------------- | ------------- |
| ID  | Unique identification of audiobook purchasing customer  |
| Book Length (mins) overall  | Sum of length of all purchases  |
| Book Length (mins) average  | Sum divided by the number of purchase  |
| Price overall | Total price of all purchases |
| Price average  | Total price of all purchases divided by number of purchase  |
| Review  | 0 : no review was given ; 1: review was given  |
| Review 10/10  | Review out of 10 (to takle missing reviews, substituded blanks with average review score: 8.91)  |
| Minutes listened  | Total minutes spent listening to the audio book   |
| Completion  | Minutes listened  divided by total length of book purchased  |
| Support request| Total number of support request the person has open (it can be forgotten password to assistance on using platform)  |
| Last visited minus purchase date | the difference between the last time a person interacted with the platform and their first purchase date. (bigger the difference the better)  |
| Targets | 0: Customer didn't convert ; 1: Customer converted |

Assumptions:

-- for someone who bought 1 audio book overall and avergae length will be same


-- Our assumption is that people who leave reviews are more likely to convert again.


-- 8.91 would indicate above average feelings, while the review less than 8.91 would indicate below average feelings.


-- It may turn out that the more support a person needed, the more he or she got fed up with the platform and abandoned it, or he or she likes it so much that by using it stumbles upon different issues, unlike


-- If a person engages regularly with the platform, this difference will be bigger, thus the customer is likely to convert again if the value of this variable is zero, we are sure the customer has never access what he has bought


2. New_Audiobooks_data:

-- 6 months of data, this will be used in testing
