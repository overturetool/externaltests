external tests
===

This repository contains the external tests for Overture. The folders are organised as follows:

* cgip: tests for the Interpreter
* pog: tests for the POG
* tc: tests for the Type-Checker
* skip: tests that are not run

each folder has subfolders [sl/pp/rt]test that hold the test files for the respective dialect.

To run these tests, use `mvn test -DexternalTestsPath=/path/to/tests`
