EntityLib
=========

A persistent `object` system.

# Specification

Specified here are basic prinicipals for the library.

* Every this is an `object`
* Basic data types are:
  * `boolean`; can be `true` or `false`
	* `integer`
	* `id`; an `integer` with auto-generated value
	* `decimal`
	* `date`
	* `timeofday`
	* `timestamp`; `date` + `timeofday`
	* `text`
	* `binary`
	* `list`
	* `map`; an associative `list`
* Type can COPY from one or more types
* Type can compose one or more types
* Type can have one or more annotations

A user friendly interface is required to provide CRUD facilities for types

# Clojure

## Why Clojure

* I want to learn lisp. This is my entry point.
* It is hosted on jvm. So, it's cross platform.
* Java libraries are accessible through Clojure, so I can use a whole lot of libraries.

