================
FunctionNodeBody
================
**[req.function_node_body]**

A type `Body` satisfies `FunctionNodeBody` if it meets the following requirements:

----------------------------------------------------------------------

**FunctionNodeBody Requirements: Pseudo-Signature, Semantics**

.. cpp:function:: Body::Body( const Body& )

    Copy constructor.

.. cpp:function:: Body::~Body()

    Destructor.

.. cpp:function:: void operator=( const B& )

    Assignment.

.. cpp:function:: Output Body::operator()( const Input& v )

    **Requirements:** The ``Input`` and ``Output`` types must be the same as the ``Input`` and ``Output``
    template type arguments of the ``fucntion_node`` instance in which the ``Body`` object is passed
    during construction.

    Performs operation on ``v`` and returns a value of type ``Output``.
  

