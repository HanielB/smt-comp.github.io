---
layout: result
resultdate: 2020-07-04 11:50:14

year: 2020

divisions: divisions_2020
participants: participants_2020

disagreements: disagreements_2020
division: QF_LIA
track: track_model_validation
n_benchmarks: 1532
time_limit: 1200
mem_limit: 60

winner_seq: CVC4-mv
winner_par: CVC4-mv
sequential:
- name: z3
  competing: "no"
  errorScore: 0
  correctScore: 1461
  CPUScore: 188635.889
  WallScore: 188590.757
  timeout: 70
  memout: 1
- name: CVC4-mv
  competing: "yes"
  errorScore: 0
  correctScore: 1413
  CPUScore: 171782.588
  WallScore: 171520.789
  timeout: 116
  memout: 0
- name: Yices2 Model Validation
  competing: "yes"
  errorScore: 0
  correctScore: 1293
  CPUScore: 318640.804
  WallScore: 318586.617
  timeout: 239
  memout: 0
- name: Yices2-fixed Model Validation
  competing: "no"
  errorScore: 0
  correctScore: 1292
  CPUScore: 318817.204
  WallScore: 318835.381
  timeout: 240
  memout: 0
- name: SMTInterpol-fixed
  competing: "no"
  errorScore: 0
  correctScore: 1273
  CPUScore: 404680.659
  WallScore: 389779.138
  timeout: 259
  memout: 0
- name: SMTInterpol
  competing: "yes"
  errorScore: 0
  correctScore: 1272
  CPUScore: 404643.459
  WallScore: 389786.135
  timeout: 260
  memout: 0
- name: MathSAT5-mv
  competing: "no"
  errorScore: 14
  errorFootnote: "The error score is caused by MathSAT not giving full models (syntactic problems).  It does not indicate an unsoundness."
  correctScore: 1440
  CPUScore: 176506.816
  WallScore: 176433.952
  timeout: 78
  memout: 0
parallel:
- name: z3
  competing: "no"
  errorScore: 0
  correctScore: 1461
  CPUScore: 188641.519
  WallScore: 188588.467
  timeout: 70
  memout: 1
- name: CVC4-mv
  competing: "yes"
  errorScore: 0
  correctScore: 1413
  CPUScore: 171792.048
  WallScore: 171517.539
  timeout: 116
  memout: 0
- name: Yices2 Model Validation
  competing: "yes"
  errorScore: 0
  correctScore: 1293
  CPUScore: 318653.504
  WallScore: 318579.807
  timeout: 239
  memout: 0
- name: Yices2-fixed Model Validation
  competing: "no"
  errorScore: 0
  correctScore: 1292
  CPUScore: 318829.934
  WallScore: 318829.741
  timeout: 240
  memout: 0
- name: SMTInterpol-fixed
  competing: "no"
  errorScore: 0
  correctScore: 1275
  CPUScore: 404712.029
  WallScore: 389760.068
  timeout: 257
  memout: 0
- name: SMTInterpol
  competing: "yes"
  errorScore: 0
  correctScore: 1274
  CPUScore: 404650.729
  WallScore: 389736.485
  timeout: 258
  memout: 0
- name: MathSAT5-mv
  competing: "no"
  errorScore: 14
  errorFootnote: "The error score is caused by MathSAT not giving full models (syntactic problems).  It does not indicate an unsoundness."
  correctScore: 1440
  CPUScore: 176516.546
  WallScore: 176431.022
  timeout: 78
  memout: 0
---
