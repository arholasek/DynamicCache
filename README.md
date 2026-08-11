# DynamicCache
An intelligent eBPF tool that treats your disk storage a bit like RAM. It has your system hold on to temporary files—like shader and other application caches—to prevent time-consuming re-compilation down the line. It puts unused disk space to work, and dynamically yields it when needed for permanent files.


I am working on this, I promise!
I will push my barebones pre-release proof of concept soon


Dependencies:
- Linux kernel >= 4.4 w/ eBFP enabled (ideally full eBPF Support, but partial may work in some cases)
- System-level Python >= 3.12 w/ a few py modules (TBD... likely numpy)
- Probably some other crap, idk... still figuring all this out
