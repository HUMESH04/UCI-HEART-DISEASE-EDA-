## ViLearnX Advanced Technologies ##
ViLearnX Advance Technologies aim to impart technical knowledge with innovative learning modules, from a young age, which makes learning not only informative but interesting.
This company aspire to bring out the leaders, thinkers, and creators of tomorrow, who with the help of technology build a technically racing world. 

## REPORT SUMMARY ##
After executing the code, we will have several visualizations and statistical summaries that will help us in understanding the UCI Heart Disease dataset. Here's a brief summary on the findings:
AIM : the main is to find the insights from heart disease dataset. Like the effect of different attributes on heart disease such as fasting blood sugar, chest pain type, resting electrocardiographic results and the level of cholesterol etc.
Observation:
            We have the data of 920 individuals with 16 columns
            Which includes ['age', 'sex', 'cp', 'trestbps', 'chol', 'fbs', 'restecg', 'thalach', 'exang', 'oldpeak', 'slope', 'ca', 'thal', 'num', 'dataset']
                  num is the predicted attribute which tells us the level of heart disease
                  dataset is the source of the data
                  age is the age of the person
                  trestbps is the resting blood pressure
           Our data has average age of individuals of 53 years and maximum is 77 years whereas we also have a minimum age of 28 years old patient in our dataset with an suspected heart disease
           The average resting blood pressure is 132 and the maximum is 200.
## EXPLORATORY DATA ANALYSIS ## 
1. Distributions: Most features are normally distributed, but some, like trestbps and chol, show a right skew.
2. EXPLORING AGE COLOUMN :
                         The minimum age to have a heart disease is 29 years and the maximum is 77 years according to data set
                         Most of the people gets heart disease between 53 to 54 years
3. EXPLORING THE SEX BASED DISTRIBUTION OF AGE COLOUMN :
                                                        The number of male is greater than the number of feamles in our dataset
                                                        The percenatge of males is 78.9 whereas, the percentage of feamle is 21.1 percent
4. AGE DISTRIBUTION BY SEX :
                            We have 78.9% males and 21.1% females patients in our dataset
                            The number of male is greater than the number of feamles in our dataset
                            From the histogram ploted by using plotly we can get idea that there are 4 males with the age less than 30 who have heart disease
5. DATASET COLUMN :
                   The datatset column has been collected from four different sources which includes ['Cleveland', 'Hungary', 'Switzerland', 'VA Long Beach']
                   We have highest number of patients from Cleveland dataset which are 304
                   Hungary has highest count of male patient which is 212
                   The count of female patients is higher in Cleveland dataset which iw 97 and VA Long Beach have very low number of females which are just 6.
6. EXPLORING CHEST PAIN COLUMN :
                                There are 4 unique enteries in cp (chest pain )column which are ['typical angina', 'asymptomatic', 'non-anginal', 'atypical angina']
                                The count of asymptomatic is highest in cp column with 426 male and 70 female whereas, typical angina chest pain is lowest in both gender
                                The patients reported as asymptomatic is highest in all datasets. Despite of that patients with typical and atypical angina is same in switzerland dataset which is equal to 4.
                                Hungary has largest number of patients whohave atypical angina as compared to other.
7. CATEGORIAL FEATURES :
                         Sex: Majority of the patients are male.
                         Chest Pain Type (cp): Most common type is asymptomatic (type 4).
                         Resting ECG (restecg): Most patients have a normal resting ECG.
                         Exercise Induced Angina (exang): Majority of the patients do not experience exercise-induced angina.
                         Slope: Majority of the patients have a slope type flat.
                         Number of Major Vessels (ca): Most patients have 0 or 1 major vessel colored by fluoroscopy.
                         Thalassemia (thal): Most patients have a normal or reversable defect defect.
                         Target: The target variable indicates that the dataset is fairly balanced between patients with heart disease and without.
8. PLOTTING INSIGHTS FROM NUMERIC COLUMNS:
                                          As we can clearly see that trestbps and chol have outliers and we can deal them using z-score method.
                                          Whereas, thalch and age columns have almost no outliers. except some extreme values in thalch column
                                          age & thalch almsot follows normal distribution
                                          trestbps shows some skewness
9. TREATING OUTLIERS USING Z SCORES :
                                     As we have removed outliers from trestbps and chol columns by using z-score method.
                                     While removing outliers from trestbps 8 rows were detected as outliers and In case of chol 3 rows were detected as outliers
                                     But still we have left with some extreme values which are the actual records of patients that cannot be removed. As in clincial trials we encounterd such extreme values.
                                     So we have removed 11 rows in total as outliers.
10. CORRELATION ( NUMERIC COLUMNS ) :
                                     There is not any higly pstive correlation between any of the numeric column.
                                     Although there is some negative correlation between trestbps , thalch , age and chol column
                                          

