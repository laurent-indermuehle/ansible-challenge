# My Notes

## Spotter venv

```sh
virtualenv --python=python3.11 ~/python-venv/spotter
source ~/python-venv/spotter/bin/activate
pip install \
    ansible-lint \
    ansible==8.5.0 \
    antsibull-changelog \
    argcomplete \
    psutil \
    selinux \
    steampunk-spotter \
    yamllint
```
