# HW

* HW1
	*Part 1 - Code run 1 - HTTP Scrape 
	
#Import Scientific Packages into Python Kernel
from bs4 import BeautifulSoup 
import requests 
import re 

import pandas as pd
import numpy as np

 #Set a user-agent in your header so you aren't flagged by the browser when making an HTTP request
headers = {'User-Agent': 'Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_1) AppleWebKit/537.36 (KHTML, like Gecko) \
           Chrome/39.0.2171.95 Safari/537.36'} 
	   
*Code run 1.2
All packages found (including pandas, numpy, Beautiful Soup). 

* Part 1.3.1
Images not shown. No output other than string variable root-url creation -> size = 105, http://caselaw.findlaw.com/court/us-supreme-court/years/.

* Part 1.3.2
 “Years” list created with an undefined variable limit, size currently at 2216. No output.
 * Part 1.3.3
Dataframe var = 374368. Creates data set. Output as follow: Out[12]: 'http://caselaw.findlaw.com/us-supreme-court/05-1101.html'
* Part 1.4
End Array size of (23393, 2). That is, 23K+ court cases available.

* Part 2
Packages reloaded as per instructions (e.g. Beautiful Soup, pandas, etc). As far as I can tell, the "supcourt" def is meant to be a service request limit for requests made to the web server. Similarly, these def's (Supcourt, test_df, test2_df and test3_df) are DF variables with given, varying sizes.
* Part 2.2
Purpose of database creation.
* Part 3
No errors so Im assuming something is going right(?).
* Part 4.
No output or readout (but I guess that's good since there are no error messages either).
	   
	   
* Tensorflow - Word2Vec Completed

/Users/justinjimenez/anaconda3/lib/python3.6/importlib/_bootstrap.py:219: RuntimeWarning: compiletime version 3.5 of module 'tensorflow.python.framework.fast_tensor_util' does not match runtime version 3.6
  return f(*args, **kwds)
Found and verified text8.zip
Data size 17005207
Most common words (+UNK) [['UNK', 418391], ('the', 1061396), ('of', 593677), ('and', 416629), ('one', 411764)]
Sample data [5234, 3081, 12, 6, 195, 2, 3134, 46, 59, 156] ['anarchism', 'originated', 'as', 'a', 'term', 'of', 'abuse', 'first', 'used', 'against']
3081 originated -> 5234 anarchism
3081 originated -> 12 as
12 as -> 6 a
12 as -> 3081 originated
6 a -> 195 term
6 a -> 12 as
195 term -> 2 of
195 term -> 6 a
2018-01-27 17:49:49.194220: I tensorflow/core/platform/cpu_feature_guard.cc:137] Your CPU supports instructions that this TensorFlow binary was not compiled to use: SSE4.1 SSE4.2 AVX AVX2 FMA
Initialized
Average loss at step  0 :  272.033447266
Nearest to a: pigweed, parte, detectives, somerset, meyers, amarna, jakarta, drucker,
Nearest to had: connecting, occultation, consecrated, sal, breve, benefited, datagrams, charterers,
Nearest to or: apes, donor, ergaster, beluga, transformation, nascar, comiskey, holmes,
Nearest to many: llewellyn, honouring, vargas, hou, nahuatl, labours, unpaired, behavior,
Nearest to one: postcards, surrenders, cancels, aha, slings, hollowed, firenze, congenial,
Nearest to nine: surpass, streamlining, implications, sounded, harshly, goalie, spot, superseding,
Nearest to all: alpaca, xxviii, screename, shikai, subtitling, dragoon, monopolize, precluded,
Nearest to five: kingdom, jays, bain, breeding, leland, psyche, resounding, dystopia,
Nearest to two: barbiturates, petrochemicals, archaeologists, lise, encompassing, ness, mycological, stouffer,
Nearest to states: squarely, gnome, nl, avalanche, geocache, nave, wellington, dwelling,
Nearest to these: geosynchronous, industrialist, screwball, crane, mosaic, anus, moments, billiard,
Nearest to of: shasta, maternal, ceylon, toe, burundi, honours, incorporated, clo,
Nearest to was: heartbreak, hammer, eisa, assad, passage, scottie, locator, ragged,
Nearest to war: integrates, appellant, leftmost, vernacular, jeremy, unsuited, ignored, sanctions,
Nearest to about: albury, bookshop, hexer, hmac, diana, prerequisites, teenagers, kyi,
Nearest to state: bonzos, parked, icc, henley, xxxix, souk, egon, sighting,
Average loss at step  2000 :  113.699126593
Average loss at step  4000 :  52.2736972332
Average loss at step  6000 :  33.6049896674
Average loss at step  8000 :  23.5933928249
Average loss at step  10000 :  18.1916000829
Nearest to a: the, gb, rich, reported, their, UNK, and, omega,
Nearest to had: connecting, deity, has, international, agave, borough, motor, presidents,
Nearest to or: and, lymphoma, archie, king, transformation, a, of, major,
Nearest to many: aberdeen, forall, the, behavior, llewellyn, glutamate, eugenics, languages,
Nearest to one: two, coke, agave, zero, vs, nine, canaris, omega,
Nearest to nine: zero, eight, coke, six, lymphoma, mosque, one, vs,
Nearest to all: cl, differing, despite, alpaca, the, zambia, basins, friend,
Nearest to five: eight, nine, kingdom, one, soroban, six, two, km,
Nearest to two: one, nine, lymphoma, aberdeen, coke, agave, phi, trench,
Nearest to states: wellington, qutb, var, typically, computers, exhibition, emirates, mm,
Nearest to these: sensitive, abandoned, crane, mosaic, max, percussion, full, industrialist,
Nearest to of: in, and, for, the, on, from, var, with,
Nearest to was: is, were, are, in, be, and, processor, mandaic,
Nearest to war: appellant, qur, methyl, animal, ignored, producer, coke, resort,
Nearest to about: aberdeen, turks, record, austin, phi, doubt, harmful, cooper,
Nearest to state: mya, bring, sighting, discourse, winning, changed, agents, lutheran,
Average loss at step  12000 :  14.0059898702
Average loss at step  14000 :  11.757604073
Average loss at step  16000 :  9.87551633203
Average loss at step  18000 :  8.4185485183
Average loss at step  20000 :  7.8934492873
Nearest to a: the, his, rich, circ, gb, their, any, one,
Nearest to had: has, was, connecting, have, is, deity, circ, wanting,
Nearest to or: and, circ, three, archie, the, for, zero, lymphoma,
Nearest to many: the, aberdeen, circ, llewellyn, vargas, forall, fermilab, nahuatl,
Nearest to one: two, circ, eight, nine, operatorname, six, agouti, three,
Nearest to nine: eight, six, seven, zero, four, five, operatorname, circ,
Nearest to all: alpaca, circ, cl, operatorname, differing, alcs, despite, favour,
Nearest to five: eight, nine, zero, six, two, agouti, three, circ,
Nearest to two: one, three, circ, nine, five, eight, six, zero,
Nearest to states: circ, epistles, qutb, nave, wellington, emirates, var, squarely,
Nearest to these: hydrophilic, sensitive, crane, abandoned, max, full, his, ada,
Nearest to of: in, and, for, nine, circ, from, operatorname, truetype,
Nearest to was: is, were, are, by, has, be, circ, agouti,
Nearest to war: apatosaurus, ignored, qur, methyl, appellant, hydrophobic, currie, ocean,
Nearest to about: dasyprocta, eight, seven, two, turks, doubt, diana, four,
Nearest to state: operatorname, batll, mya, discourse, circ, shortcuts, winning, mikhail,
Average loss at step  22000 :  7.06762288988
Average loss at step  24000 :  6.83585777926
Average loss at step  26000 :  6.82017090189
Average loss at step  28000 :  6.38677701104
Average loss at step  30000 :  5.85894906461
Nearest to a: the, gb, any, amazonas, their, circ, this, arriving,
Nearest to had: has, was, have, is, circ, connecting, were, deity,
Nearest to or: and, archie, circ, agouti, six, lymphoma, three, s,
Nearest to many: the, some, llewellyn, circ, aberdeen, fermilab, vargas, such,
Nearest to one: two, four, circ, eight, seven, three, operatorname, six,
Nearest to nine: eight, seven, six, five, four, zero, three, circ,
Nearest to all: alpaca, circ, cl, operatorname, differing, despite, agouti, alcs,
Nearest to five: eight, six, zero, four, nine, seven, three, two,
Nearest to two: three, four, one, five, six, eight, circ, zero,
Nearest to states: circ, gnome, epistles, wellington, nave, qutb, emirates, var,
Nearest to these: hydrophilic, mishnayot, max, sensitive, examples, the, crane, abandoned,
Nearest to of: and, in, for, eight, operatorname, second, from, nine,
Nearest to was: is, were, by, has, had, are, be, circ,
Nearest to war: integrates, ignored, apatosaurus, currie, appellant, qur, ocean, hydrophobic,
Nearest to about: seven, dasyprocta, adhering, eight, nine, turks, six, doubt,
Nearest to state: operatorname, batll, discourse, mya, shortcuts, brightest, mikhail, winning,
Average loss at step  32000 :  5.97424175012
Average loss at step  34000 :  5.77205809665
Average loss at step  36000 :  5.7618423965
Average loss at step  38000 :  5.50708753216
Average loss at step  40000 :  5.21602883613
Nearest to a: the, zero, gb, any, recitative, tetris, circ, wissowa,
Nearest to had: has, have, was, were, circ, wanting, fingers, panther,
Nearest to or: and, zero, archie, circ, agouti, lymphoma, three, dasyprocta,
Nearest to many: some, the, circ, such, fermilab, llewellyn, most, other,
Nearest to one: two, three, eight, six, four, seven, circ, five,
Nearest to nine: eight, seven, six, zero, five, three, four, recitative,
Nearest to all: alpaca, circ, cl, operatorname, differing, aveiro, agouti, living,
Nearest to five: eight, four, six, three, seven, zero, nine, two,
Nearest to two: three, one, four, five, eight, six, zero, seven,
Nearest to states: circ, gnome, epistles, qutb, emirates, wellington, enid, var,
Nearest to these: mishnayot, hydrophilic, some, examples, zero, sensitive, accelerates, ada,
Nearest to of: zero, in, and, for, operatorname, from, dasyprocta, circ,
Nearest to was: is, were, has, by, had, zero, be, did,
Nearest to war: ignored, currie, qur, integrates, apatosaurus, methyl, vernacular, sacraments,
Nearest to about: albury, seven, four, dasyprocta, adhering, turks, moderation, three,
Nearest to state: operatorname, vma, discourse, circ, mya, batll, aveiro, brightest,
Average loss at step  42000 :  5.36812242639
Average loss at step  44000 :  5.24987703943
Average loss at step  46000 :  5.24495700073
Average loss at step  48000 :  5.20192115557
Average loss at step  50000 :  4.98021268225
Nearest to a: the, any, gb, tetris, this, recitative, wissowa, no,
Nearest to had: has, have, was, were, is, wanting, circ, having,
Nearest to or: and, circ, archie, three, six, eight, four, agouti,
Nearest to many: some, these, circ, the, such, other, fermilab, amalthea,
Nearest to one: two, three, four, six, eight, seven, five, circ,
Nearest to nine: eight, six, seven, zero, five, three, four, recitative,
Nearest to all: circ, cl, alpaca, two, differing, four, these, three,
Nearest to five: four, six, three, eight, seven, agouti, two, zero,
Nearest to two: three, one, four, five, six, eight, circ, seven,
Nearest to states: circ, gnome, qutb, wellington, emirates, epistles, enid, var,
Nearest to these: some, mishnayot, the, many, all, hydrophilic, accelerates, solicitation,
Nearest to of: in, for, circ, dasyprocta, and, truetype, eight, operatorname,
Nearest to was: is, were, has, by, had, did, be, circ,
Nearest to war: ignored, currie, apatosaurus, integrates, qur, leftmost, vernacular, aleutians,
Nearest to about: albury, seven, dasyprocta, three, adhering, turks, osteoblasts, moderation,
Nearest to state: operatorname, discourse, vma, shortcuts, brightest, batll, winning, recitative,
Average loss at step  52000 :  5.04187427318
Average loss at step  54000 :  5.20315855026
Average loss at step  56000 :  5.03142092001
Average loss at step  58000 :  5.05961871696
Average loss at step  60000 :  4.94956232548
Nearest to a: the, ursus, any, gb, tetris, recitative, this, arctos,
Nearest to had: has, have, was, were, circ, having, ursus, wanting,
Nearest to or: and, ursus, circ, michelob, six, arctos, archie, agouti,
Nearest to many: some, these, ursus, such, other, most, circ, thibetanus,
Nearest to one: two, six, three, ursus, seven, four, circ, eight,
Nearest to nine: eight, seven, six, five, four, zero, ursus, michelob,
Nearest to all: ursus, two, these, alpaca, cl, circ, some, three,
Nearest to five: four, six, eight, three, seven, ursus, zero, nine,
Nearest to two: three, four, one, five, six, ursus, circ, eight,
Nearest to states: bz, michelob, circ, epistles, ursus, qutb, gnome, emirates,
Nearest to these: some, many, ursus, all, mishnayot, their, such, hydrophilic,
Nearest to of: in, ursus, and, operatorname, michelob, current, for, nine,
Nearest to was: is, were, has, had, by, be, did, been,
Nearest to war: currie, ignored, apatosaurus, integrates, vernacular, sacraments, qur, leftmost,
Nearest to about: albury, seven, ursus, michelob, microsite, osteoblasts, adhering, moderation,
Nearest to state: operatorname, bonzos, ursus, circ, vma, discourse, aveiro, recitative,
Average loss at step  62000 :  4.99555888486
Average loss at step  64000 :  4.84054678071
Average loss at step  66000 :  4.60959122896
Average loss at step  68000 :  4.9827575053
Average loss at step  70000 :  4.88611993182
Nearest to a: the, ursus, cebus, any, gb, mico, another, tetris,
Nearest to had: has, have, was, were, having, is, circ, wanting,
Nearest to or: and, ursus, cebus, michelob, circ, agouti, thaler, arctos,
Nearest to many: some, these, other, ursus, most, all, such, circ,
Nearest to one: six, two, three, four, five, seven, eight, circ,
Nearest to nine: eight, seven, six, five, four, ursus, zero, three,
Nearest to all: ursus, these, many, circ, some, cl, living, both,
Nearest to five: six, three, four, eight, seven, two, nine, zero,
Nearest to two: three, four, six, five, eight, one, seven, ursus,
Nearest to states: circ, michelob, bz, ternary, nations, qutb, gnome, wellington,
Nearest to these: some, many, all, their, ursus, such, mishnayot, which,
Nearest to of: ursus, michelob, and, operatorname, dasyprocta, circ, current, mitral,
Nearest to was: is, were, has, had, by, did, been, became,
Nearest to war: currie, vernacular, sacraments, integrates, ignored, apatosaurus, qur, allahabad,
Nearest to about: albury, ursus, michelob, microsite, moderation, microcebus, that, osteoblasts,
Nearest to state: operatorname, bonzos, ursus, circ, aveiro, vma, thibetanus, recitative,
Average loss at step  72000 :  4.75844426978
Average loss at step  74000 :  4.79410154271
Average loss at step  76000 :  4.71765997243
Average loss at step  78000 :  4.78894071189
Average loss at step  80000 :  4.79611130899
Nearest to a: the, any, ursus, mico, cebus, tetris, arctos, gb,
Nearest to had: has, have, was, were, having, been, circ, wanting,
Nearest to or: and, ursus, busan, cebus, michelob, circ, agouti, thaler,
Nearest to many: some, these, other, several, all, such, most, ursus,
Nearest to one: six, two, seven, three, ursus, circ, five, vma,
Nearest to nine: eight, seven, six, five, four, zero, ursus, michelob,
Nearest to all: ursus, these, both, many, some, circ, two, every,
Nearest to five: six, four, seven, three, eight, zero, two, nine,
Nearest to two: three, six, four, five, seven, one, ursus, busan,
Nearest to states: nations, circ, michelob, ternary, bz, indicative, emirates, wellington,
Nearest to these: some, many, all, their, such, which, ursus, accelerates,
Nearest to of: ursus, operatorname, in, michelob, dasyprocta, circ, kosar, nine,
Nearest to was: is, were, had, has, by, became, been, did,
Nearest to war: currie, sacraments, integrates, vernacular, ignored, allahabad, qur, apatosaurus,
Nearest to about: albury, ursus, that, moderation, busan, which, microcebus, michelob,
Nearest to state: operatorname, bonzos, ursus, fachhochschule, aveiro, batll, shortcuts, circ,
Average loss at step  82000 :  4.77827569687
Average loss at step  84000 :  4.75610430193
Average loss at step  86000 :  4.77705219245
Average loss at step  88000 :  4.74938085413
Average loss at step  90000 :  4.71444744682
Nearest to a: the, any, ursus, cebus, tetris, mico, arctos, gb,
Nearest to had: has, have, was, were, having, circ, is, been,
Nearest to or: and, ursus, busan, cebus, michelob, circ, agouti, thaler,
Nearest to many: some, these, several, most, all, other, such, ursus,
Nearest to one: two, four, three, seven, eight, six, five, ursus,
Nearest to nine: eight, seven, six, five, four, zero, three, ursus,
Nearest to all: ursus, these, both, some, many, circ, every, two,
Nearest to five: seven, eight, six, four, three, nine, zero, ursus,
Nearest to two: three, four, six, one, five, seven, busan, eight,
Nearest to states: nations, ternary, bz, circ, michelob, gnome, indicative, wellington,
Nearest to these: some, many, all, such, which, their, ursus, several,
Nearest to of: ursus, circ, michelob, mitral, dasyprocta, operatorname, in, including,
Nearest to was: is, had, were, has, by, became, been, being,
Nearest to war: cryopreservation, integrates, sacraments, currie, vernacular, ignored, apatosaurus, allahabad,
Nearest to about: albury, ursus, that, which, busan, microcebus, osteoblasts, moderation,
Nearest to state: operatorname, bonzos, ursus, fachhochschule, circ, aveiro, shortcuts, batll,
Average loss at step  92000 :  4.68756850183
Average loss at step  94000 :  4.72888552415
Average loss at step  96000 :  4.68780016243
Average loss at step  98000 :  4.58374595642
Average loss at step  100000 :  4.71492347121
Nearest to a: the, any, ursus, cebus, tetris, mico, gb, arctos,
Nearest to had: has, have, was, were, having, circ, is, been,
Nearest to or: and, ursus, cebus, busan, michelob, thaler, agouti, but,
Nearest to many: some, these, several, most, all, such, various, ursus,
Nearest to one: six, two, four, seven, five, eight, circ, ursus,
Nearest to nine: eight, seven, six, five, zero, four, ursus, three,
Nearest to all: both, these, ursus, some, many, every, circ, two,
Nearest to five: seven, four, six, eight, three, nine, zero, two,
Nearest to two: three, four, five, six, seven, one, busan, ursus,
Nearest to states: nations, circ, ternary, michelob, bz, avalanche, gnome, indicative,
Nearest to these: some, many, all, such, their, several, they, ursus,
Nearest to of: ursus, in, including, michelob, circ, dasyprocta, operatorname, kosar,
Nearest to was: is, has, had, were, been, became, by, be,
Nearest to war: dmd, cryopreservation, sacraments, vernacular, currie, integrates, apatosaurus, ignored,
Nearest to about: albury, ursus, that, stenella, osteoblasts, busan, microcebus, microsite,
Nearest to state: operatorname, bonzos, ursus, fachhochschule, shortcuts, circ, batll, vma,
