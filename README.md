[st](https://st.suckless.org/)

- [Patches](https://st.suckless.org/patches/)
    - st-focus-20200731-43a395a.diff
    - st-meta-vim-full-20210425-43a395a-8.4.patch
    - st-rightclickpaste-0.8.2.diff


# st - simple terminal
st is a simple terminal emulator for X which sucks less.


## Requirements
In order to build st you need the Xlib header files.


## Installation
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    sh build.sh


## Running st
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

## Credits
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

