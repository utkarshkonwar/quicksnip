---
title: Convert Snake Case to Camel Case
description: Converts a snake_case string to camelCase.
author: axorax
tags: python,string,snake-case,camel-case,convert,utility
---

```py
def snake_to_camel(s):
    parts = s.split('_')
    return parts[0] + ''.join(word.capitalize() for word in parts[1:])

# Usage:
print(snake_to_camel('hello_world'))  # Output: 'helloWorld'
```