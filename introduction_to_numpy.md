# Introduction to NumPy
Table of contents
=================

* [Numpy Standard Data Types](#numpy-standard-data-types)


NumPy Standard Data Types
-------------------------
Numpy arrays contain values of a single type, so it is important to have detailed knowledge of those
types and their limitations. Because NumPy is Built in C, the types will be familiar to users of C,
			Fortan, and other related languages.

**Table 2-1 show data types with their description**

| Data type | Description  |
| :---------- | :---------------- |
| bool_  | Boolean( True of False ) stored as a byte |
| int_ | Default integer type(same as C long; normally either int64 or int32) |
| intc | Identical to C int(normally int32 or int64) |
| intp | Integer used for indexing (same as C ssize_t; normally either int32 or int64) |
| int8 | Byte(-128 to 127) |
| int16 | Integer(-32768 to 32767) |
| int32 | Integer(-2147483648 to 2147483647) |
| int64 | Integer(-9223372036854775808 to 9223372036854775807) |
| unt8 | Byte(0 to 255) |
| unt16 | Integer(0 to 65535) |
| unt32 | Integer(0 to 4294967295) |
| unt64 | Integer(0 to 18446744073709551615) |
| float_ | Shorthand for float64 |
| float16 | ShorthandHalf-precision float:sign bit, 5 bits exponent, 10 bit mantissa |
| float32 | Single-precision float:sign bit, 8 bits exponent, 23 bit mantissa |
| float64 | Double-precision float:sign bit, 11 bits exponent, 52 bit mantissa |
| complex_ | Shorthand for complex128 | 
| complex64 | Complex number, represented by two 32-bit floats | 
| complex128 | Complex number, represented by two 64-bit floats | 

The basics of NumPy Arrays
--------------------------
* [Attributes of arrays](#numpy-array-attributes)
* [Indexing of arrays](#array-indexin-gaccessing-single-elements)
* [Slicing of arrays](#array-slicing)
* [Reshaping of arrays](#reshaping-of-arrays)
* [Joining and splitting of arrays](#array-concatenation-and-splitting)


