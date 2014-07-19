# Rubytest Suite

[Homepage](http://rubyworks.github.com/rubytest) /
[User Guide](http://wiki.github.com/rubyworks/rubytest) /
[Support](http://github.com/rubyworks/rubytest/issues) /
[Development](http://github.com/rubyworks/rubytest)

[![Build Status](https://secure.travis-ci.org/rubyworks/rubytest.png)](http://travis-ci.org/rubyworks/rubytest)
[![Gem Version](https://badge.fury.io/rb/rubytest.png)](http://badge.fury.io/rb/rubytest)


## Description

Rubytest is a universal test harness for Ruby development. Think
of Rubytest as a *testing meta-framework*. It defines a straight-forward
specification that anyone can use to create their own testing DSLs 
quickily and easily. This can be used for testing end applcations or it
can be used by test framework as a backend. In addition, since all Rubytest
controls the backend, multiple frameworks can be used in a single test suite
all of which can run through a single uniform interface in a process.

To learn more about Rubytest see https://rubyworks.github.io/rubytest.

This project is a metapackage which bundles the rubytest gem and a common 
set of plugins for developer convenience. Instead of listing each individual
gem in a project's Gemfile, just add `rubytest-suite`. This package includes
the following gems:

* [rubytest](https://github.com/rubyworks/rubytest)
* [rubytest-cli](https://github.com/rubyworks/rubytest-cli)
* [rubytest-rake](https://github.com/rubyworks/rubytest-rake)
* [rubytest-outline](https://github.com/rubyworks/rubytest-outline)
* [rubytest-progress](https://github.com/rubyworks/rubytest-progress)
* [rubytest-summary](https://github.com/rubyworks/rubytest-summary)

See the various project sites for more details.


## Installation

Rubytest is available as a gem metapackage. Install it manually with:

    $ gem install rubytest-suite

Or add it yo your project's Gemfile.

    gem "rubytest-suite"


## Copyrights

Copyright (c) 2011 Rubyworks

Made available according to the terms of the <b>BSD-2-Clause</b> license.

See LICENSE.txt for details.

