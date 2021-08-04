This project contains the following supplementary data:

## RQ1:

- The mapping of rules from style checkers to rules from style guidelines:
	- [Java rule mapping.ods](/RQ1/Java_rule_mapping.ods) for Java
	- [Python rule mapping.ods](/RQ1/Python_rule_mapping.ods) for Python
	
In both of these files, the column "rule" lists the rule, the column "scope" lists the scope to which the rule applies and the column "type" lists the type(s) of the rule. The other columns list the rules that are equivalent in the style guidelines or style checkers as labelled.
	
## RQ2:

- [commit_ids.txt](/commit_ids.txt) - The commit ids for all projects that we ran style checkers on.
- [configs](/configs) - The XML configuration files for PMD and Checkstyle from projects stripped to only include rules relating to comments. Style checkers other than PMD and Checkstyle do not need XML config files, but can be configured from the command line, which we did; as such we do not have config files for other style checkers.
- [linter output](/linter_output) - The output of a style checker run on all projects that use it.
-- [ansible-output.txt](/linter_output/ansible-output.txt) contains the discarded results of Pylint run on ansible.
-- [apollo attributed.txt](/linter_output/apollo attributed.txt) contains the results of Checkstyle run on apollo with additional attrubution to which module of Checkstyle generated the message.
-- [checkstyle linter run results.txt](/linter_output/checkstyle linter run results.txt) contains the results of Checkstyle run on all projects using Checkstyle except elasticSearch (which is in its own file to its size).
-- [codespell celery.txt](/linter_output/codespell celery.txt) contains the results of codespell run on celery. Other projects did not generate any messages from codespell.
-- [elasticsearchOutput.txt](/linter_output/elasticsearchOutput.txt) contains the results of Checkstyle run on elasticSearch.
-- [flake8 linter run results.txt](/linter_output/flake8 linter run results.txt) contains the results of Flake8 run on all projects using Flake8.
-- [graal linter output.txt](/linter_output/graal linter output.txt) contains the discarded results of Checkstyle run on graal.
-- [pmd linter run results.txt](/linter_output/pmd linter run results.txt) contains the results of PMD run on all projects using PMD.
-- [pycodestyle linter run results.txt](/linter_output/pycodestyle linter run results.txt) contains the results of pycodestyle run on all projects using pycodestyle.
-- [pydocstyle linter run results.txt](/linter_output/pydocstyle linter run results.txt) contains the results of pydocstyle run on all projects using pydocstyle.
-- [pylint linter run results.txt](/linter_output/pylint linter run results.txt) contains the results of Pylint run on all projects using Pylint.
