---
title: "MIKED (8)"
#date: 2020-10-13T16:15:25Z
draft: false
---

## NAME
```
miked - IT Systems Architect, Maker, Technical Debt Consolidator,
 and Yak Barber
```

## SYNOPSIS
```
miked [OPTIONS] COMMAND
miked [--help|--req-resume]
```
## DESCRIPTION
```
miked is a daemon capable of providing many services useful to
 IT Departments and IT integration shops. With a pedigree in
Systems Architecture and last mile implementation, miked is good
for any environment that requires tight integration for all
aspects in the full IT workflow.
```

## OPTIONS
```
-h --help           show usage
-r --req-resume     requests a resume for the mike daemon
-g --good           produces high quality result  
-c --cheap          produces inexpensive result  
-f --fast           produces fast result  

see KNOWN BUGS
```

## COMMANDS
```
architect     Build a new IT system from scratch (or upgrade
              one already in place).  Omission of -f and -c flags
              will automatically invoke the **document** command.

fabricate     Create 3D CAD models and fabricate them into physical
              objects.
              Sub-Commands include:
                  Metalwork
                  Woodworking
                  3D Printing

tinker [STR]  Maintenance process.  Recommended to run at minimum
              weekly. Allows miked to upgrade knowledgeDB with new
              concepts. Allows for significantly faster runs of
              architect, fabricate, and repair. String (optional)
              will instruct what concepts to focus on.


repair        This command can be applied from a wide range of
              concepts from IT systems to physical objects (cars,
              appliances, etc.).

              Note: the repair command works on all IT systems,
              not just those created by the "architect" command.
              Though you'll have better success repairing systems
              created by the miked architect command.

document      This command forces miked to provide run documentation
              on previously run commands.

              Note: miked provides it's best documentation when
              un-prompted; brief documentation can be produced
              when required.

cleanupDebt   Command forces the daemon to work on old tickets, or
              other technical debt accrued by the organization.  
```
## EXAMPLES
```
miked tinker garageDoor - https://youtu.be/gGVCw3Sehcw
miked fabricate lights - https://youtu.be/jo2RVxMrmOo
```

## KNOWN BUGS
```
Only two option flags (of -g -c and -f) can be used at the same time.
Bug report has been filed, current status is WONTFIX, NOTABUG.

miked works best in environments where -c and -f are used sparingly;
especially in conjunction. Continued (ab)use of the -c and -f flags
and omission of the -g flag will eventually result in poor daemon
performance.

The OpenML implementation in miked has shown emergent properties
of the daemon taking "pride" in its output.  While this facilitates
use in environments where quality output is preferred.  It has an
inversely negative effect for environments that prioritize
"band-aid" fixes.  In extreme cases the daemon has been known to
stop working for organizations all together.
```


## Dependancies
```
goodManager (2)
@linux-workstation (1)
libWorkLifeBalance (3)
hourlyNotSalaried (2)
hl.exe (6)
```
