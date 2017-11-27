# db2ynab
DeutscheBank to YNAB CSV converter

## Purpose
A Node.js® tool to convert bank statements from Deutsche Bank's CSV format into that required for importing into YNAB4.

## Requirements
- A running Node.js environment (http://lmgtfy.com/?q=install+node)

## Installation
- Clone the script's repository in a local folder (http://lmgtfy.com/?q=clone+a+github+repository)

## Usage

Convert statement CSV downloaded from "meine.deutsche-bank.de" into YNAB importable format.

```$ node db2ynab.js [--in=]FILE [[--out]=FILE]```

In case no "out" file was specified, the script will create a new "converted.csv" in the current folder.

Thats's it!