# CPSC 310 D1 Public Suite

This is the public test suite for CPSC310 [Deliverable 1](https://github.com/ubccpsc/310/blob/2016sept/project/Deliverable1.md). It also contains the data file you will use for testing and developing your D1 implementation.

### Configure Environment

1. Clone your project repo from Github.

1. Rename the project repo to ```cpsc310project```.

1. Clone this repo.

1. The ```cpsc310project``` repo and this repo (```cpsc310d1-pub_teamXXX```) should have the same parent directory.

### Prepare project

1. Make sure ```cpsc310project``` is configured and built. 

1. ```cd``` into this repository:

1. ```npm run clean``` (or ```npm run cleanwin```)

1. ```npm run configure``` (or ```npm run configurewin```)

1. ```npm run build```

### Run integration tests

* Test: ```npm run test``` (or ```npm run testwin```)
* Test w/ JSON/HTML output ```npm run testprog``` (or ```npm run testprogwin```) HTML report: ```./mochawesome-reports/```

You can also run the tests as a Mocha target inside your favourite IDE.

## Caveats

Remember: this is an integration test suite. It will not be super easy to debug specific code failures with this suite, but will be helpful to make sure you are on the right path for executing against the private suite (which will contain all of these tests and more). Your best bet remains to extend your own unit test suite within your project repository.
