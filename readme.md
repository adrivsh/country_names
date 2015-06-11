These files provided with no warranty whatsoever.
If you spot an error you can send me an e-mail to adrien.vogt.schilb@gmail.com.
If you know a better repo tell me. If you have more matches send me (or fork this git).

##USAGE

* iso3_to_wb_name matches iso3 to the name of the country using the spelling that the World Bank likes to use
* iso3_WBname_iso2_uni_undp_fasotat_gaul provides even more correspondences
* names_to_iso matches several possible spellings of the country names to iso3, iso2 and iso number codes.

##GOTCHAS

* The European Union uses codes that look like iso2 but are actually slightly different. EU uses "EL" for "GR" (Greece in iso2) and "UK" for "GB" (Great Britain in iso2). In python pandas use .replace({"EL":"GR","UK":"GB"})
* Some people use old iso3 codes. replace "ROM" with "ROU" and "ZAR" with "COD" to go from old to new iso3
in python pandas use .replace({"ROM":"ROU","ZAR":"COD"})


