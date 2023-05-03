# This is a part of GIT homework - TXT
## 1. Create an external repository called "txt": 
```
GitHub > New repository > Create repository 
```
***
## 2. Clone the TXT repository to a local machine: 
```
$ git clone HTTPS
```
***
## 3. Inside the local TXT create a “new.txt” file: 
```
$ cd TXT
$ touch new.txt
```
***
## 4. Add changes to indexed files section: 
```
$ git add touch new.txt
```
***
## 5. Commit the file: 
```
$ git commit -m "First commit"
```
***
## 6. Push the file to the external GitHub repository: 
```
$ git push
```
***
## 7. Edit the content of the file “new.txt” - write information about yourself. Everything is written in txt format:
```
$ vim new.txt
press i
name: Olga
surname: Rozina
age: 24 
hobby: hiling 
country: Lithuania 
city: Vilnius 
press Esc > :wq
```
***
## 8. Push changes the an external repository
```
$ git add .
$ git commit -m "TXT"
$ git push
```
***
## 9. Create a file "preferences.txt"
## 10. In the file "preferences.txt", add information about your preferences in txt format:
```
$ cat > preferences.txt
eat: pizza 
film: Interstellar 
series: Force_majeure 
time_of_year: summer
```
***
## 11. Create a file "skills.txt" and add information about the skills that will be studied in the course in txt format:
```
$ cat > skills.txt
GIT: a version control system used for software development to track changes in code over time and collaborate with other developers.
SQL: a programming language used for managing and manipulating data in relational databases.
Postman: a popular tool for testing and debugging APIs.
Fiddler: a web debugging proxy tool used to capture and analyze HTTP/HTTPS traffic between a computer and the internet.
Android Studio: an integrated development environment (IDE) for developing Android mobile applications.
Charles: a web proxy tool used to monitor and debug web traffic.
HTTP: a protocol used for communication between web servers and clients, such as web browsers or mobile apps.
JSON: a lightweight data interchange format used for storing and exchanging data between a server and a client.
XML: a markup language used for describing data and enabling communication between different systems.
```
***
## 12. Send two files at once to the external repository:
```
$ git add .
$ git commit preferences.txt skills.txt -m "First commit"
$ git push
```
***
## 13. On the web interface, modify the file "bug_report.txt" and add a bug report in txt format:
```
ID: 1
Environment: OS = Win_10, Browser = Chrome_112
Summary: 404 error when user is accessing the purchase order report page as a sales manager
Actual result: The report isn't shown as per the criteria selected
Expected result: The report should show as per the criteria selected
Steps to reproduce:
Login as Sales Manager
Go to the Reports page and choose Purchase Order Report
Select any filter criteria
Click the Show Report button
Severity: Medium
Priority: Normal
Reproducibility: Always
Symptom: Missing_feature
Workaround: No
Attachment: Link
Status: Open
Author: Olga_Rozina
Sign to: Olga_Fefilova
```
***
## 14. Press "Commit changes" and save changes on the web interface:
```
ID: 1
Environment: OS = Win_10, Browser = Chrome_112
Summary: 404 error when user is accessing the purchase order report page as a sales manager
Actual result: The report isn't shown as per the criteria selected
Expected result: The report should show as per the criteria selected
Steps to reproduce:
Login as Sales Manager
Go to the Reports page and choose Purchase Order Report
Select any filter criteria
Click the Show Report button
Severity: Medium
Priority: Normal
Reproducibility: Always
Symptom: Missing_feature
Workaround: No
Attachment: Link
Status: Open
Author: Olga_Rozina
Sign to: Olga_Fefilova
```
***
## 15. Press "Commit changes" and save changes on the web interface:
```
>Commit changes
```
***
## 16. Synchronize the external and the local TXT repository:
```
$ git pull
```
***
