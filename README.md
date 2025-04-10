
# ChatGPT Scientific Abstracts

## Introduction
Certain words appear much more frequently in texts now than they did before, for example the word "delve". [Here's a good description why this might be the case](https://hesamsheikh.substack.com/p/why-does-chatgpt-use-delve-so-much). People have noticed this also in scientific publications. But can it be quantified? And can this observation really be tied to the use of Large Language Models (LLMs) by researchers? Or could other effects, such as increased overall publication numbers, explain the more frequent occurence of some words? 

## Use of AI in Scientific Research
As anyone else, also scientists use ChatGPT to reformat text in publications. Recently, a survey published by Wiley revealed that 44% of researchers reported using LLMs such as ChatGPT in the research process. [Here's the report](https://www.wiley.com/content/dam/wiley-dotcom/en/b2c/content-fragments/explanaitions-ai-report/pdfs/Wiley_ExplanAItions_AI_Study_February_2025vers1.pdf). However, surveys can be biased, for example by the people willing to participate or by social norms ("It's not good to use ChatGPT to improve my manuscript.").

## Objective Evidence from Scientific Literature
I wondered whether the scientific literature offers more objective evidence for the use of AI in research publications than a survey does. Specifically, I investigated whether the use of certain words increased or decreased after 2022 in scientific literature. PubMed, a large search engine for biomedical literature, was queried for words commonly used by ChatGPT (e.g., "delve") or which should be present in most scientific work (e.g., "in this study", "our results").

## Methodology
### Data Collection
- **Time Frame:** 2014-2024
- **Source:** PubMed
- **Search Terms:** Multiple words in quotes ("word1 word2") and combinatorial searches using the boolean operator OR ("word1 word2" OR "word3 word4").
- **Data Format:** .csv files

### Analysis
- **Linear Regression:** Performed on data from 2014 to 2022 to establish a trend line before the widespread use of LLMs.
- **Prediction:** Using the regression model, publication counts for 2023 and 2024 were predicted.
- **Visualization:** Actual counts, regression line (2014-2022), and predicted counts (2023-2024) were plotted.

### Why Linear Regression?
- **Trend Analysis:** Identifies the underlying trend in the data over time.
- **Prediction:** Allows for predicting future values based on past trends.
- **Simplicity:** A straightforward method to model the relationship between year and publication count.

## Findings
This approach helps to visually and quantitatively assess whether the actual counts for 2023 and 2024 significantly deviate from the expected trend based on the previous years.

### Increased Frequency
Some words are clearly more frequently found in biomedical literature after 2022, such as "delve into" and "treasure trove". This could be due to overall publication numbers increasing for LLM-unrelated reasons.

![image](https://github.com/user-attachments/assets/2f747388-b958-45c6-9ea3-22094cca266f)
![image](https://github.com/user-attachments/assets/eaf2fc23-706f-41f8-a373-a4bbaf01d864)
![image](https://github.com/user-attachments/assets/e946a99c-9d71-4ef8-b481-4aefeb0caaab)
![image](https://github.com/user-attachments/assets/3bb5e964-77a6-4f28-9744-78ee3fd4679b)

### Decreased Frequency
Unexpectedly, there was a drop in abstracts using widespread words like "our results" or "we show" after 2022. This might indicate the use of LLMs by researchers, as LLM-generated text often uses passive rather than active language ("this shows" versus "we show").

![image](https://github.com/user-attachments/assets/a38d6fe5-9b6c-4f77-8de2-67846b90b0e9)
![image](https://github.com/user-attachments/assets/e9393577-6849-4209-b720-468fbcfc8dcc)

### Consistent Frequency
When searching PubMed for "in this study," the results for 2023-2024 were exactly on the trendline based on the 2014-2022 data. So probably, there is no reason to believe that publication numbers rose in general after 2022, but that increased use of certain words can be tied to increase usage of LLMs by researchers.

![image](https://github.com/user-attachments/assets/45e0f4b0-245b-4247-aa28-b07aabfca634)

## Conclusion
Linear regression captures past trends well, at least for the last couple of years. The 44% of researchers using AI for their publications might be an underestimation. It is also interesting to see that not only some words increase, but that others words in an active voice context also can decrease when using LLMs.




