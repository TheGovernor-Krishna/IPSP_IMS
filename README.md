Inventory Management System for Small Business 
[Project Record Format IPSP.docx](https://github.com/user-attachments/files/23729930/Project.Record.Format.IPSP.docx)


 

Project Record
CSE1021 Introduction to Problem Solving and Programming

A14+D11+D12, BL2025260100809
Fall Semester:2024-2025

Name of the student: Tejas Nilesh Dusane
Register Number: 25BCE11315 
B.Tech Computer Science and Engineering
Programme Output (POs):
1.	Engineering knowledge: Apply the knowledge of mathematics, science, engineering fundamentals, and an engineering specialization to the solution of complex engineering problems.
2.	Problem analysis: Identify, formulate, review research literature, and analyze complex engineering problems reaching substantiated conclusions using first principles of mathematics, natural sciences, and engineering sciences.
3.	Design/development of solutions: Design solutions for complex engineering problems and design system components or processes that meet the specified needs with appropriate consideration for the public health and safety, and the cultural, societal, and environmental considerations.
4.	Conduct investigations of complex problems: Use research-based knowledge and research methods including design of experiments, analysis and interpretation of data, and synthesis of the information to provide valid conclusions.
5.	Modern tool usage: Create, select, and apply appropriate techniques, resources, and modern engineering and IT tools including prediction and modeling to complex engineering activities with an understanding of the limitations.
6.	The engineer and society: Apply reasoning informed by the contextual knowledge to assess societal, health, safety, legal and cultural issues and the consequent responsibilities relevant to the professional engineering practice.
7.	Environment and sustainability: Understand the impact of the professional engineering solutions in societal and environmental contexts, and demonstrate the knowledge of, and need for sustainable development.
8.	Ethics: Apply ethical principles and commit to professional ethics and responsibilities and norms of the engineering practice.
9.	Individual and teamwork: Function effectively as an individual, and as a member or leader in diverse teams, and in multidisciplinary settings.
10.	Communication: Communicate effectively on complex engineering activities with the engineering community and with society at large, such as, being able to comprehend and write effective reports and design documentation, make effective presentations, and give and receive clear instructions.
11.	Project management and finance: Demonstrate knowledge and understanding of the engineering and management principles and apply these to one’s own 

Identify a real-world problem or need:
“Inventory Management System for Small Business”

1.	An Inventory Management System (IMS) is a software tool that helps small businesses track goods across the entire supply chain—from purchasing raw materials to selling finished products. It replaces spreadsheets and manual counting with automated, real-time tracking
2.	Why Small Businesses Need It (Benefits)
•	Cash Flow Optimization: Prevents "dead stock" (money tied up in unsold goods) and overstocking.
•	Time Savings: Automates manual tasks like reordering and stock counting.
•	Customer Satisfaction: Ensures popular items are always in stock and orders are fulfilled accurately.
•	Theft & Loss Reduction: Makes it easier to spot discrepancies between physical stock and recorded numbers.
“Apply concepts learned in the course to design the solution.”

1.	Have successfully translated the theoretical concepts of an Inventory Management System into working Python code.
2.	It is clear you have applied Object-Oriented Programming (OOP) by creating a class, used Control Structures (loops/if-statements) for logic, and implemented Security (password protection).









“Top-Down Design / Modularization”


We break the system into logical modules to keep the code clean.
•	Module A: Database Connection Layer
o	Handles connecting to inventory.db.
o	Creates the table if it doesn't exist.
•	Module B: Business Logic Layer
o	Functions: add_item, update_stock, delete_item.
o	Contains the rules (e.g., "Stock cannot be negative").
•	Module C: Presentation Layer (UI)
o	The main loop that accepts user input and prints results.

“Problem Definition”
The Problem: A small business currently tracks inventory using manual methods (paper/memory) or non-persistent methods (the previous Python list code).
•	Issue 1: Data is lost when the computer/program turns off.
•	Issue 2: No validation prevents duplicate Product IDs.
•	Issue 3: Search operations are slow on large datasets.
The Solution: Develop a Python-based IMS using SQLite. SQLite is the appropriate tool here because it is serverless, lightweight, and built into Python, making it perfect for small business applications without complex setup.
