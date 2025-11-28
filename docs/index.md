# DENOG Working Group Access

Die **Working Group (WG) Access** soll ein dediziertes Forum für den Austausch und
die Erarbeitung von Lösungen rund um nationale Themen im Bereich der Internet 
Service Provider (ISP) und Access-Infrastrukturen in Deutschland schaffen. Im 
Fokus stehen jene spezifischen Herausforderungen und Fragestellungen, die aufgrund 
nationaler Regularien, Gesetzeslagen oder einzigartiger Marktbedingungen nicht 
in der allgemeinen Standard-Literatur oder internationalen Foren behandelt werden.

Themen wie Routing oder Peering werden weiterhin von der [DENOG WG Routing](https://routing.denog.de) 
behandelt. Beide Gruppen arbeiten eng zusammen, insbesondere dort, wo es Überschneidungen gibt.

## Thematische Schwerpunkte:

Die Gruppe wird sich mit der gesamten Bandbreite der Prozesse und Technologien befassen, 
die für den Betrieb eines deutschen ISP relevant sind, insbesondere:

1. **Broadband Network Gateway (BNG):** Austausch zu BNG-relevanten Themen, von der Weitergabe von Standardkonfigurationen (z.B. QoS) und Entscheidungshilfen für die Wahl zwischen PPPoE oder IPoE, bis hin zur gemeinsamen Erarbeitung von Konfigurationstipps zur Steigerung der Service-Qualität und operativen Effizienz.
2. **Access-Technologien:** Fokus auf den Austausch zu allen relevanten Zugangstechnologien, mit besonderem Augenmerk auf xDSL, wo in Deutschland spezifisches Expertenwissen oft rar ist. Weiterhin behandeln wir PON, AON und DOCSIS, die Übertragung Leitungsspezifischer Informationen via Intermediate Agent oder ANCP, sowie die Vor- und Nachteile verschiedener VLAN-Modelle (wie 1:1 oder N:1). 
3. **L2BSA:** Ein besonderer Fokus liegt auf dem Layer-2-Bitstromzugang (L2BSA). Hier besteht ein erheblicher Bedarf, gemeinschaftlich neue technische Lösungen und Best Practices zu erarbeiten und diese gegebenenfalls proaktiv den zuständigen Behörden vorzuschlagen. Dies soll verhindern, dass die Community von den Ergebnissen weniger großer Marktteilnehmer abhängig ist. Spezifische Herausforderungen, wie der Betrieb von L2BSA-Szenarien mit 100G bzw. 400G-Schnittstellen und der Umgang mit mehr als 4095 Kunden pro Schnittstelle, bilden hierbei wichtige Diskussionsschwerpunkte.
4. **L3BSA:** Adressierung von L2TPv2-basierten Diensten, die nach wie vor signifikante operative Relevanz im deutschen ISP-Markt aufweisen.
5. **IP-Adress-Effizienz und Einsparungstechnologien:** Optimierung der IPv4-Adressressourcen durch Technologien wie CGNAT, DS-Lite und MAP-T zur Reduktion des Bedarfs an öffentlichen IPv4-Adressen.
6. **IT, OSS & BSS-Systeme:** Diskussion und Best-Practice-Austausch zu den dazugehörigen operativen und geschäftlichen Unterstützungssystemen, einschließlich Inventory und Provisionierung.
7. **Auto Configuration (ACS) und CPE Management:** Hier geht es um alles rund um das CPE Management. 
8. **PON ONT Management:** Verwaltung von Optical Network Terminals (ONT)  im PON-Umfeld, einschließlich Firmware-Aktualisierungen von Kundensystemen sowie Kompatibilitätslisten zwischen OLT und ONT Modellen.
9. **Authentifizierung & Accounting:** Vertiefung der Themen RADIUS und die Erfüllung nationaler Vorgaben bezüglich Accounting und Protokollierung.
10. **Nationale Regulatorische Anforderungen (Exklusive Deutschland-Themen):** Ein zentraler Fokus liegt auf der Umsetzung und den technischen Implikationen von in Deutschland gültigen Pflichten, wie z.B.: Legal Interception (LI), Vorratsdatenspeicherung (VDS) / Verkehrsdaten-Speicherung, Verbindungspreisberechnung (TKG §45g), NIS2 oder S/PRI.
11. **Referenzkonfigurationen:** Dokumentation und Austausch von Referenzkonfigurationen etablierter Netzwerkhersteller einschließlich BNG, CGNAT, OLT, MASN und weitere relevante Systemkomponenten.
12. **IPTV:** Bereitstellung und Betrieb von Unicast- und Multicast-basierten IPTV-Diensten unter Beachtung regulatorischer und technischer Anforderungen. 
13. **VoIP:** Adressierung von technischen Lösungsansätzen und regulatorischen Anforderungen wie beispielsweise Notruf im Kontext von IP-basierten Telefonie-Diensten.
14. **Geschäftskunden:** Austausch zu Best Practices bei der Bereitstellung von Diensten im Individualmarkt sowie für Geschäfts- und Unternehmenskunden. 

!!! danger "Haftungsausschluss"

    Die DENOG Working Group Access beschäftigt sich zwar mit Themen, die Regularien und rechtliche Fragestellungen beinhalten können, stellt jedoch ausdrücklich keine Rechtsberatung dar und übernimmt keinerlei Gewähr für die Richtigkeit der bereitgestellten Informationen. Die in der Arbeitsgruppe besprochenen Inhalte dienen ausschließlich Informationszwecken und sind weder verbindlich noch als Ersatz für eine qualifizierte juristische Beratung zu verstehen. Für individuelle rechtliche Anliegen wird empfohlen, einen zugelassenen Rechtsanwalt oder eine entsprechende Fachperson zu konsultieren.

## Arbeitsweise & Ergebnis:

Die Working Group dient primär als Austauschplattform für Provider und Hersteller (BNG, CPE oder OLT), um in einem vertrauensvollen Umfeld Lösungen für nationale Problemstellungen zu finden und voneinander zu lernen. Darüber hinaus soll die Gruppe aktiv an der Erstellung von eigenen Dokumenten und Guides arbeiten, wie beispielsweise einem "Handbuch für deutsche Service Provider", das die Komplexität des deutschen Internet-Ökosystems widerspiegelt und konkrete Hilfestellung bietet.

Als konsequente Folge der nationalen Themensetzung wird die Arbeitssprache primär Deutsch sein.

Wir sind davon überzeugt, dass dieses Working Group einen signifikanten Mehrwert für die deutsche DENOG-Community schafft, indem es ein lange überfälliges Forum für diese spezifischen, nationalen operativen und regulatorischen Themen bietet.

## Mitarbeit

Die Zusammenarbeit innerhalb der Working Group Access findet hauptsächlich über die Mailingliste
[denog-wg-access@denog.de](https://groups.google.com/a/denog.de/g/denog-wg-access) und aktuell 
auch über einen [Matrix Chat](https://matrix.to/#/#denog-wg-access:matrix.org) statt.

Die aktive Mitgestaltung dieser Webseite, insbesondere das Bereitstellen von Beispielkonfigurationen,
Informationen und Best Practices, erfolgt über Pull Requests auf das GitHub Repository. Dabei wird das
von der Working Group Routing entwickelte und bereitgestellte Tooling verwendet. Dort sind auch eine
ausführliche [Anleitung](https://routing.denog.de/contribution/) sowie ein 
[Code of Conduct](https://github.com/denog/routing-guide/blob/main/CODE_OF_CONDUCT.md) 
zu finden, dem wir uns ebenfalls verpflichtet fühlen.
