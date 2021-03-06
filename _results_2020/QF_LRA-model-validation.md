---
layout: result
resultdate: 2020-07-04 11:50:14

year: 2020

divisions: divisions_2020
participants: participants_2020

disagreements: disagreements_2020
division: QF_LRA
track: track_model_validation
n_benchmarks: 378
time_limit: 1200
mem_limit: 60

winner_seq: OpenSMT
winner_par: OpenSMT
sequential:
- name: OpenSMT
  competing: "yes"
  errorScore: 0
  correctScore: 366
  CPUScore: 23196.707
  WallScore: 23147.053
  timeout: 12
  memout: 0
- name: Yices2 Model Validation
  competing: "yes"
  errorScore: 0
  correctScore: 361
  CPUScore: 27231.252
  WallScore: 27220.592
  timeout: 17
  memout: 0
- name: Yices2-fixed Model Validation
  competing: "no"
  errorScore: 0
  correctScore: 361
  CPUScore: 27293.683
  WallScore: 27273.164
  timeout: 17
  memout: 0
- name: z3
  competing: "no"
  errorScore: 0
  correctScore: 361
  CPUScore: 30902.311
  WallScore: 30890.314
  timeout: 17
  memout: 0
- name: CVC4-mv
  competing: "yes"
  errorScore: 0
  correctScore: 360
  CPUScore: 36177.219
  WallScore: 36183.088
  timeout: 18
  memout: 0
- name: SMTInterpol-fixed
  competing: "no"
  errorScore: 0
  correctScore: 351
  CPUScore: 54948.511
  WallScore: 52217.779
  timeout: 27
  memout: 0
- name: SMTInterpol
  competing: "yes"
  errorScore: 2
  errorFootnote: "The error score is caused by SMTInterpol giving values to defined functions (syntactic problems).  It does not indicate an unsoundness."
  correctScore: 350
  CPUScore: 54559.699
  WallScore: 51766.013
  timeout: 26
  memout: 0
- name: MathSAT5-mv
  competing: "no"
  errorScore: 2
  errorFootnote: "The error score is caused by MathSAT not giving full models (syntactic problems).  It does not indicate an unsoundness."
  correctScore: 345
  CPUScore: 53776.173
  WallScore: 53764.771
  timeout: 31
  memout: 0
parallel:
- name: OpenSMT
  competing: "yes"
  errorScore: 0
  correctScore: 366
  CPUScore: 23197.627
  WallScore: 23146.593
  timeout: 12
  memout: 0
- name: Yices2 Model Validation
  competing: "yes"
  errorScore: 0
  correctScore: 361
  CPUScore: 27233.072
  WallScore: 27220.212
  timeout: 17
  memout: 0
- name: Yices2-fixed Model Validation
  competing: "no"
  errorScore: 0
  correctScore: 361
  CPUScore: 27294.953
  WallScore: 27272.744
  timeout: 17
  memout: 0
- name: z3
  competing: "no"
  errorScore: 0
  correctScore: 361
  CPUScore: 30904.961
  WallScore: 30889.864
  timeout: 17
  memout: 0
- name: CVC4-mv
  competing: "yes"
  errorScore: 0
  correctScore: 360
  CPUScore: 36181.659
  WallScore: 36182.578
  timeout: 18
  memout: 0
- name: SMTInterpol-fixed
  competing: "no"
  errorScore: 0
  correctScore: 351
  CPUScore: 54948.511
  WallScore: 52217.779
  timeout: 27
  memout: 0
- name: SMTInterpol
  competing: "yes"
  errorScore: 2
  errorFootnote: "The error score is caused by SMTInterpol giving values to defined functions (syntactic problems).  It does not indicate an unsoundness."
  correctScore: 350
  CPUScore: 54559.699
  WallScore: 51766.013
  timeout: 26
  memout: 0
- name: MathSAT5-mv
  competing: "no"
  errorScore: 2
  errorFootnote: "The error score is caused by MathSAT not giving full models (syntactic problems).  It does not indicate an unsoundness."
  correctScore: 345
  CPUScore: 53783.173
  WallScore: 53763.351
  timeout: 31
  memout: 0
---
