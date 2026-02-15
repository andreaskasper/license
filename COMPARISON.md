# License Comparison

How the FastFood License compares to popular open-source licenses.

## Quick Reference Table

| Feature | FFM | FFS | FFE | MIT | GPL-3.0 | Apache 2.0 |
|---------|-----|-----|-----|-----|---------|------------|
| **Commercial use** | ✅ | ✅ | ✅* | ✅ | ✅ | ✅ |
| **Modify** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| **Distribute** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| **Closed derivatives** | ✅ | ❌ | ❌ | ✅ | ❌ | ✅ |
| **Patent grant** | ❌ | ❌ | ~ | ❌ | ~ | ✅ |
| **Trademark protection** | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| **Attribution required** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| **Same license** | ❌ | ✅ | ✅ | ❌ | ✅ | ❌ |
| **State changes** | ❌ | ✅ | ✅ | ❌ | ✅ | ✅ |
| **Ethical constraints** | ❌ | ❌ | ✅ | ❌ | ❌ | ❌ |
| **Gratitude culture** | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ |
| **OSI-approved** | ❌ | ❌ | ❌ | ✅ | ✅ | ✅ |

*FFE: With ethical constraints

## Detailed Comparisons

### FastFood Minimal vs MIT License

**Similarities:**
- Highly permissive
- Allow commercial use
- Allow closed-source derivatives
- Require attribution
- Simple and short

**Differences:**
| Aspect | FFM | MIT |
|--------|-----|-----|
| **Gratitude clause** | ✅ Optional but encouraged | ❌ None |
| **Community focus** | ✅ Emphasized | Neutral |
| **OSI-approved** | ❌ Not yet | ✅ Yes |
| **Corporate adoption** | ⚠️ Limited | ✅ Widespread |

**When to choose:**
- **FFM**: You want to encourage gratitude and community
- **MIT**: You need maximum adoption and OSI approval

---

### FastFood Standard vs GPL-3.0

**Similarities:**
- Strong copyleft
- Require source code availability
- Derivatives must use same license
- Commercial use allowed

**Differences:**
| Aspect | FFS | GPL-3.0 |
|--------|-----|----------|
| **Complexity** | Simple (2 pages) | Complex (7 pages) |
| **Gratitude clause** | ✅ Emphasized | ❌ None |
| **Patent clauses** | Limited | Explicit |
| **Anti-TiVoization** | ❌ None | ✅ Included |
| **OSI-approved** | ❌ Not yet | ✅ Yes |
| **Legal testing** | Limited | Extensive |

**When to choose:**
- **FFS**: You want copyleft with community culture
- **GPL**: You need battle-tested copyleft with patent protection

---

### FastFood Ethical vs Hippocratic License

**Similarities:**
- Ethical use restrictions
- Human rights focus
- Copyleft
- Non-OSI-approved

**Differences:**
| Aspect | FFE | Hippocratic |
|--------|-----|-------------|
| **Scope** | Core ethical issues | Comprehensive human rights |
| **Enforceability** | Aspirational | Intended as binding |
| **Gratitude clause** | ✅ Emphasized | ❌ None |
| **Complexity** | Moderate | High |
| **Updates** | Stable | Evolving (multiple versions) |

**When to choose:**
- **FFE**: You want ethics + gratitude culture, lighter approach
- **Hippocratic**: You need comprehensive human rights alignment

---

### FastFood vs Apache 2.0

**Similarities:**
- Permissive (FFM)
- Allow commercial use
- Require attribution

**Differences:**
| Aspect | FFM | Apache 2.0 |
|--------|-----|------------|
| **Patent grant** | ❌ None | ✅ Explicit |
| **Trademark** | ❌ Not addressed | ✅ Protected |
| **Contribution licensing** | Implicit | Explicit |
| **Gratitude clause** | ✅ Yes | ❌ None |
| **Corporate use** | ⚠️ May need review | ✅ Standard |
| **Complexity** | Simple | Moderate |

**When to choose:**
- **FFM**: You want simplicity + gratitude culture
- **Apache**: You need patent protection and corporate acceptance

---

### FastFood vs BSD (3-Clause)

**Similarities:**
- Permissive (FFM)
- Short and simple
- Allow commercial use
- Require attribution

**Differences:**
| Aspect | FFM | BSD-3 |
|--------|-----|-------|
| **Endorsement clause** | ❌ None | ✅ Prohibits name misuse |
| **Gratitude clause** | ✅ Yes | ❌ None |
| **Age** | Modern (2025) | Classic (1980s) |
| **Recognition** | Growing | Established |

**When to choose:**
- **FFM**: You want gratitude culture
- **BSD**: You need established, minimal license

---

### FastFood vs Creative Commons (CC-BY-SA)

**Note:** CC licenses are designed for creative works, not software!

**Similarities (FFS/FFE):**
- Copyleft/Share-Alike
- Attribution required
- Allow commercial use

**Differences:**
| Aspect | FastFood | CC-BY-SA |
|--------|----------|----------|
| **Designed for** | Software | Creative works |
| **Source code** | Required (FFS/FFE) | N/A |
| **Patent rights** | Limited | None |
| **Gratitude** | ✅ Emphasized | ❌ None |

**When to choose:**
- **FastFood**: For software
- **CC-BY-SA**: For documentation, art, music

---

## Philosophy Comparison

### Permissive Licenses (MIT, BSD, Apache)
**Philosophy:** Maximum freedom, minimal restrictions  
**FastFood Minimal:** Adds community and gratitude to permissiveness

### Copyleft Licenses (GPL, LGPL)
**Philosophy:** Freedom to use, but improvements must be shared  
**FastFood Standard:** Adds gratitude to copyleft philosophy

### Ethical Licenses (Hippocratic, Anti-996)
**Philosophy:** Software for good, not harm  
**FastFood Ethical:** Combines ethics with gratitude culture

### Community Licenses (Beerware, WTFPL)
**Philosophy:** Fun, informal, human-centered  
**FastFood:** Formalizes community values with legal clarity

---

## Practical Decision Tree

```
Do you need OSI approval?
├─ YES → Use MIT/Apache/GPL
└─ NO
   |
   Do you want derivatives to stay open source?
   ├─ NO → FastFood Minimal (like MIT + gratitude)
   └─ YES
      |
      Do you want ethical constraints?
      ├─ NO → FastFood Standard (like GPL + gratitude)
      └─ YES → FastFood Ethical (ethics + copyleft + gratitude)
```

---

## Migration Scenarios

### From MIT → FastFood Minimal
**Impact:** Minimal  
**Compatibility:** ✅ Smooth  
**Reason:** Adds gratitude culture without restrictions

### From GPL → FastFood Standard  
**Impact:** Moderate  
**Compatibility:** ✅ GPL-compatible  
**Reason:** Simplifies GPL, adds gratitude

### From Proprietary → Any FastFood
**Impact:** Major  
**Compatibility:** N/A  
**Reason:** Opens your code, builds community

### From FastFood → OSI License
**Impact:** Low  
**Compatibility:** ✅ Can always go more permissive  
**Reason:** Need corporate adoption

---

## Real-World Examples

### Good use cases for FastFood Minimal:
- Personal utility libraries
- Developer tools
- Starter templates
- Educational code
- Portfolio projects

### Good use cases for FastFood Standard:
- Community frameworks
- Open-source SaaS alternatives
- Developer platforms
- Educational platforms

### Good use cases for FastFood Ethical:
- Social good projects
- Environmental tools
- Privacy-focused software
- Human rights tech

### When to use something else:
- Enterprise software → Apache 2.0
- Linux-style projects → GPL-3.0
- Research code → MIT or BSD
- Maximum adoption needed → MIT

---

## Bottom Line

**FastFood License is best for:**
- Personal/community projects
- Developers who value gratitude culture
- Projects where OSI approval isn't critical
- Building human connections through code

**Traditional licenses are better for:**
- Corporate/enterprise adoption
- Legal certainty and case law
- Maximum interoperability
- Critical infrastructure

**You can have both!** Use FastFood for community versions, offer commercial licenses for enterprise.

---

*Have questions about specific license combinations? [Open an issue](https://github.com/andreaskasper/license/issues)*