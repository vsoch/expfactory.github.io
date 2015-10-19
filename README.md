# Instructions to Generate Site

[psiturk.github.io](http://psiturk.github.io)

First cd to the scripts folder - the relative path is important:

      cd scripts

You will need psiturk-python installed for this to work:


      pip install git+git://github.com/psiturk/psiturk-python.git


Next, run "make_site.py"


      python make_site.py


This will regenerate all the files in the directory above. You should next commit and push to the master branch. Since this is under the repo psiturk.github.io, it will be pushed to the main github pages for the Organization automatically.

    git commit -a -m "I have (made these changes)"
    git push origin master

Done!
