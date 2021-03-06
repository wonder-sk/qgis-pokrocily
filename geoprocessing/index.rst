***********************************
Nástroje zpracování - Geoprocessing
***********************************

Kromě spouštění různých nástrojů a analýz z hlavního menu (položky
:menuselection:`Vektor` a :menuselection:`Rastr`), můžeme stejné (nebo
obdobné) funkce a mnoho dalších spouštět i z okna :item:`Nástroje zpracování`.

.. figure:: images/geoproc.png
   :scale: 80%

   Okno :item:`Nástroje zpracování`.

Použití nástrojů zpracování má hned několik výhod. V jednom okně
najdeme funkce z knihovny GDAL, algoritmy poskytované pluginy a další
funkce dostupných externích nástrojů jako jsou například GRASS GIS,
SAGA nebo R.

.. note:: Více o knihovně GDAL ve školení :skoleni:`GeoPython pro
          začátečníky <geopython>`. Nástroj GRASS GIS je podrobně
          popsán ve školení :skoleni:`GRASS GIS pro začátečníky
          <grass-gis-zacatecnik>`.

Jednotlivé funkce lze rychle vyhledávat pomocí filtru v horní části
okna. Snadno lze spouštět dávkové zpracování dat, a v neposlední řadě
funkce (včetně externích) lze používat v grafickém modeleru
(viz. kapitola :ref:`modeler`).

Algoritmy mohou generovat 4 typy dat:
	
	- rastrové vrstvy
	- vektorové vrstvy
	- tabulky
	- HTML soubory (textové a grafické výstupy) 
		
.. note:: Dalším výstupem může být například výběr prvků ve vektorové vrstvě.



.. toctree::
   :maxdepth: 2
   
   uvod
   spousteni
   nastaveni
   externi
   davka
           
