# OSXCollector Manual
OSXCollector is a forensice evidence collection & analysis toolkit for OSX.

### Forensic Collection
The collection script runs on a potentially infected machine and outputs a JSON file that describes the target machine. OSXCollector gathers information from plists, sqlite databases and the local filesystem.

### Forensic Analysis
Armed with the forensic collection, an analyst can answer the question like:
* _Is this machine infected?_
* _How'd that malware get there?_
* _How can I prevent and detect further infection?_

Yelp automates the analysis of most OSXCollector runs converting OSXCollector output into an easily readable and actionable summary of _just the suspicious stuff_.

# Performing Collection
`osxcollector.py` is a single Python file that runs without any dependencies on a standard OSX machine. This makes it really easy to run collection on any machine - no fussing with brew, pip, config files, or environment variables. Just copy the single file onto the machine and run it.

`sudo osxcollector.py` is all it takes.
```shell
$ sudo osxcollector.py
Wrote 35394 lines.
Output in osxcollect-2014_12_21-08_49_39.tar.gz
```

# Details of Collection

# Performing Analysis

# Automated Analysis

# Contributing to OSXCollector

# License

This work is licensed under the GNU General Public License and a derivation of [https://github.com/jipegit/OSXAuditor](https://github.com/jipegit/OSXAuditor)
