# Useful Scripts & Notes
This repository contains some funny scripts. I write them all the time, they make my daily tasks very easy. Further I am taking some notes on things that I came across. Despite I use some scripts only once, you may have a good day when you can use a out of the box solution ;)

### Github Repo Downloader
Download all your repos from Github, while maintaining the original datetimes (upload, edit etc).

Becaerful: It places them inside a json in your repo root, with a side note in README.md. 
Therefore it creates or writes to the README.md (therefore it's possible that you experience a few side effects) 

I wrote it in June 2021, because I had issues with the already given solutions. :-) 

### FindFile 
It's a very nice Tool to find text in files non-recursively without the need to open VS Code or smth. like that.
I wrote it because I had +2000 Files in a Dir (PHP Scripts btw) and I needed to find out one little var and I wanted to know in what files the var is included.
Successfully worked ;p

### DoInstall 
Uses docker-compose to setup a Env for the Mondial Database (if you're studying informatics it could be you need it)
It makes a lot of fun to write such shell scripts and even docker-compose :-)

### GetIP
The fast way to find out your external IP. (Needs inet connection)
I wrote it just 4 fun and maybe for future use in hacking labs
But mostly it wont work there, because the most vuln machines in the Labs don't have open inet connectivity due to obvious reasons :-D

### FileListing_Comapre
Two directories A and B. Changed files in both directories. To compare a filelist of A with the current directory B. The script goes over the filelist and uses bash's -f checks see if the *file or directory* **exists**. There is **NO hash comparison** to check if both files are identical.

### Wekan Snap Writeup
I just came across interesting claims in the issues Tab of Wekan Snap and tried to fix the TLS config, showing people how it works. 
- [wekan_snap_writeup.md](wekan_snap_writeup.md)

### CleanLogs.py
- Truncats the log files in `/var/log`, `/var/lib/docker/containers` and `/tmp`
- Returns a metric message

### Adding Abbreviation Detector for SpacyNLP from SciSpacy
During some NLP information extraction I wanted to get rid of the abbreviations. I came across Scispacy but the installation fails.. https://github.com/allenai/scispacy/issues/504 - Surrender? Nah, no problem for me, I just had to rip that Abbreviation piece out and use it in my project.
- [adding_abbreviation_detection_to_your_spacy_nlp_project.md](adding_abbreviation_detection_to_your_spacy_nlp_project.md)
