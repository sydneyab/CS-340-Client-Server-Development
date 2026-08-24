# CS 340 Client/Server Development

This repository contains the final dashboard code and README documentation for Project Two: the Grazioso Salvare rescue animal dashboard.

## Portfolio Reflection

**How do you write programs that are maintainable, readable, and adaptable?**
I focused on separating concerns by building a CRUD Python module in Project One that handled all database interaction independently from the dashboard code. 
That separation made it easy to plug the module into Project Two without rewriting anything. The same module could connect to any MongoDB collection in the future, not just animal shelter data, by changing a few parameters.

**How do you approach problems as a computer scientist?**
I work through problems methodically — reading error messages carefully and tracing issues back to their root cause instead of guessing. 
That approach got me through authentication errors, callback issues, and display bugs in this project. Future database projects would follow the same pattern: understand the data structure first, then build around it.

**What do computer scientists do and why does it matter?**
We build tools that let people work faster and smarter with data they already have. The Grazioso Salvare dashboard turned a raw database into something actionable. 
Without that tool, someone would be manually sorting through thousands of records. The work we do removes that burden and lets people focus on what actually matters — in this case, saving lives.
