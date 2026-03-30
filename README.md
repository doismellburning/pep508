# pep508

This is an "implementation" of [PEP 508 -- Dependency specification for Python Software Packages](https://www.python.org/dev/peps/pep-0508/) as a Python string, for use with a parser like [Parsley](https://github.com/pyga/parsley).

For example:

```python
import parsley
import pep508

parsley.makeGrammar(pep508.grammar, {})
```

For a worked example, see https://github.com/doismellburning/emporium/blob/1ab98ae5b4b7df21cf18f384e5bc3a83522438ce/emporium/emporium/parser.py
