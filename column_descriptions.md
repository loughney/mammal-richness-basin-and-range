mammal-richness-basin-and-range

#Data and code from Loughney, Badgley, Bahadori, Holt, and Rasbury, 2021, "Tectonic influence on Cenozoic mammal richness and sedimentation history of the Basin and Range, western North America"

Accompanies Data S1 - species occurrences from MioMap, FaunMap, and the Paleobiology Database.
Original data downloaded from https://ucmp.berkeley.edu/miomap/index.html on 31 October 2019; superfluous columns omitted.

column names
* Source DB				: the database containing the occurrence
* Machine Number		: unique collection identifier
* Site Name				: the name of the locality
* Analysis Unit			: specific information about the locality
* Alternate Name		: alternative locality name
* Class					: the identified class of the entry
* Order					: the identified order of the entry
* Family				: the identified family of the entry
* Genus					: the identified genus of the entry
* Species				: the identified species of the entry
* ID Confidence			: comment on identification of the entry
* Faunal Comment		: comment on the identification of the entry or reporting source
* Formation				: name of the formation containing the locality
* State					: the state in which the locality occurs
* County				: the county in which the locality occurs
* Site Number			: the locality number
* Comment				: comment on the location of the locality
* Quadrangle			: the name of the map quadrangle in which the locality occurs
* Quadrangle Size		: the size of the quadrangle (minutes)
* Latitude				: the latitude of the locality
* Longitude				: the longitude of the locality
* Repository			: the institution holding records of the entry
* Member				: name of the member containing the locality
* Period				: geochronologic period of the locality
* Epoch					: geochronologic epoch of the locality
* LMA					: North American Land Mammal Age of the locality
* Magnetochron			: magnetochronologic division of the locality
* Minimum Age			: youngest age estimate of the locality
* Minimum Age Method	: method used to date the minimum age
* Maximum Age			: oldest age estimate of the locality
* Maximum Age Method	: method used to date the maximum age
* Subregion				: subregion of the Basin and Range in which the locality occurs

Accompanies Data S2 - sedimentary packages from the Macrostrat database and additions from literature sources.
Original data downloaded from Macrostrat.org on 13 November 2018 using the API (https://www.macrostrat.org/api/units?age_top=0&age_bottom=40&response=long&format=csv); superfluous columns omitted.

column names (see https://macrostrat.org/api/units for more information)
* unit_id		: unique identifier of each package from Macrostrat.org. "nb_xxx," "cb_xxx," and "sb_xxx" identifiers denote packages added by the authors
* section_id	: unique identifier of each section from Macrostrat.org. "nb_xxx," "cb_xxx," and "sb_xxx" identifiers denote sections added by the authors
* col_id		: unique identifier of each column from Macrostrat.org. "nb_xxx," "cb_xxx," and "sb_xxx" identifiers denote columns added by the authors
* col_area		: area (square kilometers) covered by the column
* strat_name_id	: unique identifier for known stratigraphic names from Macrostrat.org
* Mbr			: lithostratigraphic member name
* Fm			: lithostratigraphic formation name
* Gp			: lithostratigraphic group name
* t_age			: top age of package (millions of years)
* b_age			: base age of package (millions of years)
* unit_duration	: complete time duration (millions of years) of accumulation of the package
* bin_duration	: time duration (millions of years) of accumulation of the package in each time bin
* t_bin			: top age (millions of years) of the time bin
* b_bin			: base age (millions of years) of the time bin
* max_thick		: maximum thickness (meters) of the package
* min_thick		: minimum thickness (meters) of the package
* unit_SAR		: sediment-accumulation rate (meters per million years) over the entire duration of the package
* bin_SAR		: sediment-accumulation rate (meters per million years) over the duration of the time bin
* bin_thick		: maximum thickness (meters) of the package in each time bin
* outcrop		: whether package is exposed or not; surface, subsurface, or both
* lith			: description and proportion of major lithologies comprising each package
* clat			: current latitude of the centroid of the column
* clong			: current longitude of the centroid of the column
* Subregion		: the subregion of the Basin and Range in which the package occurs
* Reference		: citation for age, thickness, or lithologic information used to add packages or to alter the original entry from Macrostrat.org

Accompanies Data S3 - fossiliferous sedimentary units compiled from literature sources.

column names
* Unit Name		: name of the unit
* Subregion		: the subregion of the Basin and Range in which the unit occurs
* State			: the state in which the unit occurs
* Thickness		: the maximum thickness of the unit
* top_age		: top age (millions of years) of the unit
* base_age		: base age (millions of years) of the unit
* unit_duration	: complete time duration (millions of years) of accumulation of the unit
* bin_duration	: time duration (millions of years) of accumulation of the unit in each time bin
* top_bin		: top age (millions of years) of the time bin
* base_bin		: base age (millions of years) of the time bin
* unit_SAR		: sediment-accumulation rate (meters per million years) over the entire duration of the unit
* bin_SAR		: sediment-accumulation rate (meters per million years) over the duration of the time bin
* bin_thickness	: maximum thickness (meters) of the package in each time bin
* Reference		: citation for age, thickness, or other geological information for each unit
* Comment		: comments about the unit