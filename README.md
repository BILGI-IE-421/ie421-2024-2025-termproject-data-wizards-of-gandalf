[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/5i0xgF2j)
## Beyond the Medal: Women in the Olympics

Gender discrimination in sports has been a long-standing issue, with male and female athletes receiving unequal chances and recognition across disciplines. Despite significant progress in many areas of society, gender disparities persist in sports, both in terms of participation and representation. This research seeks to investigate the amount of gender discrimination in the participation of male and female athletes in certain sports and nations, with an emphasis on detecting trends that show gender equality or inequality.

The goal of this study is to examine at gender representation across different sports at the national level by comparing the participation of male and female athletes. The study will determine if various sports display gender equality or discrimination by thoroughly examining a dataset that contains sex, nation, and sport category statistics. The study will be conducted using the male-to-female athlete ratio, offering a quantitative way to assessing inequalities or progress toward equal representation.

## Research Question and Aim

What extent is gender discrimination in the participation of male and female athletes in particular sports and nations, and what are the trends of equal representation in various sports?

The purpose of this study is to examine gender representation in athlete involvement across many sports in order to discover trends of gender equality or discrimination at the national level. Using a dataset that includes sex, nation, and sport category, the study will determine whether sports are gender-equal or gender-unequal based on the male-to-female athlete ratio. Inequality can be detected using classification approaches, with visualizations offering further information. A bar chart can provide male-to-female participation rates for each sport type, color-coded by equality status, whereas a heatmap can show the severity of gender discrepancies among nations and sports. Furthermore, a pie chart can show the overall proportion of gender-equal vs gender-unequal sports, providing a clear picture of worldwide trends. This analysis will ensure that findings regarding gender discrimination in sports participation are accessible.

# Beyond the Medal: A Data Story Women in the Olympics

Imagine a world where sports truly reflect equality, transcending borders and prejudices and bringing people together. How do cultural, socioeconomic, and structural factors affect the participation of male and female athletes in various countries and disciplines? Despite substantial progress in gender equity across many aspects of society, sports continue to show inequities that necessitate further investigation. What can we learn from patterns and trends in gender representation in sports? Let's examine the trends and features of the Paris 2024 Olympics. Our research aims to add valuable information to the ongoing debate on gender equality in sport, to inform policies and initiatives that promote equal opportunities for all athletes. Identify trends in gender equality or disparity by examining the male-female athlete ratio in various sports and national contexts. Determine the amount of gender equality or discrimination in sports participation using a dataset that includes gender, nation, and sport category information. Provide insight into the existing state of gender representation in sports, with the goal of identifying areas where more development is required to achieve equal opportunities for both genders. We made 4 different analysis, we will explain them one by one.

First of all, Sport is, above all, a mirror of society; It reflects cultural values, norms, and sometimes prejudices. But how do these norms influence participation in different sports? This analysis dives into gender dynamics across a variety of sports disciplines, demonstrating patterns of representation and identifying areas where further improvement is needed. The journey begins with a detailed dataset visualized with a scatter plot of gender distribution in sports. This chart shows the female participation rate in various sports from 0% to 100%, with bubble sizes representing the number of athletes in each discipline. The background gradient visually emphasizes the gender ratio; cool blues indicate female-dominated sports, while warm reds highlight male-dominated sports. The gray band in the middle identifies sports with relatively balanced participation (40-60%).

+ ![Exploring Gender Parity in Global Sports Participation](https://github.com/BILGI-IE-421/ie421-2024-2025-termproject-data-wizards-of-gandalf/blob/main/Visuals/gender_distribution_scatter.png)

The gender distribution chart highlights clear trends in sports participation: female-dominant sports like Rhythmic Gymnastics contrast with male-dominant ones like Wrestling and Football. Sports like Rowing, Badminton, and Tennis show near-equal gender participation, proving balance is achievable. Even in larger disciplines like Athletics, equitable participation remains a challenge but is possible. This visualization offers insights into gender representation and emphasizes the need to challenge biases and promote inclusivity, ensuring everyone has a fair chance to succeed in sports.

Secondly, Gender representation in sports reflects deeply ingrained societal conventions and cultural expectations. The graph compares the gender distribution of various sports, categorizing them as female-dominant (more than 60% female participants) or male-dominant (more than 60% male athletes). By showing these inequalities, the image helps us understand how gender preferences, prejudices, and access influence participation trends across fields. This analysis invites reflection on the broader implications of inclusion and equality in sport.

+ ![Gender Distribution Across Sports](https://github.com/BILGI-IE-421/ie421-2024-2025-termproject-data-wizards-of-gandalf/blob/main/Visuals/gender_distribution_in_sports.png)

The chart showcases the gender distribution across various sports, highlighting a clear division between female-dominant and male-dominant categories. Female-dominant sports, defined by having over 60% female athletes, include Rhythmic Gymnastics and Artistic Swimming, which are exclusively female with 100% participation. Similarly, Cycling Road and Triathlon also appear to have 100% female representation, though this is based on a single athlete, limiting its broader significance. Meanwhile, sports like Cycling Road and Cycling Track show some male presence, with men making up 27.3% of participants.
In male-dominant sports, where over 60% of participants are men, Marathon Swimming has the highest male representation at 76.5%, followed by Wrestling at 67%, and Equestrian at 61.7%. These figures underline a significant male skew in these disciplines.
The data highlights the persistent gender imbalances in sports, prompting discussions about fostering inclusivity and breaking down stereotypes. By encouraging broader participation across all sports, the path toward a more equitable and supportive sports environment can be paved.

The big question was clear: Do men and women have the same chances in sports? This research looked at sports around the world to find answers. The focus was on understanding which sports and countries give everyone fair chances to play The chart provides a clear visualization of the gender ratio distribution by sport for each country in this example. It offers a country-specific perspective on gender representation in sports, highlighting the percentage of male and female athletes participating in various disciplines. Allowing other countries to be explored via an interactive drop-down menu, the graphic places these findings in a global context and encourages reflection on the broader dynamics of inclusivity and gender balance in sports participation.

+ ![Gender Ratio Distribution by Sports for Each Country](https://github.com/BILGI-IE-421/ie421-2024-2025-termproject-data-wizards-of-gandalf/blob/main/Visuals/Gender%20Ratio%20Distribution%20by%20Sports%20for%20Each%20Country.png)

The chart presents an intriguing visualization of gender ratios in various sports, highlighting how male and female athletes participate in different disciplines in Countries. As we explore the dropdown list of countries, providing a broader context for gender representation in sports worldwide. As we navigate through this animated chart, it becomes evident that gender representation in sports varies widely across different disciplines. Hope this narrative captures the essence of the data and inspires deeper reflection on gender dynamics in sports.

Imagine a model tasked with categorizing athletes into two groups—"Equal" or "Unequal"—based on attributes like gender, nationality, and discipline. This classification isn’t just about numbers; it’s about uncovering patterns and understanding disparities. The confusion matrix becomes a window into the model's thought process, revealing how often it gets things right and where it falters. For the "Unequal" class, the model’s accuracy can inspire confidence, but for the "Equal" class, the missteps remind us that classification tasks often face real-world complexities. This breakdown provides a foundation to improve the model, ensuring it delivers fairer and more accurate predictions.

+ ![Confusion Matrix](https://github.com/BILGI-IE-421/ie421-2024-2025-termproject-data-wizards-of-gandalf/blob/main/Visuals/Confusion%20Matrix.png)

The confusion matrix shows that the model performs well for the "Unequal" class, with 1,380 correct predictions (90% precision, 82% recall) and only 158 misclassifications. However, for the "Equal" class, the model correctly predicts 382 cases but misses 302 actual instances (71% precision, 56% recall). These results highlight an imbalance in performance, suggesting the need to improve the model's ability to detect "Equal" cases, potentially by addressing class imbalance or enhancing feature differentiation.

+ ![ROC Curve](https://github.com/BILGI-IE-421/ie421-2024-2025-termproject-data-wizards-of-gandalf/blob/main/Visuals/ROC%20Curve.png)

In the realm of predictive analytics, precision matters. Our machine learning model emerges as a robust performer, demonstrating remarkable accuracy in its decision-making capabilities. The ROC curve reveals an AUC of 0.83, placing our model well above the baseline of random chance and into the territory of reliable prediction.
The journey of our model's performance begins at the origin, where it rapidly ascends, capturing a high rate of true positives while maintaining minimal false alarms. This swift initial climb speaks volumes about the model's confidence in its early predictions. By the time we reach a false positive rate of 0.2, our model successfully identifies approximately 70% of all positive cases – a testament to its discriminative power.
As we trace the blue curve upward, we witness a thoughtful balance between sensitivity and specificity. The model's decisions become more nuanced in the upper regions of the curve, carefully weighing each classification to maximize accuracy. This measured approach ensures that additional true positive identifications are gained without unnecessarily sacrificing precision.
The substantial gap between our model's performance curve and the diagonal reference line (where AUC would be 0.5) quantifies the model's predictive superiority. At 0.83, the AUC indicates that our classifier successfully distinguishes between positive and negative cases 83% of the time – a robust foundation for reliable decision-making in practical applications.


## Datasets
https://olympics.com/en/paris-2024/athletes
https://en.wikipedia.org/wiki/2024_Summer_Olympics

## Hosting
The project is hosted using GitHub Pages (https://berilpltt.github.io/BeyondTheMedal/)

## Team 
- İlayda Aslan 120203068
- Ayşe Kocavelioğlu 120203054
- Beril Polat 120203009



