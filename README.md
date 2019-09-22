### Building Inventory Challenge
This repository is produced in [Climate Change AI Hackathon](https://www.eventbrite.com/e/climate-change-ai-hackathon-kickoff-conference-open-to-all-tickets-68731749513#). You can look at the other challenges from this competition [here](https://github.com/ai-launchlab/ccai-hackathon-2019).  

### Problem Statement:  
- To respond to climate-change-related hazards (e.g. floods, wildfires), the public safety community conducts:
    1. Emergency management (real-time evaluation of negative impacts)  
    2. Mitigation planning (modeling and what-if scenarios)
- There is insufficient data on Canadian buildings — limited number of attributes, incomplete spatial coverage, aggregated data

### Approach:
- Using AI/ML to Generate Building Attributes for Use in Risk Assessment.  
- Construct a pipeline to merge data from various sources to form one big database containing multiple attributes data.
- Deploy unsupervised or semi-supervised deep learning techniques to label more data.

### Steps:
#### Phase 1:
- Using Web Scrapping to obtain building data attributes from various sources.
- Merge datasets from already available sources. 
- Use machine learning techniques such as linear and logistic regression to predict the missing values in the data.
- You can find more information on this approach [here](./National_Building_Inventory.pdf).  
- Some of the labeled building dataset collected during the above approach is available in the [dataset](./dataset) folder.

#### Phase 2 (Proposed + some implementation available):
- Find the number of floors and windows and wall-to-window ratio for buildings using Facade Parsing System using DualGAN.  
- Building Height Estimation System using Google Street View Images train data with the current state of the art techniques. 
- More information on the above-discussed approaches can be found [here](./National_Building_Inventory_Deep_Learning.pdf).