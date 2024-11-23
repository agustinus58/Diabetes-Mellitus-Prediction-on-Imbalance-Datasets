No	Variable Name	Role	Type	Demographic	Description	Missing Values
0	Diabetes_binary	Target	Binary		0 = no diabetes 1 = prediabetes or diabetes	no
1	HighBP	Feature	Binary		0 = no high BP 1 = high BP	no
2	HighChol	Feature	Binary		0 = no high cholesterol 1 = high cholesterol	no
3	CholCheck	Feature	Binary		0 = no cholesterol check in 5 years 1 = yes cholesterol check in 5 years	no
4	BMI	Feature	Integer		Body Mass Index	no
5	Smoker	Feature	Binary		Have you smoked at least 100 cigarettes in your entire life? [Note: 5 packs = 100 cigarettes] 0 = no 1 = yes	no
6	Stroke	Feature	Binary		(Ever told) you had a stroke. 0 = no 1 = yes	no
7	HeartDiseaseorAttack	Feature	Binary		coronary heart disease (CHD) or myocardial infarction (MI) 0 = no 1 = yes	no
8	PhysActivity	Feature	Binary		physical activity in past 30 days - not including job 0 = no 1 = yes	no
9	Fruits	Feature	Binary		Consume Fruit 1 or more times per day 0 = no 1 = yes	no
10	Veggies	Feature	Binary		Consume Vegetables 1 or more times per day 0 = no 1 = yes	no
11	HvyAlcoholConsump	Feature	Binary		Heavy drinkers (adult men having more than 14 drinks per week and adult women having more than 7 drinks per week) 0 = no 1 = yes	no
12	AnyHealthcare	Feature	Binary		Have any kind of health care coverage, including health insurance, prepaid plans such as HMO, etc. 0 = no 1 = yes	no
13	NoDocbcCost	Feature	Binary		Was there a time in the past 12 months when you needed to see a doctor but could not because of cost? 0 = no 1 = yes	no
14	GenHlth	Feature	Integer		Would you say that in general your health is: scale 1-5 1 = excellent 2 = very good 3 = good 4 = fair 5 = poor	no
15	MentHlth	Feature	Integer		Now thinking about your mental health, which includes stress, depression, and problems with emotions, for how many days during the past 30 days was your mental health not good? scale 1-30 days	no
16	PhysHlth	Feature	Integer		Now thinking about your physical health, which includes physical illness and injury, for how many days during the past 30 days was your physical health not good? scale 1-30 days	no
17	DiffWalk	Feature	Binary		Do you have serious difficulty walking or climbing stairs? 0 = no 1 = yes	no
18	Sex	Feature	Binary	Sex	0 = female 1 = male	no
19	Age	Feature	Integer	Age	13-level age category (_AGEG5YR see codebook) 1 = 18-24 9 = 60-64 13 = 80 or older	no
20	Education	Feature	Integer	Education Level	Education level (EDUCA see codebook) scale 1-6 1 = Never attended school or only kindergarten 2 = Grades 1 through 8 (Elementary) 3 = Grades 9 through 11 (Some high school) 4 = Grade 12 or GED (High school graduate) 5 = College 1 year to 3 years (Some college or technical school) 6 = College 4 years or more (College graduate)	no
21	Income	Feature	Integer	Income	Income scale (INCOME2 see codebook) scale 1-8 1 = less than $10,000 5 = less than $35,000 8 = $75,000 or more	no
