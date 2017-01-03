[![Build Status](https://travis-ci.org/YenF/personal-website.svg?branch=master)](https://travis-ci.org/YenF/personal-website)

# personal-website
Followed http://www.clock.co.uk/blog/a-simple-website-in-node-js-2016-edition

# Auto deployment to digital ocean
https://kjaer.io/travis/  
https://www.digitalocean.com/community/tutorials/how-to-use-git-hooks-to-automate-development-and-deployment-tasks

Set up post-receive, ssh authorized_keys
  However not able to push to server. or after push it I still have to do something in server?...
  It is because my post-receive hook is not config properly.  
  `git --work-tree=/var/www/yenfengc/public_html/ --git-dir=/var/www/yenfengc/.git checkout -f`  
  Should be without trailing '/'  
  `git --work-tree=/var/www/yenfengc/public_html --git-dir=/var/www/yenfengc/.git checkout -f`  
  
# Going to set up nginx or apache server

# Going to actually program something

# Good sites for reading and concept
SSH concept and how to use it: https://www.digitalocean.com/community/tutorials/ssh-essentials-working-with-ssh-servers-clients-and-keys  
Git hook how to and concept: https://www.digitalocean.com/community/tutorials/how-to-use-git-hooks-to-automate-development-and-deployment-tasks  
