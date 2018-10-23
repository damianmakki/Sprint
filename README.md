# Sprint
A compilation of some of the best configuration settings for getting a Mac up and running quickly.

This script is dependent upon having [Dropbox](http://www.dropbox.com) set up before starting.

### Use at your own risk
While I've run this a few times myself to work the kinks out, you should take a look through before running it. There are some pretty heavily opinionated options (alas, I couldn't find a suitable hot corners setup), and some [Casks](https://github.com/caskroom/homebrew-cask/tree/master/Casks) you may not want to install, so definitely take the time. **Protip:** Change out the email addresses!

### Usage

1. Download this package and drop it into your Dropbox folder of choice. I call mine **Sprint**.
2. Open up Terminal and


```sh
$ cd ~/Dropbox/Sprint
$ sh sprint.sh
```

Let it run and follow the prompts.

## Advanced Usage
This script was designed to keep my Macs in tandem. In that vein, I keep backups of:
- .bash_profile
- .ssh folders
- hosts file

and store them in the same Dropbox folder as **Sprint**. If you don't have them, it's cool, this script will non-destructively make/backup these files and folders (good thinking, @joetannenbaum).

### Standing on the shoulders of giants
Perhaps one line of this was actually written by me. I'd like to give credit to the sources and original files I compiled this from.


- [Joe Tannenbaum](https://github.com/joetannenbaum) for the base script and the idea.
- [OS X for Hackers/Brandon Brown](https://gist.github.com/brandonb927/3195465) where most of the code is actually from.
