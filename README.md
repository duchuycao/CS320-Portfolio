# CS320-Portfolio
# CS-320 Software Test, Automation, and Quality Assurance
# portfolio Submission – Module Eight Journal

#Submitted Artifacts
- Contact.java  
- ContactService.java  
- ContactTest.java  
- ContactServiceTest.java  
- CS320_Project_Two_Report.docx


#Reflection

**How can I ensure that my code, program, or software is functional and secure?**  
To ensure that my code is functional, I employ unit testing strategies using JUnit to verify that each method behaves correctly under expected and edge-case conditions. For example, in the ContactService project, I used `assertThrows` to test invalid input scenarios and ensure exceptions were handled. To promote security, I adopt defensive programming habits like validating all inputs, rejecting null values, and enforcing constraints (e.g., length limits, data format).

**How do I interpret user needs and incorporate them into a program?**  
I interpret user needs by analyzing software requirements and identifying how those translate into program behavior. In the Contact service, requirements like “each contact ID must be unique and non-editable” directly influenced my implementation logic and test conditions.

**How do I approach designing software?**  
My approach to software design begins with simplicity and modularity. I break down responsibilities into smaller, self-contained classes and methods. For example, I separated concerns across Contact, ContactService, and their respective test files. I also rely on iteration: I test early and often, refining the code and tests together.
