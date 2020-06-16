# llSPS-INT-1819-Intelligent-Customer-Help-Desk-with-Smart-Document-Understanding
<h1>Intelligent Customer Help Desk with Smart Document Understanding<h1>
<h1>1.	Introduction: </h1>
 
 <h3>1.1 Overview</h3> <br>
  The project is titled as "Intelligent Customer Help Desk with Smart Document Understanding". Here a chatbot is created which unlike other chatbots which answers simple questions and if the particular question is out of the scope then the chatbot typically replies in a manner stating that the question is invalid, intends to answer operational questions by using IBM Watson Discovery service and redirect the customer to the owner's manual that is uploaded in the Watson Discovery sevice.This chatbot leads the customer to the desired section in the owner's manual where the solution for the problem exists instead of redirecting to a customer service.
	
 <h3>1.1 Purpose </h3><br>
	The purpose of the project is to save up on the time and money of the owner or manager of the chatbot by reducing the need to connect to a customer care service person by including Smart document Understanding in the chatbot which answers to most of the operational doubts from the organisation's manual thus saving up on time and increasing the efficiency.
<h2>2. LITERATURE SURVEY </h2><br>
<h3>2.1 Existing Problem </h3><br>
The typical customer care chatbot can answer simple questions, such as store locations and hours, directions, and maybe even making appointments. When a question falls outside of the scope of the pre-determined question set, the option is typically to tell the customer the question isn’t valid or offer to speak to a real person.

<br>

<h3>2.2 Proposed solution </h3><br>
In this project, there will be another option. If the customer question is about the operation of a device, the application shall pass the question onto Watson Discovery Service, which has been pre-loaded with the device’s owners manual. So now, instead of “Would you like to speak to a customer representative?” we can return relevant sections of the owners manual to help solve our customers’ problems.

 
<h2>4. EXPERIMENTAL INVESTIGATIONS</h2><br>
The experimental investigations to get the most appropriate results are as follows
•	Structuring the document/manual using discovery service of IBM. It includes omitting the unwanted text as footer and helping the service understand by laying out the title, subtitles, text, tables among others
•	Trying to parse the file using the webhook to give the most appropriate answer.
•	Modifying and checking which intent works best under which node of the dialog to give appropriate answer.
•	Modifying and checking the node red flow so that the text is fitted well in the ui
•	Modifying and changing the ui according to the need and layout
•	Trying to integrate it with several platforms.

<h2>RESULT:</h2><br>
As you can see in the pictures, the user starts off with a normal conversation, the intent of which is recognized by the ibm watson assistant and relevant answer is fetched from the dialog. 
In the second picture when the user asks any operational query(in my case query about the Admission in Army Institute of Technology) the bot would simply parse the document(AIT Admission Prospectus) using Watson Discovery and give back the section of the document as a reply to the user.

<h2>APPLICATIONS:</h2><br>
The application of this smart help desk is
1)	To answer operational queries
2)	To give real time answers which are usually answered by connecting to a customer care
3)	Helps in knowing the need of the users

<h2>CONCLUSION:</h2><br>
Thus, I have developed a chatbot using IBM Watson which uses the smart document understanding to fetch results from the Prospectus file of my college(AIT Pune) using Discovery service of IBM and gives returns with the section of the document containing the answer to the user’s query.

<h2>FUTURE SCOPE</h2><br>
The future scope of the project is:
It can be scaled to answer other operational doubts by the college students about the infrastructure, exam and form filling queries.

<h2>Video Demonstration:</h2><br>
https://youtu.be/-EKdtRuk8sk

<h2>Internship Feedback </h2><br>
https://youtu.be/SKyF332Oef4
