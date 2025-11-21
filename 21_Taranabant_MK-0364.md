# Slide 21: Taranabant (MK-0364)

**Initial Task:** DILI

**SMILES:** `C[C@@H]([C@@H](CC1=CC=C(C=C1)Cl)C2=CC=CC(=C2)C#N)NC(=O)C(C)(C)OC3=NC=C(C=C3)C(F)(F)F`

---

## ❌ Optimization Failed for Taranabant (MK-0364)

**No valid paths found.** The optimization could not generate any improved molecules.

### 📊 Initial Molecule Scores

**Input SMILES:** `C[C@@H]([C@@H](CC1=CC=C(C=C1)Cl)C2=CC=CC(=C2)C#N)NC(=O)C(C)(C)OC3=NC=C(C=C3)C(F)(F)F`

- **Molecules Generated:** 1
- **Valid Paths:** 0

**Reason:** All generated molecules had worse scores than the initial molecule.

### 🔧 Recommendations

1. **Increase beams:** Try `num_beams=7` or `num_beams=10` for more diversity
2. **Change initial task:** Try a different task as the starting point
3. **Reduce depth:** Start with `depth=1` to see if single-step improvements work
4. **Check initial molecule:** It may already be highly optimized

