
# ArthaRaksha 



# About the Project
This project focuses on building a prototype resembling a Fraud Protection agent that can help ordinary citizens, especially those who are less aware and emerging digital users against scam calls and texts. Such people may include senior citizens, teenagers with recent digital bank accounts, people from rural parts becoming the emerging digital banking customer segment, people who are not very conversant with English or not so tech savvy etc. though recent reports suggest that well-informed individuals in senior private and public sector roles have also fallen for such frauds. This prototype Fraud Protection agent, named ArthaRaksha, is intended to be at the user’s service 24x7 in his / her native language through its mobile app version. The prototype is built using Vertex AI's Agent Builder and is powered by Google Cloud Platform and Google's latest Large Language and Multi-modal languages such as Gemini 1.0 and Gemini 1.5 pro. The prototype can transcribe and translate native language speech and text, summarize the event, identify the possibility of fraud, analyze a potential fraud, categorize as per RBI (Reserve Bank of India) fraud classification guidelines and help generate incident reports of the potential fraud as per the inputs needed by cybercrime departments with pre-filled parameters (powered by Google’s Gen-AI LLM and MLM models underneath) and finally submit the incident with just one ‘click’ through automated API integration to the agencies and also to banks (if applicable). 

# Inspiration
The first inspiration was from the recent 

The inspiration for this project came from personal experiences: 
1.	In one case, one of the prototype developer’s aunts received a fraud call concerning my cousin with the ultimate intent to siphon off money. The caller claimed that the developer’s cousin was in trouble and demanded immediate payment for supposed legal fees. Although the developer's aunt did not fall for the scam, the experience left a lasting impact on the family, highlighting the urgent need for effective fraud detection mechanisms.
   
2.	In another incident, the prototype developer’s mother received a fraudulent call from a bank that attempted to steal personal information under the garb of KYC renewal for an existing joint account. This joint account has the family’s lifelong savings linked to it.
When we researched further, we found a recent report by the Indian Cybercrime Coordination Centre in Mar'2024 outlining that digital financial fraud's impact on direct individual banking users amounted to a staggering ₹40,000 crore over the last two years, that's approx. 4.8 Billion US Dollars. At the same, time, the number of such fraud calls has grown by more than 110% in the last 2 years in India. Cybercrime, especially financial fraud, poses a burgeoning and rapidly expanding threat in India, impacting millions of individuals and unsuspecting digital banking users.


This alarming situation underscored the increasing prevalence of phone scams and motivated us to develop a solution to help detect and mitigate such fraudulent activities. The Generative AI-powered ArthaRaksha App prototype built upon the Google Cloud VertexAI Agent Builder platform is an attempt to demonstrate the possibility of complementing the relentless efforts of the Indian govt, RBI, and banking players in dealing with the herculean, rapidly mutating fraud patterns of scammers. With a collective effort of all legitimate financial players in India, ArthaRaksha can be powered by a fraud detection and processing platform owned by RBI and contributed to by all interested and legitimate banking players (similar to working models such as those powered by NPCI (UPI), NSDL (for e-commerce marketplace), Digilocker, or upcoming interoperable payment system of RBI). This way, such an underlying model can be continuously trained on the newest fraud data and patterns across languages and be up to date not only with the latest fraud detection patterns but also new fraud awareness protection, response, and control mechanisms developed by both RBI / Govt agencies and banking and other financial players.
Customized versions of the App can be built and deployed by legitimate financial institutions such as banks whereas the underlying platform, data, and model may be contributed to by all financial players, RBI, and Government financial and cybercrime detection agencies. The app intends to bridge the gap between the genuine, dedicated, and independent initiatives by law enforcement agencies, RBI, banks etc. and their adoption as part of a banking user’s daily life. Adoption is best when the interaction with sophisticated backends is hidden to make it a layman’s app in his hand-held device.
Financial fraud methods are similar to viruses and follow viral evolution patterns - they mutate fast and if the protection system is not fast enough to respond, damage is done at a mammoth scale by the time controls are put in place. The ability envisioned through the solution is to embed a much needed “real-time”, trusted analysis capabilities for fraud call and text content providing users with an immediate warning (in some cases, even before a fraud call is terminated) and reducing the reaction times of the protection, control, and reporting systems in place.

# What it does
Generative AI-powered Arth Raksha application prototype built upon the Google Cloud Vertex AI agent builder platform and powered by Google's large language models is an attempt to demonstrate the possibility of complementing the relentless efforts of the government of India, Reserve Bank of India and the legitimate banking players in dealing with a Herculean rapidly mutating fraud patterns of scammers. Backed by powerful generative AI models and collective effort of all legitimate financial players and government authorities in India, Arth Raksha can be continuously trained on newest fraud data and patterns collected by the agencies and the banks and then can be positioned well to provide an intuitive 24/7 available service to every digital banking user in his own native language, helping him through the life cycle of a fraud incident including awareness, early detection and prevention, understanding and analysis of possible fraud, and reporting fraud incidents automatically in real-time.
 
In case the fraud poses risks, it is directly to the authorities with virtually no effort. The audio call that you are now going to hear, though simulated bears a strong resemblance to millions of similar calls that have been ruining the lives and the finances of digital banking users and citizens of India on a daily basis. Of course, the prototype can be scaled at a global level.

# How we built it
Step 1: Research and Data Collection The first step involved extensive research into the characteristics of fraud calls. We collected data from various sources, including publicly available datasets of scam call recordings and transcripts. Below are example datasets that were used: 
● RBI published publicly available documents were used to benchmark the category of fraud 
○ < (https://github.com/7shiny786/ArthaRaksha/blob/main/Data/RBIDoc_DataStore.docx) > 
● A BigQuery scam call dataset was used that was publicly available: 
○ <https://github.com/7shiny786/ArthaRaksha/blob/main/Data/ScamCalls_SM_Scam%20Call_1.mp3 > 
● A few audio calls simulating real fraud calls were made - they are available in GitHub as example calls and used in the prototype flow. Bank/e-commerce clients' names that were used to make the call look like real scam calls made by scammers. These are not real scam calls and have no relation with the bank name or e-commerce company name taken in the scam calls. 
○ <https://github.com/7shiny786/ArthaRaksha/blob/main/Data/ScamCalls_SM_Scam%20Call_2.mp3 >


Step 2: Designing the Architecture I designed the system architecture using Vertex AI's agent builder. The architecture included: ● Data Ingestion: Data is stored on GCS Bucket. ● Pls add here ● Deployment: Deploying the trained Agent Builder on Slack.

Step 3: Implementation and Testing After deploying the Agent Builder, we integrated it with Slack which alerts users when a call is suspected to be fraudulent. We conducted extensive testing to ensure the system's reliability and accuracy, making adjustments as necessary based on feedback and performance metrics.

Here's a breakdown of the flow:
1.	User initiates a call: A user makes a phone call to the ArthaRaksha helpline.
2.	Call recording and transcription: The call is automatically recorded and transcribed using the Speech_to_Text_Agent_SM service.
3.	Translation: If the user's native language is not English, the transcribed call is translated into English using the Translate function.
4.	Summarization: The transcribed and translated call is summarized using the Summarize function, which utilizes the VertexAl Model Garden Gemini 1.5 API.
5.	Fraud analysis: The summarized transcript is then analyzed by the fraud_Analysis_Agent to identify any potential fraud-related questions or concerns raised by the user.
6.	Fraud category identification: Based on the analysis, the FraudCategory component identifies the specific category of fraud being discussed.
7.	Fraud Reporting API: The identified fraud category is then passed to the Fraud_Reporting_API_SM for further action and reporting.
8.	Temporary file storage and management: Throughout the process, temporary files are stored and managed to ensure efficient data handling.
9.	Agent Builder - Tool Function (Fraud_Reporting_API_SM): This component provides tools and functionality for reporting and addressing the identified fraud, ensuring that the user receives appropriate assistance and protection.
The entire process is facilitated by the ArthaRaksha_We_care-Starter Playbook and powered by Google Cloud and Gemini.


# Challenges Faced
Developing ArthaRaksha presented several challenges, primarily stemming from the intricate nature of fraud detection and the need for robust, adaptable AI solutions:

1. Agent Builder Challenges:

Agent Context Passing: Ensuring seamless context passing between different components of the agent was critical for accurate analysis and decision-making. This involved developing strategies to effectively store and retrieve context across stages, such as the initial call transcription, translation, and subsequent fraud analysis steps.
Agent Training & Fine-Tuning: Training the agent builder on diverse datasets and real-world fraud scenarios proved challenging. Adapting the model to recognize subtle variations in fraud patterns and evolving scammer tactics required continuous learning and fine-tuning.
Agent Scalability: Ensuring the agent could handle a high volume of incoming calls and maintain responsiveness without compromising performance was a significant consideration.
2. Data Management and Security:

Data Collection and Annotation: Curating a comprehensive dataset of fraud calls with accurate annotations was essential for effective model training. This involved sourcing data from various sources and ensuring data quality and consistency.
Data Privacy and Security: Maintaining user privacy and protecting sensitive information was a paramount concern. Implementing robust data encryption, and access controls, and adhering to relevant regulations were critical.
3. Integration and API Management:

API Integration with Third-Party Systems: Seamless integration with external APIs from banks, cybercrime departments, and other relevant entities was crucial for automated incident reporting and response. Managing API keys, handling authentication, and ensuring data consistency across systems presented challenges.
API Security and Reliability: Maintaining the security and reliability of APIs was essential to prevent unauthorized access and ensure the smooth operation of the system.
4. Language and Cultural Considerations:

Multilingual Support: Developing a system that effectively recognizes and processes various Indian languages posed a significant challenge. Translating and understanding diverse dialects and accents required advanced natural language processing techniques.
Cultural Nuances: Recognizing and adapting to culturally specific fraud tactics and communication styles was essential to ensure the system's effectiveness across diverse demographics.
5. Model Accuracy and Bias:

Minimizing False Positives: Ensuring high accuracy in fraud detection was crucial to avoid unnecessary alarm and disruption for users. Striking a balance between sensitivity and specificity while minimizing false positives required careful model training and validation.
Addressing Bias in Data: Potential bias in training data could lead to unfair or inaccurate fraud detection. Implementing strategies to mitigate bias and ensure fairness in the model's output was essential.

# Accomplishments that we're proud of
Successfully developed a prototype for a 24/7 fraud protection agent, ArthaRaksha, capable of detecting and reporting potential financial fraud in multiple languages. This prototype utilizes advanced Generative AI technology and Google Cloud services for real-time analysis and reporting.
Demonstrated the potential of using AI to combat financial fraud in India, specifically targeting vulnerable user groups. By addressing the concerns of senior citizens, teenagers, and emerging digital banking users, ArthaRaksha aims to empower individuals against increasingly sophisticated scams.
Developed a user-friendly mobile application interface, designed for ease of use even for individuals with limited technical skills. This focus on accessibility ensures a broader reach and adoption of the fraud detection solution.
Built a strong foundation for collaboration with government agencies, banking institutions, and other stakeholders in the fight against financial fraud. The project has demonstrated the feasibility of a shared platform and data infrastructure, paving the way for a more coordinated and comprehensive approach to combating financial crime.

# What we learned

Throughout the project, we gained invaluable insights and skills:

Understanding of Fraud Tactics and Response systems in place: Most common tactics used by fraudsters, understanding their methods, channels and psychological ploys to deceive victims.

Understanding of Fraud protection initiatives: This includes RBI campaigns, crime registration rules, policies, bank initiatives to curb fraud cases, and processes to raise fraud incidents.

Google CLoud’s Vertex AI: We became proficient in using Vertex AI's agent builder integrating with other Google Cloud services such as cloud function, cloud run, and Gemini 1.5 pro model available in VertexAI Model Garden. Learnings also include building, using, and integrating VertexAI data stores (vector Databases), Ready-to-use Google Cloud API services such as speech-to-text and translation services, and more.

Prompt Engineering and grounding: the reality that Prompt engineering for complex scenarios needs a structured logical approach to problem-solving and works best with robust full functional examples and a fine-tuned model is best suited to avoid hallucinations and model distractions. The underlying quality and richness of the data used for grounding is a key make-or-break factor for such use cases that need to deal with highly unstructured and unexpected data patterns.

Gen-AI-based developer empowerment: Gen-AI capabilities are still evolving but even at their current state of maturity, the technology can fast-track complex Data and AI development projects significantly, they can empower technologies with business acumen and Business analysts with tech acumen thereby blurring the lines of traditional core competence and areas of expertise. Gen-AI supported by an ecosystem of data, application, and integration capabilities, can rapidly increase the proportion of AI investment and projects that lead to real, positive Business ROI (and real NPV realizations) but more importantly, it can have a real, positive social impact on using technology for the genuine welfare of people.

Promises, Limitations and Opportunities: We learned that Vertex AI Agent builder can become a game changer Through the development experience, we came across many limitations, or alternatively opportunities

# What's next for ArthaRaksha:-
Further development of the ArthaRaksha prototype to enhance its accuracy and capabilities. This includes expanding the training data, optimizing the AI models, and incorporating feedback from real-world users.
Exploring partnerships with banks and financial institutions to integrate ArthaRaksha into their existing fraud prevention systems. This would allow for wider adoption and a more proactive approach to fraud detection and mitigation.
Collaborating with government agencies and regulatory bodies, such as the Reserve Bank of India (RBI) and the Indian Cybercrime Coordination Centre, to develop a more comprehensive and collaborative framework for combatting financial fraud. This could involve sharing data, best practices, and resources to create a more robust and effective ecosystem for fraud prevention.
Expanding the reach of ArthaRaksha beyond India to other countries facing similar challenges with financial fraud. This would require tailoring the solution to local languages and regulatory environments.
Continuous research and development to stay ahead of evolving fraud tactics and technologies. This includes exploring new AI models, data sources, and methodologies to ensure the effectiveness of ArthaRaksha in the long term.

ArthaRaksha can be installed on mobile which will tell real-time in ongoing calls if the call is fraud or not. This will help users protect themselves from Fraud.


# Conclusion
This project was both a personal and professional journey. Inspired by a real-life incident, We were motivated to leverage advanced Vertex AI technologies to address a growing concern. Through this project, we not only honed our technical skills but also contributed to a cause that could potentially protect others from falling victim to fraud. The challenges faced along the way were valuable learning experiences, shaping our understanding of Vertex AI applications and their impact on society.


