# Steps to run the program

1. Install **Java** and **Oracle** (preferably oracle 10g).

2. Change your oracle environment details on line 1665 in [Application](./Application.java).

3. Set temporary or permanent classpath to the ojdbc14.jar file.

4. Restart the listener if program doesn't run.

5. Compile: ````javac Application.java````

6. Run: ````java Application````

# user id and password details
These can be changed according to the Institutional rules.

|SERIAL_NO | DEPARTMENT_NAME                                  |  USER_ID                     |  PASSWORD                    |                       
|----------|--------------------------------------------------|------------------------------|------------------------------|           
|         1|HOD (Chemical Engineering)                        | chemhod                      | chemhodigit                  |                            
|         2|HOD (Civil Engineering)                           | civilhod                     | civilhodigit                 |                         
|         3|HOD (Electrical Engineering)                      | electhod                     | electhodigit                 |                          
|         4|HOD (Electronics and TC Engineering)              | etchod                       | etchodigit                   |                          
|         5|HOD (Mechanical Engineering)                      | mechhod                      | mechhodigit                  |       
|         6|HOD (Metallurgy and Materials Engineering)        | meta                         | metaigit                     |     
|         7|HOD (Computer Science and Applications)           | cseahod                      | cseahodigit                  |           
|         8|HOD (Architecture)                                | archhod                      | archhodigit                  |   
|         9|Physics                                           | phy                          | phyigit                      |
|        10|Chemistry                                         | chem                         | chemigit                     |
|        11|English                                           | eng                          | engigit                      |
|        12|Mathematics                                       | maths                        | mathsigit                    |
|        13|Workshop                                          | ws                           | wsigit                       |
|        14|Officer-in-charge, Library                        | lib                          | libigit                      |
|        15|V.P., Cutural Association                         | cult                         | cultigit                     |
|        16|V.P., Audio Visual Club                           | avclub                       | avclubigit                   |
|        17|V.P., Athletics                                   | athl                         | athligit                     |
|        18|Academic Section                                  | acad                         | acadigit                     |
|        19|Examination Section                               | exam                         | examigit                     |
|        20|Accounts Section                                  | acc                          | accigit                      |
|        21|Officer-in-charge, Book Bank                      | bb                           | bbigit                       |
|        22|Hostel Superintendent                             | hostel                       | hosteligit                   |
|        23|Programme Officer, NCC                            | ncc                          | nccigit                      |
|        24|Programme Officer, NSS                            | nss                          | nssigit                      |
|        25|End                                               | end                          | endigit                      |

# Sample output:
1. Login page:
![hostelloginhome](https://github.com/prateekshyap/Student-Management-System/blob/main/img/hostelloginhome.png)

2. For all the sections in the login table apart from the section named "End" will get access to only two sections as follows. Below is a sample for "Hostel" section.
![hosteloptions](https://github.com/prateekshyap/Student-Management-System/blob/main/img/hosteloptions.png)

3. Sample for the "End" section:
![endoptions](https://github.com/prateekshyap/Student-Management-System/blob/main/img/endoptions.png)
Only "End" section gets the options to print the Transfer Certificate and Conduct Certificate. All other sections can only give clearance to the students.

4. Sample Data Entry page:
![dataentry](https://github.com/prateekshyap/Student-Management-System/blob/main/img/dataentry.png)

5. Sample clearance page for "Hostel" section:
![hostelclearance](https://github.com/prateekshyap/Student-Management-System/blob/main/img/hostelclearance.png)

6. Sample print page:
![printsection](https://github.com/prateekshyap/Student-Management-System/blob/main/img/printsection.png)

# Found improvements?

Fork the repository and create a pull request.
