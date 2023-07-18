# Kathara
Kathará (from the Greek Καθαρά, purely) is a lightweight network emulation system based on Docker containers. It can be really helpful in showing interactive demos/lessons, testing production networks in a sandbox environment, or developing new network protocols.

Kathará is the spiritual successor of the notorious Netkit, hence it is cross-compatible, and inherits its language and features.

## Install for Ubuntu 22.04 jammy
- [Docker](https://docs.docker.com/engine/install/)
- [Kathara](https://github.com/KatharaFramework/Kathara/wiki/Linux)

## Install and manual for Python APIs
- [Kathara Api](https://github.com/KatharaFramework/Kathara-Labs/tree/main/tutorials/python-api/getting-started)
- [Pyuv](https://github.com/saghul/pyuv)
  (since it may be blocked by PyPI from being downloaded from a git repository, giving this error)
- [Tutorials](#tutorials)
- [Switch versions](https://kfields.me/blog/pyenv_on_ubuntu_22) 

## Kathara Manual
- [Link](https://www.kathara.org/man-pages/kathara.1.html)

## Simple steps
1.  Install Kathará by following the Installation section.
2. Download and unpack the network scenario of a "Small Internet" from here (network topology can be found here).
3. cd inside small-internet-with-dns-webserver and run kathara lstart.
4. Kathará will read the configuration of the scenario from lab.conf and the various *.startup files and start the devices, opening terminal windows to 5. Interact with them.
5. After you're done experimenting, simply run kathara lclean and wait until the network scenario closes.

## Main Labs
- [Link](https://github.com/KatharaFramework/Kathara-Labs/tree/main/main-labs)

## My documents
- [Link](https://github.com/Trourest186/Kathara/tree/master)

## Tutorials

This section contains several tutorials about basic and advanced usage of Kathará.

* [Kathará Introduction](https://github.com/KatharaFramework/Kathara-Labs/tree/main/tutorials/introduction): Introduction slides of the Kathará tool.
* [Capture Packets](https://github.com/KatharaFramework/Kathara-Labs/tree/main/tutorials/capture-packets): A tutorial explaining how to capture packets using the [Wireshark](https://www.wireshark.org/) GUI in Kathará.
* [Python API](https://github.com/KatharaFramework/Kathara-Labs/tree/main/tutorials/python-api): Several tutorials about the usage of the Kathará Python APIs. 
