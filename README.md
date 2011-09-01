## A command line file uploader for Fileslap

### Installation

- Install [python-requests](http://python-requests.org) (it's the only dependency).
- Download the "fileslap" script
- Edit the script, replacing YOURUSERNAME and YOURPASSWORD with your login info
- Make it executable:

    `$ chmod o+x ./fileslap`
- Move the script to /usr/local/bin/

### Usage

    $ fileslap yourfilename

### Result

The link to the file (both on the site and the raw file) will be output to stdout.
