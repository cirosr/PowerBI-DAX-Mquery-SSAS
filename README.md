# powerbi
PowerBI Projects

Hi all, 

It is my personal take on AdventureWorksDW dataset. Link below:
https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms

Work-in-progress disclaimer including this document :)

Microsoft has a simpler set you can download as .pbix, the one I found in SQL Server sample had more tables so I went with it.

My hopes were to have plenty Procurement data but, nothing is perfect. :)

Index:

1. Report Content overview;
2. Assumptions and decisions;
3. DAX used;
4. M used;
5. Visuals and bookmarks;
6. 

1. My idea picking up this data was to showcase some of the work I do everyday for companies.
Common use cases:
As a future employee, I would like understand my future company's improvement opportunities so I can nail the interview.
As an employee/contractor, I would like understand my my function data so I can be more effective.
As a manager, I would like to monitor my main KPIs so I can support team members to reach their goals.
As a director, I would like to understand if my teams are on track to meet the targets set out to shareholders.
As a shareholder, I would like to compare my company's health to industry's top 10% in EBIT so I can decide to keep or sell my stocks.

2.
Data Quality get-go questions:
Identify SCD (slow-changing dimensions) present in data;
have all organizations reported their last balance?
last cash?
last inventory?

then:
what to do with that information

1. Limit all to last complete set of data?
2. 
