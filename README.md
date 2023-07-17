# Kathara
Kathará (from the Greek Καθαρά, purely) is a lightweight network emulation system based on Docker containers. It can be really helpful in showing interactive demos/lessons, testing production networks in a sandbox environment, or developing new network protocols.

Kathará is the spiritual successor of the notorious Netkit, hence it is cross-compatible, and inherits its language and features.

## Install for Ubuntu 22.04 jammy
- [Docker](https://docs.docker.com/engine/install/)
- [Kathara](https://github.com/KatharaFramework/Kathara/wiki/Linux)
  
## Kathara Manual
- [Link](https://www.kathara.org/man-pages/kathara.1.html)

## Simple steps
1.  Install Kathará by following the Installation section.
2. Download and unpack the network scenario of a "Small Internet" from here (network topology can be found here).
3. cd inside small-internet-with-dns-webserver and run kathara lstart.
4. Kathará will read the configuration of the scenario from lab.conf and the various *.startup files and start the devices, opening terminal windows to 5. interact with them.
5. After you're done experimenting, simply run kathara lclean and wait until the network scenario closes.
