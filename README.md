# Udacity Bertelsmann Data Science Project 
Developed by the HealthHackers group for the Udacity Bertelsmann Data Science Scholarship. I have worked with an incredible group of people on a mini-project for classifying the genetic risk for pediatric acute myeloid leukemia. Our project was selected as one of the Top 14 (out of 140 submissions) for the  Udacity Bertelsmann Data Science Project Showcase. 

The dataset dataset includes five columns: Karyotype, FLT3 Allelic Ratio, Down syndrome, Age, and Nucleophosmin (NPM). 
For the karyotype column, 
q. The last number between square brackets indicates the number of cells. 
2. The first number is the number of the chromosomes 
3. The second part (XX, XY) indicates gender
4. If there is a slash, it means that the patient has a mixed response. 
5. Each item in the karyotype is separated by a comma, so if a comma-delimited piece contains several letters and numbers (not separated by a comma), then it refers to a single abnormality. 

Identifying risk groups:
1. If FLT3/ITD > 0.4, then high risk
2. If NPM == Mutated, then low risk
3. If down syndrome ==1 and age >= 4, then low risk
4. If either t(16;16) or t(8;21) is present in the karyotype, then the patient is low risk
3. If any of the following are present (-7q, -7, -5q, -5) is present in the karyotype, then the patient is high risk
4. If the karyotype has at least 4 unique abnormalities (none of them are within the low risk), then the patient is high risk
5. If the patient is neither low nor high risk, then the risk is standard  

Group Members
-- 
1. Mahmoud Hamza
2. Minerva Panda
3. Úrsula Pérez
4. Hirza Pimentel
5. Marwa Qabeel

