ldmconfig
=========

LDM Configuration files used on local servers

IEM's `EXP` flow needs to be careful to not cross-the-streams...

Sources | Aggregators + Sinks
--- | ---
iemvm5 | iem12 -> webfarm
iem8-dc | iemvm4
iem11-dc | iemvm6
iem27-dc |idd-dc -> webfarm-dc
iem9-dc | metvm33-dc -> rtwriter
weaterstation |
