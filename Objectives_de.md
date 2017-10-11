AndroidAPS hat eine Reihe an Objectives, die erfüllt werden müssen um dich durch die Funktionen und Einstellungen des loopens zu führen. Sie garantieren, dass du alles korrekt eingestellt hast und verstehst was das System genau macht, somit du ihm trauen kannst.
 
* **Objective 1:** Visualisierung und Konstrolle einrichten, und die Basalrate und Faktoren überprüfen
  * Wähle die richtige BZ-Quelle. Siehe [BZ-Quelle](https://github.com/MilosKozak/AndroidAPS/wiki/Blutzucker-Quelle_de) für Informationen.
  * Wähle deine Pumpe im ConfigBuilder (wähle Virtual Pump, wenn du eine Pumpe ohne Treiber für AAPS verwendest). Wenn du die Dana verwendest, versichere dich, dass du die [Dana R](https://github.com/MilosKozak/AndroidAPS/wiki/DanaR-Insulinpumpe_de) und [AAPS](https://github.com/MilosKozak/AndroidAPS/wiki/AndroidAPS_de) Anleitung gelesen, und richtig eingestellt hast.
  * Folge den Einstellungen zu [Nightscout](https://github.com/MilosKozak/AndroidAPS/wiki/Nightscout_de) um sicher zu stellen, dass du deine Daten erhältst und anzeigen lassen kannst.
<br><br>_Es könnte sein, dass du für den nächsten BZ warten musst, damit ihn AAPS erhält und akzeptiert._
 
* **Objective 2:** Start mit Open Loop
  * Wähle Open Loop, entweder in den Preferences, oder indem du den Loop Button drückst und hältst, dieser befindet sich links oben im Homescreen.
  * Aktiviere mindesten 20 vorgeschlagene temp. Basalraten manuell über einen Zeitraum von 7 Tagen (Falls du eine andere Pumpe verwendest, gebe die Vorschläge in der Pumpe ein und bestätige es in AAPS). Versichere dich, dass die Daten in AAPS und Nightscout angezeigt werden.
 
* **Objective 3:** Den Open Loop, mit seinen temp. Basal Empfehlungen, verstehen.
  *Versuche die Logik hinter den Empfehlungen zu verstehen indem du dir diese [Seite] (https://openaps.readthedocs.io/en/latest/docs/While%20You%20Wait%20For%20Gear/Understand-determine-basal.html), die Vorhersagelinie in AAPS/Nightscout und die Ergebnisse im OpenAPS Tab ansiehst.
<br><br>_Stoppe hier, wenn du den Open Loop mit der virtuellen Pumpe verwendest._

* **Objective 4:** Mit dem closed Loop mit Hypoabschaltung starten
  * Wähle Closed Loop von den Preferences, oder indem du den Open Loop Button links oben im Homescreen drückst und hältst.
  * Setze deinen Zielbereich, um sicher zu gehen, ein wenig höher als üblich.
  * Sehe dir an wie die temp. Basalraten aktiv sind, indem du die blaue Linie auf der Homescreen Grafik, oder in Zahlen darüber kontrollierst.
  * Gehe sicher, dass deine Einstellungen korrekt sind, wenn du über 5 Tage keinen Unterzucker mehr behandeln musstest, sollten die Einstellungen in Ordnung sein. Im anderen Falle solltest du deine Faktoren noch einmal kontrollieren.
<br><br>_Das System ist auf einen maxIOB von 0 begrenzt, d.h. dass der Loop eine Hypo abfangen kann, aber keine Steigungen, das System kann die BR nur erhöhen wenn der IOB unter 0 liegt und dadurch auf 0 bringen.._
 
* **Objective 5:** Tuning the closed loop, raising max IOB above 0 and gradually lowering BG targets
  * Raise your maxIOB above 0 over a period of 1 day, the default is recommended to be 2 but you should slowly work up to this until you know your settings work for you.
  * Once confident on how much IOB suits your looping patterns then reduce your targets to your desired level.
<br><br>_The system allows a low target to be a minimum of 4 or maximum of 10, and a high target to be a minimum of 5 and maximum of 15.  A temporary target as a single value can be anywhere in the range of 4 to 15._
 
* **Objective 6:** Adjust basals and ratios if needed, and then enable auto-sens
  * You can use [autotune](https://openaps.readthedocs.io/en/latest/docs/Customize-Iterate/autotune.html) as a one off to check your basals remain accurate, or do a traditional basal test.
  * Enable [auto-sens](https://github.com/MilosKozak/AndroidAPS/wiki/Open-APS-features) over a period of 7 days and watch the white line on the homescreen graph show how your sensitivity to insulin may be rising or falling as a result of exercise or hormones etc, and keep an eye in the OpenAPS report tab how AndroidAPS is adjusting the basals and/or targets accordingly.
<br><br>_Don’t forget to record your looping in [this form](http://bit.ly/nowlooping) logging AndroidAPS as your type of DIY loop software, if you have not already done so._
 
* **Objective 7:** Enabling additional features for daytime use, such as advanced meal assist
  * Now you should feel confident with how AndroidAPS works and what settings reflect your diabetes best, then over a period of 14 days you can try additional features that automate even more of the work for you.