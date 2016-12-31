FLSDK Nix Meta Package
======================
Meta package to install Development & Runtime dependencies for:

* Comptext
* Comptty
* Flamp
* Fldigi
* Fllog
* Flmsg
* Flnet
* Flrig
* Flwkey
* Flwrap
* Linsim

flsdk-native
----------
Development and Runtime dependencies for all `FLDIGI`_ applications on
suported Linux distributions.

flsdk-wsl
---------
Install all dependencies needed for `MXE`_ cross compiling `FLDIGI`_
applications for Windows-10 Subsystem Linux (WSL).

flsdk-docs
---------
Package to install all dependencies needed for to build manpages, HTML
documentation, and Doxygen docs.

Usage
-----
- Add the PPA repository:

.. code-block:: bash

   sudo add-apt-repository -y ppa:ki7mt/flsdk-meta
   sudo apt-get update

- Install one or more of the meta packages, type the following

.. code-block:: bash
   
   sudo apt-get install flsdk-native
   sudo apt-get install flsdk-wsl
   sudo apt-get install flsdk-docs

Upstream Project
----------------

* Project Manager: Dave (W1HKJ)
* Upstream URL: http://www.w1hkj.com

.. _FLDIGI: https://sourceforge.net/projects/fldigi
.. _MXE: http://mxe.cc/

