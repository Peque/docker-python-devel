docker-python-devel
===================

A Docker image for Python development based on Fedora. Not the slimmest image,
but very convenient when working with Python, CI, Tox and Pipenv.

You can pull the image from Docker Hub:

```
peque/python-devel
```

Available packages:

- Tox
- Pipenv
- Python 2.7
- Python 3.4
- Python 3.5
- Python 3.6
- Python 3.7
- PyPy
- PyPy 3
- Kernel headers
- Python headers
- GCC (with C++ support)
- Make
- Git
- OpenSSH
- POSIX (UTF-8) locale
- Utils: `which`, `curl`, `wget`

Instructions for update (for self-reference):

```bash
docker build --pull -t peque/python-devel .
docker login --username=peque
docker push peque/python-devel
```
