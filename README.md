# scikit-dda
Scikit-learn-compatible Deep Discriminant Analysis

## Status
[![Build Status](https://travis-ci.com/daviddiazvico/scikit-dda.svg?branch=master)](https://travis-ci.com/daviddiazvico/scikit-dda)
[![Maintainability](https://api.codeclimate.com/v1/badges/a37c9ee152b41a0cb577/maintainability)](https://codeclimate.com/github/daviddiazvico/scikit-dda/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/a37c9ee152b41a0cb577/test_coverage)](https://codeclimate.com/github/daviddiazvico/scikit-dda/test_coverage)

## Installation
Available in [PyPI](https://pypi.python.org/pypi?:action=display&name=scikit-dda)
```
pip install scikit-dda
```

## Documentation
Autogenerated and hosted in [GitHub Pages](https://daviddiazvico.github.io/scikit-dda/)

## Distribution
Run the following command from the project home to create the distribution
```
python setup.py sdist bdist_wheel
```
and upload the package to [testPyPI](https://testpypi.python.org/)
```
twine upload --repository-url https://test.pypi.org/legacy/ dist/*
```
or [PyPI](https://pypi.python.org/)
```
twine upload dist/*
```

## Citation
If you find scikit-dda useful, please cite it in your publications. You can use this [BibTeX](http://www.bibtex.org/) entry:
```
@misc{scikit-dda,
      title={scikit-dda},
      author={Diaz-Vico, David},
      year={2019},
      publisher={GitHub},
      howpublished={\url{https://github.com/daviddiazvico/scikit-dda}}}
```