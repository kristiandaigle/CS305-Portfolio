# CS305-Portfolio

•	Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a financial consulting company developing plans for savings, retirement, etc.  They wanted to add file verification to their web application and ensure secure communications.  The problem to be solved is to add these steps to secure the information used.  
•	What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
It’s important to code securely to keep the information being transferred safe.  In the case of this client, there is a lot of sensitive data that goes along with the financial industry.  Personal information, as well as access to people’s funds.  Security adds to the reputation of Artemis Financial.  I think I did well when questioning whether what I was doing was correct.  My checksum was strange in the homework assignments, but I spent more time on the one for project 2.  
•	What about the process of working through the vulnerability assessment did you find challenging or helpful?
I found the process of using the keytool to generate a self-signed certificate difficult at first.  However, most of my issues were formatting/how I formed the request.  I also found that I had to generate a new keystore.  But working through the challenges I had was really helpful in how I look at security.
•	How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
I added security by refactoring the code to use HTTPS which is more secure than HTTP.  My screenshot however didn’t look like it did because my certificate wasn’t trusted by my computer.
•	How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

I ensured that the code was functional by checking runnability frequently, and running a dependency check before and after refactoring.
•	What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
Maven was a really useful tool to find vulnerabilities.  I think I would use them again.
•	Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
I would want to showcase working with vulnerabilities, and creating the secure HTTPS connections.  

