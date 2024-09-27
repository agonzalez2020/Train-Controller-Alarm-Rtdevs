#RealTime-DEVS model of a railway controller implemented in Uppaal

This is an Uppaal project about a model of a railway controller (RCS). The RCS is first described in RealTime-DEVS and then is translated into Uppaal. One distinguishing feature of the RCS is that it must verify quantitative temporal properties (QTP). That is, the kind of temporal properties seen in real-time systems (for example, "the alarm must sound for 9 seconds"). QTP are recurrent properties in real-time systems. The translation from RealTime-DEVS into Uppaal, as well as the implementation of QTP, make use of a number of features of Uppaal's timed automata. Finally, the combination between these timed automata and some TCTL queries allow Uppaal to verify QTP.

Furthermore, the project contains so-called mutants of QTP. These mutants allow users to find timing errors when some QTP is not verified by the model. If the model doesn't verify a QTP but it does verify one of its mutants, then the error can easily found.

A thorough description of our technique is shown in this paper https://arxiv.org/....

# Requirements
Uppaal 5.0 (https://uppaal.org/)

# Files
Uppaal-Train-Controller-Alarm.xml: Uppaal project

RT-DEVS-Train-Controller-Alarm.eps: RealTime-DEVS specification of the TCS
