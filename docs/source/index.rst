Blaze
=====

Blaze is the next generation of NumPy, Python’s extremely popular
array library. Blaze is designed to handle out-of-core computations
on large datasets that exceeds the system memory capacity, as well as
distributed and streaming data.

Blaze will allow analysts and scientists to productively write robust
and efficient code, without getting bogged down in the details of how
to distribute computation, or worse, how to transport and convert data
between databases, formats, proprietary data warehouses, and other
silos.

The core of Blaze is a generic N-dimensional Array and Table objects
with an associated type system for expressing all kinds of data
types and layouts; especially semi-structured, sparse, and columnar
data. Blaze’s generalized calculation engine can iterate over the
distributed array or table and dispatch to low-level kernels specialized
for the layout and type of the data.

Overview
~~~~~~~~

.. toctree::
   :maxdepth: 2

   install
   quickstart
   overview
   datashape
   memory
   format

API Reference
~~~~~~~~~~~~~

.. toctree::
   :maxdepth: 1

   types
   persistence
   layout
   sources
   graph
   ops
   typechecker
   table
   execution
   releases
   legal

Index
~~~~~

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`