# hos-mips

This is a simple mips architecture OS in windows platform based on Tsinghua ucore OS. 
We run the OS on Nexys4-DDR Board using vivado tcl scripts and OpenOCD.
The compiler is mips-sde-elf cross compiler(version 2012.03). The vivado bin path should be added into PATH.
After you set up the environment, you can just make and run the run.bat(uncomment the fifth line). The output will show in PUTTY.exe.(You may need to change the COM number in run.bat, this can be found by using PUTTY.EXE)
The .vscode directory gives an example about how to use gdb to debug the OS in Visual Studio Code with the extension Native Debug. You can just run the run.bat and set a breakpoint. Then press F5 to debug in vscode.