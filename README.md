Banking Loan Origination System:

This is a practice project where I act as a Business Analyst for a bank that wants to move its personal loan process from paper to an online system.

Note: This is a dummy project made for learning. The bank, the data and the test results are not real.

Prepared by: Pathan Laiba Hafsa Maheen Khanam
Tools used: Jira, Microsoft Word, Microsoft Excel

The problem

The bank takes loan applications on paper. It takes many days, and documents can get lost or be filled in wrongly. The bank wants customers to apply, upload documents and track their loan online, and wants officers and managers to have one place to verify and decide.

What I did (step by step)
Step	What I made	Folder
1)	Studied how a bank gives a personal loan and drew the process flow	BRD (inside Section 5)
2) Wrote the Business Requirement Document (BRD v1.1)	BRD
3) Wrote 4 use cases, each with a normal path and a problem path	Use-Cases
4) Set up a Jira board with an epic, user stories and 2 sprints	Jira-Screenshots
5) Wrote 10 test cases and did a mock UAT	UAT
6) Built the Requirement Traceability Matrix (RTM)	RTM

   
Project at a glance

Users: Customer, Loan Officer, Manager and the System
Requirements: 19 in total (15 functional and 4 non-functional)
Use cases: 4


UC-01 Customer applies for a personal loan
UC-02 Loan officer verifies documents
UC-03 Manager approves or rejects a loan
UC-04 Loan amount is credited and EMI is collected


Jira: 1 epic, 14 user stories, 2 sprints
Mock UAT: 10 test cases, 8 passed, 2 failed, 2 defects logged
RTM: links every requirement to its use case, Jira story and test case


What the RTM found
13 of 19 requirements passed their tests and 3 failed.
3 requirements (security of stored data, page speed, browser support) had no test case yet, so they are marked "Not covered".
Some Jira story statuses did not match the test results, and the RTM marks them so they can be corrected.



What I learned
How to turn a business problem into clear, numbered requirements.
How to write use cases with a normal path and a problem path.
How to break requirements into Jira user stories with acceptance criteria.
How to write test cases and log defects.
How an RTM helps to see which requirements are built, tested or missed.

Limits of this project
It is a practice project with no real stakeholders, so sign-offs in the BRD are marked "Pending".
The UAT results are illustrative.

Only personal loans are in scope. Home loans, gold loans and a mobile app are out of scope for this version.
