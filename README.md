# Installation setup

```sh
$ git clone git@github.com:uwrit/leaf-docs.git
$ cd leaf-docs
$ python3 -m venv venv
$ source venv/bin/activate
$ python3 -m pip install -r requirements.txt
$ mkdocs serve
```

# Updating changes to leafdocs.rit.uw.edu

1. Change files as needed on any branch
2. Merge changes to master
3. Run command `mkdocs gh-deploy`

leafdocs.rit.uw.edu should update automatically

Note: keep CNAME file in docs/CNAME

Mkdocs GitHub pages deployment reference: https://www.mkdocs.org/user-guide/deploying-your-docs/