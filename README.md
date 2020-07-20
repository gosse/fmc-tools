# FMC Tools
A repository of python scripts to perform some routine changes in a quicker way than FMC typically allows via GUI. This is built upon a fork from [rnwolfe/fmc-tools](https://github.com/rnwolfe/fmc-tools) which was forked from [kaisero/fireREST](https://github.com/kaisero/fireREST) with some of my own changes to the functions. The tools were originally inspired by [this post by the same person](http://dependencyhell.net/2017/08/27/Automating-ACP-Bulk-Changes/).

## Requirements
Clone this repo and install fireREST:
``` bash
git clone https://github.com/gosse/fmc-tools
pip3 install fireREST
```
Afterwards, you can use the specific tool script you want.

## Tools 
* export-acp-to-csv.py - export an Access Control Policy to CSV 
* export-prefilter-to-csv.py - export a Prefilter Policy to CSV
* export-objects-to-csv.py - export objects to CSV 
* update-all-rules.py - update all rules 
