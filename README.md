## A command line file uploader for Fileslap

### Installation

- Download the "fileslap" script
- Edit the script, replacing USERNAME and PASSWORD with your login info
- Make it executable:

    `$ chmod o+x ./fileslap`
- Move the script to /usr/local/bin/

### Usage

    $ fileslap yourfilename

### Result

The link to the file will be output to stdout.

Also, if you have xclip installed, it will copy the link to your clipboard.
