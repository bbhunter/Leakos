# Leakos

**Search with gitleaks in the responses of the given URLs or in all the repos of an organization and its members.**

## Quick Start

```
pip3 install -r requirements

python3 leakos.py -h
usage: leakos.py [-h] [--github-token GITHUB_TOKEN] [--github-orgs GITHUB_ORGS] [--github-users GITHUB_USERS] [--urls-file URLS_FILE]
                 [--stdin-urls STDIN_URLS] [--not-exts NOT_EXTS] [--json-file JSON_FILE] [--threads THREADS] [--debug] [--generic-leak-in-web]

Search leaks in a github org or in web files

optional arguments:
  -h, --help            show this help message and exit
  --github-token GITHUB_TOKEN
                        Token to access github api (doesn't require any permission)
  --github-orgs GITHUB_ORGS
                        Github orgs names (comma separated). Users will be searched also in the orgs.
  --github-users GITHUB_USERS
                        Github user names (comma separated)
  --urls-file URLS_FILE
                        Search leaks in responses from web urls. Path to file containing URLs to search for leaks.
  --stdin-urls STDIN_URLS
                        Get URLs from stdin
  --not-exts NOT_EXTS   Do not search for leaks in urls with these extensions (comma separated)
  --json-file JSON_FILE
                        Store json results in the indicated file
  --threads THREADS     Number of threads to use
  --debug               Debug
  --generic-leak-in-web
                        Accept generic leaks in web (disabled by defult)
```

For the gihub part of this tool you need to **generate a github token** from your account (however this **token doesn't need ANY PERMISSION**).

If you like **Leakos** you will probably like also **[Gorks](https://github.com/carlospolop/Gorks)** and **[Pastos](https://github.com/carlospolop/PastosLICE)** 


