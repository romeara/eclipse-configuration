# Ryan's Workspace Mechanic Preferences

Contains definitions and JSON file for workspace mechanic tasks which perform basic workspace preference setup

# Tasks

The tasks provided by ryan-settings.json do the following

## code_templates.epf

Adds two code templates to the set of standard insertable templates:

* slf4j-logger
    * Inserts a static slf4j logger instance statement into the file
* test-unimplemented
    * Inserts a TestNG test with an Assert.fail() as its content (prevents false passing, unimplemented tests)

## new_method_unsupported.epf

Changes the default code tempale for generated methods from a TODO and standard value return to a TODO and an unsupported operation exception

## type_filters.epf

Adds entries to the ignore set for suggested imports for the following packages:

* com.beust.jcommander.*
* com.sun.org.apache.*
* org.testng.collections.*
* org.testng.internal.*

## window_focus.epf

Sets the Servers, TestNG, and Console windows to not be forcibly brought to the top of a multi-window set when they complete a task. Also doubles the default number of lines kept in the console from 8000 to 16000

# Additional Files

There are few other Eclipse files available

## dictionary

The file in this directory can be configured as the custom Eclipse dictionary so it will stop flagging certain things as mispelled

## templates

The file(s) in this directory can be imported as code templates - the about task does not always work
