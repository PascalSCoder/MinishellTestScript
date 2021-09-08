# MinishellTestScript v0.2
(WIP) Minishell testing script, written in shell

**Installation**
- Ensure that BASH is installed
- Place test.sh and cases.txt in the same folder as the minishell executable
**IMPORTANT: LEAVE A BLANK LINE AT THE BOTTOM IN YOUR CASES FILE**

**Configuration**
- You can change the config variables at the top, to easily adapt to your needs
- Add testcases to your testcases file

**How it works**
The script runs every line in cases.txt with both minishell and bash, compares the output and returns OK/KO depending on whether they are **exactly** equal.
