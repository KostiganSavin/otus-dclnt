# DCLNT
Dclnt is a static analysis tool for python code that gets function names form project and counts most common verb for function names.

### Example

From command line:
```bash
$ python dclnt.py
total 20 files
trees generated
functions extracted
total 20 files
trees generated
total 5131 words, 560 unique
('get', 31) 1
('make', 10) 1
('add', 9) 1
('find', 6) 1
('run', 3) 1
('save', 3) 1
('do', 2) 1
('finalize', 1) 1
```

### Installation

With pip:
```bash
pip install git+https://github.com/KostiganSavin/otus-dclnt.git
```

Or just clone the project and install the requirements:
```bash
$ git clone https://github.com/KostiganSavin/otus-dclnt.git
$ cd otus-dclnt
$ pip install -r requirements.txt
```

### Contributing

To contribute, [pick an issue](https://github.com/KostiganSavin/otus-dclnt/issues) to work on and leave a comment saying
that you've taken the issue. Don't forget to mention when you want to submit the pull request.

### Launch tests
`python -m pytest`

### Versioning
We follow [semantic versioning](https://github.com/dbrock/semver-howto/blob/master/README.md).
