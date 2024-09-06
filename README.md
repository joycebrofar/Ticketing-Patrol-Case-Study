# Ticketing Patrol Case Study
The purpose of the State Patrol ticket-processing system is to record moving violations, keep records of the
fines paid by drivers when they plead guilty or are found guilty of moving violations, and notify the court that
a warrant for arrest should be issued when such fines are not paid in a timely manner. A separate State
Patrol system records accidents and the verification of financial responsibility (insurance). But a third system
uses ticket and accident records to produce driving record reports for insurance companies. Finally, a fourth
system is obviously integrated, where they share access to the same database; otherwise, they are operated
separately by different departments of the State Patrol.


When an officer gives a ticket to the driver, a copy of the ticket is turned in and entered into the system. A
new ticket is turned, a record is created, and relationships to the correct driver, officer, and court are
established in the database. If the driver pleads guilty, he or she mails in the fine in a preprinted envelope
with the ticket number on it. In some cases, the driver claims innocence and wants a court date. When the
envelope is returned without a check, and the trial request box has an “X” in it, the system does the following:
notes the plea on the ticket record; looks up driver, ticket, and officer information; and sends a ticket details
report to the appropriate court. A trial date questionnaire form is also produced at the same time and is
mailed to the driver. The instructions on the questionnaire tell the driver to fill in convenient dates and mail
the questionnaire directly to the court. Upon receiving this information, the court schedules a trial date and
notifies the driver of the date and time.


When the trial is completed, the court sends the verdict to the ticketing system. The verdict and the trial date
are recorded for the ticket. If the verdict is innocent, the system that produces driving record reports for
insurance companies will ignore the ticket. If the verdict is guilty, the court gives the driver another envelope
with the ticket number on it for mailing in the fine.
If the driver fails to pay the fine within the required period, the ticket-processing system produces a warrant
request notice and sends it to the court. This happens if the driver does not return the original envelope
within two weeks, or does not return the court-supplied envelope within two weeks of the trial date. What
happens next is in the hands of the court. Sometimes, the court requests that the driver’s license be
suspended, and the system that processes driver’s licenses handles the suspension.


1. To what events must the ticket-processing system respond? List each event, the type of event, the
resulting use case, and the actor(s). Think carefully about who the actors are. Does the officer
directly enter the ticket into the system? Or does a state patrol clerk do it when the paper ticket is
received from the officer? The existing system uses paper forms, so assume that the state patrol
clerk enters all of the information. A new system would use the same use cases, but opportunities
for efficiency and accuracy would lead to changes in who the actors are.


2. Write a brief use case description for each use case.


3. Draw a use case diagram for the ticket-processing system assuming the actors are based on your
answer in question 1 (the existing system as described)
