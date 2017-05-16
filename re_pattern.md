# regular expression

# Material

**Material_Te/Bi**

^Bi.*?Te|^[A-Z][a-z].*?[0-9]Te[0-9]|^[A-Z][a-z].*?[0-9]Bi[0-9]|Ag[A-z].*?|Ag.*?[0-9]|.*?BiTe|Bi[0-9].*?

tp: 46

fp: 1216

fn: 0

presision: 0.03645007923930269

recall: 1.0

F-score: 0.07033639143730885


**Material_Oxide**

^[A-Z][a-z].*?[0-9]O[0-9].*?$|[A-Z][a-z]O[0-9].*?$

tp: 14

fp: 297

fn: 0

presision: 0.04501607717041801

recall: 1.0

F-score: 0.08615384615384615


**Material_Clathrate**

^[A-Z][a-z]8[A-Z][a-z]16[A-Z][a-z]30$

tp: 2

fp: 6

fn: 0

presision: 0.25

recall: 1.0

F-score: 0.4

**Material_Skutterudite**

^[A-Z][a-z][A-Z][a-z]3$|^[A-Z][a-z][A-Z][a-z]4[A-Z][a-z]12$|Ce[0-9]

tp: 7

fp: 54

fn: 0

presision: 0.11475409836065574

recall: 1.0

F-score: 0.2058823529411765

**Material_Heusler-based_phase**

Fe[0-9].*?V

tp: 1

fp: 60

fn: 0

presision: 0.01639344262295082

recall: 1.0

F-score: 0.03225806451612903

**Material_silicides**

Si[0-9]

tp: 13

fp: 208

fn: 0

presision: 0.058823529411764705

recall: 1.0

F-score: 0.1111111111111111

**Material_Other**

現状収集していない


# Value

**Temperature (temp): 温度**

^[0-9]K|^[0-9][0-9]K|^[0-9][0-9][0-9]K|[0-9].*?oC|[0-9].*?OC|^T=[0-9].*?K

tp: 12

fp: 201

fn: 77

presision: 0.056338028169014086

recall: 0.1348314606741573

F-score: 0.07947019867549668

**PF: power factor/性能指数**

PF=.*?$|[0-9]μWcm-[0-9]K-[0-9]|μWcm-[0-9]K-[0-9]|Wm-[0-9]K-[0-9]

tp: 3

fp: 151

fn: 10

presision: 0.01948051948051948

recall: 0.23076923076923078

F-score: 0.03592814371257485

**ZT:無次元性能指数 **

ZT=.*?$

tp: 9

fp: 96

fn: 69

presision: 0.08571428571428572

recall: 0.11538461538461539

F-score: 0.09836065573770493

**Thermal conductivity (kapp):熱伝導率**

[0-9].*?Wm-[0-9]K-[0-9]

tp: 5

fp: 40

fn: 7

presision: 0.1111111111111111

recall: 0.4166666666666667

F-score: 0.17543859649122806

**Electrical conductivity (sigma):電気伝導性**

^[0-9].*?Sm-[0-9]

tp: 1

fp: 4

fn: 2

presision: 0.2

recall: 0.3333333333333333

F-score: 0.25

**Electrical resistivity (rho):電気抵抗率**

現状収集していない


**Seekeck/seebeck:ゼーベック係数**

μVK-[0-9]|S=.*?

tp: 2

fp: 59

fn: 5

presision: 0.03278688524590164

recall: 0.2857142857142857

F-score: 0.05882352941176471

**ohter**

^x=.*?$|^y=.*?$

tp: 12

fp: 372

fn: 10

presision: 0.03125

recall: 0.5454545454545454

F-score: 0.059113300492610835
