========================
Team and repository tags
========================

.. image:: http://governance.openstack.org/badges/openstack-doc-tools.svg
    :target: http://governance.openstack.org/reference/tags/index.html

.. Change things from this point on

OpenStack Doc Tools
*******************

This repository contains tools used by the OpenStack Documentation
project.

For more details, see the `OpenStack Documentation Contributor Guide
<http://docs.openstack.org/contributor-guide/>`_.

Prerequisites
=============

You need to have Python 2.7 installed for using the tools.

This package needs a few external dependencies including lxml. If you
do not have lxml installed, you can either install python-lxml or have
it installed automatically and build from sources. To build lxml from
sources, you need a C compiler and the xml and xslt development
packages installed.

To install python-lxml, execute the following based on your
distribution.

On Fedora, RHEL 7, and CentOS 7::

    $ yum install python-lxml

On openSUSE::

    $ zypper in python-lxml

On Ubuntu::

    $ apt-get install python-lxml

For building from source,  install the dependencies of lxml.

On Fedora, RHEL 7, and CentOS 7::

    $ yum install python-devel libxml2-devel libxslt-devel

On openSUSE::

    $ zypper in libxslt-devel

On Ubuntu::

    $ apt-get install libxml2-dev libxslt-dev


* License: Apache License, Version 2.0
* Source: https://git.openstack.org/cgit/openstack/openstack-doc-tools
* Bugs: https://bugs.launchpad.net/openstack-doc-tools


Regenerating config option tables
=================================

See :ref:`autogenerate_config_docs`.
