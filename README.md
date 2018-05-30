# StoreFinances
A place to store code and files for the sales history tracker

## Excel
The system currently in use is the excel template.
A fresh template gets created for each month, and figures are entered.

| Pro | Con |
| --- | --- |
| Easy to use | No historic tracking |
| | No direct comparison |

## Access
Would provide a method for data comparison.
This would be the 'quick and nasty' solution.
Could be coupled with an SQL backend to allow for multi-site access.

| Pro | Con |
| --- | --- |
| Still relatively simple | Requires MS Access to maintain |
| Could provide multi-user access | Can be hard to secure |
| Has a very limited internal database structure | Would require additional dependencies to function properly |

## C/# Application
This would be the best option.
An application in C#, possibly deployed via WinSparkle and InnoSetup, would allow for true multi-site access.
This would require an SQL-based backend, and some form of API and security to ensure access remains secure.

| Pro | Con |
| --- | --- |
| Can be as easy or hard to use as possible | Harder to create and requires more maintenance |
| Can provide true multi-user access | Vulnerable to online attacks |
| Has a database structure that is completely customizable | Requires additional dependencies to function properly |
| | Requires internet access to function |
