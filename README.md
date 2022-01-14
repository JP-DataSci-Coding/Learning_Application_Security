# Learning_Application_Security


## Table of Contents

1. [OWASP Top 10](#owasp-top-10)

### OWASP Top 10

Open Web Application Security Project (OWASP) is an international non-profit organisation dedicated to web application security. One of OWASP’s core principles is that all of their materials be freely available and easily accessible on their website, making it possible for anyone to improve their own web application security. The materials they offer include documentation, tools, videos, and forums.

#### 1. Injection

Injection attacks occur when untrusted data is sent to a code interpreter as a form of command, query or some other data submission to a web application. For example, an attacker could enter SQL database code into a form that expects a plaintext username. If that form input is not properly secured, this would result in that SQL code being executed. This is known as an **SQL injection** attack.

Injection attacks can be prevented by validating and/or sanitising user-submitted data. **Validation** means rejecting suspicious-looking data, while **sanitisation** refers to cleaning up the suspicious-looking parts of the data. In addition, a database admin can set controls to minimise the amount of information an injection attack can expose.





