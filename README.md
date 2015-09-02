# moave

## Mother of All Virtual Environments

This is the Virtual Env that has the Python modules I use
commonly. Instead of having a Virtual Env for each project, I find
that most can just use this one.

### Instructions

```
mkdir ~/Envs
cd ~/Envs
sudo pip install virtualenv
virtualenv moave
source bin/activate
pip install -r ~/src/github/moave/requirements.txt
```

###### *Nota bene*

My Virtual Env use case is to easily configure non-core Python
libraries without modifying the site packages and without needing to
be root. I am not trying to solve the 'project X needs version N of
library L' problem (since I haven't faced it yet with Python).

###### Bibliography

http://docs.python-guide.org/en/latest/dev/virtualenvs/
