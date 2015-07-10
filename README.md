# git_test2
Testing how git thing works

Two issues were faced while 'push'ing:

(a) It gave an error that it could not find user. So I followed the instructions from this page where someone reported exact same issue (https://github.com/OHI-Science/ohicore/issues/104) and then used an SSH route instead of HTTPS route.

(b) But Push did not think my SSH was authenticated and got another error. To fix this, I followed instructions in this which reported exact same issue (http://stackoverflow.com/questions/21255438/permission-denied-publickey-fatal-could-not-read-from-remote-repository-whil)

In the above link, scroll down to the bottom of the page to find this link: https://help.github.com/articles/generating-ssh-keys/ and follow the instructions. Then Push again. It finally worked for me.

Is there a shorter or easier way? 
