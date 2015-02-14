Hi Shin (@jonasuke),

I have added all of your sample HTML files to this repository and added you as a collaborator. You can begin by cloning this repo. I think you already have git installed on your laptop, but if not then you can install it using the following command:
```bash
$ sudo apt-get install git
```
Once you have installed ```git``` or confirmed that it is already installed, then configure it because every git commit uses this information and it identifies you as the person creating the commits.
```bash
$ git config --global user.name "Shinsuke Miyamoto"
$ git config --global user.email youremail@address.com
```


```bash
$ git clone https://github.com/scmorrison/shin-html5.git
```

This will copy the code to your computer into a directory named ```shin-html5```. You can add all of your new sample HTML files to that directory and then commit / push them to this repository using the following commands:

Add new files to repository
-------------------------------------
```bash
$ git add name-of-file.html
```

Commit new files or changes to files
----------------------------------------------------
```bash
$ git commit -a -m"Describe your modifications here"
```

Push all of your modifications to github so that we can share the code
---------------------------------------------------------------------------------------------------
```bash
$ git push origin master
```

Let me know if you have any questions. Also, you might be interested in this to help you better understand why git (version control) is all about: http://git-scm.com/book/ja/v1
