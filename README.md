# r53mon
Route 53 Monitor

# Problem
External monitoring tools such as Pingdom, can only monitor public URLs, plus (in most cases) you pay for each URL you want to monitor. Often you would like to monitor internal tools, and staging/test environments that are not accessible via public internet and don't want to pay for them, but it would be nice to see their uptime availability and be alerted of downtime.

# Solution
r53mon is a simple solution that runs inside your network. r53mon reads all Route 53 entries in all regions of your account and automatically begins monitoring them with simple checks.

# Roadmap
In future releases you will be able to:
- Link an SNS topic with r53mon to be notified when a record is not responding.
- Advanced check - Find text on page
- Advanced check - Return code
- Filter by Region
- Filter by Hosted Zone
- Advanced check - Login to site
