---
title: NotAnExpr
layout: article
---
<!-- Copyright 2023 The Go Authors. All rights reserved.
     Use of this source code is governed by a BSD-style
     license that can be found in the LICENSE file. -->

<!-- Code generated by generrordocs.go; DO NOT EDIT. -->

```
NotAnExpr occurs when a type expression is used where a value expression
is expected.

Example:
 type T struct {}

 func f() {
 	T
 }
```

