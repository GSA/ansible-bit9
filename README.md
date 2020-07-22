ansible-bit9
=========

Bit9, the global leader in Advanced Threat Protection, today announced the results from an independent test demonstrating that Bit9 Parity Suite outperforms the competition in protecting against Advanced Persistent Threat (APT) attacks. This ansible role installs and configures the agent required to communicate with client machines.

Requirements
------------

```bash
windows_bit9_agent_filename: #windows installer msi
```

Role Variables
--------------

```bash
None
```

Dependencies
------------
Acquire Installers
```bash
cpb.msi - windows installer package
```

Example Playbook
----------------

```bash
    - hosts: servers
      roles:
         - ansible-bit9
```

License
-------

MIT

Author Information
------------------

Lance White - GSA/GEO
