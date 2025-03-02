# Python installation on Linux

Installing Python on Linux is actually easy.
The only difficult part could be that there are many distributions that
needs different installation commands.

## Python 3

First check in your command line/terminal
if you don't already have python3 installed.
Open the terminal and type into it:

```console
$ python3 --version
```
If "Python" and version number (e. g. `Python 3.8.2`) will appear
and the version is higher than or equal to 3.8 then everything is fine and please continue with
further section.

If there will be "Python" and version lower than 3.8, ask us how to proceed.

If `bash: python3: command not found` or something similar will appear
you will have to install Python3.
Command depends on your distribution.


* Fedora:
  {% filter markdown(inline=True) %}
  ```console
  $ sudo dnf install python3
  ```
  {% endfilter %}
* Ubuntu:
  {% filter markdown(inline=True) %}
  ```console
  $ sudo apt-get install python3
  ```
  {% endfilter %}

If you are using some other distribution we expect that you already know
how to install programs. If not try to ask Google.
