[<< Back](https://cntt-n.github.io/CNTT/)
# Common NFVI Telco Taskforce

## Table of Contents
* [1. Overview](#1.0)
* [2. Scope](#2.0)
* [3. Principles](#3.0)
* [4. Technology Direction and policies](#4.0)
  * [4.1 SR-IOV](#4.1)
  * [4.2 PCI-Pass Through](#4.2)
  * [4.3 SmartNICs](#4.3)
  * [4.4 Acceleration Cards](#4.4)
  * [4.5 FPGA](#4.5)
  * [4.6 GPUs/NPUs](#4.6)
  * [4.7 EPA/NFD](#4.7)
* [5. Transitional Plans](#5.0)
* [6. Roadmap](#6.0)
* [7. Available Specifications](#7.0)

<a name="1.0"></a>
## 1. Overview

Initially organized early in 2019, the Common Network Function Virtualisation Infrastructure Telecom Taskforce (CNTT) was initially created in response to rapid changes in how networking applications are being designed, built and managed, plus a growing recognition of a perceived functional gap between the previous standard infrastructure models and the architectures needed to support Network Function Virtualization (NFV) applications.  Organizationally the Common Telco Network Function Virtualisation Infrastructure (NFVI)  project, jointly hosted by GSMA and the Linux Foundation, operates as an open committee responsible for creating and documenting an industry aligned Common NFVI Framework.  The CNTT group was created with the intent that it would create the NFVI framework, and eventually morph into an on-going project under the auspices of the GSMA and the Linux Foundation umbrellas.  The final on-going operational form of the group will be determined as the project evolves. 

<a name="2.0"></a>
## 2. Scope

Within the framework of the Common Telecom NFVI vision, there are three levels of documents needed to document the components and allow the practical application of the systems. They are, as highlighted in **Figure 1**:  **Reference Model**, **Reference Architecture**, and **Reference Implementation**.

<p align="center"><img src="./figures/tech_scope_doc_types.png" alt="scope" title="Document Types" width="100%"/></p>
<p align="center"><b>Figure 1:</b> Scope of CNTT</p>

<a name="2.1"></a>
## 2.1 Specification Types

- **Reference Model**: focuses on the __**NFVI Abstraction**__ and how NFVI services and resources are exposed to VNFs. It written at a high enough level that as new **Reference Architectures** and **Reference Implementations** are added, the model document should require few or no changes. Additionally, the Reference Model is intended to be neutral towards VMs or Containers.
- **Reference Architecture**: High level NFVI system components and their interactions that takes the Reference Model goals and maps them to something that has components in the real world.  It is expected that at least one, but not more than a few, Reference Architecture will conform to the Reference Model.  The intention whenever possible to use existing elements, rather than specify entirely new architectures in support of the high-level goals specified in the **Reference Model**.
- **Reference Implementation**: Builds on the requirements and specifications developed in the other two documents and adds details so that it can be implemented.  Each Reference Architecture is expected to be implemented by at least one Reference Implementation.

Below is a diagram of the different artifacts that will need to be created to support the implementation of the abstract concepts presented in the **Reference Model**, which are then applied to create the **Reference Architecture**, that will be deployed using the requirements spelled out in the **Reference Implementation**.

<p align="center"><img src="./figures/tech_scope_3.png" alt="scope" title="Document Types" width="100%"/></p>
<p align="center"><b>Figure 2:</b> Description of the possible different levels of CNTT artefacts</p>

<a name="3.0"></a>
## 3. Principles

Any specification work created within CNTT **must** obey to set of principles specified by CNTT:

[Reference Model Principles](../ref_model/chapters/chapter01.md#13-principles)
[Reference Architecture Principles](../ref_arch#principles)

<a name="4.0"></a>
## 4. Technology Direction and policies

<a name="4.1"></a>
### 4.1 SR-IOV

SR-IOV is a technology that allows 

<a name="4.2"></a>
### 4.2 PCI-Pass Through

<a name="4.3"></a>
### 4.3 SmartNICs

<a name="4.4"></a>
### 4.4 Acceleration Cards

<a name="4.5"></a>
### 4.5 FPGAs

<a name="4.6"></a>
### 4.6 GPUs/NPUs

<a name="4.7"></a>
### 4.7 EPA/NFD

<a name="5.0"></a>
## 5. Transitional Plans

It is vitally important for CNTT to have working NFVI solutions from NFVI vendors and mature VNFs/CNFs designs from application vendors that is compliant to CNTT specifications. It is also understood that, in some areas, the industry might not have solutions that are fully aligned with CNTT requirements. Therefore, it is important to have transitional plans to move from what is available today in the industry into fully CNTT compliant solutions and designs.

[Reference Model Guidelines and Transitional Plan](../ref_model/chapters/appendix-a.md) Describes maturity levels of VNFs/CNFs and technologies that might be allowed on each for VNFs/CNFs consumptions. 

**Figure 3** explains transitional plan approach in CNTT.

<p align="center"><img src="./figures/tech_transitional_plan.png" alt="scope" title="Transitional Plan" width="100%"/></p>
<p align="center"><b>Figure 3:</b> Transitional Plans in CNTT</p>

<a name="6.0"></a>
## 6. Roadmap

<a name="7.0"></a>
## 7. Available Specifications
* [Reference Model](../ref_model)
* [Reference Architecture](../ref_arch)
* [Reference Implementation](../ref_impl)
* [Reference Certification](../ref_cert)