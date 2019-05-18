* Motivation for Process Isolation
* Overview / Structure
* Introduction
    * Define / Differentiate Process Isolation
        * Multiple Concurrent Processes
    * Define / Differentiate Real Time
    * Threat Model(s)
    * Limitations for IoT devices
    * Multi Process Systems
    * Limitations for Real Time applications
    * (Limitations for Static / Dynamic Task Creation)
    * Secure IPC (is part of Isolation)
    * Reduce the risk from misbehaving actors
        * Guaranteed execution
        * Application Secrets / Proprietary Software
        * Dominance of Computing power
        * Interrupt Handling
    * Limitation from real time applications
        * Memory Overhead
        * Computational Overhead
        * Hard time constraints
    * Secure Interprocess Communication is necessity of Isolation
        * Attestation
* Process Isolation
    * Software Solutions
        * Compile Time bounding
        * Programming Language solutions
            * embedded NodeJS (JerryScript)
        *  Formal Verification
            * Of Programs
            * Of Operating System
        * Discuss Limitations
    * Hardware Solutions (Discuss for each)
        * MPU (Sancus / TyTAN)
        * Self Protecting Modules
        * Alternatives to MPU?
        * Hypervisors (ARINC 653)
        * Timber V
        * ARM TrustZone
        * Enclaves / Intel SGX
        * —  Virtual Memory
        * —  processor privilege levels / rings
* Scope / Capability Matrix of Solutions
    * (How) Are Interrupts handled in protection?
    * How are misbehaving actors handled?
    * Threat Model?
    * Size of Trusted Computing Base / Does it have a kernel/OS?
* Real Time
    * Define / Differentiate
    * Hardware Limitations
    * Software Limitations
    * Scheduling with Hard time requirements
    * Interrupt Handling
        * With Multiple Processes
    * Challenges with Process Isolation
