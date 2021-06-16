# PracticesForSecureSoftware

# Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
This client is a financial consulting firm that creates individualized financial portfolios for its customers.  They wanted to updgrade their current systems to a secure web interface that will handle online transactions.  Specifically, they want to add a checksum for data verification and ensure that their website uses the https protocol.

# What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I think my code accurately shows the implementation of a checksum verification on a string of data.  I implemented the SHA-256 algorithm by creating an instance of the MessageDigest class and then converted that hash to a hex string for demonstration purposes.  This shows that the data was successfully encrypted and that this encryption can be used for any data passed to the application.  This adds value to the company's overall wellbeing by allowing them to assure their clients that any transactions through this webb application will be secure.

# What about the process of working through the vulnerability assessment did you find challenging or helpful?
The most challenging and helpful part of working through the vulnerability assessment was just assuring that the code I added didn't introduce any new vulnerabilities to the application.  I wanted to check that all of the dependencies and vulnerabilities identified were exisiting and that I didn't creat any new vulnerabilities.

# How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
I looked through the code systematically by manual review to determine what additional security was needed.  I will definitely use checksums and certificate authorities for future projects to add layers of security to web applications.  I will also ensure that my code is free of errors and of the highest possible quality.

# How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
After executing my refactored code, I was able to see that it executed without errors and used the https protocol when I loaded the application on the localhost port.  I could see the checksum that I generated loaded on the secure port.  After demonstrating that my code worked, I installed the Maven dependency check and ran the dependency check report to check that I didn't introduce any new vulnerabilites to the existing code.

# What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
I think that implementing a checksum, setting up the https protocol, and running the Maven dependency check will all be useful for future projects.  These tools used together will ensure a highly secure web application.

# Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
I think my best piece of work to showcase in this assignment was the implementation of the checksum.  This implementation can serve as a template and reference for future projects and will be useful as a tool in my toolbox.
