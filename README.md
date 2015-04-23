check.sh
========
Version 1.0.0

### What is check.sh? ###
check.sh is a simple shell script that checks the status codes of every link
within an html file. It serves as a useful sanity checker of sorts for 404's or
other broken links on personal websites. This was uploaded at the request of a
friend.

### Does it work? ###
Possibly? I used a regular expression to parse the html for <a> tags, so
nothing is guaranteed. It works for my website at least.

### How to run ###
Ensure that `check.sh` has the appropriate permissions then run the following:

```
./check.sh /path/to/some/html/file.html
```

