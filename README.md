
# ChatGPT Scientific Abstracts

## Introduction
Certain words appear much more frequently in texts now than they did before, for example the word "delve". [Here's a good description why this might be the case](https://hesamsheikh.substack.com/p/why-does-chatgpt-use-delve-so-much). 

## Use of AI in Scientific Research
Scientists also use ChatGPT to reformat text in publications. Recently, a survey published by Wiley revealed that 44% of researchers reported using Large Language Models (LLMs) such as ChatGPT in the research process. [Here's the report](https://www.wiley.com/content/dam/wiley-dotcom/entors such as the people who like to take surveys or social expectations ("Scientists should not use ChatGPT").

## Objective Evidence from Scientific Literature
I wondered whether the scientific literature offered more objective evidence. Specifically, I investigated whether the use of certain words increased or decreased after 2022 in scientific literature. PubMed, a large search engine for biomedical literature, was queried for words commonly used by ChatGPT or typically present in scientific work (e.g., "in this study").

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
This approach helps to visually and quantitatively assess whether the actual counts for 2023 and 2024 significantly deviate from the expected trend.

### Increased Frequency
Some words are clearly more frequently found in biomedical literature after 2022, such as "delve into" and "treasure trove". This could be due to overall publication numbers increasing for LLM-unrelated reasons.

### Decreased Frequency
Unexpectedly, there was a drop in abstracts using widespread words like "our results" or "we show" after 2022. This might indicate the use of LLMs by researchers, as LLM-generated text often uses passive rather than active language ("this shows" versus "we show").

### Consistent Frequency
When searching PubMed for "in this study," the results for 2023-2024 were exactly on the trendline based on the 2014-2022 data.

## Conclusion
Linear regression captures past trends well, at least for the last couple of years. The 44% of researchers using AI for their publications might be an underestimation.
