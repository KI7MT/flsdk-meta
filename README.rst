FLSDK Nix Meta Package
======================
Meta package to install Development & Runtime dependencies for:

* Fldigi
* Flamp
* Flmsg
* Flrig
* Flwkey
* Fllog
* Flnet
* Flwrap
* Linsim
* Comptty
* Comptext

flsdk-meta
----------
Development and Runtime dependencies for all `FLDIGI`_ applications.

flsdk-mxe
---------
Experimental package to install all dependencies needed for `MXE`_ cross compiling `FLDIGI`_ applications for Windows.

Usage
-----
- Add the PPA repository:

.. code-block:: bash

   sudo add-apt-repository -y ppa:ki7mt/fldigi
   sudo apt-get update

- Install one or more of the meta packages, type the following

.. code-block:: bash
   
   sudo apt-get install flsdk-meta
   sudo apt-get install flsdk-mxe

Upstream Project
----------------

* Project Manager: Dave (W1HKJ)
* Upstream URL: http://www.w1hkj.com

.. _FLDIGI: https://sourceforge.net/projects/fldigi
.. _MXE: http://mxe.cc/


