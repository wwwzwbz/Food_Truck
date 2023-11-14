# Food_Truck Thing

### What is this?
This is one of the TechPoint Xtern program's Assessment. I was able to move to the finalist, but unfortunately, due to personal reasons, I cannot make it to the actual in-person event. Anyways, this is definitely one of the most time-consuming and interesting OA for an intern application, and I learned a lot from this experience, so I thought it be nice to put it here and share my experience if anyone needs some sample for similar OAs. 

## (30%) Consider implications of data collection, storage, and data biases you would consider relevant here considering Data Ethics, Business Outcomes, and Technical Implications
1. Ethical implications regarding data collection, storage, and data biases
   - Data privacy :: collecting, analyzing, store personal data may raise privacy concerns
   - Dual use :: data may be leveraged to conduct harmful things
       - address information
   - Biases :: biased algorithmn or data collection will cause discrimination or inequality
       - for example, a certain age group, or population from a certain university
   - Algotihm :: decision made by algorithm needs to be ethical
3. Business outcome implications regarding data collection, storage, and data biases
   - Competitive Advantage !!
       - identifying market trends, customer preference, efficient operations
       - the BEST food truck
   - An investment in data / collection / analysis / data management / training may be costly
5. Technical implications regarding data collection, storage, and data biases
   - Data collection :: data sources, quality, volumne
   - Storage :: Security, accessibility
   - Biases :: Algorithmic biases, data pre-processing, bias detection

## Plan for the Predictive Model
- I have no prior experience in building predictive models, so I used the internet to help me understand the process:
- Plans:
  1. Data explorattion :: dimensions, data types, N/A values
  2. Pre-processing :: missing values, outliers
  3. Analyze features :: normalize numerical values, data visulization
  4. Encode Categorical values :: categorical encodings, One-hot encoding is used in this case
  5. Model Building :: split data, train vs target, DecisionTree is used in this case
  6. Findings, results, report on perfomance
- Resources used:
   - ChatGPT
   - https://www.kaggle.com/code/manibhask/data-exploration-and-predictive-modeling
   - a ton of Stack Overflow, Exchange, blah, blah

## (10%) Given the work required to bring a solution like this to maturity and its performance, what considerations would you make to determine if this is a suitable course of action?
- more data
- a better encoding method for categorical target elements :: this looks like a multi-class classification, but I'm not sure how to implement it using skLearn
- a more mature model
     - Gradient Boosted Model, K-Means, Prophets, etc.
- cross validation 
