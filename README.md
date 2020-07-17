<img src="https://www.linaro.org/assets/images/projects/yocto-project.png" width="200" align="right">
<br>

### Supported Hardware


|                       SMARC Module                       | Description                                                  |
| :------------------------------------------------------: | :----------------------------------------------------------- |
| <img src="https://cdn.adlinktech.com/webupd/products/images/1752/LEC-iMX8M-F_(1)_web.jpg" width="200"/> | **LEC-iMX8M** ([More details](https://www.adlinktech.com/Products/Computer_on_Modules/SMARC/LEC-iMX8M?lang=en))  <br />     SMARC Short Size Module with NXP i.MX 8M<br /> |

<br />


**SD Card image for the quick evaluation**

* Support 4G Memory with Wayland Weston Desktop (carrier board: LEC-BASE 2.0): [download link](https://hq0epm0west0us0storage.blob.core.windows.net/public/SMARC/LEC-iMX8M/core-image-weston-lec-imx8m_4G.zip)
* Support 2G Memory with Wayland Weston Desktop (carrier board: LEC-BASE 2.0): [download link](https://hq0epm0west0us0storage.blob.core.windows.net/public/SMARC/LEC-iMX8M/core-image-weston-lec-imx8m_2G.zip)
* Support 1G Memory with Wayland Weston Desktop (carrier board: LEC-BASE 2.0): [download link](https://hq0epm0west0us0storage.blob.core.windows.net/public/SMARC/LEC-iMX8M/core-image-weston-lec-imx8m_1G.zip)


<br>

**Supported features & interfaces**

* Linux Kernel version: 5.4
* UART ports: Com 0, Com1, COM2 on LEC BASE 2.0
* 2x USB 2.0 + 2x USB 3.0
* HDMI output 
* Audio & speaker
* Camera 2 Lane support: OV5640 Camera module
* MIPI DSI support with the resolution up to 1920x1200 (need Hardware BOM change): using AUO B101UAN0 DSI panel  
* LVDS panel support with 1920x1080 Dual 24bit: using AUO G133HAN01
* eMMC/SD card support
* PCIe Gen2 support




<br />

**How to build Yocto Image**

* see [documentation](https://github.com/ADLINK/meta-adlink-nxp/wiki/01.-Build-Yocto-Image) for more details.

**How to flash image to your storage**

* [Boot from SD card](https://github.com/ADLINK/meta-adlink-nxp/wiki/03.-How-to-install-Yocto-Image-into-SD-Card)

 

<br>
 

Please feel free to send us (email: ryanzj.huang@adlinktech.com) patches for this layer or report any bugs found in this layer. 
<br> For hardware support, please contact your local representative.




Best Regards
Ryan
#8906

