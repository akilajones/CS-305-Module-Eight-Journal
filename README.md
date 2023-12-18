Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial operates as a financial services firm specializing in offering financial planning and insurance solutions to its clientele. Their primary concern involved ensuring the safe storage of sensitive data and establishing secure communication channels for both uploading and downloading information.


What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I believe I successfully implemented the keystore.jks despite encountering unclear instructions at times. Managing to get the keystore operational. Prioritizing secure coding practices is crucial due to pervasive threats in the digital landscape where data theft is rampant. Some entities, including other companies, may attempt to illicitly access or pilfer sensitive information. Developing secure code serves as a robust defense against numerous threats. It plays a pivotal role in enhancing a company's overall well-being by fostering trust among stakeholders, bolstering reliability, and significantly reducing the likelihood of the company becoming headline news due to a major data breach—a sadly common occurrence nowadays.



What part of the vulnerability assessment was challenging or helpful to you?
The part that I found to be challenging was the scope definition, determining the extent and boundaries of the assessment was difficult. identifying the assets to be assessed required more planning and understanding than I anticipated.


How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I began by conducting dependency checks, followed by a thorough analysis of the source code to ensure its error-free status. Next, I proceeded with implementing TLS and encryption. In a real-world scenario, I would maintain a comparable process. However, I would aim to refine the list of false positives associated with the dependency checks, seeking a more precise compilation as some existing lists were lengthy and challenging to navigate.


How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
check to see whether you introduced new vulnerabilities?
To guarantee functionality, my initial step in Eclipse was to ensure a code error-free environment. Once I confirmed the absence of errors, I executed the service and accessed localhost to validate the accuracy of the output. Additionally, I verified the site's access via HTTPS using the self-signed certificate. Post-refactoring, I conducted another dependency check to identify any new vulnerabilities, cross-referencing the results with the previous assessment. Furthermore, I thoroughly reviewed my code to detect and resolve any potential errors.



What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Generating SSL certificates proved to be very beneficial. I intend to utilize this method consistently to test secure communications during website development. Additionally, I found the dependency check tool to be very useful in analyzing prevalent risks. I plan to incorporate this tool regularly to assess potential vulnerabilities in my work moving forward.



Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
To display my skills I will show a potential employer my second project. I will be able to show them my secure coding practices that will ultimately help to protect their applications. I will explain to them that during this process I had to not only identify but address security vulnerabilities, use secure libraries and Implement security controls. 
