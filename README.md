# Java Development - Day 1 Practicals

## Programs Included
- `SimpleInterest.java` - Calculates simple interest
- `DistanceConverter.java` - Converts km to m and cm
- `SixSubjectsPercentage.java` - Calculates percentage across 6 subjects
- `ArithmeticOperators.java` - Demonstrates arithmetic and increment/decrement operators
- `CompareAges.java` - Compares two ages using relational operators

## Error Encountered & Resolution Note
- **Error:** `Syntax error on token "int", delete this token` and `Type mismatch: cannot convert from double to int` during explicit type casting (`int amount2 = int amount;`).
- **Fix:** Enclosed the target type in parentheses (`int amount2 = (int) amount;`), resolving the compilation error.