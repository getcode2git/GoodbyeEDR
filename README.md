# GoodbayEDR

█████████████████████████████████████████████████████████████████████
███────██────██────██────███────███────██──█──████───██────███────███
███─█████─██─██─██─██─██──██─██──██─██─███───█████─████─██──██─██─███
███─█──██─██─██─██─██─██──██────███────████─██████───██─██──██────███
███─██─██─██─██─██─██─██──██─██──██─██─████─██████─████─██──██─█─████
███────██────██────██────███────███─██─████─██████───██────███─█─████
███████████████████████████████████████████─█████████████████████████

Disable notifications of AV & EDR from events occurring in the system.

The project has the following features:
1. List all callbacks & minifilters.
2. Removing callback functions:
    - create/exit of processes;
    - create/exit of threads;
2. Hook callback functions with filtering by process name:
    - create/exit of processes;
    - create/exit of threads;
4. Hook file system minifilters with filtering by process name.
5. Abuse AV & EDR after remove or hook.
    
The assembly is a compilation of two great projects:
1. https://github.com/uf0o/windows-ps-callbacks-experiments (Fork deleted repository https://github.com/fdiskyou/windows-ps-callbacks-experiments).
2. https://github.com/SHA-MRIZ/FsMinfilterHooking
    
Additionally, added the ability to hook callback functions with filtering by the name of the process: create/exit of processes and threads & hook of file system minifilters.

Articles covering these issues in detail:
1. http://deniable.org/windows/windows-callbacks ---> https://web.archive.org/web/20200326040826/http://deniable.org/windows/windows-callbacks
2. https://synzack.github.io/Blinding-EDR-On-Windows/
3. https://aviadshamriz.medium.com/part-1-fs-minifilter-hooking-7e743b042a9d     
