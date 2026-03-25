## Hi there 👋
I'm Gonçalo Almeida — Principal Engineer at [Critical Software](https://criticalsoftware.com/en), currently focused on **MedTech, Pharma & Life Sciences**, with background in **Automotive** and **C++/systems engineering**.
Connect: [LinkedIn](https://www.linkedin.com/in/goncalomatosalmeida) | [Linktree](https://linktr.ee/goncalomalmeida)

## Current Personal Projects
| Project | Description | Stack |
|---------|-------------|-------|
| [BluetoothPulseOximeter](https://github.com/goncaloalmeida/BluetoothPulseOximeter) | BLE pulse oximeter data acquisition and processing | C++, BLE |
| [escala](https://github.com/goncaloalmeida/escala) | Healthcare staff scheduling tool | — |
| [surveillance-system](https://github.com/goncaloalmeida/surveillance-system) | Computer vision surveillance with AI detection | C++, OpenCV |

## Medical / Healthcare
Projects, tools and references related to medical devices, health data and regulated environments.
- [OpenHealthForAll/open-health](https://github.com/OpenHealthForAll/open-health) – Open initiative promoting interoperability and open standards in healthcare systems.
- [ecostech/viatom-ble](https://github.com/ecostech/viatom-ble) – Reverse‑engineered BLE protocol and tooling for Viatom / Checkme medical devices.
- [mdpnp/mdpnp](https://github.com/mdpnp/mdpnp) – MD PnP / OpenICE reference implementation for medical device interoperability (ICE standard).
- [RespiraWorks/Ventilator](https://github.com/RespiraWorks/Ventilator) – End‑to‑end open‑source ICU ventilator project, including software, systems and regulatory artefacts.
- [cornerstonejs/cornerstone3D](https://github.com/cornerstonejs/cornerstone3D) – Web-based medical image viewer with DICOM support.

## C++ Engineering
- [JakubVojvoda/design-patterns-cpp](https://github.com/JakubVojvoda/design-patterns-cpp) – GoF design patterns in modern C++.
- [AnthonyCalandra/modern-cpp-features](https://github.com/AnthonyCalandra/modern-cpp-features) – Modern C++ language and library features overview.
- [fffaraz/awesome-cpp](https://github.com/fffaraz/awesome-cpp) – Curated C++ libraries and resources.
- [abseil/abseil-cpp](https://github.com/abseil/abseil-cpp) – Google's common C++ libraries, production-tested at scale.
- [bewuethr/stroustrup-ppp](https://github.com/bewuethr/stroustrup-ppp) – Exercises from *Programming: Principles and Practice Using C++*.
- [wxWidgets/wxWidgets](https://github.com/wxWidgets/wxWidgets) – Mature cross-platform C++ GUI framework.

## Safety / AI / Platforms / Tooling
- [eclipse-sdv](https://github.com/eclipse-sdv) – Eclipse Software‑Defined Vehicle (SDV) ecosystem and safety‑oriented middleware foundations.
- [rustfoundation/safety-critical-rust-consortium](https://github.com/rustfoundation/safety-critical-rust-consortium) – Cross‑industry effort to evaluate and promote Rust in safety‑critical systems, including medical devices.
- [awesome-safety-critical-ai](https://github.com/JGalego/awesome-safety-critical-ai) – Curated list of resources, tools, standards and research on building AI systems for safety-critical domains — covering verification, certification, fault tolerance and responsible deployment across healthcare, aerospace, automotive and beyond.
- [DeviceFarmer/stf](https://github.com/DeviceFarmer/stf) – Android device farm for testing and automation.
- [keycloak/keycloak](https://github.com/keycloak/keycloak) – Identity and Access Management solution with support for SSO, OAuth2, OpenID Connect and SAML
 
## Automotive
Key technologies, middleware, tooling and experiments from my automotive engineering years.
### COVESA (SOME/IP, CommonAPI & tools)
- [COVESA/vsomeip](https://github.com/COVESA/vsomeip) – Reference implementation of SOME/IP middleware widely used by OEMs and suppliers.
- [kamelfakihh/vsomeip-docker-benchmark](https://github.com/kamelfakihh/vsomeip-docker-benchmark) – Performance benchmarking of vsomeip in containerized environments.
- [dev-guy/vsomeip-bazel](https://github.com/dev-guy/vsomeip-bazel) – Bazel build integration for vsomeip‑based projects.
- [COVESA/capicxx-core-runtime](https://github.com/COVESA/capicxx-core-runtime) – Core runtime for CommonAPI C++ service interfaces.
- [COVESA/capicxx-someip-runtime](https://github.com/COVESA/capicxx-someip-runtime) – SOME/IP binding runtime for CommonAPI C++.
- [COVESA/capicxx-dbus-runtime](https://github.com/COVESA/capicxx-dbus-runtime) – D‑Bus binding runtime for CommonAPI C++.
- [COVESA/capicxx-core-tools](https://github.com/COVESA/capicxx-core-tools) – Code generation and tooling for CommonAPI core.
- [COVESA/capicxx-someip-tools](https://github.com/COVESA/capicxx-someip-tools) – SOME/IP‑specific tooling for CommonAPI projects.
- [COVESA/capicxx-dbus-tools](https://github.com/COVESA/capicxx-dbus-tools) – D‑Bus‑specific tooling for CommonAPI projects.

### Simulation, HMI & dashboards
- [eclipse-sumo/sumo](https://github.com/eclipse-sumo/sumo) – Large‑scale open‑source traffic simulation platform.
- [ariexi/the-automotive-collection](https://github.com/ariexi/the-automotive-collection) – Curated collection of automotive software and embedded resources.
- [afondiel/car-cluster-hmi](https://github.com/afondiel/car-cluster-hmi) – Automotive instrument cluster HMI prototype.
- [kianwasabi/DES02_PiRacer-Instrument-Cluster](https://github.com/kianwasabi/DES02_PiRacer-Instrument-Cluster) – Raspberry Pi‑based digital instrument cluster experiment.
- [cppqtdev/Qt-HMI-Display-UI](https://github.com/cppqtdev/Qt-HMI-Display-UI) – Qt‑based HMI display examples and UI concepts.
- [GomaaMohamed/Yocto_Car_Dashboard](https://github.com/GomaaMohamed/Yocto_Car_Dashboard) – Embedded car dashboard built using Yocto.

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
