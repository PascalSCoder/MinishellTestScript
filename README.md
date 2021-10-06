# MinishellTestScript v0.3
(WIP) Minishell testing script, written in shell

**Installation**
- Ensure that BASH is installed
- Place test.sh and cases.txt in the same folder as the minishell executable
**IMPORTANT: LEAVE A BLANK LINE AT THE BOTTOM IN YOUR CASES FILE**

**Configuration**
- You can change the config variables at the top, to easily adapt to your needs
- Add testcases to the files in cases dir

**How it works**
- The script runs every line in cases.txt with both minishell and bash, compares the output and returns OK/KO depending on whether they are **exactly** equal.

**Runtime options**
- ./test to run with default cases file
- ./test [path] to run with specified file
