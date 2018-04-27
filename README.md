
Education and Immigration in California

California has been beacon for immigrants from all over the world since its induction into the union in 1850. Over a quarter of the states population are immigrants. Education is essential for social mobility. For Americans born into  born into families in the bottom quintile of income, the greatest predictor of whether they will stay in that quintile is whether they graduate high school. We see differences in academic achievement of native born versus immigrant students. There are a number of possible explanations, the simplest being, that immigrants have less wealth that is correlated to academic success. There is also however great variance in the success of immigrants. By understanding how social and demographic factors affect the educational outcomes of immigrants, we can create a model to predict the success of an immigrant student for all the schools in california,The ultimate goal of this project is to improve educational outcomes for migrant students. This is accomplished in two ways, the first is to use the model to identify schools performing significantly above projection. These schools should be more closely examined to determine how other schools might try to emulate that success. The second is to advise migrants considering where to settle based on the educational future of their children.

	There are several factor i would like to account for when creating my model.

Standardized Testing Scores, to judge the academic success of any school, we will be looking at the result of the yearly star test that has averages for each school as well as for exclusively migrant students.

Income, wealth is a huge factor in determining academic success, when comparing schools we want to keep in mind whether they fall in a wealthy area that will likely affect our scores.

Per Pupil Spending, Because schools public schools are funded primarily through property taxes, area income and per pupil spending are correlated. We are still concerned with Per Pupil Spending because it will help indicate schools with greater academic resources.

Staff Educational Demographics, information about how long the average teacher at each district has been teaching may give us some indication of the quality of teachers.

Staff Racial Demographics, there have been studies that indicates people of color have better medical outcomes when their medical staff are racial similar, this will allow us to see how  immigrants’ education is affected by the demographics of the their instructors

Free Meal Program, food insecurity is far more common in immigrants than in the native born population. This will allow us to see how public benefits like food assistance can affect education.

Sanctuary Status,  This will examine how a counties sanctuary status can impact the education of the migrants that live there.
	
There are two desirable outcomes from this model. The first requires us to feed in a sample of our migrant schools list into the regression. Next, having the model predict the Migrant_Score for the schools that weren’t used for training, those schools that exceed their predicted results by a statistically significant margin are candidates for further study. These schools are likely to have other features that would account for their success.
	
The intended user for this sort of model is a school or district official looking to improve the educational outcomes for their migrant students by simulating those districts and schools whose performance exceed their demographics.
	
The second use for this regression is to give a more complete picture of how different schools would educate migrants. There are many schools in california where it is not publicly available how well the migrant students are doing. This would complicate the role of a concerned migrant parent who wants to ensure their child is in a school district where people from their demographic background can succeed. By this time training our model on the entire migrant schools training set and having the model predict the Migrant_Score of schools using only the school information and the All_Score, an estimation can be made for the success of migrant children at each school. This gives the migrant parent more security when making decisions about their child’s educational future.