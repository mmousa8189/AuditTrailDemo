# AuditTrailDemo
**Audit Trail Implementation in dotnet (.NET 5) using Entity Framework Core**.

# What’s this Audit Trail about?

Well, it’s a handy technique to track changes that are done by your logged-in users. Ever wondered who had updated the value of a certain entity record in your **dotnet** Application? 
You would want to always keep a record of each and every modification made to your application data.
This is quite vital for many businesses as well.

I will show you the exact process that happens in the background while logging the audit trails. We will track the following with our implementation.

-   TableName
-   Affected Column(s)
-   Primary Key / Value of the Table
-   Old Values
-   New Values
-   Type – Create/Delete/Update/Delete
-   User Responsible for the modification.
-   Date/Time

Seems interesting, yeah? this demo will be able to completely secure our data and track any changes associated with it at this detailed level.

