POSTMORTEM REPORT

Issue summary
The outage lasted from March 1st, 2023 at 5:00 PM UTC -  March 2nd, 2023 at 7:00 AM UTC.

Impact: Approximately 70% of users were affected.The web was completely down during the outage, resulting in users being unable to access the website.

Root cause: The root cause of the outage was a software bug in the Node.js server that caused it to crash and become unresponsive.

Timeline
5:00 PM UTC: The issue was first detected when monitoring alerts signaled that the server was unresponsive.

5:05 PM UTC: An engineer was alerted and began investigating and addressing the issue.

5:15 PM UTC: The engineer determined that the server was down and began investigating potential causes.

5:30 PM UTC: The engineer assumed the issue was related to a network outage and began investigating network connectivity.

8:00 PM UTC: The engineer determined that the issue was not related to network connectivity and shifted focus to the Node.js server.

9:00 PM UTC: The engineer discovered the software bug that was causing the server to crash and began working on a fix.

10:00 PM UTC: The engineer completed the fix and tested it in a staging environment.

12:00 AM UTC: The engineer deployed the fix to the production environment and began monitoring the server.

7:00 AM UTC: The engineer confirmed that the fix was successful and closed the incident.

Misleading investigation/debugging paths that were taken: The engineer initially assumed that the issue was related to network connectivity and spent time investigating that before realizing it was a software issue with the server.

Escalation: The incident was escalated to the software development team responsible for the Node.js server.


Resolution:
Root cause: The root cause of the issue was a software bug in the Node.js server that caused it to crash and become unresponsive.

Resolution: The issue was resolved by fixing the software bug in the Node.js server.


Corrective and preventative measures:
To prevent similar incidents in the future, the following measures will be taken:

The Node.js server will be updated to the latest stable version to ensure that any known issues are addressed.
The monitoring system will be improved to provide more detailed alerts and enable quicker detection of issues.
The development team will review their development practices to identify potential areas for improvement to prevent similar bugs from being introduced in the future.
Specific tasks to address the issue include:

Updating the Node.js server to the latest stable version.
Improving the monitoring system to provide more detailed alerts.
Reviewing the development practices to identify potential areas for improvement.

