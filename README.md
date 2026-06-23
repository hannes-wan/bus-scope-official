# Bus Scope

**Prove what a USB device did on the bus.**

Inspect live USB traffic, decode device evidence, and retain structured .bscope sessions for firmware and hardware debugging.

[Website](https://hannes-software.com/bus-scope/) · [Download](https://hannes-software.com/bus-scope/download/) · [Help](https://hannes-software.com/bus-scope/help/) · [Latest release](https://github.com/hannes-wan/bus-scope-official/releases/tag/v0.1.6)

## The problem it solves

**USB bugs should not live forever in raw dumps and guesswork.**

Built for firmware teams, hardware labs, and device vendors who need a repeatable answer to why USB enumeration, descriptors, endpoints, or transfers fail.

## Why you should try it

- You debug firmware, drivers, HID, endpoints, descriptors, or enumeration and want a readable desktop case instead of raw USBPcap/usbmon sprawl.
- You need evidence before blaming the cable, host stack, driver, firmware, or device hardware.
- You want a cheaper daily workflow before escalating to a hardware analyzer.

## What makes it strong

### Capture the bus where the bug happens

- Linux usbmon and Windows USBPcap live capture feed a dense transfer timeline instead of forcing every USB diagnostics task through a generic network analyzer.
- Adapter state, device selection, endpoint direction, transfer type, status, text, and hex filters stay visible while traffic arrives.
- The Windows package can include the USBPcap setup path, and the app verifies capture interfaces before pretending live capture is ready.

### Control transfers become readable

- Setup packets, raw bytes, descriptor evidence, class decoder output, status values, and diagnostic references are tied to the selected transfer.
- Enumeration, endpoint stalls, vendor requests, HID feature reports, CDC line coding, and mass storage command evidence can be reviewed from one USB-first surface.
- Descriptor, HID, CDC, Mass Storage, and UVC interpretation are Professional features, so the paid path adds depth where firmware teams actually spend time.

### Sessions and reports survive handoff

- .bscope save/open keeps packets, payload retention, statistics, diagnostics, descriptor evidence, decoded events, and timeline state together.
- Community can export JSON or text; Professional unlocks HTML and PDF report export for customer cases, lab notes, and support handoffs.
- Trigger stop workflows and larger capture query windows support longer investigations without turning the page into a screenshot archive.

### $19 lifetime beats toolchain friction

- Bus Scope stays USB-only by design, so the workflow starts at device, endpoint, transfer, and payload evidence instead of broad protocol menus.
- Local desktop capture means sensitive firmware, HID, control transfer, and mass storage traces stay in your lab workflow.
- Professional is a one-time $19 lifetime license with no subscription for the USB reports, .bscope sessions, native live capture depth, and class interpretation buyers need.

## What you can do with it

- **Live adapter and device selection** — Select USB capture adapters, lock a device target, and keep capture state visible while traffic arrives.
- **Transfer timeline and filtering** — Filter by endpoint, direction, transfer type, text, hex, and device context while keeping rows dense and inspectable.
- **Packet detail and raw payload evidence** — Inspect setup fields, raw bytes, descriptor evidence, class decoder output, status, and diagnostic references.

## Screenshots

### Packet detail evidence

![Packet detail evidence](https://hannes-software.com/assets/bus-scope/screenshots/packet-detail-68e9d59d62.webp)

Setup fields, payload bytes, descriptors, and class decoder output.

### Filter investigation

![Filter investigation](https://hannes-software.com/assets/bus-scope/screenshots/filter-investigation-d4c5246de6.webp)

Endpoint, hex, device, and transfer filters for a focused USB case.

## Download packages

Latest GitHub release: **v0.1.6**

- [bus-scope-0.1.6-windows-x64-setup.exe](https://github.com/hannes-wan/bus-scope-official/releases/download/v0.1.6/bus-scope-0.1.6-windows-x64-setup.exe)
- [bus-scope-0.1.6-linux-x64.AppImage](https://github.com/hannes-wan/bus-scope-official/releases/download/v0.1.6/bus-scope-0.1.6-linux-x64.AppImage)
- [bus-scope-0.1.6-linux-x64.deb](https://github.com/hannes-wan/bus-scope-official/releases/download/v0.1.6/bus-scope-0.1.6-linux-x64.deb)
- [bus-scope-0.1.6-linux-x64.rpm](https://github.com/hannes-wan/bus-scope-official/releases/download/v0.1.6/bus-scope-0.1.6-linux-x64.rpm)

Prefer the product page if you want the full download notes, licensing details, and help articles:

- https://hannes-software.com/bus-scope/download/

## Editions

- **Community** — Free: USB capture review for local labs, support desks, and field debugging sessions. Key features: USB device explorer, Adapter capability diagnostics, Live timeline preview, Packet detail inspection, JSON and text export.
- **Professional** — $19 lifetime: One-time lifetime license that unlocks every paid Bus Scope desktop capability. Key features: Native live capture, .bscope save/open, HTML and PDF report export, Descriptor, HID, CDC, Mass Storage, and UVC interpretation, Trigger stop workflows.
- **Team** — $49 team / 3 seats: Three-seat team bundle for one product. Key features: Three machine-bound seats, All Professional features, One billing email, Website checkout activation.

## Good fit / not a good fit

Good fit: Inspect live USB traffic, decode device evidence, and retain structured .bscope sessions for firmware and hardware debugging.

Boundary: Not a hardware analyzer precision claim and not an automotive diagnostics tool. It is a daily desktop workflow for USB capture evidence.

## Search terms this product is built around

USB analyzer, USB packet analyzer, USB traffic capture, USBPcap capture, usbmon trace, HID descriptor debugging, usb packet analyser, usb sniffer, usb packet sniffer, USB protocol analyzer software

## About Hannes Software

Hannes Software builds focused local-first desktop tools: protocol diagnostics, music practice/transcription utilities, and small-clinic operations software. The pattern is simple: solve a narrow workflow well, keep data on the user’s machine, and sell with one-time pricing instead of a subscription treadmill.

Website: https://hannes-software.com/
Contact: hg3328762@qq.com

## Repository note

This is the official public repository for Bus Scope downloads, screenshots, release links, and product information. The commercial desktop application source code is not published in this repository.
