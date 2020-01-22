portable FreeRadio, with fair repository managern and usercentric community, fueled with e-book/manual store: Open Source education, needed for user-centric content creation, consumption and archiving purpose. Complete differente philosophy to Linux Kernel, which is huge and monolythic.

TU Delft, WaterManagement, RijksWaterStaat, LowLands
Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.
PostGIS Implements ISO standards OGC ‘Simple feature access’, with extensions, subset of ISO ‘SQL/MM’ supported 
formats: Well-Known Text, Well-Known Binary, GML, KML, GeoJSON
Test dataset: het Nationaal Wegen Bestand, NWB.
Standardization of processes: Certified Information Privacy Professional Europe

Oracle 9g,10g,11g,12c, 
Oracle Dataguard, Forms, Sharding, Spatial
Oracle relies on Apache Spark, which has API for for Java, Python, Scala, and R
vergelijking van Oracle Spatial met MySQL,  PostgreSQL/PostGIS en SQL Server.
In samenspraak met Rijkswaterstaat is besloten MySQL niet mee te nemen in de volgende fasen vanwege de beperkte functionaliteit op ruimtelijk gebied. 
geen  referenties!
Test dataset: het Nationaal Wegen Bestand, NWB.
PostGIS Implements ISO standards OGC ‘Simple feature access’, with extensions, subset of ISO ‘SQL/MM’ supported 
formats: Well-Known Text, Well-Known Binary, GML, KML, GeoJSON

GNU/Linux Distributions Committed To Freedom
Skype replacement: W3C, HTML5 (but not WEBrtc as endorsed by CERN)
Video Editing: FSF encourages users to support Kino, Cinelerra, AVIDemux, Kdenlive, LiVES, Lumiera, PiTiVi, Blender, and Open Movie Editor. What about OpenShot, Lightworks, and Novacut?
Free Software Version of Oracle Forms / Automatic Transcription
Google Earth Replacement
PowerVR Drivers: Reverse engineering graphic drivers. The project's goals does include creating a Gallium3D PowerVR driver and using LLVM to take advantage of multi-core SoCs.

Protocols: Disrupting the norm by mixing laws, standards and trade secrets. ie. https://www.xiph.org/
blockchain invoice system is encrypted billing service based on bit transactions.
Distributed knowledge: File and Object storage, aka KarmaCloud "Just tag it".
Kokosnoten Kwekkerij De Veilige Haven


gettext ( C application that parses source code and pulls up strings for translation)

Baseline Compute by #Aquarius porting OpenCPN #Vectorrender to Kodi tm, including sensor, Vendor IP block ecosystems. Kodi & OpenCPN

Kodi runs appliance mode or admin-mode. Admin mode ads managing users, changing sources, filebrowser, notepad, and settings and database management. Also full desktop mode, supporting full stack developpers.

Both projects are build around a cross platform GPU rendering pipeline, and both have a Python Plugin Architecture while utilizing minimal resources, ridding heavy dependencies, while having lot's of overlap in it's community.
C/C++, C11, Cmake3.4, github. And multiple overlapping dependencies like tinyxml, sqlite, opengl. 

This would add navigation on both water and earth without really adding to overhead; it's mostly moving code-base and utilize Kodi's rendersystem, addon system, GUI. Optimized radar experience: less click, auto setup, many profiles. Later, Databases, PostGIS compliance, API's should be streamlined and unified anyway. Hooking into Kodi's ecosystem is an essential upgrade to OpenCPN's codebase maturity, maintainability, towards 64bit onwning cleaned legacy.

Start cloning, adding SPDX license project to create a Freecompatible roadmap. Daily builds with librelec JEOS infrastructure. Lot's of Cmake work.
deprecate and build standardize QT and wxWidgets2.9 gui conversion to Kodi GUI. 

Vectorrender for Kodi:
Projects like OpenStreetmaps and OpenCPN (maybe also Stellarium and flight simulator?) also adds sensoring, and vector-based rendering (S57ENC format, and BSB format for raster charts), and a interesting community of hardware vendors with interesting appliances and markets on similar hardware requirements. 

Openstreetmap:
The process of rendering a map generally means taking raw geospatial data and making a visual map from it. Often the word applies more specifically to the production of a raster image, or a set of raster tiles, but it can refer to the production of map outputs in vector-based formats. 
"3D rendering" is also possible taking map data as an input. The ability to render maps in new and interesting styles, or highlighting features of special interest, is one of the most exciting aspects having open access to geodata.

GBM/KMS support is essential; just like Vulcan support is the move forward. flightsim is the next render on the roadmap. As is stellarium. 


Some details, project Aquarius
Allignnment with Raspberry, Arduino and many projects and vendor communities.
OpenCompute CPU, I/O Core die and DefCon Decibel Feature Chip, crucial for core communication and maybe cache memory. 
GNU/Linux + "open-source GPU" via software Vulcan renderer and open gpu compute stack merged Vulcan, opengl, opencl and ROCm.
OpenWRT (DataBoss) + FeeNAS (AssetControl+ OpenGarage (Securitas) + Eden (OpenGarden) and Cyanogen Restarted (Mobile ICQ)!
retroplayer redesign to maintain legacy compatibilty libs.


From there, Stellarium only makes sense.
64 bit only, linux focussed, c++14 minimum, parallel focus, parallel gui, database, api's, python scrapers.


Features improvements
New redesigned DefCon Decibel Feature Chip, configurable broadcast power, from the ground up (for all Vendors IP blocks like FreeRadio).
Coreboot support.

Drivers, Performance upgrades for games: the usual 4% tuning, so driver release and product released tightly controlled.

OpenGL Extensions: 323 extensions (GL=299 and WGL=24)
- OpenGL SPIR-V Extensions: 17
>> newest since 2019 added.
30+ Vulcan 1.1 extensions


is intended to be modular and minimalist so other projects will be able to re-use the code under free license, open RTL schematic.
UserAgentOS, adds networking with OpenWRT and aims for a cyanogenmod like community. Joining Arduino and Raspbery, into a new baseline for the youth, women and the dispaired.
FOSS based OS, created to create appliances for makers, prototyping, prosumeers and consumers.
Portability is the way to making the distribution part of copyleft code reality; fusing Free and Open into FOSS. This also removes the conflict of interest from the sourcetree, managed by the foundation. 


Independent, meaning controlling external non-build dependencies.
Baseline Tree-structure:
src/
    FreeRadio Architecture + renderpipline
    Firmware
    Drivers
    Hardware
    Kodi/ Renders
        Retro/
        OpenCPN/
        Openstreetmaps/
        Legacy/ 8b/16b/32bit
depends/
docs/
build/
OS/
tools/
Toolchain/
Target/


To do's
implementing new C++-code, improving CMake, vulcanize pipeline and windowing.
Kind of like how opengl was an open standard but you had to pay to join the organization to make a "opengl" implementation. 

OpenCPN - Cmake > 3.1.1.
IF(OPENGL_FOUND)
    target_sources(${PACKAGE_NAME} PRIVATE
        include/glChartCanvas.h
        include/glTextureDescriptor.h
        include/glTexCache.h
        include/glTextureManager.h
        include/TexFont.h
        src/glTextureDescriptor.cpp
        src/glTexCache.cpp
        src/glChartCanvas.cpp
        src/glTextureManager.cpp
        src/TexFont.cpp
    )
ENDIF ()






This change moves the base functionality for CThread to std::thread
https://github.com/xbmc/xbmc/pull/13721
This is a step toward moving toward implementing an Executor service to be used to replace the Job functionality as well as form the basis for message passing in a more "actor" based software design.

https://github.com/LibreELEC/LibreELEC.tv/pull/3537
his is a bump of pretty much all non-add-on (ie. "main") packages in the following directories:
    x11
    audio
    security
    tools
    sysutils
    devel
    print
    lang
    python
    network
    graphics
    multimedia
    compress
    debug
    databases
    web
    textproc
Add OpenCPN and build it with Libreelec, than as addon from Kodi.

Kodi Apple: 
Xcode10.2 with SDK12.2 for tvos and ios and SDK10.14 for osx64.
Android: NDK_VERSION="18" DEFAULT_NDK_API="21"

watch + OLED tablet + Rasp server + Rasp Zero Client
Dev kits for Explorers: 
Cars, boats, audio, video, HomeOS (modules garden, garage, alarm, lightning,
Radeon Software Adrenalin 2020 Edition 20.0 Highlights
Day 1 open-source Linux driver support with Navi
open gpu compute pimped with Vulcan, opengl, opencl and ROCm.
Deprecate closed source GPU driver and 32 bit.
Android Chromebooks.
Improved VP9 decoding



The project goes CPU first, so there is time for Open FOSS Renderpipeline Compute to mature.

MESA ie. has to speed up GPU compute API via OpenCL. 
Mesa, also called Mesa3D and The Mesa 3D Graphics Library, is an open source software implementation of OpenGL, Vulkan, and other graphics API 
Like standards, toolchains and user spaces software became terrible delayed, and full of wrong architecture from the past, and the present (spaghetti monoliths without parrallism)


To settle patent tuning and FOSS GNU Hackers I suggest the following:

A grace period, in which solutions present themselves. The goal is to deliver an open and fair renderpipeline. I am thinking of MESA, Kodi, OpenElec, OpenCPN, OpenStreetMap, and many of it's datasources. All unified under one ultra strong and vocal label.

Main work continues but the roadmaps need to be defined and public. Open accessible info. while the value is within the language and compliance to much need stadands. So you can see where CERN comes from and where they are heading.


Continued work in trying to improve the power consumption in order to generate less heat and improve battery life. less depenedencies, code cleanups, deprecat 32 bit, and as much as possible assembly, at least to managed levels. Re engage  the communnity, by joining the fractions: The goals are simple: manageable, simplicity, useability.



In response to the failed buy-out attemp, $44 billion, by Qualcomm, blocked by Chinese authorities, NXP and Freescale merged into a $30 billion market value. 'De Eindhoven (NL) chipmaker NXP, Philips spinoff, also bought Wi-Fi/Bluetooth division (Ultra Wideband chip market with more security compared to Bluetooth, which in turn is helping drive NXP design wins for keyless entry fobs for cars and will also enable smartphone-based keyless entry solutions for cars and buildings, of Marvell Technology Group for $1.76 billion in cash. This unit $300 million in revenue for Marvell in fiscal 2019 and NXP expects that to double by 2022. Before, NXP also utilised Vivente GPU tech. So the blocked Qualcomm take-over, made NXP choose to compete Broadcom en Qualcomm. 

NXP is the world's biggest automotive chip supplier, competing Cypress Semiconductor (set to be acquired by Infineon), with a product line that covers everything from infotainment systems and instrument clusters to driver-assistance systems, in-vehicle networking chips and electric car battery management systems. The Dutch firm's silicon is also found within quite a few smartphones, IoT devices, mobile base stations, smart cards and industrial and medical products, among other things (many integrating standards and IP blocks) like a popular NXP’s NPC300 NFC controller.

CES, where NXP is unveiling an app processor for IoT/edge computing devices (the i.MX 8M Plus) that has a dedicated AI co-processor, as well as an automotive network processor (the S32G) that supports Gigabit Ethernet connections. Earlier, NXP unveiled an NFC/UWB chipset featuring a common secure element. Adding Wi-Fi/Bluetooth radios within the same package only makes sense. 5G base station + the last mile.

Automotive Radar and Battery Management Systems
NXP estimates the market for automotive radar solutions is growing at a roughly 30% clip, thanks to both higher penetration rates for driver-assistance (ADAS) systems featuring radar and the inclusion of more radars per car. The company's offerings in this space include transceivers, MCUs, power management chips and network interface solutions. Reger suggested automotive radar is a major R&D priority for NXP, and noted the company is looking to put a transceiver and an MCU on the same chip.


Chips for battery management systems -- they include products such as MCUs, battery sensors and battery cell controllers -- have also been an automotive growth driver thanks to rising electric car adoption. Reger asserted NXP has seen "enormous design wins" in this space, as automakers looking to maximize battery densities (and with them, electric car range) rely on NXP's silicon to keep batteries working reliably and avoid overcharging.

"We need to make sure our stuff is highly precise, managing every individual [battery] cell, and is functionally safe," Reger said.


Hardware unification around the same API's. Apppliances makers have to be there, so NXP chosing G77 is the quickest route. Panfrost is an open-source, reverse-engineered Arm Mali driver, supporting their Midgard/Bifrost hardware. Since earlier this year, Mesa 19.1 includes the Panfrost Gallium3D driver, which provides basic OpenGL functionality and can pair with this DRM/KMS kernel driver for a fully-open and functioning driver stack for Bifrost/Midgard. With 3 years software development, GBM/KMS + Panfrost Gallium3D driver, close to support OpenGLes 2.0 and developping 3.0 support. Also lacking OpenCL and Vulcan. Works to drive kodi. 
Also big.little (1+4) for 7W. 
two Thunderbolt 3 connectors and Intel’s latest AX200 Wi-Fi 6 module supporting 802.11ax Wi-Fi and Bluetooth 5, a Gigabit-class 4G/LTE modem, as well as NXP’s NPC300 NFC controller
Voldoen en vrij eenvoudig groeipad: NXP, Bavaria, Dommelsch, daf, campina. ASML, NXP and Bavaria might even expand Eindhoven metropool to Brabantstad. For example buying Willem2 and NEC stadium for €50 million.


Afas and Exact.
Accenture & localized CO's brainpain, but with partners Oracle, JAVA and PHP, outperformed by JavaScript and Python. 
An Alernative:
Solutions? They are there in a variety of tastes, colors and other dimensions.

Zenk.io (Scality)
Repairing the Zenko Project: Jira, payment model, databases,

Example:
HSA Foundation
LibreElec (buildsystem based on OpenElec) / ClearOS (Intel)
Kodi (Content Manager, IVM, NVidia, Samsung)
Default UserSpace / RSS3 / HTML5 / Chromium / Preferred UserSpace.

Wifi Alliance
USB:
HDMI
displayport:
DDR5: JEDEC has over 300 members, including some of the world's largest computer companies
PCIe5.0: PCI-standards consortium PCI-SIG (Special Interest Group)
SATA: Serial ATA International Organization
Unicode 12.1

 Internet Engineering Task Force (IETF) : TCP/IP, ipv6, 
 The IETF cooperates with the IETF W3C, ISO/IEC, ITU
 SD Association, a group that sets standardisation of SD and microSD cards, the Wi-Fi Alliance group and the JEDEC group

DOJ: Google & Apple
FTC: antitrust against Facabook and Amazon.


Radeon on Linux: I argue that AMD's Linux strategy is key in 2020+ continious growth in mobile markets. 
AMD's prop driver outperformane the open source driver on feature and performance. Yet, the Open Source driver also works great and is developed publicly by Red Hat, Google, Valve, Feral Interactive, AMD. Googles strategy is diveresified and diffuse, Android is on GLES3.2, moving to Vulcan 2.0? so in between Mali serves its purpose and allow for developping OPENCPN in renders in kodi and cmake in openelec to build opencpn with it. On Linux 5.2 and MESA 19.2, AMD's 2019 product line up is fully supported, except for Navi. LLVM support is needed this Linux 5.3 at least is what should be in Ubuntu 19.10, Fedora 31, etc and will presumably be the first kernel with mainline Radeon Navi support. This also ties in and the "libc++" C++ standard library, for all those cross-platform software outhere. 

With SPIR-V, the graphics program and the driver can avoid the overhead of parsing, compiling and linking the shaders. Also, it is easy to re-use shaders written in different shading languages. For example an OpenGL program for Linux can use an HLSL shader that was originally written for a Vulkan program for Windows, by loading its SPIR-V representation. The only requirement is that the OpenGL implementation and the driver support the ARB_gl_spirv extension.

I would not consider switching to AMDVLK for some extra overperformance and the cost of losing open source driver. Yet, if newer API's can force you towards AMDVLK. 

AMD is leading in cores, IPC and frequency parity, while being more energy efficient. superior product with Zen2 across all workloads, gaming included. Yet Intel has it's OEM channel and integrated PCH with wifi/bluetooth. AMD has to move more graphics card in laptops. It is lacking there and it's a very big chunk of the market.
That means it has to make cool and quiet but reasonably powerful chip.
Only since april 2019, Intel offers its full range of Mobile 45W and Desktop CPUs for its 9th Gen family. Up to eight cores and 16 threads, and up to 5 GHz, on both desktop and laptop. It doesn't offer wifi6, which comes with Ice Lake to mobile first. Cache memory in a I/O die would be quite interesting for APUs and console SOCs of the future.
So Intel is going straight to chiplets on interposer, it will be interesting to see if AMD adopts this with Zen 3 or waits until Zen 4. Anyway its nice to see competition doing its job. It looks awesome for mobile form factors!
AMD needs to imorove it's io die and move to EUV. Intel has 10nm, foveros, EMIB and chiplets coming.
wonder if a 14nm IO die is ripe for stacked DRAM on top.
Picasso can have a quick follow up with 7nm Matisse APU and 7nm Zen for Chromebooks. In between software needs to mature. Win10 may 2019 Update seems great for AMD multicore strategy.
Final CU redesign? 4xShader engines, whith 1x geometry engine per shader engine, with max 16x rops per SE so only 64rops total).
The bottlenecks with GCN are 3 fold: , and it didn't scale well to higher power enveloppes. R/DNA is the launched, with , to be GCN successor. 
7nm GPU in 2019, now AMD will split up their GPU architecture; they break off NAVI for gaming, and continouating VEGA for HPC/APU. Also the new consoles and maybe Samsung Androids will move to NAVI. 



patch management strategy to maintain status quo; you always will find fisher in the sea of information.
https://www.cybersecurity360.it/soluzioni-aziendali/nel-2019-divulgate-16mila-vulnerabilita-qual-e-lapproccio-corretto-al-patching/

More details on CERN's "Microsoft Alternatives" via the MALT table.
Analyzing the first three critical issues, at the top of the list is the bug CVE-2017-11882, a Microsoft Office memory corruption vulnerability that existed for 17 years before it was patched in November 2017.
object verification bugs in the IonMonkey just-in-time (JIT) compiler of the Mozilla's JavaScript engine SpiderMonkey.
Tracked as 'CVE-2019-17026,' the bug is a critical 'type confusion vulnerability' that resides in the IonMonkey just-in-time (JIT) compiler of the Mozilla's JavaScript engine SpiderMonkey.

In general, a type confusion vulnerability occurs when the code doesn't verify what objects it is passed to and blindly uses it without checking its type, allowing attackers to crash the application or achieve code execution.


It's the whole industry making a jump: pci4 till 6 released between now and 2021. USB4 (usb3.1+thunderbolt3+dvi2) soon, wifi6, 5g. The only difference this time is AMD combined the IP from Asmedia and licensed IP, then put in the fab order. And being short stacked, makes them not invest in HBM yet.
Basically, AMD core strategy is to make a scalable, modular structure with as little cost as possible. It offers immense flexibility while being economically feasible.

On the other hand you have a scalable I/O die that is large and contains expensive cache memory and other things crucial for core communication; but is made on a cheaper, mature node to reduce the costs once again.

That IO hub looks like you could split it into quarters for the consumer market. 2 IF links, 2 DDR4 channels, 32 PCIe lanes. Add in two highly binned chiplets for high frequency 16-core.
AMD managed to keep the NAvi die real small, 257mm2. IO-die just like for Rome, with HBCC/NVMe, PCIe PHY, Radeon Media Engine, Zero-lag Radeon Display Engine, TrueAudio 1.2 DSP 
Radeon Media Engine brings 40% encoder speedups, Improved Encoding (New HDR/WCG Encode HEVC), and 8K Encode (HEVC & VP). 
AMD’s TrueAudio 1.2 DSP and better visuals with Radeon Display Engine.

7W and 15W versions, 123 mm² max. Baseline disruption.
GCN inspiredd GPU architecture, lacking pice4/5, and hbcc/GDDR6, but scaleble from the start, geared towards drawing Triangles/pixel fillrate efficiency. directly access SSD and network drives (i.e. 4k/8K video) with superfluid disk access times. 
Radion Drivers: Shadow Engines like ShaderEngines, FreeSync2, DefConAudio,and fix function GPU parts like geomotry, memory or those that doesn't scale well with smaller process, to be extandible with GPU chiplets with blocks (like CCX) of shader engines. 
DisplayPort 1.4a, HBR3, DSC 1.2a, HDMI 2.0b, HDCP 2.2
Intel Gen11: DisplayPort 1.4, HBR3, DSC 1.1, HDMI 2.0b, HDCP 2.2

Some future synergetic effects in their lego strategy, both in APU and in Dual-gpu becomming 4 Chiplet GPU's, high yielding small chips to capture market share, grow margin. 

Main Navi features are HBCC and PCI5 with high bandwidth memory/speed, which allows for New Compute Unit Design with twice the throughput. Navi and can 


GPU-focussed 2019, to bring 7nm Vega/Navi to mass-market is a huge undertaking, also involving the mid 2020 XBOX Scarlett (Zen2+navi with 4 times the power of the Xbox One X supporting 120 frames per second and 8K visuals and improved  by 40x time (released with Halo Infinite) and Sony PS5. 
NAVI APU's will clear out remaining Nvidia laptop business. 
With gamers and prosumers favoring AMD, Nvidia created their own bubble. The datacenter is their future.

XGMI GPU-to-GPU Interconnect
XGMI is the package-to-package part of Infinity Fabric, similar to what we use between sockets on a 2P Epyc system. If you think of Infinity Fabric as having three flavours...
     on-die (SDF)
     between dies on same package (GMI)
    84GB/s between packages (external GMI or XGMI): up to 5X faster than PCIe Gen 3 interconnect speeds.

AMD has a nearly for free update of the GMI-part of Infinite Fabric thanks to PCIe4.0. 

Now, with AMD completly being equal to Intel in terms of IPC and performance, AMD can build market share in everything non-mobile. Yet, AMD can completely shutdown Nvidia's mobile laptop business, gamebooks and highend laptops: 7nm APU's ultrabooks and Navi chiplet's for the gt105TI.

In mobile, Intel still has the integrated PCH, compared to AMD's 11W external 14nm PCH.

Post Navi:
2 V20s + an IO die with 500GB/s link to each V20, move all HBM interfaces to the IO die put all the HBM around the IO die in the middle and the 2 GPUS on either side

In 2019-2020, AMD will secure the remaining NVidia gamelaptop business with Navi APU's. But to expand in mobile and compete Intel (with integrated WIFI6/Buetooth5 and mobile-first) Apple, Qualcomm and ARM-ecosystem is still a bridge to far. Yet, those zen2 apu will have their GPU strenght, only to be expanded with WIFI6 chip to become highly competetive in even 7W.

Then AMD will add Chromebook and Android as well. Android Vulcan GUI, being 20% more efficient + OLED and eInk screens. Then AMD will compete Apple, but for now the Samsung GPU IP deal will do. Samsung needs it's flagship like iPad and Microsoft Surface. And AMD build it's flagship on Exoscale computing. I think we all know by now that Samsung's GPU department hasn't produced anything to even reach ARM's Mali perf-per-watt, let alone Adreno or Apple's iGPU.
Licensing AMD's technology might put them back on the table + 8K TVs will require immense gpu power, which current mobile tech can't handle.

AMD's chromebook chips, A4-9120C & A6-9200C, are build around dualcore Excavator CPU's and Polaris GCN on 28nm. So AMD started rock-bottom part of the Chromebook market, competing Intel N4200 and ARM. Latest news, shows google adding coreboot support for picasso, ZEN+ + Vega3, Ryzen 5 3500U, 210mm2. Moving from 6w to 15, shifts competition to i5-8250u, 123 mm². Also Hygon Dhyana is pursuing Chromebook with their Zen reference design.

Google is eyeing on running Android on GPU, Vulcan is the way. rendering Android's GUI on GPU, eliminating one of Apple USP's. WebGL in Chrome also is nice. Now they hired Freedreno  dev. After Pixel 3, with Qualqomm Adreno GPU on ChromeOS. Kerneldriver Linux 5.3 is ready, probably optimizing the rendering pipeline (Wayland, MESA, Vulcan). 
GBM/KMS seems the way.
Rob joins the likes of Wayland founder Kristian Hoegsberg, Nouveau creator Stephane Marchesin, and other long-time open-source graphics driver developers now employed by Google. 



Effectivly, AMD needs to shrink it's I/O-die to fit a WIFI6 chip in there, i.e. NXP/Marvel chips, to access mobile phones and Android themselves. But than it comes with Google backing, and 

AMD software weakneasses: release day support is improving, and generally needs to mature. AMD stack is on it's way to have the best Open Source strategy to formalize in AMD Open Source Graphic Compute:
 - FOSS Video drivers:
 - ROCm3.0 (Open GPU Compute): Newest parralel stuff and 
 - OpenCL2.0 (AMD has some latency on Linux)
 - OpenGL4.6 / Vulkan2.0 / DirectX12.1
 - Coreboot: For Excavator and soon for Zen.




Out of the scope of this article but worth to mention, is DRI implementation. It uses KMS/DRM infrastructure as well but scanout content is displayed via software rendering, using double-buffered Skia surfaces. This implementation could be particularly useful for budget devices, for example those that don't have GPU at all. (Besides, Ozone-DRI also has a quite bad nomenclature because "DRI" refers to X11 direct rendering, even though X11 is not used at all there).

Maybe buy Nvidia automotive? 

dual-chip architectur becomes more interesting when doing i.e. 2x4K@120fps. In graphic pipeline, it's running the GUI and the content threaded on GPU and have small cpu's, also big.little (1+4) for 7W. 


AMD's architecture, perfectly integrates in it's modular, parallel design philosophy, with chiplet packaging. Epyc 2 Rome and Vega 20, PCIe4.0 reduces latency and power consumption, enabling GPU chiplet designs powered with XGMI.


AMD & Google added Coreboot support to Picasso, 12nm CPU + Vega. Beating current gen Intel Chromebooks. But Intel goes mobile first with 10nm, so their 2020 will be very strong in mass market, specifically portable.

AMD 7nm APU with Zen2 and Navi + 12nm I/O and maybe MARVEL WIFI6.


Ryzen 3000-series APUs will bring 12nm and PCIe4.0 for apu's. It has the new IO-chip with integrated HBCC memory controller ad XGMI and therewith a chiplet-ready design.  
4.000 series will have 7nm+ ZEN2 CPU and NAVI pcie5 GPU, mix and match chiplet design. Enable ROCm3.0 (Open GPU Compute) for APU's. But misses WIFI/Bleutooth.


For AMD GPU to grow, PCIe4.0 and 5.0 are their backbone. latency is still too high for GPU chiplet interconnection. Besdies, AMD wants to deploy ZEN succesfull strategie to GPU. Infinity Fabric is the umbrella term covering on-die (SDF), inter-die (GMI) and inter-package (XGMI) connections.
SDF - Scalable Data Fabric
GMI - Global Memory Interconnect
eXternal (off-package) GMI


https://pbs.twimg.com/media/DNF2x4RWsAENaQx.jpg
https://img.purch.com/-16d682cbcbac77a99a1276961cb0ed9af44ea7a8a1b9fac20a-pimgpsh-fullsize-distr-jpg/o/aHR0cDovL21lZGlhLmJlc3RvZm1pY3JvLmNvbS9KL1cvODA5NDIwL29yaWdpbmFsLy0xNkQ2ODJDQkNCQUM3N0E5OUExMjc2OTYxQ0IwRUQ5QUY0NEVBN0E4QTFCOUZBQzIwQS1waW1ncHNoX2Z1bGxzaXplX2Rpc3RyLmpwZw==
https://images.techhive.com/images/article/2017/01/vega-arch-preview-overview-primary-100702196-orig.jpg

Epyc 3 Milan, 12nm I/O die and PCIe5.0 and maybe 2 more 7nm+ chiplets. To power NAVI with GPU chiplets and 2 petabytes as virtual adressesable memory with 

Moreover if you look at the Zeppelin die and move all the IO and memory controller circuitry to a single die you would end up quite close to the 420 sq mm die size. 


a 10 core Mali-G77 (a configuration we often see from Huawei) looks to just about edge out this generation’s top of the line mobile graphics hardware. A 12 core configuration, typically seen in Samsung’s Exynos, provides a big lead for Arm’s latest GPU. Mali-G77 should be able to give Qualcomm’s next-gen Adreno a good run for its money, while Samsung seem to switch to Radeon.  This infrastructure is the nice to build name and rep.




