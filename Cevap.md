# Merge Sort Örneği

16, 21, 11, 8, 12, 22

16, 21, 11 || 8, 12, 22 (Birinci grup ve İkinci grup)

Birinci grup karşılaştırmaları

16, 21 || 11

16, 21 (16 < 21)

11, 16, 21 (11 < 16 & 11 < 21)

Birinci grubun son hali --> 11, 16, 21


İkinci grup karşılaştırmaları

8, 12 || 22

8, 12 (8 < 12)

8, 12, 22 (22 > 8 & 22 > 12)

İkinci grup son hali --> 8, 12, 22


İki grubun karşılaştırmalı birleştirilme sonucu 8, 11, 12, 16, 21, 22


O(NlogN)