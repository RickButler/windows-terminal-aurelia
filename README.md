# Aurelia Retro - a Windows Terminal theme

![alt text][logo]

[logo]: https://raw.githubusercontent.com/mobilemancer/windows-terminal-aurelia/master/demo.jpg "Aurelia theme for Windows Terminal"

## Installation

1. Open your Windows Terminal "LocalState" folder

   ```
   %LOCALAPPDATA%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState
   ```

2. Copy profiles.json (or rename it) to save it, in case you want to revert the changes.

3. Copy everything in from the profile folder in this repository into to your LocalState folder

## Fonts

The theme is using Cascadia Code.

Information on how to download Cascadia Code can be found here: <https://github.com/microsoft/cascadia-code>

 If you like to use another font, just change the fontFace property in profiles.json.
 
 ## Image to large!
 
 There's a smaller image to use if the default one feels too large. Just edit the background image property and substitute "au-os-L.png" for "au-os-M.png".

 ## Matching Oh my Posh theme

 I made a matching theme for Oh my Posh 3. It looks like the following:

![alt text][img1]

[img1]: https://raw.githubusercontent.com/mobilemancer/windows-terminal-aurelia/master/purple-man-retro.jpg "With Retro Terminal Effect"

![alt text][img2]

[img2]: https://raw.githubusercontent.com/mobilemancer/windows-terminal-aurelia/master/purple-man.jpg "Without Retro Terminal Effect"

To use it, install Oh my Posh 3, then copy the theme file, purple-man.json from the posh-theme folder, then edit your PowerShell profile and set the theme there.