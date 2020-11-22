# Defenses

This is a new project to create a public, stand-alone defense system for Lusternia. Download the source file and install it as a package in mudlet.

## Requirements

- Must have mudlet
- GMCP must be enabled
- Must have the skill stratagems in combat.

## Commands

The commands can be viewed with 'defense commands' along with a brief description of what each alias does.

```
def                                       #Displays a list of enabled defenses which are [x]active and [ ]inactive.
defup                                     #Will set defenses marked 'all', that are not assigned to an initial set.
defup combat                              #Will set defenses that are part of the initial 'combat' set.
defup hunting                             #Will set defenses that are part of the initial 'hunting' set.
defup influence                           #Will set defenses that are part of the initial 'influence' set.

defense disable <defense>                 #This defense will not be set or displayed.
defense enable <defense>                  #This defense will be set and displayed normally.
defense initial <defense> <initial set>   #Change the conditions for when a defense will be set(all, combat, hunting, influence).
defense auto <defense> <true/false>       #Change whether a defense will be automatically upkept.
```

Be careful with changing enable/disable/initial/auto, especially auto. None of the defenses that require equilibrium or balance are upkept automatically by default. 

## Goals

The system is intended to be very easy to use. This also means the ability to customize it is somewhat limited currently. Multiple customized profile settings are not currently supported. IE, if defense settings are changed on one character via the commands listed above, they will carry over to all other characters. The system itself, however, will automatically track currently active skillsets and adjust the possible defenses accordingly.

# Community and future updates

Please notify me if there are any defenses missing from the database, or any that are not being set that should be. I will accept suggestions for improvement, bug reports, and other forms of assistance. The system will be updated over time. All source code is available for modification.
