# vi-enable-mouse-copy-paste

By default, Vi or Vim uses visual mode, which causes mouse copy and paste not to work.

This is a way to disable visual mode, so mouse copy and paste can work:
```
echo "set compatible" >> ~/.vimrc
echo "set mouse-=a" >> ~/.vimrc
```
then log out and log in again.

Just it.
