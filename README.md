# indigo-iam.github.io

This repository holds the INDIGO IAM Website. It is built any time there is a commit in the
source code, available at https://github.com/indigo-iam/iam-website.

Any folder in the [v](./v/) directory contains a branch of the source code, whose name is equal
to the INDIGO IAM version.

**NOTE:** In order to load the latest version of the documentation (i.e. `current`) you need to
manually update the symbolic link [here](./v/current) such to point to the last tag, e.g. with

```bash
ln -sfn <tag> v/current
```

