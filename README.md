# Codacy-Psscriptanalyzer Docker Container

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/c5d062c19785439980803f4557f9e441)](https://www.codacy.com/app/Codacy/codacy-psscriptanalyzer?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=codacy/codacy-psscriptanalyzer&amp;utm_campaign=Badge_Grade)
[![Build Status](https://circleci.com/gh/codacy/codacy-psscriptanalyzer.svg?style=shield&circle-token=:circle-token)](https://circleci.com/gh/codacy/codacy-psscriptanalyzer)
[![Docker Version](https://images.microbadger.com/badges/version/codacy/codacy-psscriptanalyzer.svg)](https://microbadger.com/images/codacy/codacy-psscriptanalyzer "Get your own version badge on microbadger.com")

[Docker](https://www.docker.com) container to allow support for [psscriptanalyzer](https://github.com/PowerShell/PSScriptAnalyzer) on Codacy.

## Dockerfile building

To build the Codacy-psscriptanalyzer dockerfile : 

1. Clone the source:

    ``` sh
	$ git clone https://github.com/codacy/codacy-psscriptanalyzer.git
	$ cd codacy-psscriptanalyzer
    ```

2. Build the container:

    ``` sh
    $ docker build -f Dockerfile -t codacy-psscriptanalyzer .
    ```

## Docs

[Tool Developer Guide](https://support.codacy.com/hc/en-us/articles/207994725-Tool-Developer-Guide)

[Tool Developer Guide - Using Scala](https://support.codacy.com/hc/en-us/articles/207280379-Tool-Developer-Guide-Using-Scala)

## Test

We use the [codacy-plugins-test](https://github.com/codacy/codacy-plugins-test) to test our external tools integration.
You can follow the instructions there to make sure your tool is working as expected.

## What is Codacy

[Codacy](https://www.codacy.com/) is an Automated Code Review Tool that monitors your technical debt, helps you improve your code quality, teaches best practices to your developers, and helps you save time in Code Reviews.

### Among Codacy’s features

- Identify new Static Analysis issues
- Commit and Pull Request Analysis with GitHub, BitBucket/Stash, GitLab (and also direct git repositories)
- Auto-comments on Commits and Pull Requests
- Integrations with Slack, HipChat, Jira, YouTrack
- Track issues in Code Style, Security, Error Proneness, Performance, Unused Code and other categories

Codacy also helps keep track of Code Coverage, Code Duplication, and Code Complexity.

Codacy supports PHP, Python, Ruby, Java, JavaScript, and Scala, among others.

### Free for Open Source

Codacy is free for Open Source projects.