*Automatically create MS SQL Agent Jobs*
=============


Reads SQL Agent Jobs from MS SQL Server and creates Automic Jobs
http://github.com/Automic-Community/Automatically-create-MS-SQL-Agent-Jobs

<!-- List of attached files -->
Contents of Solution Package:

						
								*create_sql_agent_jobs_export.zip
								
						


Documenation and Instructions
---

<p>This Template can be used to create Automic Jobs based on SQL that selects all SQL Agent Jobs in MS SQL Server. The Form Tab is great if you have a few Jobs, but when you try to "convert" 100s of SQL Agent Jobs to Automic Jobs, then this little template can be you friend.</p>
<p>&nbsp;</p>
<p>To run it you will need to adjust the Variables in the Workflow to match your enviornment. I also added a Breakpoint after the&nbsp;JOBS.SQL.FIND_JOBS, so you can verify the output and the SQL_DEFINED_JOBS variable.&nbsp;</p>

Copyright and License
---

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)


Questions or Need Help? 
---
Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
