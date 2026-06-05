# Exploring Your System's Security

## Task 1 --- List System Users

Run:

    cat /etc/passwd

### Screenshot

(Add screenshot here)

### Questions

1.  How many users exist on the system?
There are 37 accounts on the system.
2.  Which accounts appear to be system accounts?
Accounts like root,daemon, bin, sys, sync, games, man, lp, mail, news, uucp, proxy, ww-data, backup, list, irc, _apt, nobody, systemd_network, dhcpcd, messagebus, sshd, and statd.These accounts appear to be system accounts.
3.  Why do operating systems create system accounts?
They are used to run specific background service, daemons, or system processes with the absolute minimum privileges required. This follows
### Reflection

Explain why understanding system users is important for cybersecurity.

------------------------------------------------------------------------

## Task 2 --- Inspect Running Processes

Run:

    ps aux

### Screenshot

(Add screenshot here)

### Questions

1.  Which processes are running as `root`?
2.  Why can processes running as root be dangerous?
3.  What could happen if a malicious program ran with root privileges?

### Reflection

What did you learn about system processes and security?

------------------------------------------------------------------------

## Task 3 --- Identify Open Network Ports

Run:

    ss -tuln

### Screenshot

(Add screenshot here)

### Questions

1.  Which ports are open?
2.  Which services appear to be listening?
3.  Why might open ports represent a security risk?

### Reflection

Explain the relationship between open ports and potential attack
surfaces.
