# Local-composer-issue
Have issue with "composer update" generating random characters(such as ? or : or bool) in vendor twig files

Here's the steps to solve it:
1. Check your local PHP & composer version. 
2. My local composer is version 1.10.22
3. My local PHP is version 7.1
4. We need to downgrade PHP to version@5.6 because we're using composer version@1 not version@2
5. Please go to https://github.com/shivammathur/homebrew-php and follow the the steps to install PHP@5.6 using homebrew
6. Once we successfully installed PHP@5.6 locally, then run "compoer update", I no longer have issue in twig files.

