
.. xclass:: datatable.Type
    :src: src/core/types/py_type.h PyType
    :cvar: doc_Type

    .. x-version-added:: 1.0.0

    Type of data stored in a single column of a Frame.

    The type describes both the logical meaning of the data (i.e. an integer,
    a floating point number, a string, etc.), as well as storage requirement
    of that data (the number of bits per element). Some types may carry
    additional properties, such as a timezone  or precision.

    .. note::

        This property replaces previous :class:`dt.stype` and :class:`dt.ltype`.


    Values
    ------
    The following types are currently available:

    - :meth:`dt.Type.arr32(T)`
    - :meth:`dt.Type.arr64(T)`
    - :attr:`dt.Type.bool8`
    - :attr:`dt.Type.date32`
    - :attr:`dt.Type.float32`
    - :attr:`dt.Type.float64`
    - :attr:`dt.Type.int16`
    - :attr:`dt.Type.int32`
    - :attr:`dt.Type.int64`
    - :attr:`dt.Type.int8`
    - :attr:`dt.Type.obj64`
    - :attr:`dt.Type.str32`
    - :attr:`dt.Type.str64`
    - :attr:`dt.Type.time64`
    - :attr:`dt.Type.void`


    Properties
    ----------
    .. list-table::
        :widths: auto
        :class: api-table

        * - :attr:`.max`
          - The maximum value for this type

        * - :attr:`.min`
          - The minimum value for this type

        * - :attr:`.name`
          - The name of this type


.. toctree::
    :hidden:

    ⭑ arr32(T)  <type/arr32>
    ⭑ arr64(T)  <type/arr64>
    ⭑ bool8     <type/bool8>
    ⭑ date32    <type/date32>
    ⭑ float32   <type/float32>
    ⭑ float64   <type/float64>
    ⭑ int8      <type/int8>
    ⭑ int16     <type/int16>
    ⭑ int32     <type/int32>
    ⭑ int64     <type/int64>
    ⭑ obj64     <type/obj64>
    ⭑ str32     <type/str32>
    ⭑ str64     <type/str64>
    ⭑ time64    <type/time64>
    ⭑ void      <type/void>
    max         <type/max>
    min         <type/min>
    name        <type/name>
