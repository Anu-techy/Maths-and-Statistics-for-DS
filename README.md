# Maths-and-Statistics-for-DS

Inferential Vs Descriptive Statistics


**Percentiles**

To get an idea of data distribution

25th percentile --- 25% of the scores are less that 25th percentile number                             
                    
                    =PERCENTILE.INC(range, 0.25)           in Excel

50 th percentile -- median
                    
                    =PERCENTILE.INC(range, 0.5)           in Excel

99 th percentile -- 99% of the scores are less than this percentile number

**Standard Deviation**

Volatility of stock returns can be assessed using variance and standard deviation

df.nvidia_returns.std(), df.nvidia_returns.var()

df.reliance_returns.std(), df.reliance_returns.var()

**Standard Normal Distribution**

Computing z-scores for each of the datapoints and plot the distribution of z-scores

mean=0       and       std dev =1

Used in comparing data sets and in z-tests to assess differences between means
=================================================================================

**Sample Bias** occurs when a sample is not representative of the population.
These terms are all types of biases that can occur in research, data collection, or analysis, often leading to inaccurate or misleading conclusions. 
Here's a breakdown of each:

**1. Selection Bias**
Selection bias occurs when the individuals or units included in a study or sample are not representative of the larger population. 

**Example:** If a survey about health habits is only conducted among people who go to a gym, 
it might exclude people who don’t exercise, thus skewing the results toward healthier habits.

**2. Participation Bias**

Participation bias is a specific type of selection bias that arises when the individuals who choose to participate in a study or survey are different 
from those who do not. This can affect the generalizability of the results, as the sample may not represent the population as a whole.

**Example:** In a study about mental health, if only people who are already receiving treatment for mental health issues choose to participate,
the results may not reflect the experiences of the general population.

**3. Survivorship Bias**

Survivorship bias occurs when only the "survivors" or the subjects that remain in a study are considered, ignoring those who have dropped out or failed. 
This leads to overly optimistic or skewed conclusions, as the people or things that "survived" the process are not representative of the full population.

**Example:** In studying the success of businesses, only the businesses that are still operating are included. 
The ones that failed are excluded, leading to a biased view that only successful businesses exist.

**4. Language Bias**

Language bias occurs when certain languages or dialects are favored over others in a study or data collection, leading to unrepresentative or skewed results. 
It can happen when data is collected, analyzed, or reported in one language that may not adequately represent other languages or cultural contexts.

**Example:** A global survey on social media usage conducted only in English might exclude non-English speakers, 
thus not capturing trends or behaviors in non-English-speaking regions or populations.

These biases can distort research findings and impact decision-making. Understanding and mitigating them is critical in ensuring 
the validity and reliability of conclusions drawn from data. 

We need to make sure training dataset is a true representative of the population

================================================================================








