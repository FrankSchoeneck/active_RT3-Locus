1. Changelog

2. Beschreibung:
   Deutsch
   English

3. Installation:
   Deutsch
   English
   
4. Licenses


-------------------------------------------------------------------------
1. CHANGELOG
-------------------------------------------------------------------------
Version active_RT3_Locus, 09.07.2019
	- leisure=stadium wird nun besser angezeigt
	- Die Anzeige von place=locality wird nun bei "any" ab Zoom 16 angezeigt
	- Die Namen von natural=valley|canyon|peninsula werden nun angezeigt
	- Die Länge von safety_rope, ladder, rungs wird dargestellt
	- Die Textfarbe der Strassennamen von schwarz in eine dunkles grau geändert
	- Die Rahmen um Autobahn-Nr., Bundesstr.-Nr., etc. verbreitert
	- Via Ferrata (Klettersteige) wird nun dargestellt
	- aerialway=zip_line (einfachst Seilbahnen) wird nun dargestellt
	- Bei aerialway=station (Seilbahnstationen) wird nun der Name angezeigt
	- Leuchttürme (man_made=lighthouse) werden nun dargestellt
	- Wanderwegfarbe orange ergänzt
	- Wegemarkierungen können nun wahlweise dargestellt werden, unabhändig von davon ob Wanderwege dargestellt werden
	- Wanderwege Knotenpunkte (hiking nodes) werden nun, wahlweise, dargestellt (nur bei OpenAndroMaps)
	- Grenzen geschützter Gebiete wurde umbenannt in Grenzen + geschützte Gebiete (Theme Switcher)
	- Landesgrenzen sind nun über Grenzen + geschützte Gebiete schaltbar gemacht (Umschaltung über den Theme Switcher)
	- Hiking-Nodes werden nun über das Tag "Addr:housenumber" ausgegeben


HiLo Versionen:
Version 11, 05.03.2019
	- Darstellungsfehler von water in Zoo's behoben
	- Richtung für Sättel, Bergpässe hinzugefügt. Neues Symbol in vier Ausrichtungen angelegt (nur bei OpenAndroMaps)
	- Berggipfel und Vulkane (peak + volcano) wurden nun sortiert und verschiedenen Zoomstufen zugewiesen (nur bei OpenAndroMaps)
	- Wanderwegefarben (OSMC:COLOR) werden nun auch von OpenAndroMaps unterstützt
	- Wanderwegesymbole um yellow,green,blue arch ergänzt
	- Gebäude die im Bau sind (building=construction) werden nun angezeigt, der Rand hat eine andere Farbe (nur bei OpenAndroMaps)
	- historic=boundary_stone wird nun dargestellt
	- Bei waterway=canal wurde der Name nicht angezeigt

Version 10, 06.09.2017
	- Die Pattern für Wald verändert, um der Darstellung von "Outdooractive" näher zukommen
	- Texte in den Wanderwegemarkierungen (OSMC:SYMBOL) werden nun etwas zuverlässiger dargestellt.
	- Nicht ständig Wasserführende Bäche, Flusse, etc. (waterway intermittent=wwi_yes) werden gestrichelt dargestellt (nur bei OpenAndroMaps)
	- leisure=playground (Spielplätze) werden nun richtig angezeigt, Symbolgröße wurde angepasst und Beschriftung (ab Zoom 17) hinzugefügt
	- amenity=kindergarten (Kindergarten) wird nicht mehr in der gleichen Farbe wie school (Schule) angezeigt, hat nun keine besondere Farbe mehr
	- Fehler bei der Darstellung von scrub behoben, landuse steht nun vor natural im Code
	- Parkplätze wo der Zugang eine Lizenz oder eine Genehmigung verlangt (access=permit) werden nun dargestellt (nur bei OpenAndroMaps)
	- Wege mit Maut (highway=toll) werden nun mit roten Punkten dargestellt (wie bei OAM "Elevate")
	- Wege wo der Zugang eine Lizenz oder eine Genehmigung verlangt (access=permit) werden nun mit roten Punkten dargestellt (nur bei OpenAndroMaps)
	- Das Symbol für bus_stop (Bushaltestelle) wird nun in Deutschland anders dargestellt wie im rest der Welt (nur bei LoMaps)
	- Das Anzeigen von rock (Freistehende Steine) war nicht korrekt, daher die Anzeige nur auf node begrenzt.
	- Die Anzeige von rock (Freistehende Steine) wurde um stone (markante Steine) (für LoMaps) und nat_stone (für OpenAndroMaps) ergänzt
	- Das Symbol für rock (Freistehende Steine) neu gezeichnet
	- Landschaftsmerkmale schaltet nun auch rock (Freistehende Steine) ab
	- Die Farbe von highway=primary und trunk (Bundesstrassen und Schnellstrassen) in ein etwas kräfigeres Gelb geändert
	- Fehlerhafte Anzeige von information=map|board behoben
	- OSMC Wegesymbol "bcg_green_circle" hinzugefügt
	- man_made=cutline (Schneise im Wald) wird nun dargestellt (nur bei OpenAndroMaps)
	- man_made=cairn (Hügel von Steinen, Steinmännchen) wird nun dargestellt (nur bei OpenAndroMaps)
	- Darstellung der Wege vom Typ sac_scale=T5|T6 in schwarz mit lang-kurz-kurz-lang Strichen
	- Unterstützung von "raw_sac_scale" bei OpenAndroMaps entfernt
	- mountain_pass (Bergpass, Sattel) wird nun angezeigt, schaltbar über die Landschaftsmerkmale
	
Version 9, 20.01.2017
	- Bei Landstrassen und Bundesstrassen werden nur noch die "ref"s der Strasse angezeigt und keine Radwege/Wanderwege "ref"s mehr
	- Landstraßennummern ("ref") Schriftart etwas kleiner und nicht mehr in Bold
	- Autobahnnummern ("ref") Darstellung etwas verbessert
	- Staatsgrenzen werden nun deutlicher (breitere Linie) dargestellt
	- Bei peak (Bergspitzen) die Beschriftung etwas verkleinert
	- Landschaftsmerkmale schaltet nun auch cliff (Klippen) ab
	- way=tourism wird nun nach water gerendert, dadurch werden nun auch attraction auf dem Wasser angezeigt
	- tourism=attraction hat eine eigene Farbe bekommen, damit es eine Unterscheidung zu pedestrian (Fußgängerzone) gibt
	- railway|public_transport=platform (Bahnsteig) wird nun richtig dargestellt
	- barrier=lift_gate (Schranken) werden nun dargestellt, ab Zoom 17
	- Bei leisure=track (Laufbahn) Farbe angepasst
	- Die Namen von place=suburb (Stadtteile) werden nun schon ab Zoom 13 angezeigt
	- Die Namen von place=city,country,etc. (Städte,Länder,etc.) werden nun nicht mehr komplett in Großbuchstaben angezeigt
	- Die Anzeige von Hausnummern vereinheitlicht
	- historic=archaeological_site wird nun besser dargestellt
	- highway=cycleway wird nun in Weiss mit grauem Rand (etwas schmaler wie tracktype=grade1) dargestellt
	- Darstellungsreihenfolge bei tracktype=grade.. gedreht
	- Symbole von peak und vulcano überarbeitet
	- Neues Symbol peak_cross wird bei Gipfel mit Kreuz angezeigt
	- Neues Symbol cross  wird bei man_made=cross (Kreuz) angezeigt
	- natural=crater (Krater) werden nun angezeigt, ab Zoom 12 (nur bei OpenAndroMaps)
	- natural=crevasse (Gletscherspalte) wird nun angezeigt, ab Zoom 14 (nur bei OpenAndroMaps)
	- Bei den Contourlinien wird die Beschriftung nun nicht mehr gedreht dargestellt (benötigt Locus Map ab Version 3.21.1)

Version 8, 14.10.2016
	- Wanderwegemarkierungen (OSMC:SYMBOL) ist nun auch in den OpenAndroMaps enthalten und wird voll unterstützt
	- Wegemarkierungen können nun wahlweise dargestellt werden, aber nur wenn auch Wanderwege dargestellt werden
	- Darstellung der Parkplätze erfolgt nun auch bei ausgeschalteter Option richtig
	- Darstellung der Strassen- und Wegenamen verbessert
	- highway=tertiary (Hauptstrassen) werden nun wie bei Outdooractive in hellgelb dargestellt
	- way=dyke (Deich) wird nun angezeigt, ab Zoom 14 (nur bei OpenAndroMaps)
	- highway=tracktype die Darstellung der grade1...5 angepasst um die Erkennbarkeit zu erhöhen
	- highway=bridleway (Reitwege) werden erst ab Zoom 15 und in gröberer Strichlierung dargestellt
	- natural=rock (Nackter Fels) wird nun, mit Synbol, dargestellt (nur bei OpenAndroMaps)
	- natural=scree|shingle (Schutt, Hangschutt|Schotter, Kies) wird nun, mit Synbol, dargestellt (nur bei OpenAndroMaps)
	- natural=fell (Überwiegend mit Gras bewachsene Fläche oberhalb der Baumgrenze) wird nun dargestellt (nur bei OpenAndroMaps)
	- natural=marsh Symbol nun im SVG Format
	- natural=beach Symbol entfernt
	- landuse=vineyard Symbol nun im SVG Format und Farbe abgepasst
	- Bei highway=path|footway wird nun auch die trail_visibility (Sichtbarkeit) der Wege ausgewertet (nur bei OpenAndroMaps)
	- Bei highway=path|footway und highway=track wird nun bei foot=no, ab Zomm 14, zusätzlich eine orange gepunktete Linie angezeigt (nur bei OpenAndroMaps)

Version 7, 16.08.2016
	- leisure=garden Farbe an Outdooractive Optik angepasst
	- emergency_access_point (Rettungspunkte) können nun wahlweise dargestellt werden, ab Zoom 14 (nur bei OpenAndroMaps) (Umschaltung über den Theme Switcher)
	- Landschaftsmerkmale (Stromleitungen, Dämme, Bäume) können nun wahlweise dargestellt werden (Umschaltung über den Theme Switcher)
	- way=embankment (Damm, Wall) wird nun angezeigt, ab Zoom 14 (nur bei OpenAndroMaps)
	- Darstellung von waterway=riverbank (breiten Wasserwegen) und natural=water verbessert
	- man_made=dam (Damm) in der Optik angepasst, ab Zoom 16 wird der Name angezeigt
	- man_made=pier (Pier) in der Optik angepasst
	- amenity=drinking_water wird nun ab Zoom 15 angezeigt
	- natural=spring (Quelle) wird ab Zoom 14 angezeigt
	- amenity_fountain (Springbrunnen) wird ab Zoom 16 angezeigt
	- man_made=water_well (Brunnen) wird ab Zoom 16 angezeigt (nur bei OpenAndroMaps)
	- waterway|natural=waterfall (Wasserfall) Auswertung und Darstellung am Zoom 14 verbessert
	- man_made=tower (Aussichtstürme + Funktürme) Auswertung und Darstellung verbessert
	- admin_level (Grenzen) werden nun in einer anderen Linienart dargestellt (Strichliert) und die Namen werden angezeigt
	- place=islet wird nun augewertet, damit werden kleine Inseln nicht mehr mit riesiger Schrift angezeigt (place=island) (nur bei OpenAndroMaps)
	- Farbton von natural=sea (Meer) angepasst.
	- Bei natural=bay wird nun ab Zoom 13 der Name korrekt angezeigt (nur bei OpenAndroMaps)
	- amenity=parking (Parkplätze) wird nun any abgefragt, damit werden nun alle Parkplätze angezeigt
	- man_made=groyne (Buhnen in Gewässer) wird ab Zoom 15 dargestellt (nur bei OpenAndroMaps)
	
Version 6, 10.06.2016
	- highway=cycleway wird ab Zoom 14 wieder angezeigt
	- Bei natural=beach wird nun ab Zoom 15 der Name angezeigt
	- Bei natural=bay wird nun ab Zoom 13 der Name angezeigt (wird aber noch nicht von OpenAndroMaps oder LoMaps unterstüzt)
	- Farbige Darstellung der Wanderwege verbessert, Wege ohne osmc_color weiter an "Waymarked Trails" angepasst
	- safety_rope|ladder|rungs werden nun bei OpenAndroMaps dargestellt
	- amenity=drinking_water Symbolgröße angepasst, Darstellung ab Zoom 16
	- tunnel=yes Darstellung verbessert
	- tracktype=grade1 wird nun mit durchgezogenem Rand dargestellt
	- highway=living_street|unclassified|service in der Breite angepasst
	- landuse=allotments (Kleingärten) werden nun dargestellt
	- amenity=parking (Parkplätze) die Umrandung entfernt
	- landuse=farmyard (landwirtschaftliche Betriebsfläche) Farbe angepasst
	- landuse=meadow, grass (Wiese/Weideland, Rasenfläche) Farbe angepasst
	- building (Gebäude) werden nun ab Zoom 14 dargestellt, erst etwas heller, dann ab Zoom 16 dunkler
	- Grenzen geschützter Gebiete können nun wahlweise dargestellt werden (Umschaltung über den Theme Switcher)
	- National Park (leisure|boundary=nature_reserve|national_park|protected_area) Auswertung vereinfacht, Linienfarbe angepasst
	- tourism=caravan_site entfernt
	- natural=grassland (Unkultiviertes Grasland ohne Bäume und Büsche) wird nun angezeigt (nur bei OpenAndroMaps)
	- access=private um |acc_no ergänzt, Symbol nun im SVG Format
	- access=destination Symbol nun im SVG Format
	- natural=scrub Symbol nun im SVG Format
	- man_made=watermill Symbol überarbeitet und Größe angepasst
	- viewpoint Symbol überarbeitet, die SVG Datei war 18kB groß, jetzt 6kB
	- Bei peak, vulcano werden nun der Name und die Höhe angezeigt
	- stylemenu id ist nun eindeutig, keine Überschneidung mit anderen Themes mehr
	
Version 5, 08.04.2016
	- archaeological_site (archäologische Fundstätte) wird nun durch ein Symbol angezeigt, ab Zoom 16, nur bei OpenAndroMaps 
	- restaurant + cafe kann nun ab Zoom 16 durch ein Symbol angezeigt werden
	- gate (Tor, Schranke) wird nun ab Zoom 16 durch ein Symbol angezeigt
	- steps (Treppen/Stufen) in der Optik angepasst
	- Schwierigkeitsgrade der Wege wird anhand der SAC-Wanderskala dargestellt
	- Bei tourism=alpine_hut (Hütten) werden nun der Name und die Höhe angezeigt
	- scrub, patterns in der Optik angepasst
	- peak, vulcano Symbol leicht vergrößert darstellen
	- area und line ohne dp in den Größenangaben und damit nicht DPI abhängig
	- waterway=riverbank (Breite Flüsse) und waterway=river (Flüsse) werden nun mit dunkelblauem Rand dargestellt
	- lock (Schleuse) bei waterways wird nun angezeigt
	- leisure=track erweitert um |ls_track, Anpassung für OpenAndroMaps Karten ab 03.2016
	- natural=tree (Bäume) werden nun ab Zoom 16 durch ein Symbol angezeigt, caption in Größe, Farbe und Position angepasst, Anzeige erst ab Zoom 18
	- highway=service|unclassified|road die Breite etwas erhöht (+0.4), Anzeige erst ab Zoom 13
	- highway=residential die Breite etwas erhöht (+0.4), Anzeige erst ab Zoom 13
	- highway=service die Breite etwas verringert (-0.3), Anzeige erst ab Zoom 13
	- waterway=stream (Bach) Farbe angepasst
	- Codestruktur von highway outline und highway core angeglichen
	- Farbige Darstellung der Wanderwege verbessert, way=osmc_color die Breite erhöht (+0,4), Wege ohne osmc_color an "Waymarked Trails" angepasst
	- Beschriftung von Bahnhöfen/Haltestellen verbessert
	- Bei highway=bus_stop (Bushaltestellen) wird ab Zoom 18 der Haltestellenname angezeigt
	- Die Namen von Schulen/Universitäten/Bibliotheken werden nicht mehr angezeigt
	- frg_white_bar Symbol überarbeitet, Darstellung war falsch bzw. fehlerhaft
	
Version 4, 11.03.2016
	- peak Symbol überarbeitet, die SVG Datei war 157kB groß, jetzt 2kB
	- tourism=picnic_site nun Anzeige erst bei OpenAndroMaps ab Zoom 15, bei LoMaps ab Zoom 16
	- tourism=museum um Symbol ergänzt, Anzeige bei LoMaps ab Zoom 14, bei OpenAndroMaps ab Zoom 17
	- Wanderwege können nun wahlweise in Farbig oder Transparent dargestellt werden (Umschaltung über den Theme Switcher)
	- Höhenlinien in Farbe und Stärke an Outdooractive Optik angepasst, somit sind sie auch besser sichtbar
	- tracktype=grade3|grade4|grade5 sind nun erst ab Zomm 14 sichtbar, dadurch kommen die Höhenlinie in Zoom 13 klarer raus
	- Es wird nun die Versionsnummer im Odner und Dateinamen mitgeführt, dies erleichtert die parallel installation von mehreren Themen
	
Version 3, 04.03.2016
	- cemetery neues patterns erstellt und Hintergrundfarbe angepasst
	- cliff wird nun deutlicher dargestellt 
	- Optimierung der Renderreihenfolge
	- way=residential und way=service Größe angepasst
	- light_rail Schienen werden nun dargestellt
	- stadium, pitch, recreation_ground, garden, residential, construction an Outdooractive Optik angepasst
	- Textfarben und Textstyle von den verschieden captions angepasst
	- access=private Wege werden in grau dargestellt, ohne rote Schraffur
	- tower:type=communication und tower:type=observation Symbole neu erstellt
	- leisure=picnic_table neu aufgenommen
	- Wanderwege, nun auch bei LoMaps in Outdooractive Farben
	- Wanderwegemarkierungen Symbole vergößert, Bugfixing, es werden nur dort Symbole angzeigt wo auch welche getagt sind
	- Fernwanderwege lassen sich nun separat anzeigen, bei LoMaps jedoch nur ohne Wanderwegesymbole und auch erst ab Zoom 12 :(

Version 2, 17.02.2016
	- Wanderwege, bei OpenAndroMaps bzw. bei LoMaps wenn keine OSMC_color getagt ist, in Outdooractive Farben
	- Seilbahnen, Darstellung der verschiedenen Arten mit Symbolen, bzw. Darstellung angepasst
	- Beschriftungen der Gewässer angepasst
	- Militärbereiche werden nun richig dargestellt. (Es wurden keine Reservoirs oder Sportplätze in Militärbereichen gerendert)
	- Beschriftungen Naturschutzgebiete (protected_area) angepasst
	- Shelter Symbol neu erstellt, Name wird ab Zoom 16 angezeigt

Version 1, 09.02.2016
	- Fist Release

-------------------------------------------------------------------------
2. Beschreibung
-------------------------------------------------------------------------
DEUTSCH:
********

ENGLISH:
********
The HiLo theme is designed for clarity of display for hiking.
Its colours and styles are based on german Outdooractive maps.
The theme is designed to work well with maps from Locus Store (LoMaps) and OpenAndroMaps.

You can choose overlays for waymarked trails in transparent or colored mode when you select the theme in the Locus Maps app.
In LoMaps the trails are displayed with the corresponding way symbols (according OSMC).

It automatically scales for devices with displays of different resolutions and symbols enlarge smoothly for higher zoom levels.
The zoom levels at which various features appear has been adjusted to provide optimal information and reduce unwanted clutter.

-------------------------------------------------------------------------
3. INSTALLATION
-------------------------------------------------------------------------
DEUTSCH:
********
- Bitte darauf achten dass die heruntergeladene Datei "HiLo_Vx.zip" heißen sollte
- Wenn es ein Update von bisherigen HiLo Kartenstil ist: lösche alle alten Dateien und Ordner
- Entpacke HiLo_Vx.zip mit einem Android Datei Explorer nach "../Locus/mapsVector/_themes/HiLo" auf der SD-Karte oder im internen Speicher (kommt auf das Gerät an)
- Benutze in Locus den Button um den Kartenstil zu wechseln, der bei der Karte unten links erscheint wenn man eine Vektorkarte lädt (wenn nicht, drücke "Menü", "Einstellungen", "Karte - Bedienung & Leisten", wähle "Themenwechsler einblenden" unterhalb von "Kartenbildschirm - Leisten")
- Wenn nötig, berühre "mehr..." am Ende von "Interne Themen" und wähle dann den Namen des Themas, z.B. "HiLo"
- Um Kartenstile und Overlays zu ändern erscheint ein weiteres Menü wenn das Thema ausgewählt wird. Um diese später zu ändern, einfach wieder den Button benutzen. 
- Die Schriftgröße ist bereits an die Auflösung angepasst, ein zusätzlicher Multiplikator durch die App ist i.d.R. nicht notwendig

Wenn Probleme auftreten, die Ordnerstruktur sollte so aussehen:

../Locus/mapsVector/_themes/HiLo
                            osmc/*.svg
							patterns/*.svg
							symbols/*.svg
							.nomedia
                            HiLo.png
                            HiLo.xml
							Read_me.txt


ENGLISH:
********
- Please make sure you downloaded "HiLo_Vx.zip"
- If it's an update of existing HiLo map styles: remove all old files and folders
- Unzip HiLo_Vx.zip with an Android file explorer to "../Locus/mapsVector/_themes/HiLo" on your SD-Card or internal memory (depending on your device)
- In Locus use the button for changing the map style that should appear at the bottom left side of the map if you load a vector map (if not, use "Menu", "Settings", "Map - control & panels", touch on "Onscreen Maps Themes Switch" below "Map screen - panels")
- If necessary hit "Show more" below "Internal themes" and touch the name of the map style, e.g. "HiLo"
- For switching mapstyles and overlays, a menu pops up when choosing the map style. To change again later, just use the button again.
- The font size is already adjusted to the resolution, an additional multiplicator by the app is probably not necessary

If you have problems, your directory structure should look like this for Locus:

../Locus/mapsVector/_themes/HiLo
                            osmc/*.svg
							patterns/*.svg
							symbols/*.svg
							.nomedia
                            HiLo.png
                            HiLo.xml
							Read_me.txt


-------------------------------------------------------------------------
4. LICENSES
-------------------------------------------------------------------------

HiLo theme
**********
by Frank Schöneck
Contact: LocusUser1@gmx.de

based on locus_internal_theme and other themes

License:
********
This theme is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License: http://creativecommons.org/licenses/by-nc-sa/3.0/

This means you can feel free to reuse everything I made if you stick to those conditions:
- attribute the origin (for example: "symbols/patterns/code based on HiLo theme by Frank Schöneck")
- don't use it for commercial purposes, that means for example you are not allowed to include (also parts) or directly download with a commercial app; if in doubt contact me
- if you use some of my work it has to be under the same license
- have a look at the licenses of the resources I used below, those can differ - please also stick to those

I'm always happy to hear someone can use my work, so it would be nice if you contact me to let me know 
