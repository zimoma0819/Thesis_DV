# MACS47000 Assignment 3
**Author:** Zimo Ma  
**Date:** 2025-02-08

## *Research Question and Data Introduction*:

For this assignment, I will utilize data from my academic thesis titled "What Is Beautiful Is Good: Visualizing the Role of Visual Stereotypes in the Workplace." This study examines the questions: "What are the visual stereotypes linked to various client-facing versus back-office roles?" and "How does attractiveness perception impact these stereotypes?" I aim to investigate how facial attractiveness perceptions affect suitability ratings for distinct job roles, especially distinguishing between client-facing and back-office positions. (Note: My thesis proposal is also included in the repository for those interested in further details.) The data will be gathered from a forthcoming experimental study in which participants will assess the job suitability of individuals using hyper-realistic facial images. The study will feature four separate surveys, each associated with a specific job position across two industries—Retail and Finance. Currently, I have 835 hyper-realistic facial images. Participants will evaluate a subset of these images—120 randomly chosen images plus an additional 30 randomly selected from these for inter-rater reliability—to determine each individual's job suitability as described in the survey. This approach is designed to reveal potential biases in hiring influenced by visual stereotypes.


For this project, as I have not yet collected any data, I have received approval from Professor Jean Clipperton to initially use self-generated data for the project and assignments. Since I have almost conducted my survey, I updated the following variable overview.

There will be at least five variables in this study: 
1. Job suitability score (continuous data)
2. Job type (categorical data: client-facing vs. back-office)
3. Job Industry (categorical data: finance / retail)
4. Demographic information of Participants (sex, age, ethnic group, ..)
5. Other Attributes (in the model created by Peterson et al, ther will be 34 attributes linked, such as attractiveness, trustworthness, age, gender, race)

## 📊 Visualizations

### **1. Density Plot**
**"Job Suitability Score Distributions by Role and Industry"**  
This density plot visualizes the distribution of suitability scores for Client-facing and Back-office roles across industries.  
**Key Features:**
- Confidence intervals (CI) are annotated to provide statistical insights into the distributions.
- Density lines are improved to avoid visual artifacts where density is zero.

### **2. Scatter Plot with Regression Lines**
**"The Effect of Attractiveness on Job Suitability Scores"**  
This scatter plot explores the relationship between attractiveness scores and job suitability ratings for each job role.  
**Key Features:**
- Slope annotations for regression lines.
- Statistical significance of slope differences is highlighted with interaction analysis.
- Interactive elements via Plotly allow for dynamic exploration of the data.


**Note**: Since plots that were made through Plotly were not able to be presented on this README.md file, please download knitted HRML file!


   [Categorical Plots html](https://github.com/MACS40700/assignment-3-zimoma0819/blob/main/Assignment3_CategoricalPlots.html) 

   
   [Continuous Y Plots html](https://github.com/MACS40700/assignment-3-zimoma0819/blob/main/Assignment3_ContinuousYPlots.html)

   
## Feedback

#### Continuous Variables

1. **Annotations Issue**
   - **Feedback:** Current annotations were noted as undesirable due to visual clutter, I was suggested to switch to coefficient bar plots with confidence intervals (CIs) to clearly illustrate differences between trend lines.

2. **Legend Placement**
   - **Feedback:** Feedback suggested that the legend placement at the bottom is not optimal, and I should move the legend to the right side instead to enhance plot aesthetics and readability.

3. **Line Plot Clarity**
   - **Feedback:** Alternative line plot configurations were found to be confusing, and I should simplify the line styles and using distinct markers or features to improve clarity.

#### Categorical Variables

1. **Visualizing CIs**
   - **Feedback:** Feedback highlighted that annotations for CIs clutter the visualization, saying I should not add annotations of CI on the graph. Instead, I should directly showing on the X-axis.
   - **Attempt:** Before submitting that assignment, I alreadt experimented with adding CI directly on the x-axis in Plotly, which resulted in an unappealing and awkward visual representation. I think it's largely due to Plotly conversion I will retain CI annotations temporarily while exploring alternative visualization techniques in Plotly or other wats to integrate CIs effectively and aesthetically.

2. **Box Plot Proportions**
   - **Feedback:** Concerns were raised about the disproportionate length of alternative box plots. I was suggested to adjust the canvas size and scaling to ensure that the box plots are proportionate and easy to interpret.
   - **Decision:** I will still go for density plot instead of box plot.

## Expansion

I was suggested by Professor Jean to create final project using Shiny; however, since Shiny has not been introduced to the class yet, I do not have idea on how to do with Shiny specifically. Regarding the data of my thesis, I do have some updates. First of all, I have successfully sent out my survey and collected data from all 394 participants. What I need to do now is to pre-manipulate the data to make it be ready to input into the model, and this process includes 
   - **1)** compute test-retest correlations for each subject on the repeated trials and drop off those subjects with no or negative test-retest correlations.
   - **2)** compute the average judgment for each face.
   - **3)** discuss the modeling with co-workers in the lab.
   - **4)** create models.
   - **5)** meet with my advisor with built models to talk about the following steps.
All of these will take time, so I will try to do these as soon as possible (I am not sure). I will also keep Professor Clipperton updated as we discussed, and we will talk about the possible directions regarding the final projects.

 Regarding the visualizations themselves, I will make adjustments based on the feedback, and once I have appropriate data, I will try to apply my data to those ideas and code to see if it is still working and if there is anything that need to be changed. 
