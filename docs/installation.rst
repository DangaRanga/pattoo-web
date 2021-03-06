
Basic Installation
==================

This section covers some key steps to get you started.

Prerequisites
-------------

There are some software components that need to be installed prior to starting.

#. `pattoo-web` requires that you use `npm` or `yarn` to install the various

Installation
------------

Follow these steps.

#. Make sure you have a fully configured ```pattoo``` server as this is a ``pattoo-web`` pre-requisite.

Follow these steps.

#. Install ``git`` on your system.
#. Select and create the parent directory in which you want to install ``pattoo-web``.

    .. code-block:: bash

       $ mkdir -p /installation/parent/directory
       $ cd /installation/parent/directory

#. Clone the repository to the parent directory using the ``git clone`` command. You can also choose to downloading and unzip the file in the parent directory. The repository can be found at: https://github.com/PalisadoesFoundation/pattoo-web

    .. code-block:: bash

       $ cd /installation/parent/directory
       $ git clone https://github.com/PalisadoesFoundation/pattoo-web.git

#. Enter the ``/installation/parent/directory/pattoo-web`` directory with the ``pattoo-web`` files.
#. Run ``npm install`` or ``yarn install`` to install dependencies

Testing
-------

All tests are done through `jest` and `react-testing-library`.

To run all tests either run:
    * ``npm test``
    * ``yarn test``
