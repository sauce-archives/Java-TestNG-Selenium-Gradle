# Java-TestNG-Selenium-Gradle

This code is provided on an "AS-IS” basis without warranty of any kind, either express or implied, including without limitation any implied warranties of condition, uninterrupted use, merchantability, fitness for a particular purpose, or non-infringement. Your tests and testing environments may require you to modify this framework. Issues regarding this framework should be submitted through GitHub. For questions regarding Sauce Labs integration, please see the Sauce Labs documentation at https://wiki.saucelabs.com/. This framework is not maintained by Sauce Labs Support.

# Setup
* Install Gradle 4.7

# Variables
* Set Sauce Labs credentials
```
$export SAUCE_USERNAME=<sauce username>
$export SAUCE_ACCESS_KEY=<sauce access key>
$export BUILD_TAG=<optional build id>
```

# Test Environment
* Set desired capabilities [Sauce Labs Platform Configurator](https://wiki.saucelabs.com/display/DOCS/Platform+Configurator)
```
$export SELENIUM_BROWSER=<browser name>
$export SELENIUM_VERSION=<browser version>
$export SELENIUM_PLATFORM=<platform name>
```

# Run Tests
* Run the gradle task as shown below
```
$./gradlew clean test
```

### Resources

##### [Sauce Labs Documentation](https://wiki.saucelabs.com/)

##### [TestNg Documentation](http://testng.org/javadocs/index.html)

##### [Java Documentation](https://docs.oracle.com/javase/7/docs/api/)

##### [SeleniumHQ Documentation](http://www.seleniumhq.org/docs/)

##### [Gradle Documentation](http://gradle.org/documentation/)

##### [Stack Overflow](http://stackoverflow.com/)
* A great resource to search for issues not explicitly covered by documentation.