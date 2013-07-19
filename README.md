This document describes a set of rules and principles for publishing Open Source code that we
explicitly intend to support.

    The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
    "SHOULD NOT", "RECOMMENDED",  "MAY", and "OPTIONAL" in this document are to be
    interpreted as described in RFC 2119.

Projects MUST:

* Include a README
* Include useful and informative commit messages about why a change was made
* Include a CHANGELOG as per https://metacpan.org/module/CPAN::Changes::Spec
* Include a valid Open Source LICENSE file as per http://opensource.org/licenses
* Provide a link to a public list of known issues and bugs 
* Provide an email address to send security related bug reports to
* Provide a version number compatible with Semantic Versioning as per http://semver.org/spec/v2.0.0.html

Projects SHOULD:

* Publish packages to relevant language specific repositories such as PyPi, Ruby Gems, NPM,
  Puppet Forge, etc.
* Publish contributors guidelines in a CONTRIBUTING file
* Set up any tests to run in a public continuous integration environment

Projects MAY:

* Include a CONTRIBUTORS file, for instance http://golang.org/CONTRIBUTORS
* Provide a mailing list for discussion of the project

