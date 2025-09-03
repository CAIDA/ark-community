# ark-community

Welcome to the Ark community!

Useful links to get started with understanding Ark:

 * [CAIDA Ark project page](https://www.caida.org/projects/ark/)
 * [Ark monitor locations](https://www.caida.org/projects/ark/locations/)
 * [Scamper measurement tool](https://www.caida.org/catalog/software/scamper/)


## Introduction

CAIDA runs a global measurement platform called Archipelago (Ark). We expand
it by adding hardware measurement nodes, usually Raspberry Pi devices, in
diverse locations to get a better view of the global Internet. In 2024, we
also started supporting software-based Ark nodes that run as containers.

Ark continuously collects data to help researchers and aims to:

 * Provide a secure, distributed platform for approved measurements.
 * Make it easier to create, deploy, and analyze large-scale Internet
   measurements.

Ark is designed for measurements that need coordination across multiple
locations. It runs ongoing measurement projects, creating public datasets on
Internet structure (e.g., the Internet Topology Data Kit). We also support
approved experiments to test new measurement techniques, keeping a record of
past and current projects.


## Measurements

### Public Datasets

The regular and ongoing measurements performed by Ark nodes get published as
public datasets. All the datasets are listed in the
[Archipelago Collection](https://catalog.caida.org/collection/archipelago)
on the CAIDA Resource Catalog, but some popular ones include:

 * [Ark Internet Topology Data Kit (ITDK)](https://www.caida.org/catalog/datasets/internet-topology-data-kit/), combining topology, geographic, AS, and DNS information
 * [Ark IPv4 Routed /24 Topology](https://www.caida.org/catalog/datasets/ipv4_routed_24_topology_dataset/)
 * [Ark IPv6 Topology Dataset](https://www.caida.org/catalog/datasets/ipv6_allpref_topology_dataset/)

### Custom Measurements

Approved researchers and collaborators can get access to the Ark integrated
active measurement programming environment which allows them to perform their
own measurements. This Python interface can be used to write programs with
pre-built measurement primitives (e.g. ping, traceroute, DNS lookups, etc)
and run them from multiple vantage points around the world, in near real-time.

If you are a researcher who would like access to this platform, please contact
ark-info@caida.org.

Useful links and documentation:

 * Doc: [Getting Started](https://www.caida.org/projects/ark/programming/)
 * Doc: [Scamper Python module documentation](https://www.caida.org/catalog/software/scamper/python/)
 * Paper: [An Integrated Active Measurement Programming Environment](https://www.caida.org/catalog/papers/2024_integrated_active_measurement_programming/integrated_active_measurement_programming.pdf)
 * Slides: [An Integrated Active Measurement Programming Environment](https://www.caida.org/catalog/media/2025_integrated_active_measurement_programming_pam/integrated_active_measurement_programming_pam.pdf)
 * Hackathon: [AIMS-17 (GMI-AIMS-5) Hackathon projects](https://www.caida.org/workshops/aims/2502/hackathon/#hackathon-projects)


## Questions, Issues, and Suggestions

We welcome anyone to get in touch with us if you have any questions about
the Ark project, getting access to data, or running your own measurements.

Send us email at ark-info@caida.org,
[create an issue](https://github.com/CAIDA/ark-community/issues), or join us
on our [Ark Mattermost channel](https://mattermost.caida.org/external/channels/ark-community-usershosts).
