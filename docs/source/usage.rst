Usage
=====

.. _installation:

Installation
------------

To use Skeleton, first install it using pip:

.. code-block:: console

   (.venv) $ pip install skeleton

Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``skeleton.sub1.modA.hello()`` function:

.. autofunction:: skeleton.sub1.modA.hello

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`skeleton.sub1.modA.hello`
will raise an exception.

For example:

>>> import skeleton
>>> skeleton.sub1.modA.hello()
Hello

