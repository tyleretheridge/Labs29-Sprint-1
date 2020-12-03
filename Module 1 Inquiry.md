Module Inquiry 1

**1. (For full-time only) What questions did you ask your stakeholder that helped in breaking down your tasks?**  
	For the data science team, an important question was the communication of the model's results. For the Family Promises project, we are given a multi-class classification problem; however, the person who would be responsible for reading the results and interpreting them was in question. After asking we discovered that we had an important part in programmatically devising a solution that would return a broken down and already interpreted version of the model's results such that the sensitive situation could be communicated effectively and respectfully to the guest. 
	
	
	
**2. What user stories did you draw from to create your product roadmap? List them below.**  

	- As a guest, I’m able to check into the application and fill out a form to check in the shelter (needs fleshing out) --if returning, I can update information based on my case  
	- As a guest, I'm able to specify whether or not I'm a new guest or returning guest when filling out the form  
	- As a new guest, I should have a profile created for me after I submit the questionnaire  
	- As a user can sign in and see the available features based on the user role.  
	- As a user I can edit and update my profile information on my dashboard  
	- As a guest, I should be able to message or post messages for my case manager  
	- As a guest I should be (only) able to view notes added/made to my case by Case Managers IF it is shared with me  
	- As a case manager  I should be able to message or post messages for the relevant parties  
	- As a case manager I should be (only) able to look a specific guest and add notes to their case (ongoing)  
	- As a supervisor, I can lookup (filter) and view all guests (names) checked inside the shelter (view only, immutable)  
	- As a case manager/supervisor I should be able to see the guest's risk level.  
	- As a case manager, I should have a banner at the top of the profile that alerts me to any warnings or concerns.  
	- As a case manager, my flags should be categorizable , customizable with colors and comments to indicate warnings.  
	- As a supervisor or case manager I should see any warnings or flags when searching or checking in guests.
	
	
**3. Select your favorite user story. What are the tasks that need to be accomplished in order to ship that particular user story?**  
	As a case manager/supervisor I should be able to see the guest's risk level. 

	This is my favorite user story because it gives lots of room for data science to declare and assign many tasks.
	The tasks include:
	- Create a risk classifier metric and add to the data
	- Create feature matrices and target vectors for the classification
	- Select a classification model type
	- Construct a modeling pipeline
	- Train the model
	- Hyperparameter tune the pipeline
	- Serialize / Pickle the model
	- Build a fully trained multi-class classification workflow
	- Interpret results and return that as 'guest_risk'
	- POST 'guest_risk' to API
	
	
**3.5 What did you do well in this task breakdown process? What were some challenges?**  
	The process of following standard modeling workflow was very simple. Some challenges were deciding what to do for the backend web team on the output side of the model. 

**4.After what you've learned in this process, given a new product roadmap, how would you approach it differently? What would you change about the way you go about breaking down individual tasks?**  
	If given this task again I would be more cautious about generalized user stories as it leads to duplication of engineering tasks in the planning stages and can make clear dependency outlining more difficult. 