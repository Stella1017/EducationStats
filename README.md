# EducationStats
Understanding how well the education systems prepare their students and what factors impact the outcomes is
essential for students, parents, teachers and governments ^[1]^ This report attempts to explore the second question
via analyzing results from international comparative census/survey and assessments. Specifically, I’m interested
in the relationship between the education performance of students and the education status of parents, as well as
factors such as studying strategy, access to education and social-economic backgrounds of students. The second
fold of this study is to explore variances of education outcomes among countries over the world.

The data used in this study is from two sources: World Bank EdStats All Indicator Query and OECD PISA
database.
I downloaded the World Bank data from their account on Kaggle.com. The dataset “holds over 4,000 internationally
comparable indicators that describe education access, progression, completion, literacy, teachers, population, and
expenditures.”^[2]^ It actually contains data from several datasets maintained by other organizations, such as Barro-
Lee Educational Attainment Data and UNESCO Institute for Statistics. I selected indicators in this dataset as
predictors in my models.
The “dependent variable” is 2012 PISA test result. Programme for International Student Assessment (PISA) was
created in 1997, as a measure of effectiveness of education systems across OECD (Organisation for Economic Cooperation
and Development) countries “within a common internationally agreed framework”.^[1]^ PISA tests have a
strong focus on the preparedness for the future, and include three subjects: reading, mathematics and science.^[3]^Via
student-, teacher- and school- level questionnaires, PISA also collected information on socioeconomic background,
studying strategy, attitudes, education access, etc. of students and schools. The student questionnaires data was
downloaded from the PISA website.^[4]^ I selected some of the features as my predictors.

`````
Please read the pdf file for analysis report.


`````

References
[1] OECD (2013), PISA 2012 Assessment and Analytical Framework: Mathematics, Reading, Science, Problem
Solving and Financial Literacy, PISA, OECD Publishing, Paris, https://doi.org/10.1787/9789264190511-en.  
[2] Cresswell, J., U. Schwantner and C. Waters (2015), A Review of International Large-Scale Assessments in
Education: Assessing Component Skills and Collecting Contextual Data, PISA, The World Bank, Washington,
D.C./OECD Publishing, Paris, https://doi.org/10.1787/9789264248373-en.  
[3] Education Statistics From World Bank Open Data https://www.kaggle.com/theworldbank/education-statistics/
home  
[4] Student Questionnaire data file http://www.oecd.org/pisa/data/pisa2012database-downloadabledata.htm  



