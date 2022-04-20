# phpunit-xml-cleanup

A handful of hacky cleanup bits to get the various JUnit XML files from
Civi's test-suites to load into Jenkins.

## Development

* Add new example input files to `examples/input`
* Add new exaple output files to `examples/expected`
* To see the current command produces expected output, use:
    ```
    ./scripts/run-tests.sh
    ```
