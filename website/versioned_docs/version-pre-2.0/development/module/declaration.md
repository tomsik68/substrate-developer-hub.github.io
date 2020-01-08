---
title: Declaring a Module
id: version-pre-2.0-declaration
original_id: declaration
---

Each Substrate runtime module is defined by a single struct called `Module` which implements the traits needed to execute the module.

In addition, the `Module` struct implements all dispatchable and internal functions which define the runtime logic.

## Declaring a Module

The `Module` struct is generated by the 