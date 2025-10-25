# CS 305 – Module Eight Portfolio Reflection

### Artifact: Artemis Financial Practices for Secure Software Report  

Artemis Financial is a company that provides financial services and needed to make sure their software followed strong security practices. The main goal of this project was to refactor their code and configure the application so that data could be transmitted securely using HTTPS encryption. I implemented a SHA-256 hashing algorithm, created a self-signed SSL certificate, and ran vulnerability scans to confirm that the software met modern security standards.

One thing I did well was setting up secure communications with HTTPS and verifying that the data being sent was encrypted. I also made sure the hashing algorithm worked correctly so data integrity could be checked. Coding securely is important because it protects sensitive information from being leaked or changed by attackers. Good software security not only builds customer trust but also helps prevent costly breaches and compliance issues.

The most challenging part of the project was generating and integrating the SSL certificate correctly. It took a few tries to get the keystore and application properties configured so that the server would run on port 8443 with HTTPS. That process helped me understand how encryption and certificates work behind the scenes. I also learned more about tools like Maven and the OWASP Dependency-Check plugin, which I used to test for vulnerabilities in project dependencies.

To increase layers of security, I applied strong encryption, used secure hashing, and confirmed that the app could only be accessed through HTTPS. After refactoring the code, I re-ran the dependency scan to make sure no new vulnerabilities were introduced. I also checked that the application still functioned correctly and didn’t break after adding new configurations.

The tools and practices I used like OWASP Dependency-Check, SSL certificate generation, and secure coding principles will definitely help me in future projects. They showed me how to identify risks early and fix them before deployment. If I were to show this project to a future employer, I’d highlight it as an example of my ability to build and secure web applications following real-world cybersecurity standards.

