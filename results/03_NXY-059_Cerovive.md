# Slide 3: NXY-059 (Cerovive)

**Initial Task:** BBBP

**SMILES:** `CC(C)(C)/[N+](=C/C1=CC=C(C=C1S(=O)(=O)OC)S(=O)(=O)OC)/[O-]`

---

## ❌ Optimization Failed for NXY-059 (Cerovive)

**No valid paths found.** The optimization could not generate any improved molecules.

### 📊 Initial Molecule Scores

**Input SMILES:** `CC(C)(C)/[N+](=C/C1=CC=C(C=C1S(=O)(=O)OC)S(=O)(=O)OC)/[O-]`

- **Molecules Generated:** 73
- **Valid Paths:** 0

**Reason:** All generated molecules had worse scores than the initial molecule.

### 🔧 Recommendations

1. **Increase beams:** Try `num_beams=7` or `num_beams=10` for more diversity
2. **Change initial task:** Try a different task as the starting point
3. **Reduce depth:** Start with `depth=1` to see if single-step improvements work
4. **Check initial molecule:** It may already be highly optimized

