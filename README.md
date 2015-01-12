# speclj-growl

speclj-junit is a plugin for [speclj](http://speclj.com/) that formats output using ant's junit xml format. This format is commonly used by continuous integration tools.

## Installation

If you use [leiningen](https://github.com/technomancy/leiningen), add the following to your project.clj under the :dev profile:

    :dependencies [[speclj-junit "0.0.5"]]

As of version 0.0.1, speclj 2.7.x is required.

## Usage

Add `-f junit` to lein spec to output spec results in Ant's [JUnitReport task](https://ant.apache.org/manual/Tasks/junitreport.html) format.

    lein spec -f junit

##

Many thanks to Paul Gross for his [speclj-growl](https://github.com/pgr0ss/speclj-growl) project for a great example of writing speclj plugins.

## License

Copyright (C) 2015 Julias Shaw

Distributed under the The MIT License.
