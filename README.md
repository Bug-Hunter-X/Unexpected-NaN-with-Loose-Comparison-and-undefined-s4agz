# JavaScript Loose Comparison Bug

This repository demonstrates a common error in JavaScript stemming from loose comparison (==) with null and undefined.  The `foo` function aims to return 0 when input is null, but it fails to explicitly handle `undefined`, resulting in `NaN`. This highlights the importance of strict equality (===) for reliable null/undefined checks.