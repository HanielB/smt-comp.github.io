## SMT-COMP 2020 Alternative

This website contains the results of [SMT-COMP 2020 Single
Query](https://smt-comp.github.io/2020/results/results-single-query) if the same
solvers had entered but the logics were combined into the following divisions:

### QF divisions

- QF_Equality
  - Logics: QF_UF, QF_AX, QF_DT
- QF_Equality+LinearArith
  - Logics: QF_ALIA, QF_AUFLIA, QF_UFLIA, QF_UFLRA, QF_UFIDL
- QF_Equality+NonLinearArith
  - Logics: QF_UFNRA, QF_UFNIA, QF_ANIA, QF_AUFNIA
- QF_Equality+BVArith
  - Logics: QF_ABV, QF_UFBV, QF_AUFBV
- QF_LinearIntArith
  - Logics: QF_LIA, QF_LIRA, QF_IDL
- QF_LinearRealArith
  - Logics: QF_LRA, QF_RDL
- QF_BV<br>
- QF_FPArith
  - Logics: QF_FP, QF_UFFP, QF_FPLRA, QF_BVFP, QF_ABVFP, QF_BVFPLRA, QF_ABVFPLRA
- QF_NonLinearIntArith
  - Logics: QF_NIA, QF_NIRA
- QF_NRA<br>
- QF_Strings
  - Logics: QF_S, QF_SLIA

### Quantified divisions

- Equality
  - Logics: UF, UFDT
- Equality+LinearArith
  - Logics: ALIA, AUFLIA, UFLIA, UFIDL, AUFLIRA, UFLRA, UFDTLIA, UFDTLIRA, AUFDTLIA, AUFDTLIRA
- Equality+MachineArith
  - Logics: AUFFPDTLIRA, UFFPDTLIRA, UFFPDTNIRA, ABVFP, ABVFPLRA, UFBV, AUFBVDTLIA
- Equality+NonLinearArith
  - Logics: AUFDTNIRA, UFDTNIA, UFDTNIRA, AUFNIA, AUFNIRA, UFNIA
- Arith
  - Logics: LRA, LIA, NIA, NRA
- BV<br>
- FPArith
  - Logics: BVFP, FP, BVFPLRA, FPLRA

### Rationale

The divisions above were determined following:
1. Similar logics that do not standout by themselves were combined
2. Integer and real, as well as bit-vector and floating-point, arithmetics are separated
  - note that the "Arith" division goes against this however its composing
    logics do not standout out by themselves as currently represented in
    SMT-LIB.
3. Arrays and datatypes are handled in a similar enough way to UF to be combined
   with it.
4. Floating-point logics are combined since generally this is the dominating
   component for any logic contaning FP.
