# Email-Alert-Tool

The initial goal for this tool is to be able to send an email based on a
condition being met.

At present, the tool is able to:
1. Connect to and query a MS SQL Server database using Flask-SQLAlchemy.
2. Retrieve the metadata of the table specified in the connection string for use in the query.
4. Store the retrieved data in a Pandas DataFrame.
5. Test whether a particular criteria has been met within the retrieved data.
6. Send an email if the criteria has been met.
7. Produce visualizations of the metric being tested, temporarily store any visualizations and tabular data as .png files in buffer so they can be attached to the email without having to be stored in permanent storage.
