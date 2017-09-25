<h1 align="center">An Introduction To The World of Testing for Front-End Developers</h1>

Speaker: [Haris Mahmood](https://twitter.com/harismahmood89)

`liniting`

* linting tools enforce defined style rules
* ensures better readability
* highlight issues (particularly sytax errors)
* `eslint`

`test tools + concepts`

* i. testing structure
* ii. assertions
* iii. spy
* iv. stubs
    * Allow you to replace funcitons with our own to ensure a behaviour
* v. code coverage
* vi. generate + display tests

`test types`
* unit tests
    * test individual functions/classes. pass in inputs and ensure expected output is desired
* integration tests
    * test several functions/module/components
* functional tests
    * test a scenario on that app/product
* snapshot tests
    * compare resulting data to an expected one. super useful for component structure testing

`keep in mind`
* start w/ unit tests. they are often quite often easier to write
* use a coverage tool
* have unit, and integration tests
* snapshot tests can be alternative to ui-based integration tests
* use the same tools for all your tests if possible
    * testing structure, syntax, assertion function, result reporting, etc.

`choosing a framework`
* pick a testing framework
    * jasmine
        * provides everything you need out of the box - running environment reporting, etc.
        * extremely popular in the `angular` world
    * mocha
        * relies on 3rd party libraies and tools for assertions, etc
        * little harder to set up but flexible
    * jest
        * build and recommended by facebook
        * wraps jasmine, and adds features on top
        * super impressive speeds and convenience
        * mainly used for react apps, but can be used elsewhere too
    * instanbul
    * karma
    * chai
    * enzyme
    * sinon
        * provides spies, stubs and mocks
