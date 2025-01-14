# KernelSU_Build_Test  

## Important Things

### KernelSU Source
- [Rsuntk KernelSU](https://github.com/rsuntk/KernelSU)
- [KernelSU Next](https://github.com/rifsxd/KernelSU-Next)

## Installation Guide  

**Anyway, read the [KernelSU official website](https://kernelsu.org/guide/installation.html) first!!**  

1. Download AnyKernel3 from github action  

**LineageOS 21**:   
- [OPlus SM8250](https://github.com/OodavidsinoO/OnePlus-KernelSU-Builds/actions/workflows/LineageOS-OPlus-SM8250-Kernel.yml): ```OnePlus 8 | OnePlus 8 Pro | OnePlus 8T | OnePlus 9R```  
- [OPlus SM8550](https://github.com/OodavidsinoO/OnePlus-KernelSU-Builds/actions/workflows/LineageOS-Salami-Kernel.yml): ```OnePlus 11 (salami)```  

2. Using ```adb sideload``` to flash AnyKernel3  
Reboot to recovery mode and use ```adb sideload AK3-xxx.zip``` to flash AnyKernel3.
> Tip: If your custom recovery does not support flashing AnyKernel3, please try to flash TWRP or OrangeFox first.
>> OrangeFox: [OnePlus 8 series and 9R](https://xdaforums.com/t/recovery-unofficial-orangefox-recovery-project-oneplus-8-8t-8-pro-9r-22-may-2024.4515657) | [OnePlus 9/9 Pro](https://xdaforums.com/t/recovery-unofficial-a12-a14-orangefox-recovery-project-oneplus-9-9-pro-28-05-2024.4601751)  

3. Using Kernel Flasher to OTA  
After installing the OTA and before rebooting, use [Kernel Flasher](https://github.com/tiann/KernelFlasher) to flash AnyKernel3 into the other slot.
> Tip: If there is not a local update in ROM, please follow step 2 to flash AnyKernel3 after update.

## Original Kernel Source  

LineageOS 22.1:  
[OPlus SM8250](https://github.com/LineageOS/android_kernel_oneplus_sm8250) | [OPlus SM8550](https://github.com/LineageOS/android_kernel_oneplus_sm8550)  
