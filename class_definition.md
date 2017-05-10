# Class definition on material domain

熱電素子のドメインの論文では、熱電半導体材料に熱（温度勾配）を与えると電位差が生じるというゼーベック効果を活用し、いかに効率良く熱電変換がおこなえる物質（熱電素子）を創るかという研究がおこなわれている。そのため、論文中から以下のエンティテイーを認識することが必要。

# Material

基本的に物質数値物質数値…の記述形式

物質の比率が異なる記述方法がある


**Material_Te/Bi:テルル-ビスマス化合物系**

・説明:主としてTe(テルル), Be(ビスマス)が含まれる材料。

・例: AgSbSexTe2-x(x=0-0.04), SnBiTe, (BiAgSeS0.97C10.03)0.5, Cu1-xInTe2, Ag(Sb0.97Sn0.03)Te2

・備考:


**Material_Oxide:酸素物系**

・説明: 酸素(Oxygen)を含む材料。

・例:SrTiO3, NaCo2, Ca3Co4O9, ZnO,In4-xGaxSn3O12, Ca3-xBixCo4O9+δ(x=0.5), NaXCo2O4

・備考: Oだけでは判別しにくい/専門知識の欠如による判定の難しさ


**Material_Clathrate:包接化合物**

・説明: I型からIX型まで9種類がある。A8X16Ge30(A=Sr, Ba, Eu; X=Al, GA, In)の形式をとる。

・例:(CH4)8(H2O)46, Ba8Ga16-xA1xSn30(0&leq;x&leq;12)

・備考: 

**Material_Skutterudite:スクッテルダイト系化合物**

・説明: TX3(T = Co, Rh, Ir; X = P, As, Sb)の構造を取る。TX3の隙間に希土類(rare elements)やアルカリ土類金属がほぼ100%入ったAT4X12は充填スクッテルダイトと呼ばれる。この場合はTがFe, Ru, Osに換わる。

・例:CoSb3, NiAs3, CoAs3, 5Ni1.S5b12, CeFe4Sb12, Ba0.L08a0.05Yb0.04, CeyMXCo4S-xb12

・備考: 

**Material_Heusler-based_phase:ホイスラーに基づく位相**

・説明: 

・例:Fe2V0.9W0.1A1

・備考: 出現例が上記のみのため、分類が難しい。


**Material_silicides:シリコン化合物**

説明: 

例:SiGe, β-FeSi2, Ba8Si48, Mg2Si, MnSi1.73など

備考: 

**Material_Other:その他**

説明: 

出現例:In4PbχSnySe3, Cu12-xNiXSb4S13

備考: 

# Value

とりたいものはTemp(温度)、PF(power factor/性能指数)、ZT(無次元性能指数)、Thermal conductivity(熱伝導率)、Electrical conductivity(電気伝導性)、Electrical resistivity(電気抵抗率)、Seebeck/seekeck（ゼーベック係数/熱発電能力）、Other

**Temperature (temp): 温度**

・説明: 温度。1000Kぐらいまでにおさまる。

・出現例:570K, 450OC, 650oC

・備考

**PF: power factor/性能指数**

・性能指数。現状値ではBi2Te3系の材料がもっと優れていて、PF~40μW/cm K^2程度。

・出現例:3.0×10-3Wm-1K-2, 0.30, 1.35×10-3Wm-1K-2

・備考:トークナイズが数字と単位で分かれている場合と、分かれていない場合があるので統一したい。K表記と℃(oC)の両方の表記がある。

**ZT:無次元性能指数 **

・説明: Z(熱電性能指数)にTを掛けると無次元量となるため、無次元性能指数と呼ぶ。現状値ではBi2Te3系の材料がもっと優れていて、ZT~1程度。0~2の間の数値。

・出現例:ZT=1.23, 0.16, (1.04&PlusMinus;0.08)

・備考:0~2の間の数値

**Thermal conductivity (kapp):熱伝導率**

・説明: 材料の熱電導率

・出現例:(k=1.34), (0.48Wm-1K-1), 1.3

・備考:Wmという単位が含まれるものを取れば良い？

**Electrical conductivity (sigma):電気伝導性**

・説明: 

・出現例:105, 3×103Sm-1

・備考: 

**Electrical resistivity (rho):電気抵抗率**

・説明: 

・出現例

・備考

**Seekeck/seebeck:ゼーベック係数**

・説明: 熱によって発電できる能力。単位温度差あたりに発生する電位差(V/K)の単位を持つ。金属では数～10数μV/Kが一般的で、半導体では100～数100μV/Kのオーダーの値をとる。

・出現例

・備考

**ohter**

・説明: その他
