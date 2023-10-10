# CS_230_Software_Security
Portfolio Artifact from CS 230 Class

<b>Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?</b> <br>
Artemis Financialis a fictional consulting company that develops individualized financial plans for their customers. The financial plans include savings, retirement, investments, and insurance. Artemis Financial required an external consultant to assess their security vulnerabilities and recommend fixes. This helps Artemis Financial to stay in alignment with the requirements of regulatory bodies. Due to the sensitivity of data the company handles, it is paramount that their security is modern to prevent breaches.

<b>What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?</b><br>
Vulnerabilities were found in the client's software via input injections, outdated software packages, potential future updates, and a lack of SHA encryption of inputs. Not only were the issues found, they were thoroughly documented with recommended next steps. Software security adds significant value to a companies well-being, breaches of customer data undermine trust and value of company. Sometimes a company never regains that trust. 

<b>What part of the vulnerability assessment was challenging or helpful to you?</b><br>
Investigating the benefits of using static testing was very helpful. What was challenging was determining what results were positives or false positives. It requries extensive knowledge of the tech stack to know what to ignore and what to dive deeper into. 

<b>How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?</b><br>
Layers of security were increased by adding SHA-256 encryption, Certificate Authentication was done, in addition I securely re-routed HTTP port traffic to HTTPS ports. In the future I want to continue to use static testing and assessing vulnerabilities that exist with any outwards-facing input vectors.

<b>How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?</b><br>
Functionality was determined by extensive testing. Each update was deployed and verified. Additionally, static testing was re-done after refactoring of the code. New vulnerabilities were noted and assessed for long-term impact. 

<b>What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?</b><br>
I found static testing extremely beneficial. The exploration of Symmetric and Asymmetric hashing algorithms was fascinating as well. In my future endeavors I'd like to apply these concepts in live development environments and automate a lot of this testing. It only serves to benefit the code-base if much of this error detection is automated so that developers can effectively spend their time on potential vulnerabilities.

<b>Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?</b><br>
I would show employers the vulnerability assessment and the refactored code. While it is not a fully functional program, it does show intiative to dive deep into new concepts and embrace new ways of assessing software. I demonstrated the ability to communicate complex concepts to a non-technical audience, which is a valuable skill.
