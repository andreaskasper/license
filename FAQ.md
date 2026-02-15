# Frequently Asked Questions

## General Questions

### What is the FastFood License?
A modern open-source license that puts gratitude and community at the center. It's similar to established licenses (MIT/GPL) but adds a voluntary gratitude clause.

### Why create another license?
Because open source should be about human connections, not just legal boilerplate. The FastFood License reminds users that behind every library is a human who would appreciate recognition.

### Is it legally binding?
Yes, the license terms are legally binding like any software license. However, the **gratitude clause is explicitly optional** and not legally required.

### Which variant should I choose?
- **FFM (Minimal)**: Maximum adoption, like MIT
- **FFS (Standard)**: Keep improvements open, like GPL  
- **FFE (Ethical)**: Add values alignment, like Hippocratic License

## Legal Questions

### Is this OSI-approved?
Not yet. OSI approval requires a formal process. For now, it's a well-documented custom license.

### Can I use this commercially?
Yes, all variants allow commercial use. FFE adds ethical constraints.

### Can I create closed-source products?
- **FFM**: Yes
- **FFS**: No, derivatives must be open source
- **FFE**: No, derivatives must be open source

### Is it GPL-compatible?
- **FFM**: Compatible with permissive licenses (MIT, Apache)
- **FFS**: Compatible with GPL-3.0+
- **FFE**: Compatible with GPL-3.0+

### What if someone doesn't show gratitude?
Nothing happens. The gratitude clause is explicitly optional and not enforceable.

### What if someone violates the ethical clause (FFE)?
This is complex. The clause is aspirational and may not be enforceable in all jurisdictions. You can:
- Request they stop using your software
- Seek legal remedies (jurisdiction-dependent)
- Use it as moral guidance rather than legal enforcement

## Practical Questions

### How do I apply the license?
See [USAGE.md](USAGE.md) for step-by-step instructions.

### Can I modify the license?
You can, but then it's no longer "FastFood License". Consider:
- Using it as-is for consistency
- Proposing changes via pull request
- Creating your own fork with a different name

### What if my company only allows OSI-approved licenses?
Use MIT or GPL-3.0 instead, and add a separate CODE_OF_CONDUCT.md or GRATITUDE.md expressing your values.

### Can I dual-license?
Yes! Offer FastFood License for open source users and a commercial license for closed-source:

```
This project is dual-licensed:
- FastFood Minimal (for open source)
- Commercial License (contact for pricing)
```

### How do I accept gratitude?
Add donation links:
- GitHub Sponsors
- Buy Me a Coffee
- Ko-fi
- PayPal
- Patreon

See [USAGE.md](USAGE.md) for setup instructions.

## Comparison Questions

### FastFood Minimal vs MIT?
**Same:** Permissive, commercial use, closed derivatives  
**Different:** FastFood adds gratitude culture

### FastFood Standard vs GPL?
**Same:** Copyleft, open source derivatives  
**Different:** FastFood is simpler, adds gratitude culture

### FastFood Ethical vs Hippocratic License?
**Same:** Ethical constraints, copyleft  
**Different:** FastFood is lighter, focuses on core values

### FastFood vs Beerware?
**Same:** Gratitude focus, buy-us-something culture  
**Different:** FastFood is more formal, legally clearer, multiple variants

## Technical Questions

### What SPDX identifier do I use?
```
SPDX-License-Identifier: FastFood-Minimal-1.0
SPDX-License-Identifier: FastFood-Standard-1.0
SPDX-License-Identifier: FastFood-Ethical-1.0
```

Note: These aren't official SPDX identifiers yet.

### Can I use this in npm/PyPI/cargo packages?
Yes, but be aware:
- Some registries may flag non-standard licenses
- Corporate users may filter out non-OSI licenses
- Document clearly in your README

### How do I handle contributions?
Add a CONTRIBUTING.md:

```markdown
By contributing, you agree to license your contributions
under the same FastFood License as the project.
```

### What about patents?
FFM and FFS don't explicitly grant patent rights (unlike Apache 2.0). FFE includes implicit patent grants through the copyleft clause.

For patent-sensitive projects, consider Apache 2.0 instead.

## Cultural Questions

### What if users can't afford to show gratitude?
That's perfectly fine! The gratitude clause is **optional**. Stars, kind words, or bug reports are free ways to show appreciation.

### Isn't requiring gratitude manipulative?
We don't require it - it's explicitly optional. We just remind users that gratitude is appreciated.

### Does this work internationally?
Yes, though "buy us a burger" translates differently across cultures. The license text is intentionally flexible about how gratitude is shown.

### What about different food preferences?
Burger/FastFood is symbolic. Gratitude can be:
- Coffee, tea, smoothie
- Vegan options
- Donations to charity
- GitHub stars
- Kind messages
- Whatever feels right

## Migration Questions

### Can I switch from MIT to FastFood?
Yes, if you're the sole copyright holder. Update your LICENSE file and document the change.

### Can I switch from GPL to FastFood?
Careful! GPL code can only be relicensed to GPL-compatible licenses. FFS/FFE are GPL-compatible, but check if all contributors agree.

### Can I switch from FastFood to MIT/GPL?
Yes, if you're the sole copyright holder.

### What about existing users?
Existing code remains under the original license. New versions use the new license.

## Support Questions

### I have more questions!
Great! Please:
- [Open an issue](https://github.com/andreaskasper/license/issues)
- [Start a discussion](https://github.com/andreaskasper/license/discussions)
- Email: [Contact info]

### Can I contribute to this license?
Yes! We welcome:
- Translations
- Documentation improvements
- Legal analysis
- Real-world usage examples
- Bug reports in the license text

See [CONTRIBUTING.md](CONTRIBUTING.md)

### How do I report license violations?
Contact the project maintainer directly. For FastFood License violations, open an issue in this repository.

---

**Not finding your answer?** [Ask in Discussions](https://github.com/andreaskasper/license/discussions) or [open an issue](https://github.com/andreaskasper/license/issues)!