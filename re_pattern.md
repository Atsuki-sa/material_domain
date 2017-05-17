# regular expression (Recall-based)

# Material

###
|Class|TP|FP|FN|Prsicion|Recall|
|-----------|-----------|-----------|-----------|-----------|-----------|
|Material_Te/Bi|46|1216|0|0.04|1.00|
|Material_Oxide|14|297|0|0.04|1.00|
|Material_Clathrate|2|6|0|0.25|1.00|
|Material_Skutterudite|7|54|0|0.11|1.00|
|Material_Oxide|1|60|0|0.02|1.00|
|Material_Oxide|13|28|0|0.06|1.00|
###

**Material_Te/Bi**

^Bi.*?Te|^[A-Z][a-z].*?[0-9]Te[0-9]|^[A-Z][a-z].*?[0-9]Bi[0-9]|Ag[A-z].*?|Ag.*?[0-9]|.*?BiTe|Bi[0-9].*?

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

###
|Class|TP|FP|FN|Prsicion|Recall|
|-----------|-----------|-----------|-----------|-----------|-----------|
|Temperature (temp)|12|201|77|0.06|0.13|
|PF|3|151|10|0.02|0.23|
|ZT|9|96|69|0.09|0.12|
|Thermal conductivity (kapp)|5|40|7|0.11|0.42|
|Electrical conductivity (sigma)|1|4|2|0.20|0.33|
|Seekeck|2|59|5|0.03|0.29|
|Other|12|372|10|0.03|0.55|
###

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

現状収集していない(出現がほとんどなく、記述できない)


**Seekeck/seebeck:ゼーベック係数**

μVK-[0-9]|S=.*?

**ohter**

^x=.*?$|^y=.*?$
