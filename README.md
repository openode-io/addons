# openode addons

Official addons on [opeNode.io](https://www.openode.io/).

An addon must be placed in folder (category): category/addon-name. *category* must only contains alphanumeric characters and dashes (-). If the category is not currently created, please propose one in the merge request.
In the folder, a config.json must be provided, see below.
Addons are available on opeNode.io.

# config.json schema

| Variable        | Description |
| ------------- |:-------------:|
|  name     | Addon name. Must be unique. |
|  category     | Category (folder) of the addon |
| minimum\_memory\_mb | Minimum memory required (MB). |
| protocol | TCP/UDP. |
| logo\_filename | Logo filename image of the addon. |
| documentation\_filename | Readme filename |
| image | Docker image |
| requires\_persistence | true/false. true if the addon requires persistence. |
| persistent\_path | If requires\_persistence is true, persistent\_path corresponds to the mounted folder path which is persisted in the service docker image. |
| target\_port | Listening port number in the service docker image. |
| required\_fields | Array. Possible values: exported\_port, persistent\_path |
| env\_variables | Key-value pairs of default ENV variables values. |
| required\_env\_variables | List of required ENV variables. |

# Contributing

Users are highly welcomed to contribute to this project. 

* Fork this project.
* Commit and push in the forked project.
* Create a pull request from the forked project.

Make sure to follow our convention:

* 

See several examples in...
