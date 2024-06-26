# Me-We-It: The Open Standard for Responsible AI

This is an Open Suggestion designed to clarify the process of building AI by exposing the steps that 
go into creating it responsibly. It is an open suggestion proposed by people who have seen the value AI can generate and the damage it can cause. Among these people are:

* experienced specialists in technology, data science, or research;
* frontline stakeholders, including developers;
* users concerned with the impact of AI.

## What's the point of this open standard?

It has three goals:

1. to give some advice to build more ethical AI to help the industry start again on healthy foundations,
2. to help the public understand the process of building an AI, and
3. to create a space in which the public can freely ask any questions to the AI and data science community.

This Open Suggestion will live as a free online forum, and we invite new suggestions and approaches under the important banner of registering intent.

We need clear, responsible communication to engage in honest discussion and make the right decisions. The creation of an AI involves significant technical work, but this open standard enables any interested person to take part in the discussions, regardless of their data science knowledge level. To this end, it offers a simple framework for monitoring and validating standard approaches to the training of machines and the results they produce.

Now more than ever, it's necessary to share how AI learns so that we can hold each other accountable 
without severely restricting innovation. The development of AI has the potential to bring about 
significant benefits, including increased efficiency, improved decision making, health discoveries 
and the ability to tackle problems that were previously impossible to solve. However, AI can also 
force human moderators to witness horrible content, disadvantage the disenfranchised, amplify data 
privacy and safety concerns, steal intellectual property not created for the process, and perpetuate 
harmful biases. Without careful consideration and planning, we risk creating AI systems that 
worsen the very problems we seek to solve.

## First version of the open standard

These are the first questions and considerations we believe every AI team and individual builder 
should ask every day to ensure we are releasing more ethical AI models. They are intended to be 
communicated in simple language without technical jargon to ensure the process can be understood by 
every audience. It will be translated over time into every language where we can find 
volunteers to support. We know we are unlikely to get this completely right, especially when dealing 
with a technology that requires continuous tracking, but with your help each iteration will bring 
meaningful improvements. This is version 1 of many future versions that developers can use when 
assessing our work. We can refine this list with your help, thanks to questions from the public and suggestions from the data science community. Such contributions will help us account for the steps that should be taken to clarify and validate our intentions.

Political decision-makers are buckling down to make up for lost time in terms of regulation, and the EU's legislation on artificial intelligence may add general-purpose AI to the category of high-risk AI systems. In the meantime, we offer you a solution to reduce silos and engage in a group discussion: a practical standard, which any team can use immediately, and which clarifies how AI is built. Instead of an Open Letter, this is an Open Suggestion from a group of experienced 
technologists, data scientists, researchers, and people concerned with the impact of AI.

This Open Suggestion will live as a free online forum, and we invite new suggestions and approaches 
under the important banner of registering intent. The steps are isolated based on the core elements 
of building AI (Training, Building, Testing) and the actors who engage in the process to help clarify 
the importance of silo reduction: Me, We, It.

**Me** - The questions each individual who is working on the AI should ask themselves before they 
start and as they work through the process.

**We** - The questions the group should ask themselves — in particular, to define the diversity required to reduce as much human bias as possible.

**It** - The questions we should ask individuals and the group as they relate to the model being 
created and the impact it can have on our world.

### Step 1. Training - Data Selection and Ingestion

**Me** - The necessary questions to ask myself before starting this part of the process. Answers should 
be saved so I can look back at how my thought process evolves.

* What are the reasons for me selecting this training data? How does that selection align with my 
  intention for this model?
* How was this training data sourced?
* Is there any protected or copyrighted material in the training data such as Personally Identifiable Information (PII), Payment Card Industry (PCI) data, and Protected Health Information (PHI)?
* Have I considered data protection or privacy legislation (such as GDPR and CPRA)?
* Have I considered any other systems for managing data sources?
* Do I have experience in using similar data for AI or Machine Learning models in the past or is this 
  the first time I am using this data source?
* If I've used this data previously, were there any issues that resulted from the models that were 
  trained on this data historically?
* If this is the first time I've used this data, what are my expectations for the impact this data   
  will have on the models outputs?
* Have I used a Model Card to communicate risks? How will this document be updated with the 
  collaboration team?
* What do I hope the data will do to this model? What is my intention of the outcome? How do I 
  expect the training data will impact that performance?
* Are there any features that could act as instrumental variables (eg. granular neighbourhood level 
  data) for disenfranchised populations? If so, do I have sufficient controls to ensure that 
  I am not perpetuating biases that can be learned from the training data?
* Can I summarise what is in this training data so as to capture the essence of the data in a 
  way a non-data scientist can understand?
* Do I feel rushed or pressured to input data from questionable sources?
* Can I cite my source of the training data?
* What biases may be acting on my selection of this data?
* Am I considering biases I have that I don't understand? Am I sharing my logic with a larger 
  group who can help me identify my bias being deployed when selecting data?
* How do I think this training data will benefit this model?

**We** - The questions we should ask ourselves as a working group before starting this part of the process. Answers should be saved so we can look back at how our thought process evolves.

* What is the group's intent for training this model?
* Who collaborated in the process of building the training data strategy and selection?
* Is the team of people who are working on selecting the training data from a diverse set of 
  backgrounds and experiences to help reduce the bias in the data selection?
* What are the likely biases inherent in this team that selected the training data?
* Does the whole team understand where the training data came from? Can they explain it back in 
  their own words?
* Is a Model Card being used to communicate risks? Did each contributor create their own document  
  that can be shared with the larger team?
* Have we considered the EU AI Act or any other regulation being proposed or that is already in place?
* Is there any protected or copyrighted material in the training data such as Personally Identifiable 
  Information (PII), Payment Card Industry (PCI) data, and Protected Health Information (PHI)?
* Have we considered data protection or privacy legislation (such as GDPR and CPRA)?
* Have we considered any other systems for managing data sources?
* What percentage of the training data are we saving for testing? How are we selecting it?

**It** - The questions we should ask ourselves of the algorithms or models before starting this part of the process. Answers should be saved so we can look back at how our thought process evolves.

* Do we have means to compensate should part of this data set be discovered to be illegal, unreliable, 
  or unacceptable at some point in the future?
* What data is needed to train thoughtfully and with intention?
* Is the full data set of known origin, explainable, and beneficial for the model?
* What are the likely biases inherent in the data?
* Is there any personal identifiable information, protected data, or copyrighted material?
* Am I prepared to handle liability for the model if part of the data set causes any legal issues in 
  the future?
* What are potential unintended uses or consequences, including subsequent level outcomes that the 
  training data could teach the model?
* What are the likely biases that could be amplified through the training data being added to the 
  model?

### Step 2. Building - Creation or Selection of Algorithms and Models

**Me** - The questions I should ask myself before starting this part of the process. Answers should be 
saved so I can look back at how my thought process evolves.

* What do I intend for this model to do? Why am I training it?
* If I am running reinforcement learning, how will this model optimise in the live environment? Is 
  it possible my selection of outcomes to test is biased?
* If I am deploying transfer learning, what are the possible biases that the transferring process 
  will uncover?
* If I am running ensemble models or systems that train each other, is there a chance that new bias or 
  bad data collection practices will enter the system?
* How do I think this model will perform? What are some examples of desired outputs I am hoping to 
  see?
* What are my human biases that impacted my goals and reasoning?
* If I didn't write the model from scratch, where did it come from? How was it initially trained?

**We** - The questions we should ask ourselves as a working group before starting this part of the 
process. Answers should be saved so we can look back at how our thought process evolves.

* Whom did I collaborate with in the process of training this model and building the strategy?
* What human biases are in this group? Have we considered whether the working group is diverse enough 
  to capture differing points of view?
* Who were the collaborators building the model and strategy?
* Who are the stakeholders? Are all the stakeholders engaging in this step of the process?
* Have we considered the EU AI Act or any other regulation being proposed or that is already in place?
* Were these models trained on any protected or copyrighted material such as Personally Identifiable 
  Information (PII), Payment Card Industry (PCI) data, and Protected Health Information (PHI)?
* Have we considered data protection or privacy legislation (such as GDPR and CPRA)?
* Have we considered any other systems for managing data sources?

**It** - The questions we should ask ourselves of the algorithms or models before starting this part of 
the process. Answers should be saved so we can look back at how our thought process evolves.

* Where did the model come from or was it developed from scratch?
* What is the intended use of the model once it is trained?
* If we didn't create the model ourselves, do we understand the intent of the original creator of the 
  model?
* What are potential unintended uses or consequences, including subsequent level outcomes?
* What are the likely biases that could be amplified through the model?
* Do we have examples of models with similar data being deployed previously? What were the 
  intended and unintended outcomes?
* What are the possible dangers of the model? Do we have a plan for the worst case scenarios?
* What type of precautionary measures have we put into place?
* Who controls the model?
* How will continued compliance with laws and regulations be monitored and implemented?
* How will biases be discovered and resolved?
* How can the model be shut down? Under what circumstances must that happen?
* Are there any self-interested stakeholders or realities of funding that may stop that from 
  happening?
* What are the contractual requirements that will dictate the management and usage of this model?

### Step 3. Testing - Managing Test Data and Tagging

**Me** - The questions I should ask myself before starting this part of the process. Answers should be 
saved so I can look back at how my thought process evolves.

* Is the data I'm using for testing sufficient for analysing how the model performs?
* Is user testing in the live environment being considered? How will the model be adapted if it 
  turns out that the user behaviour outcome is unwanted?
* What do I think is the best approach for evaluating the outcome of this model before I speak with 
  the larger group about our approach?
* Am I confident that the team and I are aware of the impact our work can have? Have we thought 
  about all the potentially bad outcomes that could result from our work that we should be testing 
  for before we go live?
* Do I believe we have been thorough in our testing strategy and deployment to ensure we have 
  unearthed any issues that could arise from the model's outputs?
* Did the results of the training data and feedback from taggers match the original intent I had when 
  creating the model? If not, what differed and how do I know it differed?

**We** - The questions we should ask ourselves as a working group before starting this part of the 
process. Answers should be saved so we can look back at how our thought process evolves.

* How do we evaluate the performance and outcomes of this model?
* Are we aware of where the testing data comes from? Is the testing data appropriate to be 
  representative in relation to the vastness of the training data?
* If the data is tagged by people, who are the people? Are they being humanely treated?
* Before they tag the data, what instruction did taggers receive that might impact their opinion?
* What questions are the taggers or working group asking of the data?
* Does the tagging strategy align with the training data and model creation strategy?
* Is there an appropriate amount of diversity on my data tagging team?
* What human biases might impact the tagging or testing process?
* Is user testing data in the live environment being collected? How will it feed back into an 
  iterative process?
* Is the user group a diverse audience that is representative of the future total user group?
* Is it possible that bias is a programmatic result of the model?
* Whom did we collaborate with in the process of building the testing or tagging data strategy?
* Are product teams involved in the process of retrieving user data and sharing human logic with the 
  larger group?
* Was the intention of the working group realised now that the model has run and been tested? (If not, 
  explain in detail with quantifiable data.)

**It** - The questions we should ask ourselves of the algorithms or models before starting this part of 
the process. Answers should be saved so we can look back at how our thought process evolves.

* Did the results of the test or tagged data match our intent for the model outputs?
* If we are testing our models to determine accuracy, how much do the results we are seeing match up 
  with the core intent of what the model will do?
* Will we now tune the model based on the outputs of the testing or tagged data? (If so, start the 
  process from Step 1.)
* If deploying reinforcement learning, how can model outcomes amplify bias and influence new data 
  from users?
* Have we considered the output of the model against the EU AI Act or any other regulation being 
  proposed or that is already in place?
* Have we tested for protected or copyrighted material in the output of the model such as Personally 
  Identifiable Information (PII), Payment Card Industry (PCI) data, and Protected Health Information 
  (PHI)?
* Have we considered data protection or privacy legislation (such as GDPR and CPRA)?
* Have we considered any other systems for managing data sources?
