.. :changelog:

Release History
---------------

Next release
++++++++++++++++++

* ???

0.6.2 (2015-07-09)
++++++++++++++++++

* Improvement: Adding continuous space.
* Improvement: Adding a simultaneous activation scheduler.
* New models:
	- Flockers
	- Spatial Demographic Prisoner's Dilemma (PD_Grid)

0.6.1 (2015-06-27)
++++++++++++++++++

* Bug Fix: Order of operations reversed: agent is removed first and then it is placed.
* Improvement: `LICENSE`_ was updates from MIT to Apache 2.0.

.. _`LICENSE` : https://github.com/projectmesa/mesa/blob/master/LICENSE


0.6.0 (2015-06-21)
++++++++++++++++++

* Improvment: Add modular server feature, which breaks up a model into a .py file and a .js file. This breaks backwards compatibility.

Pre 0.6.0
++++++++++++++++++

Code that is pre-0.6.0 is very unstable.

Our inital release was 0.5.0 (2014-11).

It included code for placing agents on a grid; a data collector and batch runner; and a front-end visualization using HTML 5 and JavaScript.

**General**

* Objects create -- Agent, Time, Space
* Project moved to Python 3
* Tornado server setup

**Front-end**

* Front-end grid implemented
* ASCII visualization implemented

**Examples models**

* Forest Fire
* Schelling
* Wolf-Sheep Predation

**0.1.0 (2014-09-19)**

* A conversation
* Birth
