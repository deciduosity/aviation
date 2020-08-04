=======================================
``aviation`` -- gRPC Middleware Helpers
=======================================

Overview
--------

Aviation is a set of tools for building services, as a kind of
analogue for what `gimlet <https://github.com/deciduosity/gimlet>`_
does for REST services.

Goals
-----

- provide middleware to support common patterns including logging, recovery,
  middleware.

- support basic authentication mechanism for interoperability with
  gimlet services.

Limitations
-----------

- aviation does not provide client interceptors.

- aviation should not attempt to wrap gRPC in the way that gimlet
  wraps negroni and gorilla mux.

Development and Use
-------------------

Aviation is available under the terms of the Apache License (v2.)

Please see the `godoc for complete documentation of the API
<https://godoc.org/github.com/deciduosity/aviation>`_.

If you encounter an issue with Aviation or have a feature request please open
an issue in the github project.

There's a ``makefile`` which supports development operations: use the ``test``
and ``lint`` targets to validate code when making changes.
