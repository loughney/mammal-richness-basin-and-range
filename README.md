# mammal-richness-basin-and-range
Supplemental information, code, and output to accompany "Tectonic influence on Cenozoic mammal richness and sedimentation history of the Basin and Range, western North America"

R code files

* bootstrap_functions.r		: functions required to run bootstrapping analyses
* bootstrap_code.r			  : code to bootstrap species richness and localities, includes code to plot figures 2, 3, 4A, 5A

Data files

* BR_localities.csv			    		: all Basin and Range fossil localities from MioMap and the Paleobiology Database
* BR_species_occurrences.csv		: all mammalian species occurrences from MioMap and the Paleobiology Database
* NB_localities.csv					    : Northern Basin and Range fossil localities from MioMap and the Paleobiology Database
* NB_species_occurrences.csv		: Northern Basin and Range mammalian species occurrences from MioMap and the Paleobiology Database
* CB_localities.csv					    : Central Basin and Range fossil localities from MioMap and the Paleobiology Database
* CB_species_occurrences.csv		: Central Basin and Range mammalian species occurrences from MioMap and the Paleobiology Database
* SB_localities.csv					    : Southern Basin and Range fossil localities from MioMap and the Paleobiology Database
* SB_species_occurrences.csv		: Southern Basin and Range mammalian species occurrences from MioMap and the Paleobiology Database
* macrostrat_June-2021.csv			: number, thickness (m) and sediment-accumulation rates (SAR) of all sedimentary Macrostrat packages per time bin
* macrostrat_nonfossil_June-2021.csv	: number, thickness (m), and sediment-accumulation rates (SAR) of nonfossiliferous sedimentary Macrostrat packages per time bin
* macrostrat_lithology.csv				: thickness (m) of major lithologies of sedimentary Macrostrat packages
* fossiliferous_units_January-2021.csv	: number, thickness (m), and sediment-accumulation rate (SAR) of fossiliferous units per time bin
* area_change.csv						: area-change rates (km2/Myr) for subregions of the Basin and Range
* deformation_rates_January-2021.csv	: deformation rates (km/Myr) for subregions of the Basin and Range 

Figure files

* fig-4BCD_code.r		: code to plot Figure 4B, C, and D
* fig-5B_fig-S1_code.r	: code to plot figures 5B and S1
* fig-6_code.r			: code to plot Figure 6

All figures plotted in R were finished and formatted in Adobe Illustrator CC.

R analyses files 

* changepoint_output.r				: R code and output from changepoint analyses and t tests on means
* correlation_output_raw.r			: R code and output from correlation analyses on raw data
* correlation_output_differences.r	: R code and output from correlation analyses on first differences
* cross_correlation_output.r		: R code and output from cross-correlation analyses
* partial_correlation_output.r		: R code and output from partial-correlation analyses

Additional files

* column_descriptions.md	: description of columns in Data S1, S2, S3 spreadsheets
