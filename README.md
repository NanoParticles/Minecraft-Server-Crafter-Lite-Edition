# Minecraft Server Crafter - Lite Edition
Minecraft Server Crafter - Lite Edition is a Lightweight GUI Console that allows the user to create, configure, and manage a Minecraft Server with the given server jar file.

# Credits
Yot360 - Huge thanks for helping me with the Console Shell interaction with input and output between the Minecraft Server and Minecraft Server Crafter. (Github page: https://github.com/Yot360)

# What is Minecraft Server Crafter?

Minecraft Server Crafter is a modernized GUI Server Manager with a clean look for Minecraft Servers, featuring a direct console that shows the input/output of the Minecraft Server, configuring the server.properties file directly, manages whitelisting, and player bans. Minecraft Server Crafter doesn't collect any of your personal data. Its not the "server crafting" way.

# Wait, but my Antivirus sees it as a virus!

That can be scary. Believe me, Minecraft Server Crafter is my baby. Like any parent, I want to take care of my baby. Minecraft Server Crafter has such a low score it should be no problem. Lower the score the better. Its highly likely it came back as a falsely positive. First take a deep breath. Now that we have taken that deep breath, consider the following:

- Have I updated my virus definitions?

Updating the virus definitions is a potitiental elaphant in the room. Try updating the definitions first then try it again.

- What can I do within my antivirus software to effectively communicate to my security vendor?

Most antivirus software has ways to report to the security vendor directly within their own application. If your antivirus software doesn't have a way to contact them directly, heres a repository with their information: https://github.com/yaronelh/False-Positive-Center

- What antivirus software is affected?

If you are using any of the following antivirus software, Minecraft Server Crafter will be blocked by the security vendor:
- Bkav Pro
- SecureAge
- Skyhigh(SWG)
- Trellix(FireEye)

You will need to configure your antivirus software to tell it that Minecraft Server Crafter isn't what it is claiming to be

For statistical data on the matter(regarding the virus score, and other information), refer to this data: https://www.virustotal.com/gui/file/f8ea222edf92222be6a5b6943fba994271bdfd221f4a14c3b7715ff9d295c3bb/detection

# Requirements
An active internet connection and server directory

# Features

Console Shell - The core component of Minecraft Server Crafter. This shows the input/output of the Minecraft Server, as well as what Minecraft Server Crafter outputs

Server Properties File detection - Any pre-existing server properties file that is detected by Minecraft Server Crafter in the given server directory is automatically imported to Minecraft Server Crafter

Sqlite 3 Database - Minecraft Server Crafter also searches for the JSON files for whitelisting, and bans to add them to their respective tables. All changes is configured in Minecraft Server Crafter

Networking - This program automatically detects the Local IP address of the machine the program is on and sets it as the IP address by default for the Server IP, which can be changed within the program under Server Properties File > Networking.

Version Updater - Detects realtime version updates at boot for the given server types that Minecraft Server Crafter. When this is running, only official resources thats provided by the creators(when applicable) of the specific server type, including Minecraft Server Crafter - Lite Edition

Curseforge API Compatible - Minecraft Server Crafter - Lite Edition has the compatiblity to use Curseforges API. This is primarily used ONLY for server types that doesn't have an API for version updates. The usage of Curseforge API in Minecraft Server Crafter - Lite Edition is subjected to change(I.E. usage of modpacks)

Sandbox-like Server Instances - Minecraft Server Crafter - Lite Edition generates the nessisary files to its own folder similarity to(but not exact) to the Curseforge's Launcher. During this file generation, officially public resources/binaries(including server jars) is unmodified(as-is condition) by Minecraft Server Crafter - Lite Edition but only downloads into its instance folder. For custom instances that Minecraft Server Crafter - Lite Edition does not generate resources/binaries is provided by the user. For licensing, go into Minecraft Server Crafter > View Instances > Licensing. This will show the license(s) for server types that Minecraft Server Crafter - Lite Edition only generates files for and other components that Minecraft Server Crafter - Lite Edition uses and acknowledges its creators.
