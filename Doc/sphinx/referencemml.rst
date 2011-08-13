.. _mmlref:

MML Reference
=============

The Mufasa Macro Library is the core library of Simba. It is used not just to
provide scripts with the required functionality, but also used to pick colours
and select windows with Simba itself. The MML can run without any user
interface.

There currently is an effort to create a standalone library of the MML; called
*libMML*. This way any application can just load the library and use the MML
functionality.

The MML is split up in "Core" classes and "Addon" classes.

.. note::
    This section needs to explain more on the core/addon differences,
    and provide some more general info about the mml.

.. toctree::
    :maxdepth: 2

    mmlref/client.rst
    mmlref/iomanager.rst
    mmlref/finder.rst
    mmlref/bitmap.rst
    mmlref/ocr.rst
    mmlref/libmml
