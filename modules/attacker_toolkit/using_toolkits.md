# Using Attacker Profiles

Attacker tools are a guide and set of constraints for aggressor teams during scenarios. The goal is to allow a range of possible realistic threat actors, from small script kiddie groups to APTs.

A tool card must have:
- name
- resource points cost (abstract number to represent the combination of financial outlay and resource required for deployment and maintenance of a capability)
- associated tactics (where multiple tactics are available, multiple cards should be provided as part of the toolkit)

A tool card may have:
- aliases (other names)
- network (associated networks, APTs, )
- family (the group of tools to which the tool exists)
- advantages (e.g. obfuscated code, sandbox-aware, polymorphic, professional support)
- flaws (e.g. old tooling, popular tool, known C&C)
- dependencies
- limitations

At the beginning of the scenario, and exploitation may already be in place or partly complete.

Example tool cards are below. Additional fields may be included and used in templates where available

{
  card: [
    {
      "Name": "GHOSTRAT",
      "Aliases": [
        "Farfli",
        "Palevo",
        "Redosdru",
        "Keylogger",
        "Swisyn"
      ]

      "Resource": 4,
      "Family": [
        "RAT",
        "Keylogger"
      ],
      "Tactics": [
        "Persistence",
        "Execution",
        "Discovery",
        "Data Exfiltration",
        "Collection",
        "Credential Access",
        "Impact",
        "Lateral Movement"
      ],
      "Dependencies": [
        "Windows 2000",
        "Windows XP",
        "Windows Server 2003",
        "Requires Initial Access"
      ],
      "Flaws": [
        "Known IOC",
        "No Privilege Escalation"
      ]
    }
  ]
  card: [
    {
      "Name": "Watering Hole",
      "Resource": 1,
      "Family": [
        "Social Engineering"
      ],
      "Tactics": [
        "Initial Access"
      ]
    }
  ]
}
