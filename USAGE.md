# Usage Guide

How to apply the FastFood License to your projects.

## Step 1: Choose Your Variant

### 🍟 FastFood Minimal (FFM)
**Choose this if:**
- You want maximum adoption
- You're okay with commercial/closed use
- You just want people to be grateful

### 🍔 FastFood Standard (FFS)
**Choose this if:**
- You want improvements shared back
- You believe in copyleft
- You want a GPL-like approach with gratitude

### 🌱 FastFood Ethical (FFE)
**Choose this if:**
- Your values matter more than adoption
- You want to prevent harmful use
- You're willing to risk legal complexity

## Step 2: Add to Your Repository

### Option A: Direct Copy
```bash
# Download your chosen license
wget https://raw.githubusercontent.com/andreaskasper/license/master/LICENSE-FFM.txt

# Rename to standard LICENSE filename
mv LICENSE-FFM.txt LICENSE
```

### Option B: Via Git
```bash
# Clone the license repo
git clone https://github.com/andreaskasper/license.git temp-license

# Copy your chosen variant
cp temp-license/LICENSE-FFM.txt ./LICENSE

# Cleanup
rm -rf temp-license
```

### Option C: Via npm/Composer
*Coming soon - package manager integration*

## Step 3: Customize the License

Replace these placeholders in your LICENSE file:

```diff
- Copyright (c) [year] [fullname] <email@example.com>
+ Copyright (c) 2025 Andreas Kasper <your@email.com>
```

**Required replacements:**
- `[year]` → Current year or range (e.g., "2025" or "2020-2025")
- `[fullname]` → Your full name or company name
- `<email@example.com>` → Your contact email

## Step 4: Add License Headers (Optional)

For better clarity, add license headers to your source files:

### JavaScript/TypeScript
```javascript
/**
 * SPDX-License-Identifier: FastFood-Minimal-1.0
 * Copyright (c) 2025 Your Name <your@email.com>
 * 
 * If this code helped you, a coffee would be appreciated! ☕
 */
```

### Python
```python
# SPDX-License-Identifier: FastFood-Minimal-1.0
# Copyright (c) 2025 Your Name <your@email.com>
#
# If this code helped you, a coffee would be appreciated! ☕
```

### PHP
```php
<?php
/**
 * SPDX-License-Identifier: FastFood-Minimal-1.0
 * Copyright (c) 2025 Your Name <your@email.com>
 * 
 * If this code helped you, a coffee would be appreciated! ☕
 */
```

### HTML/CSS
```html
<!-- 
  SPDX-License-Identifier: FastFood-Minimal-1.0
  Copyright (c) 2025 Your Name <your@email.com>
  
  If this code helped you, a coffee would be appreciated! ☕
-->
```

## Step 5: Update Package Metadata

### package.json (Node.js)
```json
{
  "license": "FastFood-Minimal-1.0",
  "author": "Your Name <your@email.com>",
  "repository": {
    "type": "git",
    "url": "https://github.com/yourusername/yourproject"
  }
}
```

### composer.json (PHP)
```json
{
  "license": "FastFood-Minimal-1.0",
  "authors": [
    {
      "name": "Your Name",
      "email": "your@email.com"
    }
  ]
}
```

### setup.py (Python)
```python
setup(
    name='yourproject',
    license='FastFood-Minimal-1.0',
    author='Your Name',
    author_email='your@email.com',
)
```

### Cargo.toml (Rust)
```toml
[package]
name = "yourproject"
license = "FastFood-Minimal-1.0"
authors = ["Your Name <your@email.com>"]
```

## Step 6: Add to README

Let users know about your license choice:

```markdown
## License

This project is licensed under the FastFood Minimal License.

If this code helped you, I'd appreciate a ⭐ star or a ☕ coffee!

- [Buy me a coffee](https://buymeacoffee.com/yourname)
- [GitHub Sponsors](https://github.com/sponsors/yourname)

See [LICENSE](LICENSE) for details.
```

## Step 7: Make Gratitude Easy

### Add Donation Links
Create a `.github/FUNDING.yml`:

```yaml
github: [yourusername]
ko_fi: yourname
buy_me_a_coffee: yourname
patreon: yourname
custom: ['https://paypal.me/yourname']
```

### Add Badges
```markdown
[![License: FastFood](https://img.shields.io/badge/License-FastFood_Minimal-orange.svg)](LICENSE)
[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-Donate-yellow.svg)](https://www.buymeacoffee.com/yourname)
```

## Step 8: Communicate It

### In your README
```markdown
## 💚 Show Your Appreciation

If this project saved you time or helped you:
- ⭐ Star this repo
- ☕ [Buy me a coffee](https://buymeacoffee.com/yourname)
- 📝 Write a testimonial
- 🐛 Report bugs or contribute
```

### In your documentation
Mention the license and gratitude aspect prominently.

## Common Scenarios

### Multiple Authors
```
Copyright (c) 2025 Alice Smith <alice@example.com>
Copyright (c) 2025 Bob Jones <bob@example.com>
```

### Company/Organization
```
Copyright (c) 2025 YourCompany GmbH <info@yourcompany.com>
```

### Year Ranges
```
Copyright (c) 2020-2025 Your Name <your@email.com>
```

### Dual Licensing
You can offer both FastFood License and another license:

```markdown
## License

This project is dual-licensed under:
- FastFood Minimal License (for open source use)
- Commercial License (contact us for pricing)

See LICENSE-FFM.txt and LICENSE-COMMERCIAL.txt
```

## Verification

After setup, verify:

✅ LICENSE file in repository root  
✅ Placeholders replaced  
✅ Package metadata updated  
✅ README mentions license  
✅ Optional: Source file headers  
✅ Optional: Funding/donation links  

## Need Help?

- [FAQ](FAQ.md)
- [Open an issue](https://github.com/andreaskasper/license/issues)
- [Discussions](https://github.com/andreaskasper/license/discussions)