# Match Library for SCPL

Pattern matching and type checking utilities.

## Usage

```scpl
import match

set: x 42

match: x 'number'       -- true
match: x 'positive'     -- true
match: x 'even'         -- true
match: x 42             -- True
match: x 'string'       -- false

set: name 'SCPL'
match: name 'any'       -- true
match: name 'string'    -- true 
```
