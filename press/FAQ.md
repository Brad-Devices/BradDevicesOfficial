# Frequently Asked Questions

**Is Brad Devices a real company?**
Yes. It is a vertically-integrated computer company founded by Festus Bradley Nyadimo in Kisumu, Kenya. The software toolchain is real and runs today; the silicon is designed and documented.

**What does "software before silicon" mean?**
The company ships its software toolchain — the BradVector assembler, interpreter, debugger and profiler — before its silicon is fabricated. This means the software is tested and verified against a real target, and the receipts exist before the promises.

**What is BradVector?**
BradVector is the GPU instruction set and the toolchain that builds for it. The toolchain includes `bradc` (assembler), `BVRT` (interpreter), `braddev` (CLI), `bradgdb` (debugger) and `BradTimeline` (profiler). It runs in any modern browser.

**What is BradISA?**
BradISA is the CPU instruction set. It is separate from BradVector — the company's rule is two ISAs, never one. They meet on the BradFusion fabric and share SPMP memory, but they do not share instructions.

**What is BradSense-Render?**
BradSense-Render is the company's neural rendering engine. Its M0 spatial upscaler is shipped and has been measured at 39.43, 39.44 and 39.57 dB PSNR. The temporal core and later rungs are queued.

**What is SPMP?**
SPMP — Super Power Memory Pool — is the unified memory pool that the CPU and GPU share. It is the ecosystem's nexus: one address space, one pool, accessed by both ISAs.

**What is the BradFusion fabric?**
BradFusion is the interconnect that ties the dies together. It is a mesh NoC — electrical in Gen1, optical in Gen2, quantum-entangled in the vision tier.

**How can I verify the claims?**
Every claim on the site carries a tag — SHIPPED, DESIGNED or VISION — and a link to verify it. The toolchain runs in your browser. The specification is open to read. The receipts are the product.

**How do I contact the company?**
Email <mailto:brad.devices.official@gmail.com>. Please include your outlet, deadline and the angle you are working.
