
# Apex Coding Resources

## References

- https://help.salesforce.com/articleView?id=code_about.htm&type=5

- https://help.salesforce.com/articleView?id=writing_code.htm&type=5

- https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_dev_guide.htm
  + v50.0
    * https://developer.salesforce.com/docs/atlas.en-us.228.0.apexcode.meta/apexcode/apex_dev_guide.htm

- https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_reference.htm

- https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_classes.htm
  + https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_classes_defining.htm

- https://help.salesforce.com/articleView?id=code_manage_packages.htm&type=5
- https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_manpkgs_dev.htm


- https://developer.salesforce.com/docs/atlas.en-us.228.0.object_reference.meta/object_reference/sforce_api_objects_concepts.htm


## Community Resources
- https://stackoverflow.com/search?q=apex


## Static Code Analysis Tools

- ApexLink
  + https://github.com/nawforce/ApexLink
  + "Salesforce Apex static analysis library & SFDX CLI plugin"
  + 201903-07 Article: Preventing Salesforce Regression Introducing the Apex Linter
    * https://medium.com/quantcast-engineering/preventing-salesforce-regression-introducing-the-apex-linter-10df9622ce82
    * "We’re sharing some of our Salesforce learnings in the form of a linter
      (code checker). The linter flags things that have caused problems for us
      in Apex, the programming language used in Salesforce. It flags a tricky
      problem with Map and Set, the use of futures and SeeAllData in unit tests,
      and the obsolete ‘testMethod’ keyword. Because Map and Set are used a lot,
      that check can be suppressed on a line-by-line basis by putting a comment
      with a link on back to a document about it in the GitHub open source
      project. "


- PMD [*RECOMMENDED*]
  + https://pmd.github.io/
    * https://github.com/pmd/pmd
    * https://github.com/pmd/pmd/releases/
  + https://pmd.github.io/latest/pmd_rules_apex.html
    * https://github.com/pmd/pmd/tree/master/pmd-apex
      * https://github.com/pmd/pmd/tree/master/pmd-apex/src/main/resources/rulesets/apex
  + https://pmd.github.io/latest/pmd_apex_metrics_index.html
    * https://www.sonarsource.com/docs/CognitiveComplexity.pdf
  + https://pmd.github.io/latest/pmd_rules_apex.html


- Quantcast Apex Linter for Salesforce
  + https://github.com/quantcast/apexlint
    * *Last updated*: 2019-02-01 


- sonarlint
  + https://www.sonarlint.org/vscode  
  + https://github.com/SonarSource/sonarlint-vscode
    * "SonarLint is a free IDE extension that lets you fix coding issues before
      they exist! Like a spell checker, SonarLint highlights Bugs and Security
      Vulnerabilities as you write code, with clear remediation guidance so you
      can fix them before the code is even committed."
    * "You can connect SonarLint to SonarQube >= 6.7 or SonarCloud and bind your workspace folders to a SonarQube/SonarCloud project to benefit from the same rules and settings that are used to inspect your project on the server. SonarLint then hides in VSCode the issues that are marked as Won’t Fix or False Positive."
      * Connected mode will also allow to unlock analysis of those languages:
        * ```Apex rules```


- SonarSource
  + https://www.sonarsource.com/apex/
  + SonarQube
    * https://www.sonarqube.org/features/multi-languages/apex/
  + https://rules.sonarsource.com/apex


- vscode Apex Pmd
  + https://marketplace.visualstudio.com/items?itemName=chuckjonas.apex-pmd
    * Allows you to run Apex Static Analysis directly in vscode on apex & VisualForce files.
      * Run analysis on file open
      * Run analysis on file save
      * Run analysis on file change (new!)
      * Run analysis on entire workspace
      * Run analysis on single file
      * Ability to define your own ruleset
  + https://github.com/ChuckJonas/vscode-apex-pmd
    * PMD static analysis for Apex in vscode 

