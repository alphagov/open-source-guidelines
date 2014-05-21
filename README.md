This document describes a set of rules and principles for publishing Open Source code that we
explicitly intend to support.

    The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
    "SHOULD NOT", "RECOMMENDED",  "MAY", and "OPTIONAL" in this document are to be
    interpreted as described in RFC 2119.

Projects MUST:

* include a README
* include useful and informative commit messages about why a change was made
* include a CHANGELOG as per https://metacpan.org/module/CPAN::Changes::Spec
* include a valid Open Source LICENSE file as per http://opensource.org/licenses
* provide a link to a public list of known issues and bugs 
* provide an email address to send security related bug reports to
* provide a version number compatible with Semantic Versioning as per http://semver.org/spec/v2.0.0.html

Projects SHOULD:

* publish packages to relevant language specific repositories such as PyPi, Ruby Gems, NPM,
  Puppet Forge, etc.
* publish contributors guidelines in a CONTRIBUTING file
* set up any tests to run in a public continuous integration environment

Projects MAY:

* include a CONTRIBUTORS file, for instance http://golang.org/CONTRIBUTORS
* provide a mailing list for discussion of the project
