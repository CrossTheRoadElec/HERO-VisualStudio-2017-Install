# What is this?
This Visual Studio 15 Extension is for using HERO with VS2017.

After 2017 Visual Studio testing has been completed, the VS2017 Plugin will be integrated into the CTRE Tool Suite installer available here... http://www.ctr-electronics.com/control-system/hro.html#product_tabs_technical_resources

... but in the meantime, the VSIX and instructions can be found in this repository.

# How to get HERO development working on Visual Studio 2017
Download NetmfVS15.vsix from this repository (press the Download button)... <br />
https://github.com/CrossTheRoadElec/HERO-VisualStudio-2017-Install/blob/master/NetmfVS15.vsix

Double click on the VSIX. Ensure Visual Studio 2017 is closed before doing this.  Otherwise VSIX Installer will prompt you to close VS. <br />
![](https://github.com/CrossTheRoadElec/HERO-VisualStudio-2017-Install/blob/gh-pages/image1.png)

VSIX Installer will begin with this prompt. <br />
![](https://github.com/CrossTheRoadElec/HERO-VisualStudio-2017-Install/blob/gh-pages/image2.png)

Ensure Visual Studio 2017 is selected and press Install. <br />
![](https://github.com/CrossTheRoadElec/HERO-VisualStudio-2017-Install/blob/gh-pages/image3.png)

Installer will take approximately 20 seconds before completing with the following prompt. <br />
![](https://github.com/CrossTheRoadElec/HERO-VisualStudio-2017-Install/blob/gh-pages/image5.png)

At this point open Visual Studio 2017 and confirm MicroFramework appears under New Project menu.  Use the Console Application to create C# projects for HERO. <br />
![](https://github.com/CrossTheRoadElec/HERO-VisualStudio-2017-Install/blob/gh-pages/image66.png)

Add the CTRE Reference (CTRE.dll) to use CTRE features (HERO, Talon SRX, PCM, Display Module, WiFi Module, etc.) <br />
![](https://github.com/CrossTheRoadElec/HERO-VisualStudio-2017-Install/blob/gh-pages/image7.png)
