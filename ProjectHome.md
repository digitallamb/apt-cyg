# Note #

This project was republished on Github and new development is happening on that fork of apt-cyg. For the latest version or to report an issue, go there: https://github.com/transcode-open/apt-cyg


# Intro #

apt-cyg is a command-line installer for Cygwin which cooperates with Cygwin Setup and uses the same repository. The syntax is similar to apt-get. Usage examples:

  * "apt-cyg install <package names>" to install packages
  * "apt-cyg remove <package names>" to remove packages
  * "apt-cyg update" to update setup.ini
  * "apt-cyg show" to show installed packages
  * "apt-cyg find <pattern(s)>" to find packages matching patterns
  * "apt-cyg describe <pattern(s)>" to describe packages matching patterns
  * "apt-cyg packageof <commands or files>" to locate parent packages

# Quick start #

First install subversion and wget through the standard cygwin setup
program. Then run the following commands:
```
  # svn --force export http://apt-cyg.googlecode.com/svn/trunk/ /bin/
  # chmod +x /bin/apt-cyg
```

  * use apt-cyg, for example:

```
  # apt-cyg install nano
```
