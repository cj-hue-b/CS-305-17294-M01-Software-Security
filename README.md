# CS-305-17294-M01-Software-Security

Client Summary and Software Requirements
Artemis Financial is a financial planning company that provides customized services such as savings, retirement, investment, and insurance planning. The client wanted to modernize its RESTful web application and strengthen its security posture. Specifically, they needed help identifying vulnerabilities in their existing code base, improving secure communication, and ensuring that their software followed modern security best practices.

What I Did Well in Identifying Vulnerabilities
I was thorough and systematic during both the manual review and the static testing phases. I identified insecure dependencies, missing input validation, outdated libraries, and weak or missing cryptographic practices. I also documented each vulnerability clearly, including its location, impact, and recommended mitigation. This level of detail made the final mitigation plan more actionable.

Why Secure Coding Matters
Secure coding prevents attackers from exploiting weaknesses that could compromise sensitive financial data. For a company like Artemis Financial, software security protects client trust, reduces financial and legal risk, and ensures long‑term operational stability. Strong security practices also support compliance with industry regulations and help the company maintain a competitive edge.

Most Challenging or Helpful Parts of the Assessment
The most challenging part was interpreting the dependency‑check report and mapping each vulnerability to its real impact on the application. The most helpful part was the manual review, because it forced me to understand the code structure and think like an attacker. Combining both approaches gave me a more complete picture of the system’s weaknesses.

How I Increased Layers of Security
I added checksum verification, recommended stronger encryption algorithms, ensured secure communication through HTTPS, and updated vulnerable dependencies. I also applied secure coding principles such as input validation, proper exception handling, and avoiding hard‑coded secrets. In the future, I would continue using tools like OWASP Dependency‑Check, static analysis scanners, and threat‑modeling frameworks to evaluate risks and choose mitigation strategies.

Ensuring the Code Was Functional and Secure
After refactoring, I re‑ran the application to confirm it executed without errors. I also performed another dependency‑check scan to verify that no new vulnerabilities were introduced. Manual testing helped confirm that the checksum feature worked correctly and that the application still behaved as expected.

Resources, Tools, and Practices I Will Use Again
Tools such as Maven, OWASP Dependency‑Check, and secure coding checklists were especially valuable. Practices like validating inputs, updating dependencies regularly, and reviewing code for logic and security flaws will continue to be part of my workflow. These approaches are transferable to future projects and professional environments.


What I Could Show Future Employers
This assignment demonstrates my ability to:

Conduct a full vulnerability assessment

Use static analysis tools

Interpret and mitigate security risks

Refactor code to improve security

Document findings clearly and professionally

I could show employers my vulnerability assessment report, my mitigation plan, and the refactored code demonstrating secure communication and checksum verification. Together, these artifacts highlight my understanding of secure software development and my ability to apply security concepts in real projects.
