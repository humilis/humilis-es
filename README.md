Humilis plug-in to deploy an Elasticsearch domain
===================================================

[![PyPI](https://img.shields.io/pypi/v/humilis-es.svg?style=flat)](https://pypi.python.org/pypi/humilis-es)
[![Build Status](https://travis-ci.org/humilis/humilis-es.svg?branch=master)](https://travis-ci.org/humilis/humilis-es)

A [humilis][humilis] plug-in layer that deploys an
[Elasticsearch][es] domain into a humilis environment.

[es]: https://aws.amazon.com/elasticsearch-service/
[humilis]: https://github.com/InnovativeTravel/humilis


## Installation

```
pip install humilis-es
```


To install the development version:

```
pip install git+https://github.com/humilis/humilis-es
```


## Development

Assuming you have [virtualenv][venv] installed:

[venv]: https://virtualenv.readthedocs.org/en/latest/

```
make develop
```

Configure humilis:

```
make configure
```


## Testing

There is no logic in this layer beyond the deployment of AWS resources so
there is no unit test suite. You can test the deployment of a dummy ES
domain with:

```
make testi
```


## More information

See [humilis][humilis] documentation.

[humilis]: https://github.com//humilis/blob/master/README.md


## Contact

If you have questions, bug reports, suggestions, etc. please create an issue on
the [GitHub project page][github].

[github]: http://github.com/humilis/humilis-es


## License

This software is licensed under the [MIT license][mit].

[mit]: http://en.wikipedia.org/wiki/MIT_License

See [License file][LICENSE].

[LICENSE]: https://github.com/humilis/humilis-es/blob/master/LICENSE.txt


© 2016 German Gomez-Herrero, [Find Hotel][fh] and others.

[fh]: http://company.findhotel.net
