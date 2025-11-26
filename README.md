# sha1.salt.sha1.salt.sha1.pass
sha1($salt.sha1($salt.sha1($pass))) Pure Hashcat Kernel

Someone was having issues creating a kernel for this algorithm and asked for help. This is a quick pure -a 0 kernel to help them out. Developed on Hashcat v6.2.6.

Install:  
Add the module_95000.c file into the ./src/modules directory.  
Add the m95000_a0-pure.cl file into the ./OpenCL/ directory.  
Run make in the root hashcat directory  
Run rm -rf ./kernels in the root hashcat directory  

![image](https://i.ibb.co/JRqHMY93/Screenshot-2025-11-25-at-01-36-20.png)
