# gh-stars

[![gh-actions](https://img.shields.io/github/workflow/status/nschloe/gh-stars/ci?style=flat-square)](https://github.com/nschloe/gh-stars/actions?query=workflow%3Aci)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg?style=flat-square)](https://github.com/psf/black)
[![PyPI pyversions](https://img.shields.io/pypi/pyversions/gh-stars.svg?style=flat-square)](https://pypi.org/pypi/gh-stars/)
[![PyPi Version](https://img.shields.io/pypi/v/gh-stars.svg?style=flat-square)](https://pypi.org/project/gh-stars)
[![GitHub stars](https://img.shields.io/github/stars/nschloe/gh-stars.svg?style=flat-square&logo=github&label=Stars&logoColor=white)](https://github.com/nschloe/gh-stars)
[![PyPi downloads](https://img.shields.io/pypi/dm/gh-stars.svg?style=flat-square)](https://pypistats.org/packages/gh-stars)

gh-stars is a Python/command-line tool that collects the star count from [GitHub
stars](http://github.com/) and produces nice plots from it.

For example, with
are produced with
```
gh-stars nschloe/meshio nschloe/quadpy -m 30 -t file-with-gh-token -o nschloe.svg
```
the plots

[github-nschloe](https://nschloe.github.io/gh-stars/nschloe.svg)

GitHub and has a rate limit so you might want to get a token and provide it to gh-stars.

Install with
```
pip install gh-stars
```
and use the command-line tools as displayed. The `-h` switch gives more details.

## Gallery

A collection of the GitHub stars for of a number of topics.

#### Programming languages
![github-programming-languages](https://nschloe.github.io/gh-stars/github-programming-languages.svg)

#### Version control systems
![github-vcs](https://nschloe.github.io/gh-stars/github-version-control-systems.svg)

#### Front-End frameworks
![github-frontend-frameworks](https://nschloe.github.io/gh-stars/github-frontend-frameworks.svg)

#### Back-End frameworks
![github-backend-frameworks](https://nschloe.github.io/gh-stars/github-backend-frameworks.svg)

#### Browsers
![github-browsers](https://nschloe.github.io/gh-stars/github-browsers.svg)

#### Databases
![github-databases](https://nschloe.github.io/gh-stars/github-databases.svg)

#### JavaScript package managers
![github-javascript-package-managers](https://nschloe.github.io/gh-stars/github-javascript-package-managers.svg)

#### JavaScript testing frameworks
![github-javascript-testing-frameworks](https://nschloe.github.io/gh-stars/github-javascript-testing-frameworks.svg)

#### Text editors
![github-text-editors](https://nschloe.github.io/gh-stars/github-text-editors.svg)

#### Operating systems
![github-operating-systems](https://nschloe.github.io/gh-stars/github-operating-systems.svg)

#### Shells
![github-shells](https://nschloe.github.io/gh-stars/github-shells.svg)

#### Code-hosting platforms
![github-code-hosting-platforms](https://nschloe.github.io/gh-stars/github-code-hosting-platforms.svg)

#### Content-management systems
![github-content-management-systems](https://nschloe.github.io/gh-stars/github-content-management-systems.svg)

#### Continuous-integration services
![github-continuous-integration-services](https://nschloe.github.io/gh-stars/github-continuous-integration-services.svg)

#### Office suites
![github-office-suites](https://nschloe.github.io/gh-stars/github-office-suites.svg)

#### Computer algebra systems
![github-computer-algebra-systems](https://nschloe.github.io/gh-stars/github-computer-algebra-systems.svg)

#### DevOps
![github-devops](https://nschloe.github.io/gh-stars/github-devops.svg)

#### Build systems
![github-build-systems](https://nschloe.github.io/gh-stars/github-build-systems.svg)

#### Machine learning
![github-machine-learning](https://nschloe.github.io/gh-stars/github-machine-learning.svg)

#### Scientific Python
![github-scientific-python](https://nschloe.github.io/gh-stars/github-scientific-python.svg)

#### Python plotting
![github-python-plotting](https://nschloe.github.io/gh-stars/github-python-plotting.svg)

#### Python testing
![github-python-testing](https://nschloe.github.io/gh-stars/github-python-testing.svg)

#### Popular JavaScript packages
![github-popular-javascript](https://nschloe.github.io/gh-stars/github-popular-javascript.svg)


### Related projects

 * [star-history](https://github.com/timqian/star-history)
 * [star-history](https://github.com/dtolnay/star-history)

### License
This software is published under the [GPLv3 license](https://www.gnu.org/licenses/gpl-3.0.en.html).
