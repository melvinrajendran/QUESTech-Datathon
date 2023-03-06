# QUESTech Datathon

<img src="https://user-images.githubusercontent.com/44681827/223002743-6e5d327c-9923-4bbf-9921-6513cb29341a.png" alt="Word cloud" width="1000">

A Jupyter notebook analyzing the major reasons for Tesla order cancellation and how Elon Musk's tweets correlate with order cancellation.

This data analysis project was submitted to the 2023 QUESTech Datathon at the University of Maryland, sponsored by Fifth Tribe. Team Coil, which includes myself and Daniel Lamb, won 1st place at the competition and was awarded a $500 cash prize.

## Prompt

Elon Musk (founder of SpaceX, Tesla, and Neuralink) is one of the most influential, yet controversial figures in the tech industry. His tweets are known to cause fluctuations in the stock market and spark intense discourse. We were instructed to analyze a dataset of Elon Musk's tweets and tweets about Tesla order cancellations. We had to conduct a thorough analysis of the data and provide insights into the sentiment, behavior, and trends surrounding Musk and Tesla. We were expected to analyze the dataset using various data science techniques. The winning submission was the analysis that provided the most insightful and actionable insights into the data.

## Findings
* According to the given dataset, Tesla order cancellation is largely due the following four reasons:
  * Difficulty ordering or receiving a Tesla (32%)
  * Issues with customer service (25.6%)
  * Elon Musk's online persona (25.3%)
  * Tesla's supply chain (17.1%)
  
![Screenshot 2023-03-05 at 8 54 40 PM](https://user-images.githubusercontent.com/44681827/223002285-5fb555bc-dd9b-41ce-9aa4-72407a66d1f0.png)
 
* Elon Musk's tweets that involve the following three topics are strongly correlated with Tesla order cancellation:
  * His acquisition of Twitter (39.7%)
  * Politics (30.2%)
  * Engaging in discourse / Tagging others (30.1%)

![Screenshot 2023-03-05 at 8 55 40 PM](https://user-images.githubusercontent.com/44681827/223002367-b23fde7d-889a-4571-a473-230d01b7d81d.png)

## Recommendations
* Streamline the Tesla delivery process
  * Provide regular updates on delivery timelines
  * Offer convient delivery options (e.g. home, work, local Tesla service center)
  * Provide a more seamless handover experience
* Improve the customer experience
  * Incentivize the mobile service program
  * Expand service center network
  * Personalization!
* Invest in domestic manufacturing facilities
  * Simplify the supply chain
* Elon Musk should avoid discussing the topics that are strongly correlated with Tesla cancellation
* Five-year implementation plan:
  * Year 1
   * Conduct customer feedback surveys to identify specific areas for improvement in customer service.
   * Hire and train additional customer service personnel to improve response times.
   * Conduct feasibility studies and site selection for a new factory and begin the process of securing funding and permits.
  * Year 2
   * Launch an online knowledge base and self-help tools to empower customers to troubleshoot and resolve common issues on their own.
   * Begin construction on the new factory and install the necessary equipment and infrastructure.
  * Year 3
   * Launch a customer loyalty program to reward repeat purchases and referrals.
   * Complete construction of the new factory and begin production.
  * Year 4
   * Develop new partnerships with other companies to increase reach and accessibility for customers.
   * Introduce new product lines or features to increase demand and maintain a competitive edge.
  * Year 5
   * Continue to refine and optimize the customer service system, production processes, and distribution channels.
   * Evaluate and review progress.

## Project Timeline

* Data Collection
  * Reading in tweet data from CSV files
* Data Cleaning
  * Removing unnecessary columns and unwanted characters
  * Converting text to lower-case
  * Expanding contractions
  * Lemmatizing every word
  * Converting every tweet into a list of words
* Data Exploration
  * Creating a list of stop words to eliminate bias
* Data Modeling
  * Performing Latent Dirichlet Allocation (LDA) topic modeling
  * Determining the number of topics based on the maximized coherence
* Data Visualization
  * Creating word clouds
  * Plotting coherence score vs. number of topics
  * Displaying a bar chart for the top-30 most relevant terms for each topic
  
# Future Improvements
  * Eliminate biases such as the presence of bot data
