*[Go back](README.md)*
# The structure of my Python 🐍 libraries

| File / Folder name | Type   | Description |
| ------------------ | ------ | ----------- |
| .github/workflows/release_build.yaml | FILE   | PIP and BUILD Workflow|
| .run               | FOLDER | PyCharm runs config|
| .gitignore         | FILE   | GitIgnore   |
| LICENSE            | FILE   | MIT License |
| README.md          | FILE   | README      |
| changelog.md       | FILE   | Changelog   |
| *{lib_name}*       | FOLDER | PyLib folder|
| clear_wheels       | FILE   | AfterBuild Cleanup **(BASH)**|
| clear_wheels.bat   | FILE   | AfterBuild Cleanup **(CMD)**|
| pylib.json         | FILE   | Something like pyproject.toml, but in json|
| setup.py           | FILE   | MAIN Build entry |
| version.txt        | FILE   | VERSION File |

---

**You can find an example of the library [here](https://github.com/IgorNk500/metaerrors).**
