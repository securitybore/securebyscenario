# Using Attacker Profiles

Attacker profiles are a guide and set of constraints for aggressor teams during scenarios. The goal is to allow a range of possible realistic threat actors, from small script kiddie groups to APTs.

A profile must have:
- motivation
- a number of resource points to work with toolkit card modules
- a number of tactical option slots per turn to work with toolkit card modules

A profile may have:
- a standard operating procedure (this provides a discount to certain toolkit cards, but may be predictable to blue teams)
- social media handles (for use in creating injects)
- profile images
- additional background information

In play, along with an attacker profile, the aggressor team must be provided with:
- a broad scenario briefing
- the starting attacker briefing for the scenario

An example profile is below. Additional fields may be included and used in templates where available

{
  profile: [
    "Name": "The Devil's Ham",
    "Motivation": "Mischief and pursuit of infamy",
    "Resource": 4,
    "Tactics": 3,
    "SOP": "Must use one misinformation/media tactic per turn if desired",
    "Twitter": "@devils_hand"
    "Background" "The Devil's Ham are a group of teenagers with some basic technical ability and a reckless approach. Inexperienced, they have decided to hack the planet for fame, in the hopes that fortune (or cushy government jobs) will follow, and got together with friends to pursue this dream."
  ]
}
