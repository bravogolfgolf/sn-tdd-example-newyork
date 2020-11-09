# sn-tdd-example-newyork
## GitHub
### Create fork
    Fork this repository
    From your forked repository select 'Clone or Download'
    Copy 'Clone with HTTPS' URL
### Create token
    Open User Settings
    Click 'Developer Settings'
    Click 'Personal access tokens'
    Click 'Generate new token'
    Add Note to identify this token
    Select 'public_repo'
    Click 'Generate token'
    Make sure to copy your new personal access token now. You won’t be able to see it again!
## ServiceNow
    Login into developer instance
### Main Tab
    Open Studio
### Studio Tab
    Click 'Import From Source Control'
    Network protocol: 'https'
    URL: [URL from 'Create fork' step]
    Branch: master
    Username: [GitHub username]
    Password: [Token from 'Create token' step]
    Click 'Import'
    Click 'Select Application'
    Open 'tdd'
### Main Tab
    Switch tto 'Global' applicattion
    Navigate to 'Automated Test Framework (ATF)' -> 'Administration' -> 'Properties'
    Select 'yes' for Enable test/test suite execution
    Click 'Save'
    
    Switch to 'tdd' applicattion
    Navigate to 'Automated Test Framework (ATF)' -> 'Tests'
    Open 'Data Plan' Test
    Click 'Run Test' (This should complete successfully)
