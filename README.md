# Blackboard Import

Import Blackboard ExportFiles and ArchiveFiles as Canvas courses. The current model is that a single API user (the Blackboard Import API Process) creates all of the course components via the API. The Blackboard export Zip archive and an import receipt XML file are also uploaded to the created course's files. The tool can also import the Blackboard export into an existing course, if the API user has full access to that course. I've configured our instance so that there is a Blackboard Import sub-account, over which the API process is an admin, and courses are move in and out of the sub-account by hand (it's an easy way to track where things are in the flow).

[Some helpful background reference.](https://www.diigo.com/user/battis/smtech canvas dev-blackboard-export)
