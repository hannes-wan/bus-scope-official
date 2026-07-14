# Bus Scope

[![Community Edition: Free](https://img.shields.io/badge/Community_Edition-Free-16a34a?style=for-the-badge)](https://hannes-software.com/bus-scope/download/)
[![Windows](https://img.shields.io/badge/Windows-Desktop-2563eb?style=flat-square&logo=windows)](https://hannes-software.com/bus-scope/download/) [![Linux](https://img.shields.io/badge/Linux-Desktop-f59e0b?style=flat-square&logo=linux)](https://hannes-software.com/bus-scope/download/) [![Local first](https://img.shields.io/badge/Workflow-Local--first-7c3aed?style=flat-square)](https://hannes-software.com/bus-scope/)

> Trace a USB failure from capture readiness through transfers, endpoints, descriptors, class evidence, and raw bytes.

A free USB analyzer: Community Edition includes USBPcap/usbmon capture, packet and protocol evidence, descriptors, endpoints, HID, CDC, Mass Storage, and UVC.

Inspect live USB traffic, decode device evidence, and retain structured .bscope sessions for firmware and hardware debugging.

**Bus Scope Community Edition is free to download and use.** Complete local USB capture and diagnosis for labs, support desks, and field debugging sessions.

[Download Community Edition](https://hannes-software.com/bus-scope/download/) · [Product guide](https://hannes-software.com/bus-scope/) · [Help](https://hannes-software.com/bus-scope/help/) · [Report a bug](https://github.com/hannes-wan/bus-scope-official/issues/new?template=bug_report.yml)

## Download Bus Scope 0.1.7

| Platform | Package | Use it when |
| --- | --- | --- |
| Linux x64 (APPIMAGE) | [bus-scope-0.1.7-linux-x64.AppImage](https://github.com/hannes-wan/bus-scope-official/releases/download/v0.1.7/bus-scope-0.1.7-linux-x64.AppImage) | Portable Linux desktop package |
| Linux x64 (DEB) | [bus-scope-0.1.7-linux-x64.deb](https://github.com/hannes-wan/bus-scope-official/releases/download/v0.1.7/bus-scope-0.1.7-linux-x64.deb) | Debian, Ubuntu, Mint, and compatible systems |
| Linux x64 (RPM) | [bus-scope-0.1.7-linux-x64.rpm](https://github.com/hannes-wan/bus-scope-official/releases/download/v0.1.7/bus-scope-0.1.7-linux-x64.rpm) | Fedora, RHEL, openSUSE, and compatible systems |
| Windows x64 | [bus-scope-0.1.7-windows-x64-setup.exe](https://github.com/hannes-wan/bus-scope-official/releases/download/v0.1.7/bus-scope-0.1.7-windows-x64-setup.exe) | Guided Windows installer |

Checksums, installation notes, and the complete platform matrix live on the [official download page](https://hannes-software.com/bus-scope/download/).

## Why Bus Scope exists

Built for firmware teams, hardware labs, and device vendors who need a repeatable answer to why USB enumeration, descriptors, endpoints, or transfers fail.

> **Edition boundary:** The technical sections below describe the complete product surface and can include optional licensed workflows. The exact free Community Edition scope is listed separately below.

### Stop treating USB failures like random driver behavior.

Bus Scope is the focused desktop USB diagnostics workbench for engineers who need live capture, control transfers, descriptors, HID, CDC, mass storage evidence, reports, and saved .bscope sessions without leaving the local lab machine.

### Live adapter and device selection

Select USB capture adapters, lock a device target, and keep capture state visible while traffic arrives.

### Transfer timeline and filtering

Filter by endpoint, direction, transfer type, text, hex, and device context while keeping rows dense and inspectable.

### Packet detail and raw payload evidence

Inspect setup fields, raw bytes, descriptor evidence, class decoder output, status, and diagnostic references.

### Capture the bus where the bug happens

- Linux usbmon and Windows USBPcap live capture feed a dense transfer timeline instead of forcing every USB diagnostics task through a generic network analyzer.
- Adapter state, device selection, endpoint direction, transfer type, status, text, and hex filters stay visible while traffic arrives.
- The Windows package can include the USBPcap setup path, and the app verifies capture interfaces before declaring live capture ready.

### Control transfers become readable

- Setup packets, raw bytes, descriptor evidence, class decoder output, status values, and diagnostic references are tied to the selected transfer.
- Enumeration, endpoint stalls, vendor requests, HID feature reports, CDC line coding, and mass storage command evidence can be reviewed from one USB-first surface.
- Descriptor, HID, CDC, Mass Storage, and UVC interpretation are included in the free Community edition alongside capture and packet inspection.

### Sessions and reports survive handoff

- .bscope save/open keeps packets, payload retention, statistics, diagnostics, descriptor evidence, decoded events, and timeline state together.
- Community can export JSON or text; Professional unlocks HTML and PDF report export for customer cases, lab notes, and support handoffs.
- Trigger stop workflows and larger capture query windows support longer investigations without turning the page into a screenshot archive.

### Full diagnostics in the free Community edition

- Bus Scope stays USB-only by design, so the workflow starts at device, endpoint, transfer, and payload evidence instead of broad protocol menus.
- Local desktop capture means sensitive firmware, HID, control transfer, and mass storage traces stay in your lab workflow.
- Professional adds only durable .bscope session save/open and HTML/PDF reports; capture, decoding, triggers, large-query inspection, and JSON/text export stay free.

## Community Edition is genuinely useful

- Native usbmon and USBPcap live capture
- USB device explorer and adapter diagnostics
- Descriptor, HID, CDC, Mass Storage, and UVC interpretation
- Trigger stop workflows
- Large capture queries and packet detail inspection
- JSON and text export

Optional licensed workflows are available for people who need the expanded feature set. Licensing details belong on the website; the Community Edition remains the free way to evaluate and use the core product.

## See the real desktop workflow

### Packet detail evidence

![Packet detail evidence — Bus Scope](https://hannes-software.com/assets/bus-scope/screenshots/packet-detail-80a294b40a.webp)

Setup fields, payload bytes, descriptors, and class decoder output.

### Filter investigation

![Filter investigation — Bus Scope](https://hannes-software.com/assets/bus-scope/screenshots/filter-investigation-5a63fcca2c.webp)

Endpoint, hex, device, and transfer filters for a focused USB case.

## Local-first by design

Bus Scope is a desktop workflow. Your working files stay on the machine unless you deliberately export or share them. The product page documents the exact capability boundary so the focused workflow can be evaluated on real evidence.

## Documentation

- [Connect to a USB Device](https://hannes-software.com/bus-scope/help/connect/)
- [Bus Scope License](https://hannes-software.com/bus-scope/help/license/)
- [Platform Capture Setup](https://hannes-software.com/bus-scope/help/platform-capture/)
- [Saving and Comparing USB Sessions](https://hannes-software.com/bus-scope/help/sessions/)
- [USB Capture Troubleshooting](https://hannes-software.com/bus-scope/help/troubleshooting/)

## Frequently asked questions

> **Community scope:** Community Edition includes native live capture, descriptor and HID/CDC/Mass Storage/UVC interpretation, trigger stops, packet detail, and JSON or text export; .bscope save/open and HTML/PDF reports are optional licensed workflows.

<details>
<summary><strong>Is Bus Scope a hardware USB analyzer?</strong></summary>

No. Bus Scope is a software-only USB diagnostics desktop workbench. It captures USB traffic using the built-in Linux usbmon and Windows USBPcap interfaces — no external hardware analyzer required.

</details>

<details>
<summary><strong>Does Bus Scope work on both Linux and Windows?</strong></summary>

Yes. On Linux it captures via usbmon. On Windows it captures via USBPcap (the Windows installer can include the USBPcap setup path).

</details>

<details>
<summary><strong>Who uses Bus Scope?</strong></summary>

Firmware engineers, hardware labs, USB device vendors, and support teams who need a repeatable, reportable answer to why USB enumeration, descriptors, endpoints, or transfers fail.

</details>

<details>
<summary><strong>Should I use Bus Scope or Wireshark with USBPcap?</strong></summary>

Use Wireshark and USBPcap when you need a free general packet analyzer and already know how to build the USB workflow yourself. Use Bus Scope when your work is mostly USB firmware debugging and you want descriptor, endpoint, control transfer, session, and report evidence in one focused desktop tool.

</details>

<details>
<summary><strong>Is USBPcap by itself enough for Windows USB debugging?</strong></summary>

USBPcap is enough to collect host-visible USB traffic, but it does not provide the full diagnostics workflow. Bus Scope adds product-level capture readiness, USB-first filtering, descriptor interpretation, endpoint context, .bscope sessions, and report export around that capture path.

</details>

<details>
<summary><strong>When do I need a hardware USB analyzer instead of Bus Scope?</strong></summary>

Use hardware when the question is physical-layer proof: electrical behavior, signal integrity, link timing, compliance evidence, or a failure that never reaches the host capture layer. Use Bus Scope first for enumeration, descriptor, endpoint, control transfer, HID, CDC, mass storage, and UVC cases visible to the host.

</details>

## Community, support, and security

- Bugs: [open a structured bug report](https://github.com/hannes-wan/bus-scope-official/issues/new?template=bug_report.yml)
- Ideas: [request a focused workflow improvement](https://github.com/hannes-wan/bus-scope-official/issues/new?template=feature_request.yml)
- Product help: [documentation and troubleshooting](https://hannes-software.com/bus-scope/help/)
- Private support: [support@hannes-software.com](mailto:support@hannes-software.com)
- Security reports: follow [SECURITY.md](SECURITY.md); do not post sensitive files, credentials, patient data, or private captures in public issues.

## Official repository

This is the official public distribution and community repository for Bus Scope: verified release links, current screenshots, documentation routes, issue intake, and security guidance. Product development happens in a private workspace; public issues here are the right place to report reproducible product behavior and request focused improvements.
