# Healthway-Hospital
In this project designed and implementation of a database for Healthway Hospital.
# Problem description:
Data Base Description:  You have been asked to design a database for Healthway Hospital. Healthway depends on a large number of persons for its continued success. There are four groups of people on whom the hospital is most dependent: employees, physicians, patients, and volunteers. Of course, some common attributes are shared by all of these persons: Person_ID (identifier), Name, Birth_Date, and Address (City/ Zip code/ Phone). Each of the four groups has at least one unique attribute of its own. Employees have a Date_Hired, volunteers have a skill, physicians have a specialty and mobile number, and patients have a contact_date. Additional personnel in the hospital community do not belong to one of these four groups (their numbers are relatively small). However, a particular person may belong to two (or more) of these groups at any given time (for example, Patient and Volunteer). Each patient has one (and only one) physician responsible for that patient. A given physician may not be responsible for a patient at a given time or may be responsible for one or more patients. Patients are divided into two groups: resident and outpatient. Each resident has a date_admitted attribute. Each outpatient is scheduled for zero or more visits. The entity visit has two attributes: date (partial identifier) and comments. Notice that an instance of the visit cannot exist without an outpatient owner entity. Employees are subdivided into three groups: nurses, staff, and technicians. Only nurses have the attribute certificate, which indicates the qualification. Only staff has the attribute job_class, and only technicians have the attribute skill. Each nurse is assigned to one (and only one) care center. Examples of care centers are Maternity, Emergency, and Cardiology. Attributes of the care center are Name (identifier) and Location. A care center may have one or more nurses assigned to it. Also, one of the nurses assigned to that care center is appointed nurse_in_charge for each care center. A nurse cannot be appointed nurse_in_charge of a care center unless they have an RN certificate. Each technician is assigned to one or more laboratories. Attributes of the laboratory include Name (identifier) and Location. A laboratory must have at least one technician assigned and may have any number of technicians assigned. There may be no beds assigned to a care center,  or a care center may have one or more beds (up to any number) assigned to it. The only attribute of the bed is Bed_Id (identifier). Bed_Id is a composite attribute, with components Bed number and Room number. Each resident patient must be assigned to a bed. A bed may or may not have a resident patient assigned to it at a given time.
# Enhanced entity-relationship (EER):
EER diagrams are basically a more expansive version of ER diagrams. EER models are helpful tools for designing databases with high-level models. With their enhanced features, you can plan databases more thoroughly by delving into the properties and constraints with greater precision.
For more details about ERR and ER visit this site : https://cacoo.com/blog/er-diagrams-vs-eer-diagrams-whats-the-difference/
# EER diagram :
In the **EER diagram file**, there is an explanation of  the relationships between entities In Healthway Hospital.
 # Relational Database Design :
 Is a set of table definitions (stored base tables or derived views), constraints, and derivation rules. A table scheme is a named set of attributes (columns) that draw their values from domains. Each column, or column set, spanned by a minimal uniqueness constraint is a candidate key.
 For more details about Relational Database Design visit this paper :http://www.cs.kent.edu/~vlee/classes/cs43005_F2007/Lecture/ch7_part1_4up.pdf 
 # Relational database schema : 
In the **Relational database schema file**, there is an explanation of  the relationships between entities In Healthway Hospital.
In the Relational database schema file, there is an explanation of table definitions, constraints, and derivation rulesIn Healthway Hospital.
# Implementation (DDL, and DML) statements :
SQL statements are divided into two major categories: data definition language (DDL) and data manipulation language (DML).
For more details about DDL and DML  and visit this site : https://www.geeksforgeeks.org/sql-ddl-dql-dml-dcl-tcl-commands/
In the **Implementation  code of Healthway Hospital file**, there is an Implementation  code of Healthway Hospital.


# recommendation
To understand databases and how to deal with them and what are the concepts that I touched on above, I recommend this channel of  Mohamed Desouki to visit  this site : https://youtube.com/playlist?list=PL37D52B7714788190


