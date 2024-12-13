# What Impacts Reindeer Herd Size?
Analyzing Reindeer Herd Size in Finnmark, Norway

## About
This project was for Probability & Statistics class in which we were supposed to explore a statistical analysis method we had not yet covered in class on a topic of interest. For this project, I opted to look at reindeer herd size in Finnmark Norway because I had spent time living and working with the Sami reindeer herders there. Many of the conversations I had surrounded the health and size of the herds in the face of the changing climate and changing cultural norms. With this in mind, I wanted to explore what factors could contribute to herd size. I found some data online about herd sizes in Finnmark, and because I had more variables than observations, I decided to use a PLS model. 

## PLS - Partial Least Squares -or- Projection onto Latent Structures
Partial Least Squares is a really cool statistical method that combines features of Principal Component Analysis and Multiple Regression. It is particularly useful in situations where the number of variables is more than the number of observations. PLS works by decomposing the predictor variable matrix and the response variable matrix into latent structures to identify new latent variables that explain the relationships between our predictor and response variables-- all the while reducing dimensionality! In other words, instead of looking at each predictor variable's effect on the response individually, we are able to find combinations of predictor variables (called latent structures) that collectively affect the response. On top of this, PLS can account for a lot of complexity in a problem-- especially when predictor variable impact might overlap. It pulls from PCA's strengths and is able to find the variables that have similar effects, group them together, and reduce redundancy (dimensionality reduction). Once the latent variables are determined, PLS borrows from multiple regression to model predictions. The model forecasting is based on the identified relationships between the latent variables and the response. This is a great tool for uncovering and modeling complex relationships in data.

## Included
Attached is the data in a csv file, the R Markdown, a pdf of the Project Report, and a pdf analysis (which is just the markdown in pdf form). There are two models in this markdown. The first inlcudes all of the data and the second only inlcudes variables that the first model uncovered as important (in an attempt to reduce noise). 

## Results
Overall this research was not a success in that it did not accomplish the goal of revealing an
effective predictor model for reindeer herd size from the variables. It is, however, one of the few
projects that focuses on human behaviors and trends in education and technology as they relate to
herd size. Most of the reports found while researching for this project focus on the physical
surroundings that impact the landscape or health of the reindeer, but it would be interesting to
continue exploring some of the underlying or invisible behaviors and mindsets that can shift
motivations for tending these semi-domesticated animals. This is a complex, multifaceted question
and a way of life may depend on it. It was curious that the most important variables were related
to education level and technology use among the population. It raises interest in the possibility that
these variables describe a certain latent variable of human behavior. This could be explored in more
detail in future projects.

## Usage
Feel free to use the PLS models I made in R as a template. Make sure that your data meets the requirements of a PLS model and visit my Project Report to learn about the details of PLS, the data, the sources for this project, some learning opportunities and ideas for model improvement. 

## Contact me!
If you want to talk about the content or methods of this project or have any questions, head to the bottom of my [GitHub portfolio website](https://biscoleo.github.io/) and send me a message!
