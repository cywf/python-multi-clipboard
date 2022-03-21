# Python application that lets you store multiple words/data in a clipboard

- Author: Kyle Parisher (cywf)
- Date: 03-07-22
- Email: skoll.wfpk@pm.me
- Github: https://github.com/cywf
---
## How to use multiclip.py
#### 1) Create a key (_you can create as many keys as you like_) to save your data to:
    $ python3 multiclip.py save
- Enter key value: "_example_"

#### 2) Copy something to your clipboard:
- For Windows [ctrl-c]
- For Mac [cmd-c]
- For Linux [ctrl-c]

#### 3) Next load the data saved to your clipboard into the key you just created:
    $ python3 multiclip.py load 
- Enter your key: "_example_"

#### 4) Now list the contents of your multi-clipboard
    $ python3 multiclip.py list
- Your data saved to all your keys, should now be displayed
