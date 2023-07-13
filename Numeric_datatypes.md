
| Data Type | Description | Example | Memory | Range |
|-----------|-------------|---------|--------|-------|
| INT | Integer values | 1, 0, -5 | 4 bytes | -2147483648 to 2147483647 (signed) or 0 to 4294967295 (unsigned) |
| BIGINT | Large integer values | 1234567890123456789 | 8 bytes | -9223372036854775808 to 9223372036854775807 (signed) or 0 to 18446744073709551615 (unsigned) |
| SMALLINT | Small integer values | 100, -50, 0 | 2 bytes | -32768 to 32767 (signed) or 0 to 65535 (unsigned) |
| TINYINT | Very small integer values | 10, -5, 0 | 1 byte | -128 to 127 (signed) or 0 to 255 (unsigned) |
| NUMERIC (p,s) | Exact numeric values with fixed precision and scale | 123.45 | Depends on precision and scale | -10^(p-s)-1 to 10^(p-s)-1 (signed) or 0 to 10^(p-s)-1 (unsigned) |
| DECIMAL (p,s) | Exact numeric values with fixed precision and scale | 123.45 | Depends on precision and scale | -10^(p-s)-1 to 10^(p-s)-1 (signed) or 0 to 10^(p-s)-1 (unsigned) |
| FLOAT (p) | Approximate numeric values with floating-point representation | 3.14159E+10 | 4 bytes | -3.402823466E+38 to -1.175494351E-38, 0, and 1.175494351E-38 to 3.402823466E+38 |
| REAL (p) | Approximate numeric values with floating-point representation | 3.14159E+10 | 8 bytes | -1.7976931348623157E+308 to -2.2250738585072014E-308, 0, and 2.2250738585072014E-308 to 1.7976931348623157E+308 |

Note: p is the precision and s is the scale.


