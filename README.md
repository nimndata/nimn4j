# nimn4j
Java Serializer for Nimn data format

## Requirement

We've to write a Java serializer which can serialize Java object into Nimn data format just like some JSON serializer and can parse it back.

**Package name**: `in.nimn`

* While serialization / de-serialization it should take care of transient and static fields.
* It should support all premitive data types, list, maps, arrays, objects, and enum.
* There should be a task manager like maven, gradel etc which can help to build artifacts and versioning. 

Things to take care

* Order of the fields is important in Nimn format. Since developers can add and delete fields without taking care of order, we've to come up with some effective solution. 

Performance and Unit tests are important.

### Important links

* Nimn [specifications](https://github.com/nimndata/spec/blob/master/SPEC.md)
* [JS implementation](https://github.com/nimndata/nimnjs)
