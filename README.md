# DynamicCacheFS
An intelligent Linux FS wrapper that treats your disk storage a bit like RAM. It holds on to temporary files—like shader and other application caches—to prevent time-consuming re-compilation down the line. This put unused disk space to work, and dynamically yields it when needed for permanent files.
