# Pet-Adoption-Hackerearth-Challenge
A leading pet adoption agency is planning to create a virtual tour experience for their customers showcasing all animals that are available in their shelter. To enable this tour experience, you are required to build a Machine Learning model that determines type and breed of the animal based on its physical attributes and other factors.


# Data

The data consists the following columns
Column Description Sl No. 	Column Name 	Description
1 	pet_id 	Unique Pet Id
2 	issue_date 	Date on which the pet was issued to the shelter
3 	listing_date 	Date when the pet arrived at the shelter
4 	condition 	Condition of the pet
5 	color_type 	Color of the pet
6 	length(m) 	Length of the pet (in meter)
7 	height(cm) 	Height of the pet (in centimeter)
8 	X1,X2 	Anonymous columns
9 	breed_category 	Breed category of the pet (target variable)
10 	pet_category 	Category of the pet (target variable)

# Data Description:
The data folder consists of 2 CSV files

    train.csv - 18834 x 11
    test.csv - 8072 x 9

sample_submission:

pet_id,breed_category,pet_category
ANSL_69903,0,1
ANSL_66892,0,2
ANSL_69750,2,4
ANSL_71623,0,2
ANSL_57969,0,1

# Evaluation Metric:

s1=f1_score(actual_values[′pet_category′],predicted_values[′pet_category′],average=′weighted′)s2=f1_score(actual_values[′breed_category′],predicted_values[′breed_category′],average=′weighted′)score=100×s1+s22

Note: To avoid any discrepancies in the scoring, ensure all the index column values in submitted file matches the index column values in 'test.csv' provided.
