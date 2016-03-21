# Apéndice 2: Pruebas (Testing)


Una de las fases más importantes en el proceso de desarrollo de software es la fase de pruebas o *tests*, ya que estas permiten comprobar que el software cumple con la correcta funcionalidad que se espera que tenga dada a este por su implementación a partir de su diseño.

Se pueden distinguir varios tipos de pruebas, entre las cuales destacan las _**unitarias**_, las _**funcionales**_ y las _**de integración**_:

* **Pruebas unitarias** (_**Unit Testing**_): Estas pruebas permiten comprobar que una serie de componentes (*unidades*) cumplen completamente su función.
  * http://artofunittesting.com/definition-of-a-unit-test/
  * http://martinfowler.com/bliki/UnitTest.html
  * https://docs.python.org/3/library/unittest.html
* Pruebas funcionales ():
* Pruebas de integración ():

## Pruebas unitarias (Unit Testing)

Python dispone de un módulo incluido de serie (*built-in*)
To achieve this, unittest supports some important concepts in an object-oriented way:

Test fixture

A test fixture represents the preparation needed to perform one or more tests, and any associate cleanup actions. This may involve, for example, creating temporary or proxy databases, directories, or starting a server process.

Test case

A test case is the individual unit of testing. It checks for a specific response to a particular set of inputs. unittest provides a base class, TestCase, which may be used to create new test cases.

Test suite

A test suite is a collection of test cases, test suites, or both. It is used to aggregate tests that should be executed together.

Test runner

A test runner is a component which orchestrates the execution of tests and provides the outcome to the user. The runner may use a graphical interface, a textual interface, or return a special value to indicate the results of executing the tests.