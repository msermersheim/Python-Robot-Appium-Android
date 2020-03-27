## Python-Robot-Appium-Android

*NOTE*: This repository is now deprecated. Please see the [Demo Python](https://github.com/saucelabs-training/demo-python) project for up-to-date code samples.

This code is provided on an "AS-IS” basis without warranty of any kind, either express or implied, including without limitation any implied warranties of condition, uninterrupted use, merchantability, fitness for a particular purpose, or non-infringement. Your tests and testing environments may require you to modify this framework. Issues regarding this framework should be submitted through GitHub. For questions regarding Sauce Labs integration, please see the Sauce Labs documentation at https://wiki.saucelabs.com/. This framework is not maintained by Sauce Labs Support.

### Environment Setup

1. Global Dependencies
    * [Install Python](https://www.python.org/downloads/)
    * Or Install Python with [Homebrew](http://brew.sh/)
    ```
    $ brew install python
    ```
    * Install [pip](https://pip.pypa.io/en/stable/installing/) to install packages

2. Sauce Credentials
    * In the terminal export your Sauce Labs Credentials as environmental variables:
    ```
    $ export SAUCE_USERNAME=<your Sauce Labs username>
	$ export SAUCE_ACCESS_KEY=<your Sauce Labs access key>
    ```
3. Project Dependencies
	* Install packages (Use sudo if necessary)
	```
	$ pip install sauceclient robotframework robotframework-appiumlibrary robotframework-selenium2library
	```
### Running Tests

Tests in Parallel:
	```
	$ make run_all_in_parallel
	```

[Sauce Labs Dashboard](https://saucelabs.com/beta/dashboard/)

### Resources
##### [Sauce Labs Documentation](https://wiki.saucelabs.com/)

##### [Robot AppiumLibrary Documentation](http://jollychang.github.io/robotframework-appiumlibrary/doc/AppiumLibrary.html)

##### [Python Documentation](https://docs.python.org/2.7/)

##### [Robot Framework Documentation](http://robotframework.org/#documentation)

##### [Stack Overflow](http://stackoverflow.com/)
* A great resource to search for issues not explicitly covered by documentation.

### Known Issues
##### We do not recommend using xpath to locate elements. 