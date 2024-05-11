Compressor
==========
Wat een compressor doet is: harde passages zachter maken. Een soort automatische volumeknop dus! Hoe sterker de compressie, en hoe lager de drempel, hoe egaler het volume wordt. Doordat het gemiddelde volume daardoor groter wordt "komt het geluid er beter door". Om die reden worden bijvoorbeeld radio-uitzendingen gecomprimeerd: als je je radio zacht hebt staan vallen daardoor de zachte passages niet weg tegen het stofzuiger-geluid en hoef je voor een harder nummer niet je radio zachter te gaan zetten uit angst voor een burenruzie! Bij teveel compressie gaat de dynamiek verloren en vervormt het geluid extreem. In de volgende video wordt het duidelijk uitgelegd:

.. youtube:: bAA0kKEFByQ
   :width: 100%

Instellingen
-------------
- **Threshold**: drempel, als het signaal boven deze drempel komt begint de compressie te werken. Zolang het signaal onder die drempel blijft, verandert er niets aan het geluid. De draaiknop voor de compressor in de super-strip veranderd deze instelling.
- **Ratio**: meestal regelbaar van 10:1 of minder. Als de ratio bijvoorbeeld 2:1 is, wordt een volume van 10dB boven de threshold-waarde door de compressor teruggebracht tot 5dB boven die waarde. Bij een soft-knee instelling wijzigt de compressie geleidelijk, bij een hard-knee instelling vrij plotseling. Sommige compressors hebben ook nog een een mogelijkheid voor een intelligente ratio-instelling ("interactive knee") die zich voortdurend aanpast aan het soort signaal om zo onopvallend mogelijk te werken.
- **Attack**: hoe lang de compressor wacht met reageren op een pieksignaal, in msec (milliseconden, duizendste seconden) aangegeven. Als de attack op 20 msec staat, wordt een kortstondige piek van 5 msec lang niet gecomprimeerd. Een extreem korte attack gecombineerd met een lange release tijd produceert een soort "achterstevoren" effect op bijvoorbeeld drumbekkens of snaredrum en wordt soms als effect gebruikt. (Fast attack: Thinner, Slow attack: Thicker)
- **Release**: hoe lang de compressor wacht met reageren nadat het signaal weer onder de drempelwaarde is gekomen. Ook gemeten in msec. Attack en release instellingen zijn erg afhankelijk van het soort signaal. Experimenteren dus om er voor te zorgen dat je de compressor niet hoort "zuchten", vooral bij een hoge ratio instelling. Dat zuchten hoor je overigens sterker bij een signaal met veel ruis of andere achtergrondgeluiden die steeds (ongeveer) even sterk zijn. Daaraan kun je dan horen als de compressor de versterking wijzigt.
- **Gain**: Aangezien een compressor het signaal alleen verzwakt als het boven een bepaald niveau komt, wordt het algehele geluid gedempt. Om het weer terug te brengen naar de nullijn kan er makeup-gain toegepast worden.

De werking van een compressor wordt in een grafiek weergegeven. Op de horizontale as zie je dan de sterkte van het ingangssignaal, op de verticale as de sterkte van het uitgangssignaal. Als het ingangssignaal toeneemt, neemt de versterking (gain) steeds verder af. Een compressor beperkt dus de dynamiek (het verschil tussen hard en zacht).

.. image:: /images/compressie_grafiek.gif

Een compressor kan vaak ook als limiter gebruikt worden. Dit doe je door de ratio op oneindig te zetten. Hiermee zal het signaal nooit boven de threshold uitkomen. Een limiter wordt bijvoorbeeld gebruikt om speakers te beschermen, om vervorming te voorkomen bij digitale opnames, bij in-ear systemen om je oren te beschermen, of in kroegen om de geluidsnormen niet te overtreden.