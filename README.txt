1. Attachment in https://issues.apache.org/jira/secure/attachment/12797069/TEZ-3197.WIP.patch is clobbered.  So hosting note.json in this repo.

Installation:
=============
1. Install latest Zeppelin
2. Install "DOT/graphviz" in the zeppelin machine
3. Start Zeppelin
4. Navigate to zeppelin web page (e.g http://localhost:8088) and click on "Import note". Import note.json.
5. Populate the relevant fields (like "dagFile", "dagName", "tmpDir" etc) in the notebook and click on "Run" button in the notebook.

Pain points:
===========
1. Zeppelin does not support uploading files to remote server. So this notebook requires some configurations like populating directories whereever "PROVIDE_" etc is mentioned.



