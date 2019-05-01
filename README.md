# reference_value_pair

The reference value pair combines an entity reference with a free text value field in one new field type.
Site builders often end up using field collection or entity reference modules when all they want to do is store a value and a reference (e.g. to a taxonomy term).
This module bundles the two things, a reference to some entity and a value together in one field. It can reference any entity, the value field is a simple text field.

One typical use is storing a measurement with its unit where the units are stored in a taxonomy (e.g 50 liter, 20 cm, 80 %).
