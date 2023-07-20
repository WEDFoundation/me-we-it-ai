# Me-We-It: A Standard for Responsible AI

This is an Open Suggestion designed to clarify the process of building AI by exposing the steps that 
go into creating it responsibly. It is written from the frontlines by the actual builders, users, and 
stakeholders who have seen the value and damage Artificial Intelligence (AI) can deliver. The goal is 
to set a healthy tone for the industry while making the process understandable by the public to 
illuminate how we can build more ethical AI and create a space for the public to freely ask any 
question they may have of the AI and data science community.

Today we're seeing many doomerism narratives that play into hysteria and obfuscate the structures of 
AI instead of focusing on clear, accountable communication that enables honest discussion and assists 
decision making. The creation of AI can be a technically involved process but the standard approaches 
to teach machines and the outputs created can be monitored and validated in this simple framework 
that enables everyone to have a seat at the table regardless of a person's data science background.

Now more than ever, it's necessary to share how AI learns so that we can hold each other accountable 
without severely restricting innovation. The development of AI has the potential to bring about 
significant benefits, including increased efficiency, improved decision making, health discoveries 
and the ability to tackle problems that were previously impossible to solve. However, AI can also 
force human moderators to witness horrible content, disadvantage the disenfranchised, amplify data 
privacy and safety concerns, steal intellectual property not created for the process, and perpetuate 
biases that cause harm. Without careful consideration and planning, we risk creating AI systems that 
worsen the very problems we seek to solve.

## Open Suggestions Framework

These are the first questions and considerations we believe every AI team and individual builder 
should take everyday to ensure we are releasing more ethical AI models. They are intended to be 
communicated in simple language without technical jargon to ensure the process can be understood by 
every audience and will be translated over time into every local human language where we can find 
volunteers to support. We know we are unlikely to get this completely right, especially when dealing 
with a technology that requires continuous tracking, but with your help each iteration will bring 
meaningful improvements. This is version 1 of many future versions that developers can use when 
assessing our work. The comumnity will help it as we collect more questions from the public and 
suggestions from the data science community to refine the list and capture the necessary steps that 
should be taken to clarify and validate our intentions.

As policy makers frantically race to catch-up with regulation and the EU AI Act signals it may add 
GPAI (General Purpose AI) to the high risk category, we are here to set an actionable standard every 
team can use immediately that also clarifies how AI is built so we can reduce silos and discuss as a 
group. Instead of an Open Letter, this is an Open Suggestion from a group of experienced 
technologists, data scientists, researchers, and people concerned with the impact of AI.

This Open Suggestion will live as a free online forum, and we invite new suggestions and approaches 
under the important banner of registering intent. The steps are isolated based on the core elements 
of building AI (Training, Building, Testing) and the actors who engage in the process to help clarify 
the importance of silo reduction: Me, We, It.

**Me** - The questions each individual who is working on the AI should ask themselves before they 
start and as they work through the process.

**We** - The questions the group should ask themselves and define the diversity required to reduce as 
much human bias as possible.

**It** - The questions we should ask individuals and the group as they relate to the model being 
created and the impact it can have on our world.

### Step 1. Training - Data Selection and Ingestion

**Me** - The necessary questions to ask myself before starting this part of the process. Answers should 
be saved so you can look back at how your thought process evolves.

* What are the reasons for me selecting this training data, and how does that selection align with my 
  intention for this model?
* How was this training data sourced, is there any protected or copyrighted material in the training 
  data such as Personally Identifiable Information (PII), Payment Card Industry (PCI) data, and 
  Protected Health Information (PHI), and have we considered GDPR, CCPA or any other systems for 
  managing data sources?
* Do I have experience in using similar data for AI or Machine Learning models in the past or is this 
  the first time I am using this data source?
* If I've used this data previously, were there any issues that resulted from the models that were 
  trained on this data historically?
* If this is the first time I've used this data, what are my expectations for the impact this data   
  will have on the models outputs?
* Have you used a Model Card to communicate risks and how will this document be updated with the 
  collaboration team?
* What do I hope the data will do to this model, what is my intention of the outcome and how do I 
  expect the training data will impact that performance?
* Are there any features that could act as instrumental variables (eg. Granular neighbourhood level 
  data) for disenfranchised populations, and if so, do you have sufficient controls to ensure that 
  you are not perpetuating biases that can be learned from the training data?
* Can I summarise what is in this training data in a way that captures the essence of the data in a 
  way a non-data scientist can understand?
* Do I feel rushed or pressured to input data from questionable sources?
* Can I cite my source of the training data?
* What biases may be acting on my selection of this data?
* Am I considering biases I have that I don't understand and am I sharing my logic with a larger 
  group who can help me identify my bias being deployed when selecting data?
* How do I think this training data will benefit this model?

**We** - The questions we should ask ourselves as a working group before starting this part of the process. Answers should be saved so we can look back at how our thought process evolves.

* What is the group's intent for training this model?
* Who collaborated in the process of building the training data strategy and selection?
* Is the team of people who are working on selecting the training data from a diverse set of 
  backgrounds and experiences to help reduce the bias in the data selection?
* What are the likely biases inherent in this team that selected the training data?
* Does the whole team understand where the train data came from, and can they explain it back in 
  their own words?
* Is a Model Card being used to communicate risks and did each contributor create their own document  
  that can be shared with the larger team?
* Have we considered the EU AI Act or any other regulation being proposed or that is already in place?
* Is there any protected or copyrighted material in the training data such as Personally Identifiable 
  Information (PII), Payment Card Industry (PCI) data, and Protected Health Information (PHI), and 
  have we considered GDPR, CCPA or any other systems for managing data sources?
* What percentage of my training data am I saving for testing and how are we selecting it?

**It** - The questions we should ask ourselves of the algorithms or models before starting this part of the process. Answers should be saved so we can look back at how our thought process evolves.

* Do I have means to compensate should part of this data set be discovered to be illegal, unreliable, 
  or unacceptable at some point in the future?
* What data is needed to train thoughtfully and with intention?
* Is the full data set of known origin, explainable, and beneficial for the model?
* What are the likely biases inherent in the data?
* Is there any personal identifiable information, protected data, or copyrighted material?
* Am I prepared to handle liability for the model if part of the data set causes any legal issues in 
  the future?
* What are potential unintended uses/consequences, including subsequent level outcomes that the 
  training data could teach the model?
* What are the likely biases that could be amplified through the training data being added to the 
  model?

### Step 2. Building - Creation or Selection of Algorithms and Models

**Me** - The questions I should ask myself before starting this part of the process. Answers should be 
saved so you can look back at how your thought process evolves.

* What do I intend for this model to do, and why am I training it?
* If I am running reinforcement learning, how will this model optimise in the live environment and is 
  it possible my selection of outcomes to test is biassed?
* If I am deploying transfer learning, what are the possible biases that the transferring process 
  will uncover?
* If I am running ensemble models or systems that train each other is there a chance that new bias or 
  bad data collection practices will enter the system?
* How do I think this model will perform and what are some examples of desired outputs I am hoping to 
  see?
* What are my human biases that I possess that impacted my goals and reasoning?
* If I didn't write the model from scratch, where did it come from and how was it initially trained?

**We** - The questions we should ask ourselves as a working group before starting this part of the 
process. Answers should be saved so we can look back at how our thought process evolves.

* Whom did I collaborate with in the process of training this model and building the strategy?
* What human biases are in this group, and have we considered if the working group is diverse enough 
  to capture differing points of view?
* Who were the collaborators building the model and strategy?
* Who are the stakeholders and are all the stakeholders engaging in this step of the process?
* Have we considered the EU AI Act or any other regulation being proposed or that is already in place?
* Were these models trained on any protected or copyrighted material such as Personally Identifiable 
  Information (PII), Payment Card Industry (PCI) data, and Protected Health Information (PHI), and 
  have we considered GDPR, CCPA or any other systems for managing data sources?

**It** - The questions we should ask ourselves of the algorithms or models before starting this part of 
the process. Answers should be saved so we can look back at how our thought process evolves.

* Where did the model come from or was it developed from scratch?
* What is the intended use of the model once it is trained?
* If we didn't create the model ourselves, do we understand the intent of the original creator of the 
  model?
* What are potential unintended uses/consequences, including subsequent level outcomes?
* What are the likely biases that could be amplified through the model?
* Do we have examples of these models with similar data being deployed previously and what were the 
  intended and unintended outcomes?
* What are the possible dangers of the model and do we have a plan for the worst case scenarios?
* What type of measure have I put into place as precautionary measures?
* Who controls the model?
* How will continued compliance with laws and regulations be monitored and implemented?
* How will biases be discovered and resolved?
* How can the model be shut down and under what circumstances must that happen?
* Are there any self interested stakeholders or realities of funding that may stop that from 
  happening?
* What are the contractual requirements that have been entered into that will dictate the management 
  and usage of this model?

### Step 3. Testing - Managing Test Data and Tagging

**Me** - The questions I should ask myself before starting this part of the process. Answers should be 
saved so you can look back at how your thought process evolves.

* Is the data I'm using for testing sufficient for analysing how the model performs?
* Is user testing in the live environment being considered and how will the model be adapted if it 
  turns out that the user behaviour outcome is unwanted.
* What do I think is the best approach for evaluating the outcome of this model before I speak with 
  the larger group about our approach?
* Am I confident that the team and I are aware of the impact our work can have and have we thought 
  about all the potentially bad outcomes that could result from our work that we should be testing 
  for before we go live?
* Do I believe we have been thorough in our testing strategy and deployment to ensure we have 
  unearthed any issues that could arise from the models outputs?
* Did the results of the training data and feedback from taggers match the original intent I had when 
  creating the model. If not, what differed and how do I know it differed?

**We** - The questions we should ask ourselves as a working group before starting this part of the 
process. Answers should be saved so we can look back at how our thought process evolves.

* How do we evaluate the performance and outcomes of this model?
* Are we aware of where the testing data come from and is the testing data appropriate to be 
  representative in relation to the vastness of the training data?
* If the data is tagged by people, who are the people, are they being humanely treated?
* What instruction did taggers receive before they tag the data that might impact their opinion?
* What questions are the taggers or working group asking of the data?
* Does the tagging strategy align with the training data and model creation strategy?
* Is there an appropriate amount of diversity on my data tagging team?
* What human biases might impact the tagging or testing process?
* Is user testing in the live environment data being collected and how will it feed back into an 
  iterative process?
* Are the user group a diverse audience that is representative of the future total user group?
* Is it possible that bias is a programmatic result of the model?
* Whom did I collaborate with in the process of building the testing or tagging data strategy?
* Are product teams involved in the process of retrieving user data and sharing human logic with the 
  larger group?
* Was the intention of the working group realised now that the model has run and been tested? If not, 
  explain in detail with quantifiable data.

**It** - The questions we should ask ourselves of the algorithms or models before starting this part of 
the process. Answers should be saved so we can look back at how our thought process evolves.

* Did the results of the test or tagged data match our intent for the model outputs?
* If we are testing our models to determine accuracy, how much do the results we are seeing match up 
  with the core intent of what the model will do?
* Will I now tune the model based on the outputs of the testing or tagged data? If so, start the 
  process from Step 1.
* If deploying reinforcement learning, how can model outcomes amplify bias and influence new data 
  from users?
* Have we considered the output of the model against the EU AI Act or any other regulation being 
  proposed or that is already in place?
* Have we tested for protected or copyrighted material in the output of the model such as Personally 
  Identifiable Information (PII), Payment Card Industry (PCI) data, and Protected Health Information 
  (PHI), and have we considered GDPR, CCPA or any other systems for managing data sources?
