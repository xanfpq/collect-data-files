# Collect data files

![GitHub repo size](https://img.shields.io/github/repo-size/xanfpq/collect-data-files)
![GitHub contributors](https://img.shields.io/github/contributors/xanfpq/collect-data-files)
![GitHub stars](https://img.shields.io/github/stars/xanfpq/collect-data-files?style=social)
![GitHub forks](https://img.shields.io/github/forks/xanfpq/collect-data-files?style=social)
![Twitter Follow](https://img.shields.io/twitter/follow/xanfpq?style=social)

Collect data files is a tool that allows collect data files on the same directory.

In process of collect several data files on same folder, we can check header and encoding of which one.

## Prerequisites

Before you begin, ensure you have met the following requirements:
* You have installed the Python library to read/write Excel [openpyxl](https://openpyxl.readthedocs.io/en/stable/)
* You have installed the universal character encoding detector [chardet](https://pypi.org/project/chardet/)

## Using Collect data files

To use Collect data files, follow these steps:

```
python collect-data-files.py -i <infile> -f <field> -c <copy> -s <search> -H <header>
```

Mandatory arguments to long options are mandatory for short options too.
* -i, --input: file path with the list of files
* -f, --field: name of field on the input file with list of files
* -c, --copy: path destination to collect files
* -s, --search: (optional) path to search files that not exists on path destination
* -H, --header: (optional) header to validate with fields separated by ;

## Contributing to Collect data files

To contribute to Collect data files, follow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.

Alternatively see the GitHub documentation on [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

## Contact

If you want to contact me you can reach me at [xanfpq@gmail.com](mailto:xanfpq@gmail.com).

## License

This project uses the following license: [GNU General Public License v2.0](https://github.com/xanfpq/collect-data-files/blob/master/LICENSE).
