# Data wiki

<!-- TOC titleSize:2 tabSpaces:2 depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 skip:0 title:1 charForUnorderedList:* -->
## Table of Contents
* [Data wiki](#data-wiki)
* [Geographic Definitions](#geographic-definitions)
  * [Grunnkrets (Basic statistical units; BU)](#grunnkrets-basic-statistical-units-bu)
    * [Definition from  Byfuglien 1986](#definition-from--byfuglien-1986)
      * [Older Definitions](#older-definitions)
    * [Grunnkretser, tettsteder og menigheter: Dokumentasjon (1983)](#grunnkretser-tettsteder-og-menigheter-dokumentasjon-1983)
* [Definitions of urban area](#definitions-of-urban-area)
  * [Urban regions in Nordic countries](#urban-regions-in-nordic-countries)
    * [Tätort](#tätort)
    * [Tettsted](#tettsted)
<!-- /TOC -->

# Geographic Definitions

##  Grunnkrets (Basic statistical units; BU)

Also known as just statistical units sometimes by statistics norway, [link](https://www.ssb.no/en/klass/klassifikasjoner/1). There seems to be versions every year.

Each municipality is split into multiples BSUs -- no BSU is in two municipalities. There is degree of consistency over time for BSUs:

> In addition to being stable over a certain time period, statistical units should also be geographically coherent areas. Another main criteria is that statistical units should be homogeneous, with respect to nature and basis for economic activities, conditions for communications, and structure of buildings.

The higher order **Statistical Tracts** or **Delområde** are made up of BUs (or rather BUs were split from Tracts).

The digits of the BU are explained by Liv in an email (my comments in italics):

> Consist of 8 digits (e.g. 11060713): the 2 first digits( 11)  represent county (fylke), the first 4 digits represent the municipality (1106)[*also known as kommunenum*]. The digits 07 represent  statistical tract (*Delområde*), and 13 represent the basic statistical tracts (*BU*). All 8 digits is used to enumerate the basic statistical tract. There are different versions of these numbers (this link contains an overview of all versions[1]), which change when e.g. municipalities are merged.

### Definition from  Byfuglien 1986

Trying to find an English source from data.

> Byfuglien, Jan. 1986. ‘The Analysis of the Settlement Pattern in Relation to Planning Problems’. Norsk Geografisk Tidsskrift - Norwegian Journal of Geography 40 (4): 187–94. https://doi.org/10.1080/00291958608552163.

**Note** Jan Byfuglien seems to be key in making the BU. The BU are old and based on the 1980 census.

**Issue: Primary sources on BU is in Norwegian**

[Grunnkretser, tettsteder og menigheter: Dokumentasjon (1983)](https://ssb.brage.unit.no/ssb-xmlui/bitstream/handle/11250/2681595/rapp_198313.pdf?sequence=1)

Overview is this (haven't found):

> Byfuglien, J. 1985. The integration of data for local planning
with a national system of statistics: A Norwegian approach.
Joint UDM-SORSA symposium. The Hague, 2-6 June 1985

**Summary:** Issue seems to be on analysing Norway using a consistent statistical basis for planning and etc. So it shows off the BU.

On p.188; prior to 1980s municipalities were lowest at which stats were produced then came BU based on the census:

> As a part of the preparation of the 1980 population census a
new regional system was established with **basic
units ('grunnkretser') as building-blocks**. The
background for this was the growing demand for
more detailed and flexible regional statistics, and
the possibilities of maintaining the system on a
regular basis through the GAB-system. The
**GAB-system consists of registers on ground properties (G), addresses (A) and buildings (B) which
are going to be maintained and used by the
municipalities and other regional agencies**, St.
meld. nr. 25 (1977-78).

> The system was built up by subdividing municipalities with more than 2,000-3,000 inhabitants
in **statistical tracts**. These were further divided
into **basic units**. The statistical tracts were formed
to be an intermediate, comparable level useful
for some statistical purposes. The tract often corresponds to **some former municipalities, to a parish or a school district**. The basic units are identified by four numbers, two for statistical tract and
two for basic unit.

**Note**: So from above it goes tract --> BU; tracts often but not always some kind of meaningful feature. The below paragraph confirms these are the number match the BU and Tracts we see today (roughly):

> There are 1,553 statistical tracts with an average
population of 2,600, and 13,470 basic units with
an average population of 300.

Also both the boundaries and centroid are recorded (same page).

---
####  Older Definitions

From p.187; here are the older land definitions. Some definitely appear in older files Arnstein showed me:

> Some like to focus on the landsdel level (major region);
some on lower regional levels, fylke, (county)
region or kommune (municipality); and some are
more interested in the local level, kretser (enumeration districts)

----

**Note:** Interestingly the rest of the paper also deal with categorising the centrality of BU and commuting areas.

### Grunnkretser, tettsteder og menigheter: Dokumentasjon (1983)

We had to google translate this from the [PDF](https://ssb.brage.unit.no/ssb-xmlui/bitstream/handle/11250/2681595/rapp_198313.pdf?sequence=1).

**Note** The transliteral meaning of Grunnkretser is circuit/ circles / basic circles -- the translation isn't great. Individual handbooks were made for more detail on BU in each municipality (see p.10)

**Summary**: Basically the BU / Statistical Tracts were created out of older units whenever possible (themselves based on school districts/ parish and electoral consistuencies). Then municipalities were consulted re: the exact borders of Tracts then BUs within tracts. The same BU were designed to be consistent over time.

**Note** BU seem to be 4 digits in 1980. 0000 is the BU for people without permanent address (section 3.8). The modern BU id might be composed of those 4 digits with digits for municipality?

**Note:** Due to the way it was done -- tracts (or Delområde) are more 'natural' boundaries than BU (see p.16).

**Preface**:
> This report provides a background for and assessment of the work carried out in connection withthe division of municipalities into basic districts and parishes, and the delimitation of settlements. The work has happenedin close collaboration with municipal and church authorities. Emphasis has been placed on creating a division intobasic circles that can be a useful tool in planning and management.

**Basic reason** why BU had to be created was municipalities were getting confusing (they range hugely in size) and a better way more consistent way of breaking them up was needed .

Even early definitions such as **kretsinndelingen** (in 1950s) were based on weird rules based on existing school and parish boundaries (p.10):

> To obtain the census material, the individual municipalities were not divided into smaller areasgreater than that a counter could perform the count accurately in a short time. In a circular to the rapporteursin the manors (Statistics Norway, Census 1 December 1950, first issue), it is stated, among other things:**"As a rule, school districts shall be census districts, and no census district shall include several school districts.circuits**. However, the conditions may be such that a school district must be divided into two or more countingcircuits. This thus applies if the school district is so large that it will take too long for an individualcounts to count the whole district, and moreover when a school district is divided by the boundary between two parishes orsheriff's districts. Where one can say that a chapel district has a fixed boundary, the counting circuits must rathernot shared by this limit. If the area one wants to assign a counter includes parts of differentschool districts, chapel districts, parishes or sheriff districts, a separate census district must be createdfor each part.

Different and less detailed rules existed for Urban municipalities.

The more modern rules around counting was introduced in 1960s and 1970s (see p.11) but still different rules for urban and rural municipalities.

The pilot for what eventually became BU was trialled where Liv is in Haugesund (p.12):

> The work of revising the district division began in the spring of 1975. A number of pilot municipalities were identified.These municipalities were Haugesund, Øystre Slidre, Fræna, Tønsberg, Ringsaker and Osterøy.

Schools districted seemed to form a lot of the pilot along with electoral consistuencies.

For making the BU a list of principles were set out in section 3.4 (p.14) including consistent pop but also this one:

> The constituencies should be as comparable as possible to the census constituencies in 1970 andany previous counts, to allow historical studies. If not census circles andbasic circuits can be made directly comparable, the circuits should be able to be grouped into comparable unit

The exact boundaries were done in consultation with the municipalities:

> As early as 1976, the first municipalities were contacted. Each municipality was sent a note wherethe scope of the individual census constituency in 1970 was listed. In the note, there was also a suggestionor sketch for division into sub-areas and basic districts. First in the note, a proposal was put forward /sketch for division into sub-areas. The sub-areas were then again proposed to be divided into basic districts


# Definitions of urban area

## Urban regions in Nordic countries

In the 1960s, the Nordic countries agreed a common definition of urban area based on population density. English wiki [link](https://en.wikipedia.org/wiki/Urban_areas_in_the_Nordic_countries):

> An urban area is a densely populated area. An urban area is defined in Denmark , Finland , Norway , Iceland and Sweden as a contiguous area with at least 200 inhabitants where the distance between the houses is less than 200 meters.

**Note:** the 1960s date is mentioned in various places (including stat norway website). Have no idea what agreement between whom; maybe census / stat agencies? Maybe Nordic Council agreement -- they are interparlimentary body formed in 1952.

This is the main gist; the full rules are a bit longer. In practise each country slightly deviates in its methodology. Each also a different term: tätort (Sweden) and tettsted (Norway). These are not the same as international definitions of urban area such as Functional Urban Area (from the OECD).

**Note**: All are defined without regard to adminstrative boundaries.


### Tätort

Sweden's urban area defintion; although known in English as 'locality'. See stats Sweden [here](https://www.scb.se/en/finding-statistics/statistics-by-subject-area/environment/land-use/localities-and-urban-areas/).

We have a pdf on Tatort from 1960 - 2005 with only some background. See (Statistics Sweden 2009) in Zotero. Sweden in that report only had 5 Tatort over 100k.

 Sweden's change to urban area:

> In Sweden, it is also required that the proportion of leisure properties is less than 50 percent, alternatively (since 2010) that the day population (who work in the locality) has a size that exceeds 10 percent of the night population, for the area to be classified as an urban area. Prisoners in institutions are not included in the population. In Sweden, Statistics Sweden updates the division into urban and small towns every five years based on these criteria.

The sources are bit flakey. I think this may be the original source file [here](https://translate.googleusercontent.com/translate_c?depth=1&hl=en&prev=search&pto=aue&rurl=translate.google.com&sl=sv&sp=nmt4&u=https://www.scb.se/contentassets/48ad89a072bd4779bf19cd94d06a7130/mi0810_do_2010.pdf&usg=ALkJrhhC8-Je7x4Y2174JONZaHWIfiEiLw#8). From p.8:

>The framework for geographical delimitation is in principle Sweden's land area together with buildings inProperty and building register from the National Land Survey and the Swedish Tax Agency. Framework for statistics is alsothe content of Statistics Sweden's Population Statistics (RTB etc.) and RAMS (Register-basedlabor market statistics).Urban areas are briefly defined as contiguous buildings with a maximum of 200 meters between the housesand at least 200 inhabitants

From defintions:

> Definition: Contiguous buildings with a maximum of 200 meters between the houses and a minimum of 200inhabitant. The delimitations are made independently of administrative divisions

Seems like they use raw house data and then buffer the points. So it is independent of adminstrative divisions.

**Note:** The over 200 inhabitants definition is still very small. Hence why there are over 1k Tatort in Sweden.

The first two digits of the Tatort code refers to the county. See [here](https://translate.googleusercontent.com/translate_c?depth=1&hl=en&prev=search&pto=aue&rurl=translate.google.com&sl=sv&sp=nmt4&u=https://sv.m.wikipedia.org/wiki/T%25C3%25A4tortskod&usg=ALkJrhg9xMAa1eTknLYyrJILoU4h4NFTJg)

Interesting tidbit below (from wiki):

>  After the introduction of business freedom and the extensive railway construction in Sweden, a number of new communities arose, often without administrative city status. Some became municipal communities or köpings , others remained in the formal administrative sense rural . There were also so-called outlying settlements next to, but outside, the administrative city limits. It therefore became increasingly necessary to create a concept that reported densely populated areas in relation to sparsely populated areas, regardless of municipal boundaries or municipal status

> The 1960 census brought lasting news. Then the boundaries began to be made by geographical expertise and they were drawn on maps. Through a uniform delimitation of all localities, the assessment of the urban concept became similar throughout the country.

> Map delimitation of urban areas is also done, and from 1980 they are also digitally stored.

In 2010, it was definitely done digitally using population stats.
There are potentially higher aggregations. But questionable [more info outside the wiki](https://translate.googleusercontent.com/translate_c?depth=1&hl=en&prev=search&pto=aue&rurl=translate.google.com&sl=sv&sp=nmt4&u=https://web.archive.org/web/20160818225230/http://urbanhistory.historia.su.se/publikationer/stat05.htm&usg=ALkJrhgDzmp1JkwDUSix7ET5qpeuONZmNQ):

> An urban region , [ 8 ] T-region or urban region is a larger contiguous area of ​​urban areas consisting of a main town ( central town ) with surrounding suburbs . The suburbs may have their own center but are strongly dependent on the capital's labor market, service and cultural offerings and more. Population statistics for urban regions were most recently produced in Sweden in 1995. [ 9 ] [ not in cited source ]

**Note** Urban region = tätortsregioner

### Tettsted

Here is the page related to tettsted from Norway [link](https://www.ssb.no/en/befolkning/statistikker/beftett). They refer to it in English as *Urban Settlements*.

From their definition of stats Norway (key bits-- from webpage under definition):

> A cluster of buildings shall be registered as an urban settlement if it is inhabited by at least 200 persons.

> **The distance between the buildings should normally not exceed 50 metres**, but for some space-demanding building categories - such as apartment buildings, industrial buildings, offices / commercial buildings, schools, hospitals etc. - the distance can be increased to 200 metres.

> Urban settlements are geographical areas with dynamic boundaries. Thus the number of urban settlements and their boundaries will change over time, depending on construction activity and changes of resident population.

> **The delimitation of the urban settlements is independent of the administrative boundaries.**

**Note**: Here administrative boundaries don't matter either.

From the background section it seems like it used to be updated every year since the 1990 (using an automatic method). However in 2013 there is a change in methods leading to break:

> During the period 1990 to 1998 the statistics have been elaborated on the basis of information from the municipalities own registration in the GAB-register. Since 1999 (expect of 2001 and 2010) the delimitation will be done by Statistics Norway using an automatic method (GIS). Data should not be compared unless the method is the same.

> In 2013 the method was revised to give a more precise delimitation. **The change involves a break in the time series**. The area of urban settlements declined, and the number of inhabitants increased, leading to 16 percent higher population density.
