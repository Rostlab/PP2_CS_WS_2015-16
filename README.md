This repository holds open discussions and documentation for the [class](http://tinyurl.com/ntzqv46). The repo is specially intended for the Exercises. Every student has write access to this repo and we work on a trust basis. Students are encouraged to write in documentation, open issues, help colleagues, and even propose exam questions!

## Exercise

Students in groups will improve and move Rostlab most important tools' code and documentation to GitHub. Purpose: improve their usability and discoverability. As for motivation for students, all their contributions will be visible on Rostlab's GitHub organization.

The students will have to give various mid-term presentations on their progress. An important milestone will be to successfully run the tools on their own and provide installation and run instructions for other users. The students will also have to understand and explain how the tools work, their utility, and their biological significance. This includes giving short introductions to topics such as: machine learning methods, biological or bioinformatics concepts, databases, file formats, etc. Lastly, considering the scientific nature of the tools, peer-reviewed citations, benchmarks and comparisons with other similar tools will also have to be included in the documentation.


## Tools

* [SNAP2](https://github.com/Rostlab/SNAP2) -- Linda & Andre
* [LocTree (3)](https://github.com/Rostlab/LocTree) -- Sonja & Alejandro
* [MetaDisorder](https://github.com/Rostlab/MetaDisorder) -- Sirma & Irem
* [MetaStudent](https://github.com/Rostlab/MetaStudent) -- Ansh & Ana
* [someNA](https://github.com/Rostlab/someNA) -- Christian & Dimitri
* [TMSEQ](https://github.com/Rostlab/TMSEQ) -- Muriel & Cyril
* [PROFsec](https://github.com/Rostlab/PROFsec) -- Roc & Cristina
* consurf -- Manuel & Saion (???)

These are the most important tools developed in Rostlab for the PredictProtein service. Current documentation and code of the tools (some deprecated or not updated) can be found in:

* https://www.predictprotein.org/
* https://rostlab.org/owiki/index.php/Packages
* https://rostlab.org/resources/web-services


### Work

* Move code & documentation to GitHub
  * Move repositories from svn to git conserving all history (this will be verified!)
  * Move to GitHub
  * Remove possible passwords or sensible data (likely done internally by Juan Miguel Cejuela, Timothy Karl, and Lothar Richter)
* Check usability (create github issues for all errors you find)
  * Installable on Debian? (see below the Documentation, for a virtual machine)
  * Works on Mac OS X ?
  * Understandable?
  * Is there Documentation? Can be improved?
  * Ease of use?
  * ~~Where is the code?~~ obviously now in the respective GitHub repos. [Please update Rostlab's open wiki links](https://rostlab.org/owiki/index.php/Packages)
  * Is there a man page?
* Improve usability aspects
  * Documentation goes to README.md
  * If large attachments are needed, these will go to the repo wiki
  * Few small code fixes if necessary
  * After all improvements, any external user should be able to run the tools on their own with the provided instructions.
* Show:
  * Demo run
  * Mid-presentations: how the method works, theory behind, training or validation process, machine learning methods, ...
* [Register tool into Elixir](https://elixir-registry.cbs.dtu.dk/?q=rostlab)


### Documentation

* [HOWTO move from svn to git](https://git-scm.com/book/it/v2/Git-and-Other-Systems-Migrating-to-Git) -- May be necessary to check other tutorials
* [Rostlab current and past members](https://rostlab.org/group/people) (for git email addresses) -- Default email address: juanmi@jmcejuela.com
* For a virtual machine, use [Vagrant](www.vagrantup.com/) with a Debian Wheezy image


### Slides

Refer back to the [class page](http://tinyurl.com/ntzqv46)
