## Hi there 👋
I'm Gonçalo Almeida — Principal Engineer at [Critical Software](https://criticalsoftware.com/en), currently focused on **MedTech, Pharma & Life Sciences**, with background in **Automotive** and **C++/systems engineering**.

## Connect
- LinkedIn: https://www.linkedin.com/in/goncalomatosalmeida/ | - More links: https://linktr.ee/goncalomalmeida

## Currently working on
- https://github.com/goncaloalmeida/BluetoothPulseOximeter
- https://github.com/goncaloalmeida/escala
- https://github.com/goncaloalmeida/surveillance-system

## Medical / Healthcare
Projects, tools and references related to medical devices, health data and regulated environments.
- https://github.com/OpenHealthForAll/open-health  
  Open initiative promoting interoperability and open standards in healthcare systems.
- https://github.com/ecostech/viatom-ble  
  Reverse‑engineered BLE protocol and tooling for Viatom / Checkme medical devices.
- https://github.com/rustfoundation/safety-critical-rust-consortium  
  Cross‑industry effort to evaluate and promote Rust in safety‑critical systems, including medical devices.
- https://github.com/mdpnp/mdpnp  
  MD PnP / OpenICE reference implementation for medical device interoperability (ICE standard).
- https://github.com/RespiraWorks/Ventilator  
  End‑to‑end open‑source ICU ventilator project, including software, systems and regulatory artefacts.

## Technology & C++ (interesting references)
General-purpose repositories I often recommend, revisit, or use as references.

- https://github.com/wxWidgets/wxWidgets  
  Mature cross‑platform C++ GUI framework.
- https://github.com/JakubVojvoda/design-patterns-cpp  
  GoF design patterns implemented in modern C++.
- https://github.com/AnthonyCalandra/modern-cpp-features  
  Overview of modern C++ language and library features.
- https://github.com/fffaraz/awesome-cpp  
  Curated list of C++ libraries and resources.
- https://github.com/bewuethr/stroustrup-ppp  
  Exercises and material from *Programming: Principles and Practice Using C++*.
- https://github.com/abseil/abseil-cpp  
  Abseil common C++ libraries used at scale.
- https://github.com/DeviceFarmer/stf  
  Open‑source device farm for Android testing and automation.

## Automotive (previous background)
Key technologies, middleware, tooling and experiments from my automotive engineering years.

### COVESA (SOME/IP, CommonAPI & tools)
- https://github.com/COVESA/vsomeip  
  Reference implementation of SOME/IP middleware widely used by OEMs and suppliers.
- https://github.com/kamelfakihh/vsomeip-docker-benchmark  
  Performance benchmarking of vsomeip in containerized environments.
- https://github.com/dev-guy/vsomeip-bazel  
  Bazel build integration for vsomeip‑based projects.
- https://github.com/COVESA/capicxx-core-runtime  
  Core runtime for CommonAPI C++ service interfaces.
- https://github.com/COVESA/capicxx-someip-runtime  
  SOME/IP binding runtime for CommonAPI C++.
- https://github.com/COVESA/capicxx-dbus-runtime  
  D‑Bus binding runtime for CommonAPI C++.
- https://github.com/COVESA/capicxx-core-tools  
  Code generation and tooling for CommonAPI core.
- https://github.com/COVESA/capicxx-someip-tools  
  SOME/IP‑specific tooling for CommonAPI projects.
- https://github.com/COVESA/capicxx-dbus-tools  
  D‑Bus‑specific tooling for CommonAPI projects.

### Simulation, HMI & dashboards
- https://github.com/eclipse-sumo/sumo  
  Large‑scale open‑source traffic simulation platform.
- https://github.com/ariexi/the-automotive-collection  
  Curated collection of automotive software and embedded resources.
- https://github.com/afondiel/car-cluster-hmi  
  Automotive instrument cluster HMI prototype.
- https://github.com/kianwasabi/DES02_PiRacer-Instrument-Cluster 
  Raspberry Pi‑based digital instrument cluster experiment.
- https://github.com/cppqtdev/Qt-HMI-Display-UI  
  Qt‑based HMI display examples and UI concepts.
- https://github.com/GomaaMohamed/Yocto_Car_Dashboard  
  Embedded car dashboard built using Yocto.

### Safety / platforms
- https://github.com/eclipse-sdv
  Eclipse Software‑Defined Vehicle (SDV) ecosystem and safety‑oriented middleware foundations.

## Git config snippets
```ini
[user]
    name = ...
    email = ...
[alias]
    st   = status
    br   = branch
    adu  = add -u
    co   = checkout
    cm   = commit
    cma  = commit --amend
    rei  = rebase -i
    rec  = rebase --continue
    rea  = rebase --abort
    plog = log --graph --pretty='format:%C(red)%d%C(reset) %C(yellow)%h%C(reset) %ar %C(green)%aN%C(reset) %s'
``
