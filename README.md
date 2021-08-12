# loghelper
Include for use with SuperLogs plugin set

see https://forums.alliedmods.net/showthread.php?t=100084

Author: psychonic

This is an include psychonic wrote for use with his SuperLogs plugin set. It has stocks for many HL Standard log line formats, and also gets around the current limitations of Sourcemod's %L format operator and FormatUserLogText() function (not including team name on log line). This makes it very easy to add HLstatsX(:CE) or Psychostats support to a plugin.

All included functions are stocks so they are only compiled in with the plugin if uses, or feel free to copy individual functions so as to not create a dependency on the include.

Note: you must call the GetTeams() function during OnMapStart() to correctly cache team names.
