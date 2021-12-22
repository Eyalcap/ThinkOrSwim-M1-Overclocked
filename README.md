<p><img width="150" height="350" align='right' src="/assets/logo.png"><a aligh="right">

  ```
         _____ _     _       _     ___       ____          _           
        |_   _| |__ (_)_ __ | | __/ _ \ _ __/ ___|_      _(_)_ __ ___  
          | | | '_ \| | '_ \| |/ / | | | '__\___ \ \ /\ / / | '_ ` _ \ 
          | | | | | | | | | |   <| |_| | |   ___) \ V  V /| | | | | | |
          |_| |_| |_|_|_| |_|_|\_\\___/|_|  |____/ \_/\_/ |_|_| |_| |_|
         ____  _ _ _                   _____    _ _ _   _              
        / ___|(_) (_) ___ ___  _ __   | ____|__| (_) |_(_) ___  _ __   
        \___ \| | | |/ __/ _ \| '_ \  |  _| / _` | | __| |/ _ \| '_ \  
         ___) | | | | (_| (_) | | | | | |__| (_| | | |_| | (_) | | | | 
        |____/|_|_|_|\___\___/|_| |_| |_____\__,_|_|\__|_|\___/|_| |_| 
                                                                       
                     I just wanted it to be easy for yall       
```
  
  </a></p>  

Any errors open an <a href="https://github.com/CodeInFilth/ThinkOrSwim-Silicon-12.1/issues">issue</a>

<p align="center">
  <a target="_blank" rel="noopener noreferrer" href="https://www.patreon.com/filthy_trades">
     <img align="center" src="https://img.shields.io/badge/Version-1.2-000">
  </a>
  <a target="_blank" rel="noopener noreferrer" href="https://www.patreon.com/filthy_trades">
    <img align="center" src="https://img.shields.io/badge/☕️%20Buy%20me%20Coffee-000">
  </a>
  <a target="_blank" rel="noopener noreferrer" href="https://github.com/CodeInFilth/ThinkOrSwim-Silicon-12.1/issues">
    <img align="center" src="https://img.shields.io/badge/🤕%20Support-8B0000">
  </a>
  <a target="_blank" rel="noopener noreferrer" href="https://www.patreon.com/filthy_trades">
     <img align="center" src="https://img.shields.io/badge/🖥 Mac OS-12.1+-1E90FF">
  </a>
</p>

# README
  


#### Dependencies:
1. <a target="_blank" rel="noopener noreferrer" href="https://cdn.azul.com/zulu/bin/zulu11.52.13-ca-jdk11.0.13-macosx_aarch64.dmg">OpenJDK 11</a> for ARM64[^1] 
   - Navigate to the dependencies folder and open the .app file named `Install_OpenJDK11.app`[^3]
  
  
#### Instructions (for other platforms):
1. Be sure you have any Dependencies installed. 
2. Decompress the zip.
3. Open the folder named `Dist` and drag the ThinkOrSwim-Silicon.app to your Applications folder.
4. Open the ThinkOrSwim-Silicon.app [^2]
5. Enjoy

<p>PS: If you would like to compile this yourself open the `opn-src` folder. To run the files for yourself navigate to them in Terminal `cd ThinkOrSwim-Silicon-12.1/opn-src` type `sudo java -jar launcher.jar` in your Terminal window</p>

    <p>Note: Dont forget to ensure the you run it as sudo, please remeber this is an unoffical client intending to run thinkorswim an ARM64 Mac, Linux, Solaris or other Unix variants, manual updates and tuning may be required, has no official support for configuring these operating systems but I will do my best to make sure its turnkey for anyone.</p>



<!-- 
<details>
  <summary><b>📈&nbsp;Stock Market Tools</b></summary>
  <br/>
  <p><img width="250" align='right' src="https://raw.githubusercontent.com/CodeInFilth/CodeInFilth/root/inc/png/logo_Aurora.png"><a aligh="right">Trading is my primary income and so i will be updating this with useful tools and assets I use daily.</a></p>  
</details>



<details>
  <summary><b>🖥&nbsp;Mac Tools</b></summary>
  <br/>
  <p></p>  
</details>
 -->

<p align="center">ThinkOrSwim build for the new Mac M1 Silicon 12.1 Monterey</br>Last Saved: Tuesday, December 21st, 06:00am PST</p>	

[^1]: Ensure that Java 11 <a target="_blank" rel="noopener noreferrer" href="https://cdn.azul.com/zulu/bin/zulu11.52.13-ca-jdk11.0.13-macosx_aarch64.dmg">(Azul’s Zulu OpenJDK 11 is preferable)</a> is installed and accessible from your command line <br/> executing `$ java -version` should output `openjdk version "11.0.13" 2021-10-19 LTS`
[^2]: It might take a while to load on your first launch, when the login screen appears click on the cog in the bottom left of the box and change your maximum RAM to suit your device.
[^3]: This pulls a new copy directly from OpenJDK working on 12.1+ (no other testing done)