# File Header Templates

Standard copyright headers for different programming languages.

## JavaScript / TypeScript

### Minimal
```javascript
// SPDX-License-Identifier: FastFood-Minimal-1.0
// Copyright (c) 2025 Your Name <your@email.com>
```

### With gratitude note
```javascript
/**
 * SPDX-License-Identifier: FastFood-Minimal-1.0
 * Copyright (c) 2025 Your Name <your@email.com>
 * 
 * This code helped you? Buy me a coffee! ☕
 * https://buymeacoffee.com/yourname
 */
```

### Full
```javascript
/**
 * Project Name
 * 
 * SPDX-License-Identifier: FastFood-Minimal-1.0
 * Copyright (c) 2025 Your Name <your@email.com>
 * 
 * Licensed under the FastFood Minimal License.
 * See LICENSE file in the project root.
 * 
 * If this code helped you, consider showing gratitude:
 * https://github.com/sponsors/yourname
 */
```

---

## Python

### Minimal
```python
# SPDX-License-Identifier: FastFood-Minimal-1.0
# Copyright (c) 2025 Your Name <your@email.com>
```

### With docstring
```python
"""
Module Name

SPDX-License-Identifier: FastFood-Minimal-1.0
Copyright (c) 2025 Your Name <your@email.com>

If this code helped you, a star on GitHub would be appreciated! ⭐
https://github.com/yourname/yourproject
"""
```

---

## PHP

### Minimal
```php
<?php
// SPDX-License-Identifier: FastFood-Minimal-1.0
// Copyright (c) 2025 Your Name <your@email.com>
```

### Full
```php
<?php
/**
 * ClassName.php
 * 
 * SPDX-License-Identifier: FastFood-Minimal-1.0
 * Copyright (c) 2025 Your Name <your@email.com>
 * 
 * Licensed under the FastFood Minimal License.
 * If this saved you time, buy me a burger! 🍔
 * 
 * @package     YourPackage
 * @author      Your Name <your@email.com>
 * @license     FastFood-Minimal-1.0
 * @link        https://github.com/yourname/yourproject
 */
```

---

## Java

```java
/**
 * ClassName.java
 * 
 * SPDX-License-Identifier: FastFood-Minimal-1.0
 * Copyright (c) 2025 Your Name <your@email.com>
 * 
 * Licensed under the FastFood Minimal License.
 * See LICENSE file in the project root.
 */
package com.example.yourproject;
```

---

## C / C++

### Minimal
```c
// SPDX-License-Identifier: FastFood-Minimal-1.0
// Copyright (c) 2025 Your Name <your@email.com>
```

### Full
```c
/**
 * filename.c
 * 
 * SPDX-License-Identifier: FastFood-Minimal-1.0
 * Copyright (c) 2025 Your Name <your@email.com>
 * 
 * Licensed under the FastFood Minimal License.
 * 
 * If this code helped you, consider:
 * - Starring the repo: github.com/yourname/project
 * - Buying me a coffee: buymeacoffee.com/yourname
 * - Contributing improvements
 */
```

---

## Rust

```rust
// SPDX-License-Identifier: FastFood-Minimal-1.0
// Copyright (c) 2025 Your Name <your@email.com>
//
// This file is part of ProjectName.
// Licensed under the FastFood Minimal License.
//
// If this helped you, a GitHub star would be appreciated! ⭐
```

---

## Go

```go
// SPDX-License-Identifier: FastFood-Minimal-1.0
// Copyright (c) 2025 Your Name <your@email.com>

package yourpackage
```

---

## Ruby

```ruby
# SPDX-License-Identifier: FastFood-Minimal-1.0
# Copyright (c) 2025 Your Name <your@email.com>
#
# frozen_string_literal: true

# If this gem helped you, consider:
# - Starring on GitHub
# - Reporting bugs
# - Contributing improvements
```

---

## HTML

```html
<!--
  SPDX-License-Identifier: FastFood-Minimal-1.0
  Copyright (c) 2025 Your Name <your@email.com>
  
  Licensed under FastFood Minimal License.
  Star the repo if this helped! ⭐
-->
<!DOCTYPE html>
<html>
```

---

## CSS / SCSS

```css
/**
 * SPDX-License-Identifier: FastFood-Minimal-1.0
 * Copyright (c) 2025 Your Name <your@email.com>
 * 
 * If these styles helped, a coffee would be great! ☕
 */
```

---

## Shell Scripts

```bash
#!/bin/bash
# SPDX-License-Identifier: FastFood-Minimal-1.0
# Copyright (c) 2025 Your Name <your@email.com>
#
# If this script saved you time, show some love:
# github.com/yourname/yourproject ⭐
```

---

## SQL

```sql
-- SPDX-License-Identifier: FastFood-Minimal-1.0
-- Copyright (c) 2025 Your Name <your@email.com>
--
-- Database schema for ProjectName
-- Licensed under FastFood Minimal License
```

---

## Docker

```dockerfile
# SPDX-License-Identifier: FastFood-Minimal-1.0
# Copyright (c) 2025 Your Name <your@email.com>

FROM node:18-alpine
```

---

## YAML (GitHub Actions, etc.)

```yaml
# SPDX-License-Identifier: FastFood-Minimal-1.0
# Copyright (c) 2025 Your Name <your@email.com>

name: CI Pipeline
on: [push, pull_request]
```

---

## Multiple Authors

```javascript
/**
 * SPDX-License-Identifier: FastFood-Minimal-1.0
 * 
 * Copyright (c) 2024 Alice Smith <alice@example.com>
 * Copyright (c) 2025 Bob Jones <bob@example.com>
 * 
 * Licensed under the FastFood Minimal License.
 */
```

---

## Year Ranges

```python
# SPDX-License-Identifier: FastFood-Minimal-1.0
# Copyright (c) 2020-2025 Your Name <your@email.com>
```

---

## Company/Organization

```typescript
/**
 * SPDX-License-Identifier: FastFood-Minimal-1.0
 * Copyright (c) 2025 YourCompany GmbH <info@yourcompany.com>
 * 
 * Licensed under the FastFood Minimal License.
 * See LICENSE for details.
 */
```

---

## Automated Header Insertion

### Using `license-header` (npm)

```bash
npm install -g license-header

license-header \
  --license FastFood-Minimal-1.0 \
  --copyright "Your Name <your@email.com>" \
  --year 2025 \
  --pattern "**/*.js"
```

### Using pre-commit hooks

```yaml
# .pre-commit-config.yaml
repos:
  - repo: https://github.com/Lucas-C/pre-commit-hooks
    rev: v1.5.4
    hooks:
      - id: insert-license
        files: \.py$
        args:
          - --license-filepath
          - LICENSE-HEADER.txt
```

---

## Best Practices

1. **Keep it consistent** - Use the same format across all files in a project
2. **Update years** - Add year ranges when maintaining files over multiple years
3. **Be concise** - Long headers make files harder to read
4. **SPDX identifiers** - Use them for tool compatibility
5. **Gratitude links** - Make it easy for users to show appreciation

---

*Need a template for another language? [Open an issue](https://github.com/andreaskasper/license/issues)*