---
title: "Paper 3: Does your robot need a flamethrower? Automated astronomical instrumentation in Antarctica"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'The Antarctic Plateau contains sites with the potential to be the best in the world for many astronomical observations.The Plateau has strong advantages in the waveband between thermal-IR and millimetre-waves, for time-based astronomy, and for adaptive optics and interferometry. In such a harsh environment, automation of instrument functions becomes very important. At entirely remote (i.e., uncrewed) locations, automated instruments require robustness above all, especially in their self-contained logistics functions (power and communications). At crewed stations, with human intervention available, automation should concentrate on increasing functionality and decreasing workload on the winterover scientists, enhancing the scientific return on a significant investment.'
date: 2008-10-01
venue: 'Journal 1'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'N.F.H. Tothill1, C.L. Martin2, C.A. Kulesa3, and R. Briguglio4. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
Astron. Nachr. / AN 329, No. 3, 326 – 329 (2008) / DOI 10.1002/asna.200710941
Does your robot need a flamethrower?
Automated astronomical instrumentation in Antarctica
N.F.H. Tothill1,, C.L. Martin2, C.A. Kulesa3, and R. Briguglio4
1 University of Exeter, School of Physics, Stocker Road, Exeter, EX4 4QL, UK 2 Department of Physics and Astronomy, Oberlin College, Oberlin, OH 44074, USA 3 Steward Observatory, University of Arizona, Tucson, AZ, USA 4 Dipartimento di Fisica, Universita di Roma La Sapienza, Roma, Italy
Received 2007 Aug 31, accepted 2007 Nov 26
Published online 2008 Feb 25
Key words atmospheric effects – infrared: general – instrumentation: miscellaneous – site testing – submillimeter
The Antarctic Plateau contains sites with the potential to be the best in the world for many astronomical observations.
The Plateau has strong advantages in the waveband between thermal-IR and millimetre-waves, for time-based astronomy,
and for adaptive optics and interferometry. In such a harsh environment, automation of instrument functions becomes very
important. At entirely remote (i.e., uncrewed) locations, automated instruments require robustness above all, especially in
their self-contained logistics functions (power and communications). At crewed stations, with human intervention available, automation should concentrate on increasing functionality and decreasing workload on the winterover scientists,
enhancing the scientific return on a significant investment.
c 2008 WILEY-VCH Verlag GmbH & Co. KGaA, Weinheim
1 Introduction
For many wavelengths and observing techniques, the
Antarctic Plateau contains the best observing sites on Earth.
The cold, dry atmosphere has a lower water vapor column
than that above the Atacama desert, reducing the atmospheric opacity and thermal background throughout the IR,
out to the millimetre-wave regime.
The Antarctic atmosphere is dominated by katabatic
winds, in which cooling air sinks and flows downhill. A
strong boundary layer forms close to the ground, to which
most atmospheric turbulence is confined. This boundary
layer is quite thin at the local altitude maxima of the ice
sheet (the ‘Domes’): at Dome C, the top of the boundary
layer is about 30 m above the snow surface, and the median
seeing above the top of the layer is estimated to be < 0.3
(Lawrence et al. 2004). The concentration of atmospheric
turbulence in a thin layer also gives a large isoplanatic angle, enhancing the effectiveness of adaptive optics. The 4-
month night constitutes an advantage for time-based astronomy: the 24-hour periodicity of temperate sites is removed
and a given object in the sky changes its airmass slowly and
through a small range.
Although ground-based astronomy has been carried out
from the Antarctic Plateau for decades, the advantages described are coming to overlap more and more with the capabilities to exploit them and the scientific goals that drive
such projects. However, Antarctica has its own unique problems: a short summer season to carry out installation, testing
 This is a rhetorical question – of course it does. . . Corresponding author: nfht@astro.ex.ac.uk
Fig. 1 (online colour at: www.an-journal.org) South Pole Station
at twilight.
and maintenance, a long isolated winter for operations, logistical pressure, and human factors. Automation of equipment in the field is one of the ways in which these problems
may be minimised.
1.1 Observing sites in Antarctica
Most astronomical observations from the Antarctic Plateau
have been carried from the US Antarctic Program’s
Amundsen-Scott South Pole Station (Fig. 1). The longestestablished of all the year-round Plateau stations, the Pole
has the greatest logistical capacity of any of them (including cryogenics facilities), the greatest life-support capacity,
and the greatest bandwidth for data transfer. The newest
year-round station is Concordia, a Franco-Italian station on
c 2008 WILEY-VCH Verlag GmbH & Co. KGaA, Weinheim
Astron. Nachr. / AN (2008) 327
Dome C, lying at one end of the spine of the plateau. Dome
C is inherently a better observing site than the South Pole,
due to its higher elevation, colder temperatures, lower wind
speeds, less frequent cloud cover, and the low-lying boundary layer above the ice. It has only been occupied yearround for a few years, but there are already intense sitetesting activities going on there; Strassmeier et al. (2007)
have considered the automation of astronomical facilities
there in some detail, while Ashley et al. (2004) outlined
more general considerations. There is no year-round occupation of Dome A, the highest point on the ice sheet, but a
Chinese traverse has already reached it, and another traverse
will place an automated observatory there.
2 Full automation at remote locations
At remote locations (i.e. uncrewed, such as Dome A), all
aspects of astronomical instrumentation must be automated,
including not only operations but diagnostics, management
of and recovery from failures. Diagnostics must include not
only instrument status, but environmental status, and may
include cameras to substitute for winterover scientists looking over the instrument for problems.
Full automation of scientific instrumentation is already
in use on the Antarctic Plateau: the Automated Geophysical Observatories (AGOs) have been operating at remote
locations for decades. The publicly-available maintenance
reports on the AGOs1 give an overview of the challenges
faced by users of automated instruments: most of the problems concern infrastructure (power and communications)
rather than instrument failure. This suggests that most of the
effort in automation should be devoted to such infrastructure, with limited effort available for instrument automation. This is consistent with the comments of Strassmeier
et al. (2007) that a systems engineering approach, similar to
space engineering, is required (although, even in uncrewed
locations, Antarctic instruments may be designed for annual
servicing, unlike most spacecraft). The limited effort available for automating normal operation of instruments implies
that the operation must be simplified as much as possible,
with consequent restrictions on the instruments’ functionality.
2.1 Automated site-testing at Dome A
The first astronomical instruments are currently being built
for deployment to Dome A: PLATO is an automated observatory running a suite of site-testing instruments to characterise the site for observations from the submillimetre to the
optical (Lawrence et al. 2006). As a fully-automated system
at an entirely uncrewed location with limited-bandwidth
connections to the outside world, PLATO is close to being
a fully robotic observatory.
1 at http://space.augsburg.edu/ago
Fig. 2 (online colour at: www.an-journal.org) CAD model of
preHEAT deployed on PLATO (Courtesy Mike Schein, Steward
Observatory).
One of the instruments to be included in PLATO is preHEAT (Fig. 2), a submillimetre-wave tipper/telescope designed to carry out site-testing, technology development,
and science observations. In order to simplify the operation of preHEAT, it is restricted to only one axis of rotation,
and uses only one receiver. By only rotating in elevation, a
cable-wrap is avoided, and azimuth movement is provided
by earth rotation.
3 Automation at crewed stations
At a crewed station, power and communications are part of
the logistical infrastructure that is maintained by the station.
Although this infrastructure is no longer part of the scientific instrumentation, it cannot be taken for granted: power
glitches occur from time to time, and scientific experiments
may not have priority in using available power (life support,
for example, being more important). Loss of power is not
always predictable, so automated systems to handle power
loss (ensuring a safe power-down and -up) are a useful addition to the instrument.
However, because so much infrastructure is supplied
from outside the instrument, the requirement for tightlyintegrated automated systems covering all aspects of instrument operation is not as severe as it is at uncrewed locations (discussed above). At a crewed station, automation
is likely to be partial and can take a more piecemeal approach: the case for automating any given function or subsystem can be evaluated against the case for leaving it to a
human. Indeed, some functions are much better carried out
by humans: humans can operate in almost all conditions encountered in the Antarctic Plateau environment. Engineering fully-winterised automatic systems to substitute for human intervention may in some cases be prohibitively difficult and expensive.
Some experiments at crewed stations have been designed to be completely autonomous, including two Australian astronomical site-testing experiments, AASTO at
www.an-journal.org c 2008 WILEY-VCH Verlag GmbH & Co. KGaA, Weinheim
328 N.F.H. Tothill et al.: Antarctic astronomy
Fig. 3 (online colour at: www.an-journal.org) AASTINO at
Concordia Station (Courtesy Jon Lawrence, UNSW).
the South Pole (e.g. Storey et al. 1996), and AASTINO
at Dome C (Fig. 3; e.g. Lawrence et al. 2003). At the
South Pole, there is also a submillimetre-wave tipper experiment (Peterson et al. 2003), that continuously produces
atmospheric opacity estimates. Although these instruments
were designed to run without any human intervention, they
have profited from the availability of personnel nearby, who
could help to diagnose and repair any problems that occurred. For example, the tipper was run by a computer that
needed to be rebooted occasionally. In order to profit from
their crewed locations, such automated systems should be
designed for accessibility, to allow easy maintenance by humans in bulky cold-weather gear.
The South Pole has also hosted several experiments that
were partially-automated, mostly measuring the cosmic microwave background (CMB). The routine operation of these
experiments was largely automated, running off simple observing scripts. This was made possible by the fact that, as
dedicated CMB-mapping experiments, the observing programme was largely pre-defined. Maintenance, however,
was largely carried out by on-site winterover scientists. For
example, routine receiver refilling with cryogens was carried out manually.
By contrast, the Antarctic Submillimetre Telescope and
Remote Observatory (AST/RO; Fig. 4; Stark et al. 2001)
was a general-purpose submillimetre-wave telescope, also
at the South Pole. It was optimised for mapping molecular gas on a galactic scale, but was also used for mapping
of nearby star-forming regions, observing the Magellanic
Clouds, searching for new molecular transitions, and even
aeronomy.
AST/RO fielded 4 facility receivers operating at frequencies from 220 to 810 GHz, together with 2 guest instruments operating at 1.4 THz. All instruments were cryogenic,
using liquid helium for cooling. The facility required a large
amount of upkeep, even in the winter, and was run by one
or two winterover scientists. They had to keep cryogenic receivers filled, schedule and execute observations (including
tuning, pointing and calibration), and check the data, just
for routine operation. With essentially a complete telescope
system, faults inevitably arose, which had to be diagnosed
and repaired or worked around. This wide range of responsibilities also required the AST/RO crew to have a wide range
of competencies, from purely technical maintenance to scientific oversight.
AST/RO used a significant amount of automation in its
routine operation: observing procedures were programmed,
including routine calibration, and could be interrupted by
weather conditions (high wind speed). However, weather
sensing was only used to sense shutdown requirements.
It was down to the winterovers to determine which programmes to schedule, taking into account current and expected conditions, as well as scientific priorities. The winterovers’ ability to oversee programmes in this way tends to
decline over the winter, due to Polar T3 Syndrome (e.g.,
Palinkas et al. 2001). This condition, caused by changes
to thyroid function, tends to impair winterovers’ cognitive
abilities, including short-term memory and the ability to
plan and carry out non-routine activities. The effects increase over the course of the winter, which means they usually peak in August-September, coinciding with the best
weather for most scientific purposes.
Automation to reduce the workload on winterover crews
can therefore play an important role, even in complex
facilities at crewed stations. For example, automation of
telescope scheduling could remove a significant burden:
using current weather conditions, forecasts, and trends,
scheduling software can effectively distribute observing
time among projects. Submillimetre observations are some
of the easiest to schedule in this way, since there is only
one significant weather parameter - the atmospheric opacity. Winterovers would then only have to oversee the operation of the scheduler, which in turn might make it more
practicable to run a facility with only one winterover. At a
location with a winter capacity of less than 20 (like Concordia), this will significantly reduce the facility’s logistical footprint. Some scientific oversight of the automated
scheduling may also be carried out in the north, based on
data samples transferred daily – the winterovers would then
not need to be completely familiar with the scientific requirements of all the programmes, concentrating instead on
technical issues. Such remote oversight, however, is likely
to be limited by the available bandwidth to the station. Currently, only the South Pole Station has enough bandwidth
for such an arrangement to be implemented (as it currently
is for AMANDA/IceCube). At stations with very limited
bandwidth, data analysis and scientific oversight must be
carried out by the winterover crew: automation of routine
operations then becomes vital to allow this oversight to be
carried out.
At crewed locations, automation can often be reduced
to remote control. Merely by having a function controlled
from the warm station rather than at the instrument itself,
winterover workloads can be reduced dramatically.
c 2008 WILEY-VCH Verlag GmbH & Co. KGaA, Weinheim www.an-journal.org
Astron. Nachr. / AN (2008) 329
Fig. 4 (online colour at: www.an-journal.org) AST/RO: a general-purpose telescope on the Ice (Courtesy Greg Wright, Antiope Associates).
4 Arctic sites
The Arctic is unlikely to provide observing sites as good
as those on the Antarctic Plateau, but may still provide the
best conditions in the Northern Hemisphere for some observations. In addition, access is much easier to Arctic sites.
Two sites are currently being considered for astronomical instruments: Summit Station, at the peak of the
Greenland ice cap, and the northern end of Ellesmere Island. The Greenland ice cap has a broadly similar climate
to the Antarctic Plateau, including a katabatic wind system, and Summit may have some significant similarities to
Domes A and C, albeit lower and warmer (M.I. Andersen,
priv. comm.). It hosts a year-round crewed station, allowing
for automated site-testing with human backup. Two automated weather stations and sky monitors have been placed
on mountains on the northern coast of Ellesmere Island
(Steinbring et al. 2006). In their first year of operation, their
communication links failed, although it is thought that datataking was unaffected, so the data can be retrieved physically. This emphasises the need for robust power and communications at uncrewed sites.
5 Conclusions
We suggest the following principles for automation of astronomical instruments on the Antarctic Plateau:
1. At uncrewed locations, automation of basic infrastructure functions must be very robust. Instrument functionality should therefore be kept to the absolute minimum
required so as to reduce complexity, and allow more effort to be spent on the basic systems.
2. At crewed stations, automation can be carried out piecemeal. The costs and benefits of automation for each
function or subsystem should be evaluated. Human operation may be much easier.
3. In general, routine predictable operations are good
candidates for automation. But modern automatedscheduling techniques also have great potential to reduce the workload involved in running a facility instrument.
Acknowledgements. NFHT gratefully acknowledges the hospitality of Steward Observatory, where part of this paper was written,
the combined experience of the AST/RO project, where he learned
about Antarctic operations the hard way, and the PLATO team at
UNSW, where they are implementing automated Antarctic instrumentation, not just talking about it.
References
Ashley, M.C.B., Burton, M.G., Lawrence, J.S., Storey, J.W.V.:
2004, AN 325, 619
Lawrence, J.S., Ashley, M.C.B., Burton, M.G., et al.: 2003,
MSAIS 2, 217
Lawrence, J.S., Ashley, M.C.B., Tokovinin, A., Travouillon, T.:
2004, Nature 431, 278
Lawrence, J.S., Ashley, M.C.B., Burton, M.G., et al.: 2006, in:
L.M. Stepp (ed.), Ground-Based and Airborne Telescopes,
SPIE 6267, p. 51
Palinkas, L.A., Reed, H.L.,Reedy, K.R., Van Do, N., Case, H.S.
Finney, N.S.: 2001, Psychoneuroendocrinology 26, 421
Peterson, J.B., Radford, S.J.E., Ade, P.A.R., Chamberlin, R.A.,
O’Kelly, M.J., Peterson, K.M., Schartman, E.: 2003, PASP
115, 383
Stark, A.A., Bally, J., Balm, S.P., et al.: 2001, PASP 113, 567
Steinbring, E., Carlberg, R., Klein, J., Bayne, D., Cole, B.: 2006,
Cassiopeia 130, http://www.casca.ca/ecass/issues/2006-ae/
Storey, J.W.V., Ashley, M.C.B., Burton, M.G.: 1996, PASA 13, 35
Strassmeier, K.G., Agabi, K., Agnoletto, L., et al.: 2007, AN 328,
451
www.an-journal.org c 2008 WILEY-VCH Verlag GmbH & Co. KGaA, Weinheim
[Download paper here](http://academicpages.github.io/files/paper3.pdf)

Recommended citation: YTothill, N. F. H., Martin, C. L., Kulesa, C. A., & Briguglio, R. (2008). Does your robot need a flamethrower? Automated astronomical instrumentation in Antarctica. Astronomische Nachrichten, 329(3), 326–329. doi:10.1002/asna.200710941  <i>Journal 1</i>. 1(3).
