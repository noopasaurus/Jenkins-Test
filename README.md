# Jenkins-Test
Test GitHub repository to trigger Jenkins builds
Made it public, hopefully this commit is sent
Another change
pls work

# Integrating with Zephyr for Jira
 Added post build actions for testing + reading in xml and posting to zephyr for jira  
 error was that pytest was not installed in virtual environment
## Zephyr Test 2
path of output xml was wrong, changed
## Zephyr Test 3
permission denied to ./testreports/report.xml, lots of python 2.7 error messages  
changed permissions of report.xml file
## Zephyr Test 4
permissions still denied  
changed permissions of testreports directory
## Zephyr Test 5
still getting lots of py2.7 errors  
uninstalled pytest in virtual environment  
installed pytest using pip3 in virtual environment but said requirements already met  
running pytest still works
## Zephyr Test 6
pytest command not found  
deleted virtual environment  
tried to uninstall pytest again but it is still able to be found using "which" command  
commented out virtual environment activation and deactivation in "Execute Shell" build step
## Zephyr Test 7
pytest command not found  
installed pytest again even though it was already running  
used sudo to install
## Zephyr Test 8
