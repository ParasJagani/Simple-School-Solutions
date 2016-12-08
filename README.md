# Simple-School-Solutions.
 Module 1 - Student data management.
 
1.I have used stored procedures for Adding, Editing and Deleting data from student table.
2.STUDENT_BKP and STUDENT_HIST are exact replica of STUDENT table with no data at first.
  a)Whenever  Data is  added using ADD button , it automatically populates the same in STUDENT_BKP table using trigger.
  b) Similarly on DELETE, it should be moved to the the STUDENT_HIST. Also DELETE is not allowed on weekends.
3.In EDIT section only valid update from class N to Class N+1 is allowed.
4.Whenever a new student is added, an automatic insert goes in the student fees table with fees_paid as 0 and total and balance fees same as the course fees.


module 2- Exam and Result Management.
1.It generates a report that have students mark sheet.
2. Mark sheet has subject marks, total marks, percentage and rank(subject & division wise)
3.It generates a report that displays top 3 students for each standard and division.



 I have created Error log and Audit log for both the modules.
