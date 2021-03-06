## Change log
----------------------

Version 1.7-SNAPSHOT
-------------

Version 1.6
-------------

ADDED:

- new consumer functional interface ThrowableNoArgumentConsumer that provide a method that can
  handle checked exceptions with no argument
- new method in RuntimeExceptionDecorator that can handle methods with void return
- new test dependency file-worker in version 5.7

CHANGED:

- update of gradle to new version 6.8.1
- update of com.github.ben-manes.versions.gradle.plugin to new version 0.36.0

Version 1.5
-------------

CHANGED:

- update of gradle version to 6.7
- update of test dependency testng to new version 7.3.0
- moved method ThrowableExtensions#toRuntimeExceptionIfNeeded to appropriate
  RuntimeExceptionDecorator class with a new name decorate
- changed to new package io.github.astrapi69
- removed deprecated methods

Version 1.4
-------------

ADDED:

- new class RuntimeExceptionDecorator that can decorate checked Exception with RuntimeException
- new class ExceptionExtensions that provides methods for convert exceptions to readable string
  objects with out throwing IOExceptions

CHANGED:

- update of gradle version to 6.5.1
- extracted project properties to gradle.properties

Version 1.3
-------------

CHANGED:

- removed lombok dependency
- removed all lombok dependent imports

Version 1.2.1
-------------

CHANGED:

- gradle version downgraded to 5.6.4

Version 1.2
-------------

ADDED:

- new consumer functional interface that provide a method that can handle checked exceptions
- new method that creates a consumer that can handle checked exceptions

CHANGED:

- migrate to gradle build system
- removed all maven related files

Version 1.1
-------------

ADDED:

- new factory method for create a custom message from a given Throwable with additional infos

CHANGED:

- update of parent version to 5

Version 1
-------------

ADDED:

- added new utility class for get the result of a stacktrace as string
- new CHANGELOG.md file created

Notable links:
[keep a changelog](http://keepachangelog.com/en/1.0.0/) Don’t let your friends dump git logs into
changelogs
