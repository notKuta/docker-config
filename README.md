# A personal docker-based homelab configuration

This repository stores my current up-to-date configuration that I use for my homelab.
Try it out by doing the following (after you've installed Docker engine onto your machine):

```console
cd docker-config
sudo docker compose up -d
```

## Personal thoughts regarding the system

My main homelab is currently running Debian which may sound strange if you've looked
at my other repositories (i.e. I use Nix on my daily machines.) However, I never really
had much experience with servers and doing "sysadmin" things so I thought Debian would
be a safe pick for an initial distro (also, who doesn't love trying new distros?!) However,
I am unfortunately getting the Nix itch once more (especially after finding out about building
different machines' generations remotely and then pulling them remotely?! Like, that's **so** awesome!)
Anyways, I will most likely transfer my current homelab to Nix whenever I can and feel like it. Maybe
I'll run Nix on my Linux phone... whenever that becomes usable... (I jest, I jest.)
