---
warning:     "This is a dynamically generated file. Do not edit manually."
layout:      "default"
title:       "avoid-call-value | Solhint"
date:        "Wed, 19 Feb 2020 23:51:52 GMT"
author:      "Franco Victorio <victorio.franco@gmail.com>"
---

# avoid-call-value
![Recommended Badge](https://img.shields.io/badge/-Recommended-brightgreen)
![Category Badge](https://img.shields.io/badge/-Security%20Rules-informational)
![Default Severity Badge warn](https://img.shields.io/badge/Default%20Severity-warn-yellow)
> The {"extends": "solhint:recommended"} property in a configuration file enables this rule.


## Description
Avoid to use ".call.value()()".

## Options
This rule accepts a string option of rule severity. Must be one of "error", "warn", "off". Default to warn.

### Example Config
```json
{
  "rules": {
    "avoid-call-value": "warn"
  }
}
```


## Examples
This rule does not have examples.

## Version
This rule was introduced in [Solhint 2.0.0-alpha.0](https://github.com/protofire/solhint/tree/v2.0.0-alpha.0)

## Resources
- [Rule source](https://github.com/protofire/solhint/tree/master/lib/rules/security/avoid-call-value.js)
- [Document source](https://github.com/protofire/solhint/tree/master/docs/rules/security/avoid-call-value.md)
- [Test cases](https://github.com/protofire/solhint/tree/master/test/rules/security/avoid-call-value.js)
