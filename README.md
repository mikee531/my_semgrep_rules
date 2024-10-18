# semgrep_rules

This repo contains the rulesets i write for different custom usecases. If you are using semgrep as part of CI/CD security and if you find any issues not being detected by semgrep you can write your own custom rule that helps to detect those issues in your code
Few Usecases are:- 
1. If any zero day vulnerability is found and semgrep is not detecting, you can add this rule as part of semgrep rules so that it will check the code for this issue before any merge happens.
2. If any custom scanning needs to be added as part of Semgrep rules like scanning github actions for any speicific change, create a rule that scans only workflow files for that signature.
