# regular expression

#Material

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


**Material_Clathrate**

^[A-Z][a-z]8[A-Z][a-z]16[A-Z][a-z]30$


**Material_Skutterudite**

^[A-Z][a-z][A-Z][a-z]3$|^[A-Z][a-z][A-Z][a-z]4[A-Z][a-z]12$|Ce[0-9]


**Material_Heusler-based_phase**

Fe[0-9].*?V


**Material_silicides**

Si[0-9]


**Material_Other**

現状収集していない


# Value

**Temperature (temp): 温度**

^[0-9]K|^[0-9][0-9]K|^[0-9][0-9][0-9]K|[0-9].*?oC|[0-9].*?OC|^T=[0-9].*?K


**PF: power factor/性能指数**

PF=.*?$|[0-9]μWcm-[0-9]K-[0-9]|μWcm-[0-9]K-[0-9]|Wm-[0-9]K-[0-9]


**ZT:無次元性能指数 **

ZT=.*?$


**Thermal conductivity (kapp):熱伝導率**

[0-9].*?Wm-[0-9]K-[0-9]


**Electrical conductivity (sigma):電気伝導性**

^[0-9].*?Sm-[0-9]


**Electrical resistivity (rho):電気抵抗率**

現状収集していない


**Seekeck/seebeck:ゼーベック係数**

μVK-[0-9]|S=.*?


**ohter**

^x=.*?$|^y=.*?$
