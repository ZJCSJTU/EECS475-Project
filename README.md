# eecs475-project

## Instructions
In project root directory, create Python3 virtual environement.
```shell
$ python3 -m venv env
$ source env/bin/activate
$ which python  # check the python environment
  <project directory>/env/bin/python
```
Install the package ```substr_enc```.
```shell
$ pip install -e substr_enc
```
Run python unit tests.
```shell
$ pytest -v
```

## Group Members
- Enhao Zhang
- Jiayi Fang
- Zhiqi Chen
- Jiangchen Zhu

## Proposal
We are going to build a software that implements the Substring-Searchable
Symmetric Encryption. Further, in the software we will simulate a client-and-server
interaction where client queries a string and server returns the result using this
encryption scheme. We will also discuss the efficiency and security of this encryption.

The encryption we will implement is based on this [paper](https://eprint.iacr.org/2014/638.pdf
).
