AsyncLupa Changelog
===================

1.0 (2019-12-26)
----------------

* Released AsyncLupa Publicly
* ``AsyncLuaRuntime`` provides async wrappers for ``LuaRuntime.execute``, ``LuaRuntime.compile``, and ``LuaRuntime.eval``
* ``AsyncLuaRuntime`` is used to invoke async functions from Lua ex.

.. code-block:: lua

    ret_val = python.coroutine(python_async_function)
