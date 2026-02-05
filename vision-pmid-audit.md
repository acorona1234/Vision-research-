# PMID Citation Audit Report

**Document Reviewed:** `/research/vision-health-research-draft.md`  
**Audit Date:** February 5, 2026  
**Auditor:** Claude (subagent)

---

## Executive Summary

**⚠️ CRITICAL ISSUES FOUND: 8 incorrect PMIDs out of 15+ checked**

This audit reveals **serious citation errors** in the research draft. Multiple PMIDs point to completely unrelated studies (e-cigarettes, plant biology, marmoset gut microbiomes, stroke medications). These are not typos or minor issues—they would completely undermine the credibility of this document if published.

---

## KEY PMID VERIFICATION RESULTS

### ✅ CORRECTLY CITED

| PMID | Claimed Study | Actual Study | Status |
|------|---------------|--------------|--------|
| **23644932** | AREDS2 - Lutein/zeaxanthin for AMD | AREDS2 RCT (JAMA 2013) | ✅ **CORRECT** |
| **29044670** | Blue light blocking systematic review | Lawrenson et al. 2017 systematic review | ✅ **CORRECT** |
| **26372583** | Guangzhou outdoor myopia trial | He et al. JAMA 2015 - Outdoor activity RCT | ✅ **CORRECT** |
| **11594942** | Original AREDS | AREDS Report No. 8 (Arch Ophthalmol 2001) | ✅ **CORRECT** |
| **18294691** | Sydney Myopia Study | Rose et al. 2008 - Outdoor activity & myopia | ✅ **CORRECT** |
| **30514630** | LAMP Study (Hong Kong atropine) | Yam et al. 2019 - Low-concentration atropine | ✅ **CORRECT** |
| **12445849** | Undercorrection worsens myopia | Chung et al. 2002 Vision Res | ✅ **CORRECT** |

---

### ❌ INCORRECTLY CITED (MAJOR ERRORS)

#### 1. PMID 27613717 - CRITICAL ERROR
| | |
|---|---|
| **Document Claims** | "ATOM2 5-year follow-up" for atropine myopia treatment |
| **Actual Study** | "E-Cigarette Aerosol Exposure Induces Reactive Oxygen Species, DNA Damage, and Cell Death in Vascular Endothelial Cells" (Toxicol Sci 2016) |
| **Correct PMID** | **26271839** - "Five-Year Clinical Trial on Atropine for the Treatment of Myopia 2" (Chia et al., Ophthalmology 2016) |
| **Severity** | 🔴 **COMPLETELY UNRELATED STUDY** |

#### 2. PMID 29801005 - CRITICAL ERROR
| | |
|---|---|
| **Document Claims** | "DREAM Study" - Omega-3 for dry eye RCT |
| **Actual Study** | "Statistical Analysis Plans for Clinical Trials" - A comment/letter article (JAMA 2018) |
| **Correct PMID** | **29652551** - "n-3 Fatty Acid Supplementation for the Treatment of Dry Eye Disease" (NEJM 2018) |
| **Severity** | 🔴 **COMPLETELY UNRELATED** |

#### 3. PMID 31697779 - CRITICAL ERROR
| | |
|---|---|
| **Document Claims** | "MiSight contacts / BLINK Study" - Myopia control contacts |
| **Actual Study** | "Evaluating rectal swab collection method for gut microbiome analysis in the common marmoset (Callithrix jacchus)" (PLoS One 2019) |
| **Correct PMID** | **31343513** - "A 3-year Randomized Clinical Trial of MiSight Lenses for Myopia Control" (Chamberlain et al., Optom Vis Sci 2019) |
| **Additional Note** | Document incorrectly calls this the "BLINK Study" - it's not the BLINK study; it's the MiSight clinical trial |
| **Severity** | 🔴 **COMPLETELY UNRELATED** |

#### 4. PMID 36912752 - CRITICAL ERROR
| | |
|---|---|
| **Document Claims** | "Cochrane blue light 2023" review |
| **Actual Study** | "Antibiotics versus placebo for acute bacterial conjunctivitis" (Cochrane 2023) |
| **Correct PMID** | **37593770** - "Blue-light filtering spectacle lenses for visual performance, sleep, and macular health in adults" (Singh et al., Cochrane 2023) |
| **Severity** | 🔴 **WRONG COCHRANE REVIEW** |

#### 5. PMID 26875007 - MISLEADING CITATION
| | |
|---|---|
| **Document Claims** | Listed in table as "Global myopia prevalence" but cited earlier in text as "ATOM2 (Low-dose comparison)" |
| **Actual Study** | "Global Prevalence of Myopia and High Myopia and Temporal Trends from 2000 through 2050" (Holden et al., Ophthalmology 2016) |
| **Issue** | The PMID is correct for global prevalence data, but in section 2.2, it's cited as "ATOM2 Trial (Low-dose comparison)" which is incorrect |
| **Correct PMID for ATOM2** | **21963266** (2-year results) or **26271839** (5-year follow-up) |
| **Severity** | 🟡 **MISATTRIBUTED** - Same PMID used for two different claims |

#### 6. PMID 30860592 - CRITICAL ERROR
| | |
|---|---|
| **Document Claims** | "2019 Cochrane Review" on omega-3 for dry eye |
| **Actual Study** | "Divining responder populations from survival data" - Cancer biomarker study (Ann Oncol 2019) |
| **Correct PMID** | Unable to locate correct Cochrane omega-3/dry eye 2019 review |
| **Severity** | 🔴 **COMPLETELY UNRELATED** |

#### 7. PMID 22972044 - CRITICAL ERROR
| | |
|---|---|
| **Document Claims** | "Cochrane Review" on bilberry/anthocyanins for eye health |
| **Actual Study** | "Piracetam for acute ischaemic stroke" (Cochrane 2012) |
| **Correct PMID** | Unable to locate - may need to verify if a Cochrane bilberry review exists |
| **Severity** | 🔴 **COMPLETELY UNRELATED** |

#### 8. PMID 16488922 - CRITICAL ERROR
| | |
|---|---|
| **Document Claims** | "ATOM1 Trial (Singapore)" - 1% atropine for myopia |
| **Actual Study** | "The production and release of living root cap border cells is a function of root apical meristem type in dicotyledonous angiosperm plants" (Ann Bot 2006) |
| **Correct PMID** | The ATOM1 study is referenced in PMID **21963266** (ATOM2 paper mentions ATOM1 results) - need to find standalone ATOM1 publication |
| **Severity** | 🔴 **COMPLETELY UNRELATED (PLANT BIOLOGY!)** |

---

## SPOT-CHECK OF OTHER PMIDs

| PMID | Document Claim | Verified? |
|------|----------------|-----------|
| 30024655 | Taiwan myopia program | Not checked |
| 22214651 | LORIC ortho-K study | Not checked |
| 23023379 | ROMIO ortho-K study | Not checked |
| 31932578 | DIMS spectacle lens | Not checked |
| 27894858 | Blue light review | Not checked |
| 25535358 | Blue light melatonin | Not checked |
| 16023434 | Cyclosporine for dry eye | Not checked |
| 27208527 | Lifitegrast | Not checked |
| 32390590 | Screen breaks study | Not checked |
| 30645730 | Artificial tears review | Not checked |
| 27187278 | Blink training study | Not checked |
| 30716456 | Warm compresses for MGD | Not checked |

---

## SUMMARY OF ERRORS BY SEVERITY

| Severity | Count | Description |
|----------|-------|-------------|
| 🔴 Critical | 7 | PMIDs point to completely unrelated studies |
| 🟡 Misleading | 1 | Same PMID cited for two different claims |
| ✅ Correct | 7 | Verified accurate |

---

## RECOMMENDATIONS

### Immediate Actions Required:

1. **Replace all 8 incorrect PMIDs** with the correct citations before any publication
2. **Verify remaining unchecked PMIDs** - given the error rate (~50% of checked citations), all should be verified
3. **Cross-check the study name "BLINK Study"** - the MiSight trial is NOT the BLINK study; this appears to be a naming error

### Corrected PMIDs for Key Studies:

| Study | Incorrect PMID | Correct PMID |
|-------|---------------|--------------|
| ATOM2 5-year | 27613717 | **26271839** |
| DREAM dry eye | 29801005 | **29652551** |
| MiSight 3-year | 31697779 | **31343513** |
| Cochrane blue light 2023 | 36912752 | **37593770** |
| ATOM2 low-dose (in section 2.2) | 26875007 | **21963266** or **26271839** |

### For citations I couldn't verify:
- Bilberry Cochrane Review (claimed PMID 22972044) - may need original source verification
- Omega-3 dry eye Cochrane 2019 (claimed PMID 30860592) - may need original source verification  
- ATOM1 original publication (claimed PMID 16488922) - search for original ATOM1 paper

---

## AUDIT METHODOLOGY

1. Retrieved PubMed pages for each PMID directly via web fetch
2. Compared article titles, abstracts, and content against document claims
3. Searched for correct PMIDs when mismatches were found
4. Verified findings align with stated research topics and authors

---

*This audit was conducted on February 5, 2026. Given the high error rate discovered, a complete re-verification of ALL citations is strongly recommended before publication.*
