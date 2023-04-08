# Troubleshooting

This page contains common issues and their solutions for PyCharm.

| Issue      | Potential Issues | Solutions |
| ----------- | ----------- |----------- |
| Failure to connect to Github port| Connection refused|Check your wifi connection or if you're properly signed into github on the terminal|
| File Text is red| Untracked File|Go to the commit section and add file to either commit or commit and push.|
| Commit and Push button is greyed out| No files to commit|Add files to the commit section|
| No Commit section | Not logged into github or Not in a git repository|Log into github in PyCharm and make sure you're in a git repository|
| PyCharm not running/debugging your current file   | The run/debug config is set to the wrong file ![run/debug config](Screenshot_16.png)  | Select "current file" in the run/debug menu.  Alternatively, just run the file's _main function_ and it should be added to the run/debug configurations.      |
