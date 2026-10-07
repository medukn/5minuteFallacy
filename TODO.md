# TODO List - 5-Minute Surrender Fallacy

## Website Status
🚧 **Currently Under Maintenance** - The website has been put into maintenance mode due to unresolved issues.

## Priority Improvements

### 1. Model Refactoring - Use Score Difference Instead of Scores
**Status:** 🔴 Not Started  
**Priority:** High

**Description:**
The current mathematical model analyzes absolute scores for each team. This should be refactored to use score differences (relative advantage) instead.

**Benefits:**
- More accurate representation of game dynamics
- Simplifies the mathematical model
- Better aligns with the concept of "advantage flattening"
- Reduces complexity in calculations

**Implementation Notes:**
- Review current scoring mechanism in index.html
- Update Chart.js visualizations to show score differences
- Modify mathematical formulas to use relative advantages
- Update documentation to reflect the changes

---

### 2. Reconcile All Sections
**Status:** 🔴 Not Started  
**Priority:** High

**Description:**
Review and reconcile all sections of the analysis to ensure consistency and coherent logical flow throughout the document.

**Tasks:**
- [ ] Review section order (based on comparison.html structure)
- [ ] Ensure consistent terminology across all sections
- [ ] Verify mathematical notation is uniform
- [ ] Check that predictions/hypotheses come before validations
- [ ] Align visualizations with their respective sections
- [ ] Update cross-references between sections
- [ ] Ensure narrative flow makes sense from start to finish

**Sections to Review:**
- Section 7: Advantage Flattening Over Time (Model Prediction)
- Section 8: Real-World Evidence (Empirical Validation)
- All other sections for consistency

---

### 3. Fix Unresolved Issues
**Status:** 🔴 Not Started  
**Priority:** Medium

**Description:**
Address various technical and content issues that have been identified.

**Known Issues:**
- (Add specific issues as they are identified)

---

## Maintenance Mode
- [x] Create maintenance page
- [x] Add to-do list to maintenance page
- [ ] Test maintenance page display
- [ ] Document how to enable/disable maintenance mode

---

## Notes
- The website uses Tailwind CSS for styling
- Chart.js is used for data visualizations
- The project is hosted on GitHub: https://github.com/medukn/5minuteFallacy

---

**Last Updated:** 2026-01-21
