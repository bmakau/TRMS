# Tuition Reimbursement Management System(TRMS).
TRMS is system that enable employees to submit their expenses for tuition. Reimbursement is made for various 
courses such as University courses, certification,seminars,certification preparation classes, technical training.
Each employee is allowed to claim up to 1000 per year. Amount is reset every year. Courses are reimbursed in different rates.
University course 80%, seminars 60%, certification prep classes 75%, certification 100%, Technical training 90% and others 30%.
Benco approval is final and after approval the employee has to present a passing grade to be approved for the reimbursement.
AvailableReimbursement = total(1000) - pendingReimbursement - awardedReimbursement. If reimbursement is greater than availableReimbursement 
the amount is adjusted.

employees are supposed to submit reimbursement one week before start of an event. The form collects basic employee information. 
Employees must provide a passing grade for the reimbursement and course should marked urgent if it is less than two weeks to start

supervisor can request additional information from the employee for approval. if supervisor doe not approve the reimbursent in timely manner 
it is auto approved. If supervisor is department head head dept approval is skipped.

Head of department can request extra info from the supervisor or employee before approving. If department head does not approve
in a timely manner it is auto approved.

Benco it is not skippable and can request info from employee, supervisor, and head dept. Also has ability to alter reimbursement amount.

if benco changes the amount emmployee should be notified to either reject or accept the reimbursement.
if benco doent approve it in timely manner escalation email should be sent to the direct supervisor.
if benco provide more money than allocated for the employee should provide a reason and should be marked as exceeding the allocated amount.

employee should send passing grade to be awarded.

