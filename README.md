# FastGPUP
A WIP GUI app to make GPU-P way easier!
Based on : https://github.com/jamesstringerparsec/Easy-GPU-PV
![image](https://github.com/user-attachments/assets/9b732ced-8304-4dc3-afa2-95c409702cfa)
# Usage
Requires Visual Studio Code (exe can be provided but dont trust anything from the internet so use the code)

    - Download all files and extract the zip
    - Open visual Studio Code as Administrator (right click, run as administrator)
    - File -> open folder and open the extracted folder
    - Trust the files on the popup (as youve read through the code on github and happy its safe of course)
    - Install c# dev kit and .net 10, it should popup when you open the folder asking you to do this

    - In the terminal enter
        dotnet build FastGPU-P/FastGPU-P.csproj
      and press enter
    - In the terminal enter
        dotnet run --project FastGPU-P/FastGPU-P.csproj
      and press enter

    The GUI will now load

- Choose VM,
- Choose GPU,
- Slide the percentage you want to allocate of it and then press Add. 
- Click install/update driver. It will mount the VM's VHD, copy the driver files, and unmount the VHD.

# Troubleshooting
If you get an error related to Execution Policy you should execute:
"Set-ExecutionPolicy -ExecutionPolicy Unrestricted" on PowerShell
