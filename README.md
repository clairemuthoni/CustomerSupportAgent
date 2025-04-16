# CustomerSupportAgent
In this section I am coding a Customer Support Multi-Agent system. 
Where the Support Agent uses the Scrape website tool to scrape data from crewai's website and give feedback. 

### Structure 
It had two agents, the support agent and the quality assuarance agent. 

The support agent was to answer any enquiry the customer had based on the querry provided by the customer and the data from the website. 
The QA Agent's work was to fact check the information the support agent provided and to ensure that there were no mistakes or hallucinations 

There were two tasks 

The first task was inquiry resolution, where the agent answers the customers inquiry. Then the second task is quality assuarance review. Where the QA Agent 
reviews the work the support agent submited. 

### Results 

The model didnt perform as expected. It just repeated the instructions. This is because I was using the tinyllama model which is best suited for basic tasks and 
not complex and long tasks like this. However it completed to the end and hope you see the results at the end of the terminal ! 
