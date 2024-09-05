# **Web Vulnerability Scanner**

This project involves developing a web vulnerability scanner that detects common web security issues such as SQL Injection, Cross-Site Scripting (XSS), and Cross-Site Request Forgery (CSRF) vulnerabilities. The scanner also retrieves CVSS (Common Vulnerability Scoring System) scores for known vulnerabilities to assess their severity.

## **Features:**

- **Web Application Risk Assessment:** a security analyst, I want to identify common vulnerabilities in web applications to assess their risk.
- **Web Application Vulnerability Check:** As an IT manager, I want to understand the severity of detected vulnerabilities through CVSS scores.
- **Web Application Security Check:** as a developer, I want to ensure that the web application is free of common vulnerabilities.
- **Detailed Scan Results:** Presents detailed information about the scan results.

## **Technologies Used:**

- **Python:** Programming language for developing the scanner
- **Web Application for Testing:** A sample web application or test URL.
Kali Linux Virtual machine
- **Libraries and Tools:** requests, BeautifulSoup, urllib3

## **Prerequisites:**

- Python 3.x 
- Kali VM

## **Usage:**

**Save the Python Script:**

> - Navigate to the Kali Linux VM terminal and paste the script on the terminal then save the script by running nano script_name.py.

**Initiate a Web Vulnerability Scan:**

> - For demostration running the command `python3 web_vul.py http://testphp.vulnweb.com` on a Kali VM terminal would likely initiate a web vulnerability scan on the specified URL http://testphp.vulnweb.com. This scan aims to identify potential security weaknesses, such as SQL injection, cross-site scripting (XSS), and other common vulnerabilities.

## **Test Cases**

- **Test SQL Injection Detection:**
python3 web_vul.py http://testphp.vulnweb.com

![image](https://github.com/user-attachments/assets/d6c248de-0550-4091-a705-07133ce0075c)
 
- **Test XSS Detection:**
python3 web_vul.py http://testphp.vulnweb.com

 ![image](https://github.com/user-attachments/assets/40c0e181-e207-49b9-9edc-47b75c182201)

- **Test CSRF Detection:**
python3 web_vul.py http://testphp.vulnweb.com

 ![image](https://github.com/user-attachments/assets/2c7ba963-efd7-4121-b5a0-b5966b640b26)


- **Test CVSS Score Retrieval:**
python3 web_vul.py http://testphp.vulnweb.com

![image](https://github.com/user-attachments/assets/03157009-0d0d-433f-a0b8-574d9116d443)

**View Scan Results:**

> - **SQL Injection Detection:** Successfully identified SQL Injection vulnerabilities and displayed relevant information.
> - **XSS Detection:** Successfully detected XSS vulnerabilities and displayed relevant information.
> - **CSRF Detection:** Successfully identified CSRF vulnerabilities and provided details.
> - **CVSS Score Retrieval:** Accurately retrieved and displayed CVSS scores for known vulnerabilities.

## **Test Plan:**

- **Unit Testing:** Test each vulnerability detection method (SQL Injection, XSS, CSRF).
- **Integration Testing:** Test the overall scanner with a known vulnerable web application.
- **User Acceptance Testing:** Verify that the CVSS scores are accurately retrieved and reported.


## **Contributing:**

Contributions are welcome! If you have suggestions or improvements, please submit a pull request or open an issue.

## **Black Innovations Information Technologies:**

**Black Innovations Information Technologies EST** is a premier IT solutions provider dedicated to empowering businesses of all sizes with cutting-edge technology. Our team of highly skilled professionals is committed to delivering innovative and reliable IT services that enhance productivity, efficiency, and sustainable growth. Explore our repositories to discover how we leverage technology to solve real-world challenges and drive success for our clients.

## **Contact**
For any questions or feedback, please contact:

- https://www.linkedin.com/company/black-innovations/mycompany/
- https://www.linkedin.com/in/renuka-telu
- https://www.linkedin.com/in/paul-nwanochiri

