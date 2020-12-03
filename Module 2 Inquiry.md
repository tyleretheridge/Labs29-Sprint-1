**1. What technical choices did you make today?**   
    Today we decided on the library and pipeline we would use for our modeling, along with the API framework we would use. Specifically SciKitLearn and FastAPI. 
    We also decided to perform some programatic analysis on the model results before returning the conclusions to the dashboard so that it would be easier to interpret.  

**2. Pick two technical choices you're happy with. What was your thought process as you made those choices? What did you consider and what did you decide against?**  
    We decided against a method for modeling such as a neural network or a pre-trained model because we have labeled, tabular data that would work well in a standard classification model.  

**2.1 Take a moment to think about the advantages in choosing the route that you did.**  
    One of the advantages is that it is easier to explain and draw conclusions from the inner workings of an SKL model. There are lots of tools and features built-in to allow analysis of how each feature affected the outcome, which makes developing a method to explain and communicate the results easier.  

**2.2 Now take a moment to consider the disadvantages.**  
    We will have to be very careful with our model choice, and spend a lot of time with tuning, as in context the output of the model is a very sensitive matter.  

**3. In one or two sentences, summarize why you ultimately made the choice you did.**  
    The model choice ultimately gets us closer to both of our goals without sacrificing much for either one. We have to have an accurate model, but also a communicable model. Other model types would shift the balance of difficulty in achieving those goals.   

**4. Extracting useful conclusions from your process:**  
**- According to your understanding, what makes a good technical choice?**  
    A good technical choice is one that causes overall movement towards the end goal of the feature as described on the product roadmap. A good choice also takes into account the skillset of team members as making choices that are hard to implement or require development outside of members' skillset can introduce delays and poor implementations. It is not improper to have these tasks, but an abundance overall reduces the quality of the product or feature. These choices must weigh pros and cons and be justifiable to the stakeholder why certain disadvantages are considered acceptable if any exist. 