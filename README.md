# github-subdomains

Find subdomains on GitHub.


# Warning

This repository is not public yet.
If you get access it means that you're part of the GitHub sponsors program.
The tool will be released as soon as the current goal will be reached.
For now, you're not allowed to release it, publish it or give access to anyone else.

At the same time, please remember that this program is still under development, bugs and changes may occur.


# Install

```
go get -u github.com/gwen001/github-subdomains
```

or

```
git clone https://github.com/gwen001/github-subdomains
cd github-subdomains
go install
```

# Usage

```
github-subdomains -h

Usage of github-subdomains:
  -d string
    	domain you are looking for (required)
  -e	extended mode, also look for <dummy>example.com
  -o string
    	output file, default: <domain>.txt
  -raw
    	raw output
  -t string
    	github token (required)
```

If you want to use multiple tokens, you should create a `.tokens` file in the executable directory with 1 token per line.


# TODO

- change the order of the extra searches
- find a way to handle panic errors
- so many things...