Introduction
============

``pattoo`` is a timeseries data store. It was inspired by the need to collect and visualize data from various DevOps, network, industrial PLC controllers, electro-mechanical and enterprise systems.

Its modular design facilitates the creation of custom data collection agents and web interfaces by software developers.

The ``pattoo-agents`` repository provides a number standard data collection agents for:

* Linux
* SNMP
* Modbus
* Bacnet

Operational Overview
--------------------

``pattoo`` handles data in three steps.

#. ``pattoo-agents`` collect data and send it to a central ``pattoo`` server in a standardized format.
#. The ``pattoo`` server stores the agent data.
#. The ``pattoo`` web application can be used to visualize the data in a chart format.

Pattoo Web Objective
--------------------

Pattoo Web is a web application you can use to view collected data.


Related Documentation
---------------------

There are a number of sets of documents that cover the ``pattoo`` portfolio.

Pattoo
~~~~~~
This is data collection server that acts as the central repository of data provided by the ``pattoo`` agents.

* The `Pattoo Server documentation <https://pattoo.readthedocs.io/>`_ can be found here.
* Visit the `Pattoo Server GitHub site <https://github.com/PalisadoesFoundation/pattoo>`_ to see the code.

Pattoo-Agents
~~~~~~~~~~~~~
The ``pattoo`` agents collect data from a variety of sources and send them to the central ``pattoo`` server over HTTP. We provide a few standard agents, but you can create your own. (See Pattoo-Shared for details)

* The `Pattoo Agents documentation <https://pattoo-agents.readthedocs.io/>`_ can be found here.
* Visit the `Pattoo Agents GitHub site <https://github.com/PalisadoesFoundation/pattoo-agents>`_ to see the code.

Pattoo-Web
~~~~~~~~~~
The web front end for viewing ``pattoo`` agent data.

* The `Pattoo Web documentation <https://pattoo-web.readthedocs.io/>`_ can be found here.
* Visit the `Pattoo Web GitHub site <https://github.com/PalisadoesFoundation/pattoo-web>`_ to see the code.

Pattoo-Shared
~~~~~~~~~~~~~
Both the ``pattoo`` agents and server use a shared python library which must be pre-installed using ``pip3`` for them to work.

You can use the ``pattoo-shared`` documentation to learn the basics of creating your own custom ``pattoo-agents`` to feed data to the ``pattoo`` server

* The `Pattoo Shared documentation <https://pattoo-shared.readthedocs.io/>`_ can be found here.
* Visit the `Pattoo Shared GitHub site <https://github.com/PalisadoesFoundation/pattoo-shared>`_ to see the code.
