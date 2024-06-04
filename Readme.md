## <a name="_vzxrgm14azlq"></a>**Project demo Links**
**First Link:** Main demo link [Main Demo link](https://www.youtube.com/watch?v=T4jKsEfp5cc)
<br>
**SecondLink:** Technical deep-dive link and Architectural Workflow. Walkthrough of ArthaRaksha in action through functionality and code [Second Demo link](https://www.youtube.com/watch?v=RgnEcCYdsbQ&t=0s)
<br>



## <a name="_h1x2i0jbg1em"></a>**About the Project**
This project focuses on building a prototype resembling a Fraud Protection agent that can help ordinary citizens, especially those who are less aware and emerging digital users against scam calls and texts. Such people may include senior citizens, teenagers with recent digital bank accounts, people from rural parts becoming the emerging digital banking customer segment, people who are not very conversant with English or not so tech savvy etc. though recent reports suggest that well informed individuals in senior private and public sector roles have also fallen for such frauds. This prototype Fraud Protection agent, named ArthaRaksha, is intended to be at the user’s service 24x7 in his / her native language through its mobile app version. The prototype is built using Vertex AI's Agent Builder and is powered by Google Cloud Platform and Google latest Large Language and Multi-modal languages such as Gemini 1.0 and Gemini 1.5 pro. The prototype can transcribe and translate native language speech and text, summarize the event, identify the possibility of fraud, analyze a potential fraud, categorize as per RBI (Reserve Bank of India) fraud classification guidelines and help generate incident report of the potential fraud as per the inputs needed by cybercrime departments with pre-filled parameters (powered by Google’s Gen-AI LLM and MLM models underneath) and finally submit the incident with just one ‘click’ through automated API integration to the agencies and also to banks (if applicable). 
## <a name="_hyaaegi0ql9h"></a>**Inspiration**

The inspiration for this project came from personal experiences: 

1. In one case, one of the prototype developer’s aunt received a fraud call concerning my cousin with the ultimate intent to siphon off money. The caller claimed that the developer’s cousin was in trouble and demanded immediate payment for supposed legal fees. Although the developer's aunt did not fall for the scam, the experience left a lasting impact on the family, highlighting the urgent need for effective fraud detection mechanisms.
2. In another incident, the other prototype developer’s mother received a fraudulent call from a bank that attempted to steal personal information under the garb of KYC renewal for an existing joint account. This joint account has the family’s lifelong savings linked to it.

When we researched further, we found a recent report by the Indian Cybercrime Coordination Centre in March 2024 that highlighted the massive impact of digital financial frauds in India. The report mentions that the financial loss arising out of scams and frauds in which individual banking users got trapped amounted to a staggering ₹40,000 crore over the last two years, that's approx. 4.8 Billion US Dollars. At the same time, the number of such fraud calls has grown by more than 110%. Cybercrime, especially financial fraud, poses a burgeoning and rapidly expanding threat in India, impacting millions of individuals and unsuspecting digital banking users. And, the issue is not limited to India alone. A recent report by Trucaller brings out that around 56.2 million adults in US were impacted by the spam and scam call epidemic in 2023 that amounted to approximately $25.4 Billion - higher than the Tax revenues of the State of Arizona for FY22. Clearly, countries and regions around the world are under the grip of this menace of financial fraud and scams related to digital payments and banking. <br>

This alarming situation underscored the increasing prevalence of phone scams and motivated us to develop a solution to help detect and mitigate such fraudulent activities. Generative-AI powered ArthaRaksha App prototype built upon the Google Cloud VertexAI Agent Builder platform is an attempt to demonstrate the possibility of complementing the relentless efforts of the Indian govt, RBI, and banking players in dealing with the herculean, rapidly mutating fraud patterns of scammers. With the collective efforts of all legitimate financial players in India, ArthaRaksha can be powered by a fraud detection and processing platform under the governance of RBI can be built with a design framework similar to groundbreaking digital working models in India such as those powered by NPCI (for UPI), ONDC (for ecommerce marketplace), Digilocker, or upcoming inter-operable payment system and AA interoperability frameworks postulated by RBI) except that the proposed model may probably be the first that has Generative AI at its core value proposition.. This way, such an underlying model can be continuously trained on the newest fraud data and patterns across languages and be up to date not only with the latest fraud detection patterns but also new fraud awareness protection, response, and control mechanisms developed by both RBI / Govt agencies and banking and other ecosystem and technology players.<br>

Customized versions of the App can be built and deployed by legitimate financial institutions such as banks whereas the underlying platform, data, and model may be contributed to by all financial players, RBI, and Government financial and cybercrime detection agencies. The app intends to bring synergy between the genuine, dedicated, and independent initiatives and efforts by law enforcement agencies, RBI, banks etc. and the reach and adoption of such initiatives as part of a banking user’s everyday life. Adoption is best when the interaction with sophisticated and intricate technologies is hidden or invisible to make it a layman’s app in every user’s hand-held device. <br>

Financial fraud methods are similar to viruses and follow viral evolution patterns - they mutate fast and if the protection system is not time-sensitive and agile enough to learn and respond, the damage is already done at a mammoth scale by the time users realize that they have been conned and agencies get a hold of fraud methods. The ability envisioned through the solution is to embed a much needed “real-time”, trusted analysis capabilities for fraud call and text content empowering users with an immediate warning (in some cases, even before a fraud call is over) and drastically improve the reaction times of the protection, control, and reporting systems in place.<br>


## <a name="_30dgzx8lndoo"></a>**What it does**

Generative-AI powered ArthaRaksha App prototype built upon the Google Cloud VertexAI Agent Builder platform is an attempt to demonstrate the possibility of complementing the relentless efforts of the Indian govt, RBI, and banking players in dealing with the herculean, rapidly mutating fraud patterns of scammers. With the collective efforts of all legitimate financial players in India, ArthaRaksha can be powered by a fraud detection and processing platform owned by RBI and contributed to by all the interested and legitimate banking players, telecom players etc. (similar to working models such as those powered by NPCI (UPI), NSDL (for ecommerce marketplace), Digilocker, or upcoming inter-operable payment system postulated by RBI). This way, such an underlying model can be continuously trained on the newest fraud data and patterns across languages and be up to date not only with the latest fraud detection patterns but also new fraud awareness protection, response, and control mechanisms developed by both RBI / Govt agencies and banking and other financial players. Customized versions of the App can be built and deployed by legitimate financial institutions such as banks whereas the underlying platform, data, and model may be contributed to by all financial players, RBI, and Government financial and cybercrime detection agencies. The app intends to bridge the gap between the genuine, dedicated, and independent initiatives by law enforcement agencies, RBI, banks etc. and their adoption as part of a banking user’s daily life. Adoption is best when the interaction with sophisticated backends is hidden or invisible to make it a layman’s app in the user’s hand-held device. Financial fraud methods are similar to viruses and follow viral evolution patterns - they mutate fast and if the protection system is not time-sensitive and agile enough to learn and respond, the damage is already done at a mammoth scale by the time users realize that they have been conned and agencies get a hold of fraud methods. The ability envisioned through the solution is to embed a much needed “real-time”, trusted analysis capabilities for fraud call and text content empowering users with an immediate warning (in some cases, even before a fraud call is over) and to drastically improve the reaction times of the protection, control, and reporting systems in place.

## **How we Built it**
### **Step 1: Research and Data Collection**
The first step involved extensive research into the characteristics of fraud calls. We collected data from various sources, including publicly available datasets of scam call recordings and transcripts. Below are example datasets that were used:

- RBI published publicly available documents were used to benchmark category of frauds
  - [https://www.rbi.org.in/financialeducation/RajuandATM.aspx](https://www.rbi.org.in/financialeducation/RajuandATM.aspx%20) 
- A BigQuery scam call dataset was used that was publicly available:
  - <https://github.com/7shiny786/ArthaRaksha/blob/main/Data/ScamCalls_SM_Scam%20Call_1.mp3> 
- Few audio calls simulating real fraud calls were made - they are available in github as example calls and used in the prototype flow. Bank / ecommerce clients' names that were used to make the call look real scam calls made by scammers. These are not real scam calls and has no relation with the bank name or ecommerce company name taken in the scam calls.
  - <https://github.com/7shiny786/ArthaRaksha/blob/main/Data/ScamCalls_SM_Scam%20Call_2.mp3>

Since the RBI document was a collection of text, images, text blended within images, and a lot of customer formatting that is commonly seen in marketing materials, OCR was used to extract useful context related to fraud example and their categories and the processed document was used as input as data store for grounding.


### <a name="_zowku1vduzm"></a>**Step 2: Designing the Architecture**
We designed the system architecture on Google Cloud platform and integrated different google cloud services to bring the solution to life . A schematic representation of the technical architecture is attached here:

<https://github.com/7shiny786/ArthaRaksha/blob/main/Technical_Architecture/ArthaRaksha-Technical_LLD.png>

to enable readers to easily correlate with the below explanation. The architecture includes: 

- **Data Ingestion** **and storage**: Google Cloud storage has been used as the predominant data storage component.
  - Call (audio) record file are stored at
    - <https://github.com/7shiny786/ArthaRaksha/blob/main/Data/ScamCalls_SM_Scam%20Call_2.mp3>
  - Scam documents including text files and transcribes are stored at 
    - <https://github.com/7shiny786/ArthaRaksha/blob/main/Data/transcripts_SM_Scam%20Call_1_transcript_66553c59-0000-222f-8ea3-582429cdbdc8.json> 
  - VertexAI Agent Builder used tool Datastore for the purpose of retrieving data chunks (called snippets) when requested to be grounded to specific datasets for certain questions (for example, fraud categorization). The underlying storage for Datastore is google cloud storage. The cleansed RBI guideline is stored at 
    - <https://github.com/7shiny786/ArthaRaksha/blob/main/Data/RBIDoc_DataStore.docx> 
  - Staging area has been used to store temporary files generated as part of the conversation flow. This serves as kind of working memory for the application for a specific session. Such files are stored at
    - <https://github.com/7shiny786/ArthaRaksha/blob/main/Data/StagingArea_Content/ScamSMS_scam_text_Translation_1_SM.txt> 
- **Application Stack:**
  - **Front-end:** The user interface part is simple, intuitive, and currently built and deployed over Slack. This is the point at which user will interface with the ArthaRaksha and current implementation which is only a prototype may be replaced with interfaces built over open source frameworks such Vue.JS (vue-chatbot), Reach.js (with chatfuel), RASA etc.. Alternatively one may chose to go for managed services for developers such as Kommunicate, Microsoft Bot, Botanic or integrated with ready to use customer facing agents that are already well adopted such as Whatsapp, Telegram, facebook messenger or Google’s ‘Dialog Flow’. There are immense opportunities to differentiate an Artharaksha offering in the front-end and financial players such as banks or authorized fraud protection partners of RBI / Government may like to integrate ArthaRaksha’s capabilities through existing applications.
  - **Back-end:** This is the layer that is currently being showcased through the Vanilla App’s slack interface. The Backend has multiple stages. The hub of the backend is a mesh of **Agents** built upon Google's Vertex AI Agent builder Platform. There are multiple agents that together encompass the back-end solution. These include:
    - Anchor / greeting Agent: ArathaRaksha-We care: This agent is supposed to be single messenger for the user. It greets the user, takes questions from the user and redirects the user to the specialist agents basis the user’s intent (or ask) and topic of interest.
    - There are three specialist Agents:
      - Speech to Text Agent SM: user requests related transcription and translation are received and processed and responded to by this agent. This agent can also do a handover to the next agent if need be.
      - Fraud Analysis Agent: user request related to fraud detection, analysis, call summarization, and reporting are processed and responded to by this agent.

Agents are prompt engineered and built on top of Google’s Gemini 1.0 generative AI model. This is the latest gen-AI model supported by VertexAI Agent Builder at the time of writing this article.

Agents use **tools** to accomplish tasks. There are 3 types of tools available currently in Vertex AI Agent Builder platform - OpenAPI, DataStore, and Function. Tools are used in the following way:

- **OpenAPI type Tools** such as transcription\_sm, translation\_sm, and summarize\_sm are used to trigger Google’s latest gen-AI model, Gemini 1.5 pro available through API’s in Model Garden. Reasons to choose this API include the model’s its better performance compared to other models tested and its best in class multi-modal capabilities that were surprisingly pleasing and accurate and could be leveraged for multi-tasking. Tools such as read\_translation\_sm were used in conjunction with summarize\_sm to circumvent challenges around parameter passing beyond one agent hope as specifying system and session parameters for making calls are not possible at the moment in the current version of VertexAI Agent builder. 
- **Datastore type Tools** such as Fraud\_category have been used to retrieve the most relevant snippets from the vertex AI Datastore that host the processed and chunked RBI fraud guideline and category document. Agents have been prompted to ensure that any question that needs fraud categorization as a direct or indirect response must use the Datastore to respond to such a question as public fraud categorization knowledge of GenAI models may vary and may Built on top of Vertex AI Search, that is Google’s go to market RAG method implementation, Vertex AI Data Store tool is working as an out-of-the-box grounding system and supports RAG (or retrieval augmented generation) APIs for document layout processing, ranking, retrieval, and performing checks on grounding outputs to private trusted enterprise data such as Cyber crime databases and, in this prototype, is limited to grounding against the RBI document guidelines for fraud category. The idea is to demonstrate the grounding part that is critical to make the model more accurate, regulated, governed, and trusted and at the same time remain contextually relevant and provide a high level of accuracy in fraud analytics by only using trusted, approved data. In real world, such fraud detection and analytics gen-AI models must be regularly fine-tuned and have a working memory for RAG implementation (read: [TransfromerFAM ](https://arxiv.org/abs/2404.09173)research paper by Google), such activities have not been performed in this prototype but is highly recommended provided access could be made available to diverse, verified fraud data (both structured and unstructured)- this is where we have struggled as expected.
- **Function type Tools** such as Fraud\_Reporting\_API\_SM is supposed to be called by calling agent such as anchor of fraud analysis agent to use all the parameter variable captured through the transcribed translation and fraud analysis, add system parameters that should already be available to authorized installed app agent and then use all these inputs to create a JSON / YAML structure that can be used to automatically submit fraud incident to cyber crime reporting portals through cloud services such as Apigee. This part could not be completed as APi access to such portals is not available at the moment. However, it is built to showcase completion of the idea. The Agent is supposed to receive a Request\_ID in response to the submission of the fraud incident through the Fraud\_Reporting\_API\_SM  tool and share the same with the user and with that an initial fraud related user conversation should conclude.

Generative AI Models available in Model Garden or open source models outside Google Cloud cannot be accessed directly from VertexAI Agent Builder platform components at the moment. Therefore, second generation **Google cloud functions** deployed on serverless **Google Cloud Run** have been used to accomplish the integration with Google cloud internal systems such as to directly trigger the components such as Gemini 1.5 Pro multi-modal model available in vertex AI Model Garden.

- **Integration beyond GCP:** Proposed integration with other Applications such as those of Crime Bureau, RBI or Financial Bank’s internal or customer facing applications hosted in any other cloud or on-prem may be accomplished through Google’s extended ecosystem consisting of **pub/sub** and **Apigee**. Pub/Sub can be used as a message broker to decouple publishing agent (emitted from the Vertex AI chat interface) from the subscriber agents such as the 3rd party SAAS applications, database and servers thereby providing massive asynchronous parallel processing that will anyways be needed. Whereas, Apigee Platform (Apigee X or Apigee hybrid) may be used to expose REST APIs for publishers to publish messages to Pub/Sub topics and Async APIs (Websockets) that can be “consumed” by “Subscribers” without exposing internal ecosystem of the fraud platform. These extensions are currently proposed but not built in as part of the prototype and may be taken up in the future. Cloud Run may host services that perform “Pub/Sub to Websockets” translation wherever needed to provide integration with legacy services.
###
### <a name="_bki7qit12ehn"></a><a name="_ezjfliq18mnh"></a>**Step 3: Implementation and Testing**
After deploying the Agent Builder, we integrated it with Slack that could alert users when a call is suspected to be fraudulent. An event driven architecture may be used to raise alert to the user even in the middle of a call warning him of potential scam and giving the option to the user to continue the call or disconnect. Such alerts can go a long way to putting up a real time fraud prevention shield thereby preventing a possible damage before its done. While we have conducted testing to ensure the system's reliability, accuracy and reproducibility, readers and developers are advised to adapt the work and improve upon it by adding more example for the agents, adding more quality enriched data, and extending API exposing services as proposed above for 3rd party integration to general SAAS application and making adjustments as necessary based on outcome and performance.

Special considerations for security and privacy need to be made including at a data level (for example creating contextual custom filters for inputs to LLMs and LLm responses) and access level. The level of filtering for LLM response has been set at “BLOCK\_ONLY\_HIGH” rather than the default “BLOCK\_MEDIUM\_AND\_ABOVE” for 

- Harassment
- Hate speech
- Sexually explicit
- Dangerous

This has been done since we observed that Gemini 1.5 pro sometimes failed to process requests when the input content was detected to be unsafe with the default settings. In the specific case of fraud, we may expect that transcribed and translated content may have a higher than expected level of normally acceptable content. In real world situations, custom safety filters need to be applied at input and processing level to avoid filtering out ‘unsafe’ content while putting a different set of filters for output depending on whether the LLM is supposed to return original transcripts / translations or during the time it needs to summarize of draw conclusions regarding the events that unfolded in the scammer’s conversation with the receiver.


## **Challenges we ran into**
Developing ArthaRaksha presented several challenges, primarily stemming from the intricate nature of fraud detection and the need for robust, adaptable AI solutions:

- **Agent Builder:**
  - Agent Context Passing: Ensuring seamless context passing between different components of the agent was critical for accurate analysis and decision-making. This involved developing strategies to effectively store and retrieve context across stages, such as the initial call transcription, translation, and subsequent fraud analysis steps. 
    - We found that VertexAI Agent builder lacks a developer managed and controlled way to pass and invoke session and context parameters as well as custom parameters unlike the more structured way inbuilt to call or invoke agents and tools. We hope that the 3rd option related to structured parameter passing becomes easier to implement and use.
    - The ability to use structured and instructed data as part of the same datastore
  - Agent Prompt engineering & Fine-Tuning: Training the agent builder on diverse datasets and real-world fraud scenarios proved challenging. Adapting the model to recognize subtle variations in fraud patterns and evolving scammer tactics required continuous learning and fine-tuning. Agent Scalability: Ensuring the agent could handle a high volume of incoming calls and maintain responsiveness without compromising performance was a significant consideration. We were really features such as 
    - the ability to redo particular user request,  
    - a one click deployment and addition of a multi agent example workflow that was successfully accomplished
    - Better logging and tracing (especially end to end session tracing) for the paths taken by agents, the stored state and user parameters and agent entry points during handovers- the troubleshooting for prompt engineering turning out to be a tedious job as it involved a lot of permutations and combinations that can be minimized if the developer can trace the chain of actions that the workflow is actually taking.
    - Out of box Prompt versioning and templatization, especially for nested prompts, capabilities can be improved as prompt engineering is a mix of art and logic and therefore needs multiple rounds of repetitive iterations before desirable outcome is realized - this is effort intensive and therefore is an area of opportunity to improve developer experience
    - An aspiration feature is to enable developers to use a Like/Dislike button at the end of an Agent response during prompt engineering and implemented in the backend as a continuous reinforcement learning with human feedback (RLHF). We couldn’t find this feature.
    - Though Vertex AI Agent Builder DataStore tool powered by vertex Ai Search is phenomenal when it comes to grounding as it supports different types of structured and unstructured data, allows OCR based methods to extract information, and provides out of box capabilities for chunking, a direct integration with Langchain or LlamaIndex based retrieval mechanisms from vector DB’s is a feature that we found to be missing. In a real world scenario, it is quite possible that the data store for grounding may not be a data store hosted in an internal environment but a common vector DB hosted on a different platform co-owned and governed by Govt and RBI and contributed to by different authorized private and public entities such as banks and others.
    - Vertex AI agent components are currently not able to directly integrate with rest of the Google cloud services unless they go through a JSON based OpenAPI tool type integration through a cloud function. More seamless integration options can be built in to allow invoking a diverse set of Google cloud platform services directly from the prompts or through tools, preferably text to code tools as we may expect there will be a much larger spread of existing legacy services that will continue to need structured REST/socket based API integration prerequisites.

- **Data Privacy:** Maintaining user privacy and protecting sensitive information is of paramount concern. Invocation of services such as DLP should be enabled out of the box both for private data detection and obfuscation to make the environment even more developer friendly. We must remember that both the possibility of sensitive and private data creeping into data and the probability of such instances being overlooked or missed are higher in scenarios where unstructured data in the form of audio, images, native language text, video, and pdf documents are involved. No sensitive data has been used as input for the current prototype.

- **Security & Role based access control:** Different levels of Role based Access Controls needed at the Developer level, the user level for the front-end (ex. Slack or dialogflow), at the API integration level (mostly through service accounts) and data access level (again currently implemented through service account). The integration of VertexAI Agent builder with Dataplex may go a long way to bring uniformity and consistency of authorizing or restricting access to underlying data be it through Vertex AI Data Store (or Vertex AI Search), vector DB’s or Data lakes / Data Meshes. Such integration and role allocation will significantly fast-track projects due to ease of applying or revoking such permission by the platform administrators and guaranteed consistency from Data Governance perspective. At the end, all LLM’s and gen-AI apps are consumers of data and need to be treated at par with human uses, other traditional applications, and existing ML Models and dashboards.  

- **API Integration with Third-Party Systems** through Apigee may be brought in as an out of box functionality to provide Seamless integration with external APIs (in this case, banking systems, cybercrime departments, and other relevant entities was crucial for automated incident reporting and response). Managing API keys, handling authentication, and ensuring data consistency across systems presented challenges.

- **Multilingual Support**: Developing a system that effectively recognizes and processes various Indian languages posed a significant challenge. Translating and understanding diverse dialects and accents required advanced natural language processing techniques. Cultural Nuances: Recognizing and adapting to culturally specific fraud tactics and communication styles was essential to ensure the system's effectiveness across diverse demographics. 

- **Model Accuracy and Bias**- Minimizing False Positives: Ensuring high accuracy in fraud detection was crucial to avoid unnecessary alarm and disruption for users. Striking a balance between sensitivity and specificity while minimizing false positives required careful model training and validation. Addressing Bias in Data: Potential bias in training data could lead to unfair or inaccurate fraud detection. Implementing strategies to mitigate bias and ensure fairness in the model's output was essential.

- **Compliance Reporting and Auditing:** Auditing the conversation life-cycle with LLM and LLM processing and response patterns need to be made more robust to meet the following requirements:
  - Auditing capabilities should automatically generate reporting metrics related to Model usage, performance, accuracy, and metrics that need to be reported for legal or regulatory compliance as well as ethical guardrails related to Responsible AI
  - In built into compliance, LLM explainability should be built into Vertex AI Agent builder Platform that will not only help developers and product managers offer a strong value proposition for model adoption but also help build the next level trust in gen AI models for all parties involved in the ecosystem - Government, Regulatory bodies like RBI, public and private financial players, ecosystem partners (ex. Fraud insurance providers), law enforcement agencies, and the general public.




## **Accomplishments that we're proud of**

**Outcome Achieved:**

We successfully developed a prototype for a 24/7 fraud protection agent, ArthaRaksha, that is demonstrated to be capable of 

- Transcribing and translating audio records and text (in multiple languages) with the context of fraud
- Analyzing possibility of a call or text being a fraud attempt
- Providing explanations to the user based on natural language Q&A
- Summarizing the chronology of events with regard to the calls
- Spreading awareness about fraud to mass users at a personalized level
- Identifying the category of fraud in line with RBI fraud category guidelines
- Sharing and recommending best practices at a personalized level based on user’s recent experiences
- Assisting users to gauge the risk level of the situation the user is in and help him with inputs on personal information that the user might have shared inadvertently during the course of the call and the possible ramifications of the same
- Detecting and building the ability to auto-report fraud incidents on behalf of the user by not only self-populating the mandatory inputs but also providing detailed evidence of the potential financial fraud attempt from the model’s context. 

**Technology Experience honed:**




- Explored and used latest and cutting edge Large Language and multi-modal models from Google Cloud Platform and easy to adopt platform for building gen AI agent using vertex AI Agent Builder 

**Potential Social Impact:**




- We were able to give aspirational shape and form to an idea to counter financial scams and were able to build a strong foundation for a self-evolving ecosystem that can be fed and nurtured through collaboration and contribution of all players and institutions interested in the fight against financial fraud. The project has demonstrated the feasibility of a federated shared data and AI platform paving the way for a more coordinated and comprehensive approach to combating financial crime.

## <a name="_h1x2i0jbg1em"></a>**What We Learned**

Throughout the project, I gained invaluable insights and skills:

1. **Understanding of Fraud Tactics and Response systems in place**: Most common tactics used by fraudsters, understanding their methods, channels and psychological ploys to deceive victims.

1. **Understanding of Fraud protection initiatives**: This includes RBI campaigns, crime registration rules, policies, banks initiatives to curb fraud cases, and processes to raise fraud incidents.

1. **Google CLoud’s Vertex AI**: We became proficient in using Vertex AI's agent builder integrating with other Google cloud services such as cloud function, cloud run, Gemini 1.5 pro model available in VertexAI Model Garden, . Learnings also include building, using, and integrating VertexAI data stores (vector Databases), Ready to use Google cloud APi services such as Speech to text and translation services, and more.

1. **Prompt Engineering and grounding:** the reality that Prompt engineering for complex scenarios needs a structured logical approach to problem solving and work best with robust full functional examples and a fine tuned model is best suited to avoid hallucinations and model distractions. The underlying quality and richness of the data used for grounding is a key make or break factor for such use cases that need to deal with highly unstructured and unexpected data patterns.

1. **Gen-AI based developer empowerment:** Gen-AI capabilities are still evolving but even at their current state of maturity, the technology can fast-track complex Data and AI development projects significantly, they can empower technologies with business acumen and Business analysts with tech acumen thereby blurring the lines of traditional core competence and areas of expertise. Gen-AI supported by an ecosystem of data, application, and integration capabilities, can rapidly increase the proportion of AI investment and projects that lead to real, positive Business ROI  (and real NPV realizations) but more importantly, it can have a real, positive social impact on using technology for the genuine welfare of people.

1. **Promises, Limitations and Opportunities:** We learned that Vertex AI Agent builder can become a game changer in driving massive adoption of complex technology offerings through the simplest possible human interface and natural language based interactions. Through the development experience, we also came across limitations of the current version of Vertex AI Agent Builder which is in preview state at the time of writing this document. We expect the platform to naturally evolve through further testing and improvements to become even more helpful to developers and churn massively impacting Gen-AI apps. Some of the limitations are discussed in the section “Challenges faced”. We also have tremendous opportunities in extending VertexAI Agent Builders to become part of the larger integrated ecosystem that comprises an enormous spread of traditional tech-stack, applications, and data systems (such as data warehouses and data lakes).

## <a name="_h1x2i0jbg1em"></a>**What's next for ArthaRaksha**

1. **Robustness and Completeness:** Making the application much more robust and powerful 
   1. by fine-tuning model and enabling integration with RAG based implementation using vector DB’s enriched with large corpus of fraud datasets
   1. Rigorous testing and exception handling
   1. Feeding in quality, diverse fraud datasets in different languages and categorized by fraud patterns that are labelled to enable better model training
   1. Creating feedback loops that can use the combination of unstructured transcriptions and structured data models related to 1) events, (anonymized) user interactions, and output of the model, 2) actions of law enforcement agencies on the incident, and 3) final outcome of the incident as input data to keep the core gen AI model for Fraud Analysis always up to date with mutating fraud patterns and, therefore, always future relevant.
   1. Implementing the fraud incident reporting API in its entirety including the ability to integrate with 3rd party applications with representational schematics similar to what is expected at National Cyber Crime Reporting Bureau Portal. Explore possibility of testing integration with a test portal.
   1. Better and more universal User interface including mobile application to provide a product-level user experience that goes beyond the current prototype
   1. Integration with Call and text recording features on Android / IOS to provide a seamless end-to-end user experience to the general user.
   1. Supporting streaming record processing (ex. for ongoing call streams) and ability to build alerting mechanisms through EDA (Event-driven Architecture) that can set off alarms even during the middle of calls to alert users of potential fraud attempts, and provide reasons for the same in the preferred (or most used) language of the user. 
   1. Further development of the ArthaRaksha prototype to enhance its accuracy and capabilities.
   1. Building a more responsive model that can process parts of the analysis requirement at edge (mo mobile’s hardware) that can help reduce latency in responding to users and artistic ways to keep users engaged.
   1. Incorporating feedback from real-world users and parties involved in the ecosystem.
   1. Compliance and Auditing - building effective mechanisms to build data and model security, explainability, transparency, and auditable compliance embedded within the ArthaRaksha framework.
   1. Building in measurement metrics that can be directly correlated to desirable outcomes and trends related to fraud prevention, early detection, control, responsiveness, and incident closures.  

1. **Seeking partnerships and sponsors:** 
   1. Exploring partnerships with banks and financial institutions to get their buy-in and investments in future implementation and integration of vanilla ArthaRaksha model into their existing or upcoming fraud detection and prevention systems. This would allow for wider adoption and a more proactive approach to fraud detection and mitigation.
   1. Making representation and seeking opportunities to collaborate with government agencies and regulatory bodies, such as the Reserve Bank of India (RBI) and the Indian Cyber Crime Coordination Centre, to develop a more comprehensive and collaborative framework for combating financial fraud. This could involve sharing data for fraud research, best practices, and shared resources to create a more robust and effective ecosystem for fraud prevention and control.
   1. Exploring partnership with Google for next steps.
   1. Exploring opportunities to adapt ArthaRaksha beyond India to other countries and financial institutions facing similar challenges with financial fraud and those who are at the inflection point in digital transformation of their financial sectors. This would require tailoring the solution to local languages and aligning to respective regulatory environments.

1. **Continuous research and development** to stay ahead of evolving fraud tactics and technologies and contribute to Google’ Vertex AI Agent Builder platform evolution roadmap through the developer experience obtained through the next stages of the product development life-cycle. This includes exploring new AI models and systems, product offerings, data sources, and methodologies to ensure the effectiveness and sustainability of the idea of ArthaRaksha in the future.

We were able to successfully demonstrate an effective application of generative AI Models powered by Google Cloud platform that can have a significant and sustainable social and financial impact on the rapidly expanding digital transformation in India especially in the financial sector. If the model works in India, it might become a reference implementation for other regions to follow. 

ArthaRaksha is not about building a mobile application only. It is meant to be a working model ecosystem to fuel a fraud protection revolution in which multiple legitimate and genuine players across government, regulatory bodies, financial companies, telecom companies, tech companies, and law enforcement agencies can come together with their respective complementary specializations around data, models, customer records, fraud records, and response mechanisms (such as blocking fraud account/contact numbers) to co-create a safe, highly agile, always updated, and universally adopted system that can protect citizens from excruciating financial losses and reduce the burden of investigations by enforcement agencies by reducing the count and impact of scamming attempts in the future. ArthaRaksha, aspirationally, is meant to be the UPI equivalent model of fraud protection.
## <a name="_vzxrgm14azlq"></a>**Conclusion**
This project started with a mere brainstorming idea but has resulted in both personal and professional gratification. Inspired by real-life incidents, some personal in nature, we were motivated to contribute to a cause that could potentially protect others from falling victim to fraud and create an impact on the society and economy as a whole by increasing deterrence levels and reducing marginal gains of scammers who might eventually realize that the scamming attempts are no longer bearing expected results. We were motivated to explore the latest Google Cloud Vertex AI capabilities and the Gemini models to test their prowess in real-world scenarios and were mightily impressed by its capabilities while realizing that the platform is still at its embryonic stage and there are big opportunities to develop it further through continuous feedback cycles. 

Finally, we were able to bring to life a prototype application that could talk simply the language of the user and come to the rescue of a layman while leveraging some of the latest and most powerful technologies invisibly working in the backend. Through this project, we could hone our technical skills and we are certain that this experience would be very useful to us in the next such initiatives in the future.

## <a name="_h1x2i0jbg1em"></a>**Created by**

**1) Subhayu Mukherjee** <br>
**2) Priyanka**

