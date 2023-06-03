# react django

# Django setup notes...

## Installing python 3. Kind of a pain
Device: (Macbook Air, M1, 2020) macOS Montery V 12.0.1

- previously installed python 2.7

### My notes:
<i>loosely following a tutorial but it's very outdated...</i>

setting up the frontend
- node: v16.13.1
- `npx create-react-app frontend`


setting up the backend
1. `brew install python@3.10.1`
2. attempted to:
   1. `pip3 install virtualenv virtualenvwrapper`
   2. `virtualenv --version` --> `not found` pathing seems to be different than online guides. 
      1. Followed the ideas in: https://stackoverflow.com/questions/49470367/install-virtualenv-and-virtualenvwrapper-on-macos
         1. looked for `virtualenvwrapper.sh` under python 3.8 bin folder
         2. set up the path in `.zshrc`
         3. still didn't work
            1. `sudo -H pip3 install virtualenv` seemed to do the trick. Could be mismatch in python version...

backend
- activate `. myenv/bin/activate`
- `pip3 install django`
- `django-admin startproject backend`
