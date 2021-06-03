# repo1(base) germanvillegas@Germans-Air pets %  cd repo1
(base) germanvillegas@Germans-Air repo1 % ls
exercise1
(base) germanvillegas@Germans-Air repo1 % mkdir images
(base) germanvillegas@Germans-Air repo1 % ls
exercise1	images
(base) germanvillegas@Germans-Air repo1 % cd images
(base) germanvillegas@Germans-Air images % touch gitkeep
(base) germanvillegas@Germans-Air images % cd ..
(base) germanvillegas@Germans-Air repo1 % ls
exercise1	images
(base) germanvillegas@Germans-Air repo1 % git add .
(base) germanvillegas@Germans-Air repo1 % git commit -m "i did it"
[main 074f994] i did it
 Committer: German Villegas <germanvillegas@germans-air.attlocal.net>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 images/gitkeep
(base) germanvillegas@Germans-Air repo1 % git push
Username for 'https://github.com': violeta1218
Password for 'https://violeta1218@github.com': 
