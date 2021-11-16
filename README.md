# SpartanDevs

Hi everyone!  We are the SpartanDevs team representing Maryknoll High School!  We are excited to present our submission for the Pono Points Game!  We enjoyed working on a solution that addresses ways to preserve our culture, environment, and promote awareness to our island visitors. 

We created a game that works like the “heads up game”, where groups can play together on various topics: Local Customs, Sensitive Hawaiian Environments, Leave No Trace Ethics, Safety, and Neighborhood Sensitivities. 

Each 5-question quiz is randomly generated from our question bank. Scores will depend on accuracy, correct answer streak, and time spent answering each question.

<b>Challenges<b>: Currently working on shifting our server to host our data from local to secured.

What we learned: Effective communication, delegating of tasks, and bringing all our pages together.

Proud of: First Maryknoll School coding club competition entry. Finding a group of coders on campus to build together.

TRY OUT OUR APP
https://learnandteachdev.github.io/SpartanDevs/

SECURITY/PRIVACY PROPOSAL
As of now our game is running off temporary python socket server and json database that we have built and is only programmed with GET and POST requests with no firewalls. Later we would like to implement a AWS secure server in order to increase functionality and decrease vulnerability. Concerning data stored on our database, there is the user’s username, password, and total points. We would also implement a way to verify that the total points are legitimate for vendors such using as randomly generated QR codes, bar codes, or access keys. Some examples of our games vulnerable in terms of our server is that an experienced programmer could easily intercept the GET request response on the frontend and steal information containing every users password and total points. 
