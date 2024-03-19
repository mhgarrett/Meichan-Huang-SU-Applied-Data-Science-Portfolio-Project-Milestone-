# Wine-review-data-visualization-and-analysis
This is an exploratory project working with three data sources to complete data analysis related to wine reviews. 

## Project Description 

The first project brought together two distinct sub-projects from IST 652: Scripting for Data Analysis and IST 644: Natural Language Processing courses I completed in the Fall of 2022. It was an exploration of the comprehensive data science lifecycle to foster actionable insights, from the wine consumers’ perspectives. The aim was to predict wine scores by analyzing a blend of traditional statistical data and textual information, including origin, price, reviews from wine enthusiasts, and Twitter data. The project was structured in two segments, each with a different emphasis, showcasing the diverse data analytics skills I developed through IST 652 and IST 644. 

The initial phase of the project was completed through IST652: Scripting for Data Analysis. The sub-project was marked by a strategic compilation of multiple external data sources to augment the primary dataset in Kaggle, which was scrapped from the Wine Enthusiast magazine during 2017-2020, containing 210,000 entries of wine reviews. Using Pandas package, the data was merged with the longitude and latitude dataset of the world geographic locations in Kaggle to visualize data distribution based on the locations. 

## Business questions: 

Question 1: Which countries and provinces had the MOST and LEAST reviews (demographic distributions of wine reviews)?

Question 2: What is the MEAN, MIN and MAX points received for wines from the most and least reviewed countries and provinces? 

Question 3: What was the MEAN, MIN and MAX price of wine by country?

Question 4: How many wines were reviewed by category? What are the top 10 wine varieties reviewed?

Question 5: What are the MEAN, MIN and MAX scores, particular for top 10 most reviewed varieties?

Question 6: What was the MEAN, MIN and MAX prices of wine by top 10 reviewed varieties?

Question 7: For each country, what type of wine is most reviewed?

Question 8: What is the correlation between the price and score of a bottle of wine?

Question 9: What types of descriptors were frequently associated categories of wine in the reviews? e.g. what kind of fruit flavor were typically used in the wine reviews? 

This project enhanced my skills in thorough data exploration and analysis, incorporating traditional correlational analysis to examine the interplay between various attributes. The methodologies applied during this stage leveraged Python's robust libraries, specifically Pandas and NumPy, to facilitate data manipulation and analysis. The focus of the first part of the project was to uncover the relationships among data attributes and to understand the dataset's overall structure. Insights gleaned from this phase were aimed at data visualization and exploratory analysis, offering both graphical and statistical insights into the inherent patterns and trends within the wine review data. Key questions included identifying the top 10 most reviewed wine types and the most frequently reviewed wine regions. The following demonstrated one of such exploratory analysis done using the dataset to gain insights into the wine around the world, including the origins of the wine that were reviewed by the magazine (Figure X). 

<img width="424" alt="image" src="https://github.com/mhgarrett/Meichan-Huang-SU-Applied-Data-Science-Portfolio-Project-Milestone-/assets/94016314/fbf65bf6-a51b-442e-88e0-4a5a83f18481">

Figure 1. Top most reviewed wine origins by countries 

Additionally, the project presented me with an opportunity to explore the relationship between wine prices and their ratings, yielding insights with significant business implications. Specifically, it revealed that wines with high ratings are not necessarily associated with higher prices. To uncover this, a regression analysis was conducted using the sklearn library, examining the correlation between wine prices and the points awarded. A noteworthy hurdle of this analysis was the creation of visualizations to convey meaningful insights effectively. This was particularly important given the data's characteristics: a narrow points range (80 - 100) contrasted with a vast, densely populated price range, mostly concentrated within the lower consumer price quartile. Consequently, the correlation model was refined to consider only wines priced at $100 or less, enabling a clearer comprehension of the relationship between price and quality.

<img width="201" alt="image" src="https://github.com/mhgarrett/Meichan-Huang-SU-Applied-Data-Science-Portfolio-Project-Milestone-/assets/94016314/10dcdc0d-ee3c-42ab-8f17-c4e5a47e279f">
<img width="198" alt="image" src="https://github.com/mhgarrett/Meichan-Huang-SU-Applied-Data-Science-Portfolio-Project-Milestone-/assets/94016314/e0d20be2-41c7-4afc-a7ff-035464bc6102">

Like any research projects I have conducted, this project had its constraints. The initial phase did not fully leverage the textual data present in the primary dataset. Acknowledging this limitation, I strategized to explore this rich textual content in the subsequent stage of my research, aiming to harness the full potential of the available data.

The second segment of the project, executed as part of IST 644: Natural Language Processing, built upon the foundational work of IST 652: Scripting for Data Analysis. In this phase, I capitalized on the textual data embedded within the wine reviews. The aim was to harness linguistic features from these reviews to predict outcomes such as high vs. low ratings, price brackets, and wine varietals. Collaborating with Nicholas Nguyen, we delved into natural language processing techniques. Our toolkit included tokenization and POS tagging via the NLTK library, extracting features using the bag-of-words model and bigrams, and implementing vectorization through TF-IDF scores. To bring the data to life, we created visual word clouds. Finally, we tackled text classification with the Multinomial Naïve Bayes algorithm, navigating through the rich textual landscape to draw predictive insights.

![image](https://github.com/mhgarrett/Meichan-Huang-SU-Applied-Data-Science-Portfolio-Project-Milestone-/assets/94016314/5af05f40-ca3e-436d-b3ae-fd9b1c23d8a0)


## Reflection and Learning Goals 

The wine review project stands out as an important experience in my educational journey, marking my initial attempt into the data scientist path. This project was also crucial for my first programming experience, where I developed foundational data science skills from the ground up, with a particular focus on Natural Language Processing—a key aspect of my professional trajectory.

One of the most significant lessons from this project, which aligns with the learning goals of the program, was the realization that data analysis and data science projects are inherently cyclical, not linear. This iterative process often involves revisiting and refining each stage to achieve the most insightful results. Through this experience, I learned that each phase of analysis can shed new light and necessitate adjustments in strategy or technique. This project has not only equipped me with technical skills but has also instilled a mindset geared towards persistence and innovation—qualities that are indispensable for any aspiring data scientist.

