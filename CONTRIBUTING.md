Contributing to turboPy
=======================

Thank you for wanting to contribute to turboPy!

Issues
------

Please make use of the Issue Labels when creating issues. This helps us track
and follow the improvements being made to turboPy.

Templates
----------

Use the appropriate template when creating an issue or pull request. Adhere
to the formatting guides within the template to ensure organizational standards
are kept consistent throughout the repo.

Naming Branches
---------------

The naming convention for development branches follows a simple formula:  
`xx-brief-description`  
where `xx = issue ID number` that the branch is addressing. The brief description
should only be a two to three words. Each word should be separated by a hyphen.

Documentation
-------------

Any modules or apps that are created should include documentation, both docstrings
and comments throughout the code. TurboPy uses the 
[`numpydoc` style](https://numpydoc.readthedocs.io) for docstrings,
and we encourage the same style for those contributing to the project. The
documentation is then automatically generated and hosted 
[at ReadTheDocs](https://turbopy.readthedocs.io).

Testing
-------

It is our goal to have tests written for all the python modules in turboPy using
the `pytest` framework. Any python code created should have an accompany test file
in `tests/`

Linting
-------

Within turboPy, we strive to keep our code readable and inline with the PEP8
standards. We highly recommend using `pylint` or something similar to check
any code.  
As noted in the README.md, if using `pylint`, add `variable-rgx=[a-z0-9_]{1,30}$`
to your .pylintrc file to allow single character variable names.


Pull Requests
-------------

When making a pull request, the title should be a brief description, similar to the
branch name. If you're planning to make more changes to that branch, then add `[WIP]`
to the beginning of the title and make a draft pull request. Once you are ready to 
merge your contribution, remove `[WIP]` from the name and convert from "draft" pull 
request to "regular" by clicking the "Ready for review" button.
