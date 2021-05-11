# DankiDemAnki
**Collaborative German Anki decks for Media IT studies.** <br>
This is meant as a supplement to your regular studying. Learning via Anki cards in most cases cannot replace going through exercises in its respective media (programming, calculating, etc), so I advise you to still do that.


[Anki](https://apps.ankiweb.net/) is a tool for creating digital flash cards and remembering things easy and intuitively. It's available for Windows, Mac, Linux and most mobile operating systems for free!<br>
The Anki-addon [CrowdAnki](https://ankiweb.net/shared/info/1788670778) is used by this repository for the distribution via GitHub.

## Before you start
* Please make sure [Anki](https://apps.ankiweb.net/) is running the most recent version.
* Install [CrowdAnki](https://ankiweb.net/shared/info/1788670778).
* You should create a new Anki user dedicated to DankiDemAnki. (When importing Anki decks, merge conflicts could occur or you could publish private data to this repository. A distinct user for this repository helps averting that.)
* Download this repository into your desired directory. 

Just as a quick warning: CrowdAnki doesn't seem to be very stable or well bugfixed. On my first two days of working with it, I've already encountered various ways to freeze or crash Anki, so please follow the instructions below carefully.

## Importing
Be sure you pull the repository before importing for the most recent version. <br>
You can import Anki cards by following these steps: <br>
``` 
"Data" -> 
"CrowdAnki: Import From Disk" ->
From this repo's directory, choose your subject folder (For example "Betriebssysteme".) -> 
Don't tick anything. -> 
OK. 
```

You should now have successfully imported one subject deck into your Anki app. This needs to be repeated for each subject folder.

## Creating new DankiDemAnki cards
* Deck hierarchy goes as following, illustrated by Betriebssysteme: ``"Betriebssysteme" > "1 - Einleitung"``. <br> Going any deeper is probably not necessary. 
* If you have the luck of using an already structured guideline, please also use numbers as first part of the name of your decks. Anki sorts alphabetically, but users may want to study chronologically instead.
* Use as few highlighting as possible, but as much as needed. When editing, press Ctrl+Shift+X for HTML editor.
* Use Anki's overview to review your cards (spelling, typos, etc.) before exporting them! 
* Try to use different approaches to the medium. Don't always write "Wie lautet die Definition von x?", try to get creative when appropriate!
* Use images, videos, link helpful internet ressources! A picture often says more than a thousand words. :)
* I myself haven't done so yet, but don't be afraid of using different card layouts to make the learning experience less repetitive. (Instead of only using the front for questions and the backside for answers.)

## Exporting
``` 
"Data" -> 
"Export" -> 
Choose the "CrowdAnki JSON..." format and only your current subject's deck! ->
Include Media and Tags. -> 
"Export..." -> 
This repo's directory (NOT the subject folder!)
```

You should now have successfully exported all of your subject's updates into the repo. If you have GitHub Desktop installed, you can see your changes there.

## Contributing to DankiDemAnki via GitHub
After a few weeks in the works, I noticed that not all collaborators are used to working with git. So, please, before starting, make sure you understand the basic principles of the git workflow, most importantly **pull**, **commit** and **push**. I recommend learning it by yourself in a sandbox project, and just trying it out. If you like dry theory though, go here: https://git-scm.com/doc <br>
For visualisation of the git workflow: https://ndpsoftware.com/git-cheatsheet.html

* Try to commit your changes often so you won't lose your progress when importing. Needing too much time for a commit (and others pushing in the meantime) is no one's fault but yours. If you have problems with this, try splitting your changes into smaller commits, and export+push / pull+import more often. This way you'll have less conflicts with the current live version. (And less angry contributers wanting their lost cards back.)
* Despite this being a German course, please use English in your commit messages and when communicating through GitHub.
* When creating commit messages I would advise you to follow these rules: https://chris.beams.io/posts/git-commit/
