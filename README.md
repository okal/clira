# clira

clira is a command-line client for the JIRA API providing a quick and dirty way
to file, comment on and view issue information.

## Configuration

In your home directory, add a text file, .clirarc

    jira-instance-url = <url for your JIRA instance>
    username = <username>
    password = <password>
    default-project-key = <default project key>

## Usage

* Creating an issue
`clira create <issue type> <issue title> <description> --project='<project key>'`

* Listing projects
`clira list-projects`

* Comment on an issue
`clira comment '<issue number>' '<comment>'`

For a more full-featured implementation, try https://github.com/alisaifee/jira-cli
