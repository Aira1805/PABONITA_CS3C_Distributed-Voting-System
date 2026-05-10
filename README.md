# PABONITA_CS3C_Distributed-Voting-System

224 RECORDS:
<img width="1456" height="647" alt="Screenshot 2026-05-10 162341" src="https://github.com/user-attachments/assets/d20ab8b7-ce42-4a0b-b5f2-dcbc150aea7b" />

<img width="1466" height="643" alt="Screenshot 2026-05-10 162322" src="https://github.com/user-attachments/assets/5048c92a-4d66-4718-9fb9-fae1f338da7f" />


DIAGRAM:
<img width="499" height="584" alt="Screenshot 2026-05-10 164555" src="https://github.com/user-attachments/assets/8aadf15f-dbe7-44b2-97b5-e391f6f8b91c" />


CODE:
<img width="1757" height="957" alt="Screenshot 2026-05-10 163528" src="https://github.com/user-attachments/assets/09029c43-7b08-4513-84c1-690d686ef7fa" />


REFLECTION

In this Distributed Voting System activity, I worked on building a simple program that sends vote data to Supabase using Python in VS Code. The script creates random votes and sends them through an API into a database table.

At the beginning, the system was not working and I kept receiving 401 errors. I later learned that Supabase was blocking my requests because Row Level Security (RLS) was not properly configured. After creating the correct policy and fixing the setup, the system started working and returned 201 status codes, meaning the data was successfully inserted.

There were also mistakes along the way, such as trying to run Python code inside the Supabase SQL editor, which caused syntax errors. I learned that SQL is only for database queries, while Python code should be executed in VS Code or a terminal.

This activity helped me understand how a client application communicates with a cloud database using APIs. It also showed me how important correct configuration is, especially with authentication and security rules.

Overall, even though the process was confusing at first, I was able to fix the errors step by step. I learned how to debug problems, connect different tools, and understand the basic flow of a distributed system.
