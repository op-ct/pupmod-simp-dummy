**FIXME**: Ensure the badges are correct and complete, then remove this line!

[![License](https://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/73/badge)](https://bestpractices.coreinfrastructure.org/projects/73)
[![Puppet Forge](https://img.shields.io/puppetforge/v/simp/dummy.svg)](https://forge.puppetlabs.com/simp/dummy)
[![Puppet Forge Downloads](https://img.shields.io/puppetforge/dt/simp/dummy.svg)](https://forge.puppetlabs.com/simp/dummy)
[![Build Status](https://travis-ci.org/simp/pupmod-simp-dummy.svg)](https://travis-ci.org/simp/pupmod-simp-dummy)

#### Table of Contents

<!-- vim-markdown-toc GFM -->

* [Description](#description)
  * [This is a SIMP module](#this-is-a-simp-module)
* [Setup](#setup)
  * [What dummy affects](#what-dummy-affects)
  * [Setup Requirements **OPTIONAL**](#setup-requirements-optional)
  * [Beginning with dummy](#beginning-with-dummy)
* [Usage](#usage)
* [Reference](#reference)
* [Limitations](#limitations)
* [Development](#development)
  * [Acceptance tests](#acceptance-tests)

<!-- vim-markdown-toc -->

## Description

Start with a one- or two-sentence summary of what the module does and/or what
problem it solves. This is your 30-second elevator pitch for your module.
Consider including OS and Puppet version compatability, and any other
information users will need to quickly assess the module's viability within
their environment.

You can give more descriptive information in a second paragraph. This paragraph
should answer the questions: "What does this module *do*?" and "Why would I use
it?" If your module has a range of functionality (installation, configuration,
management, etc.), this is the time to mention it.

### This is a SIMP module

This module is a component of the [System Integrity Management
Platform](https://simp-project.com), a compliance-management framework built on
Puppet.

If you find any issues, submit them to our [bug
tracker](https://simp-project.atlassian.net/).

**FIXME:** Ensure the *This is a SIMP module* section is correct and complete, then remove this line!

This module is optimally designed for use within a larger SIMP ecosystem, but
it can be used independently:

 * When included within the SIMP ecosystem, security compliance settings will
   be managed from the Puppet server.
 * If used independently, all SIMP-managed security subsystems are disabled by
   default and must be explicitly opted into by administrators.  Please review
   the parameters in
   [`simp/simp_options`](https://github.com/simp/pupmod-simp-simp_options) for
   details.

## Setup

### What dummy affects

**FIXME:** Ensure the *What dummy affects* section is correct and complete, then remove this line!

If it's obvious what your module touches, you can skip this section. For
example, folks can probably figure out that your mysql_instance module affects
their MySQL instances.

If there's more that they should know about, though, this is the place to
mention:

 * A list of files, packages, services, or operations that the module will
   alter, impact, or execute.
 * Dependencies that your module automatically installs.
 * Warnings or other important notices.

### Setup Requirements **OPTIONAL**

**FIXME:** Ensure the *Setup Requirements* section is correct and complete, then remove this line!

If your module requires anything extra before setting up (pluginsync enabled,
etc.), mention it here.

If your most recent release breaks compatibility or requires particular steps
for upgrading, you might want to include an additional "Upgrading" section
here.

### Beginning with dummy

**FIXME:** Ensure the *Beginning with dummy* section is correct and complete, then remove this line!

The very basic steps needed for a user to get the module up and running. This
can include setup steps, if necessary, or it can be an example of the most
basic use of the module.

## Usage

**FIXME:** Ensure the *Usage* section is correct and complete, then remove this line!

This section is where you describe how to customize, configure, and do the
fancy stuff with your module here. It's especially helpful if you include usage
examples and code samples for doing things with your module.

## Reference

**FIXME:** Ensure the *Reference* section is correct and complete, then remove this line!  If there is pre-generated YARD documentation for this module, ensure the text links to it and remove references to inline documentation.

Please refer to the inline documentation within each source file, or to
[REFERENCE.md](./REFERENCE.md) for generated reference material.

## Limitations

**FIXME:** Ensure the *Limitations* section is correct and complete, then remove this line!

SIMP Puppet modules are generally intended for use on Red Hat Enterprise Linux
and compatible distributions, such as CentOS. Please see the
[`metadata.json` file](./metadata.json) for the most up-to-date list of
supported operating systems, Puppet versions, and module dependencies.

## Development

**FIXME:** Ensure the *Development* section is correct and complete, then remove this line!

Please read our [Contribution Guide](https://simp-doc.readthedocs.io/en/stable/contributors_guide/index.html).

### Acceptance tests

This module includes [Beaker](https://github.com/puppetlabs/beaker) acceptance
tests using the SIMP [Beaker Helpers](https://github.com/simp/rubygem-simp-beaker-helpers).
By default the tests use [Vagrant](https://www.vagrantup.com/) with
[VirtualBox](https://www.virtualbox.org) as a back-end; Vagrant and VirtualBox
must both be installed to run these tests without modification. To execute the
tests run the following:

```shell
bundle install
bundle exec rake beaker:suites[default]
```

**FIXME:** Ensure the *Acceptance tests* section is correct and complete, including any module-specific instructions, and remove this line!

Please refer to the [SIMP Beaker Helpers documentation](https://github.com/simp/rubygem-simp-beaker-helpers/blob/master/README.md)
for more information.
