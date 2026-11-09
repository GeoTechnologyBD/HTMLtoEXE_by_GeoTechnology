================================================================================
                      HTML TO NATIVE EXE BUILDER
================================================================================

Product Name : HTML to Native EXE Builder
Version      : 1.0.0
Publisher    : GeoTechnology
Website      : https://geotech.site.je
Founder      : Abdullah Al Mahdi
Copyright    : (c) 2026 GeoTechnology. All rights reserved.

================================================================================
1. ABOUT THE SOFTWARE
================================================================================

HTML to Native EXE Builder is a powerful, lightweight software developed by 
GeoTechnology. It allows developers and creators to seamlessly convert their 
HTML5, CSS3, and JavaScript web projects into standalone, native Windows 
Executable (.exe) files.

Unlike other tools, this software uses Microsoft's WebView2 engine and the 
native C# compiler. This ensures that the final EXE runs natively and 
lightning-fast on Windows, without requiring Python, Node.js, or any other 
third-party frameworks to be installed on the end-user's computer.

================================================================================
2. KEY FEATURES
================================================================================

- Single File EXE Generation: Embed all your HTML, CSS, JS, and media assets 
  directly into one EXE file for easy distribution.

- External Folder Mode: Keep your web assets in an external "www" folder for 
  easy debugging and modification without recompiling.

- Custom Application Icon: Personalize your app with any .ico file. If no icon 
  is provided, the default Windows icon is used.

- Native WebView2 Rendering: Utilizes the same engine as Microsoft Edge for 
  high-performance, modern web rendering.

- No Python Required: The final EXE is a pure Windows application and does not 
  require Python to be installed on the target PC.

- Portable & Lightweight: Generates fast-starting, lightweight applications 
  with no hidden background processes.

================================================================================
3. SYSTEM REQUIREMENTS
================================================================================

For the Builder (Developer's PC):
---------------------------------
- OS: Windows 10 or Windows 11 (64-bit recommended)
- RAM: 2 GB or higher
- Storage: 50 MB of free space
- Framework: .NET Framework 4.8 (Pre-installed on Windows 10/11)
- Internet: Required only for the first build (to download WebView2 dependencies).

For the Final App (End-User's PC):
----------------------------------
- OS: Windows 10 (Version 1903 and above) or Windows 11
- Runtime: Microsoft Edge WebView2 Runtime (Pre-installed on modern Windows PCs).
- RAM: 2 GB or higher

================================================================================
4. HOW TO USE (STEP-BY-STEP GUIDE)
================================================================================

Step 1: Select HTML File or Folder
   - Click "File" if your project is just a single HTML file.
   - Click "Folder" if your project contains CSS, JS, Images, and other assets. 
   - *Important: Ensure your main file is named exactly "index.html" inside the folder.*

Step 2: Enter App Name
   - Provide a name for your application (e.g., SpaceBlaster). 
   - This name will be used for the .exe file and the Window Title.

Step 3: Select App Icon (Optional)
   - Click "Browse" and select a valid .ico file to give your app a custom identity.
   - If left blank, the default system icon will be used.

Step 4: Choose Output Folder
   - Select the directory where you want to save the final .exe file.
   - If left blank, the EXE will be created in the same folder as your source files.

Step 5: Embed Mode (Checkbox)
   - Checked (Default): All HTML, CSS, JS, and media files will be hidden 
     inside the EXE. The user will receive a clean, single .exe file.
   - Unchecked: Creates an EXE alongside a separate "www" folder. 
     Use this mode if you want to modify HTML files later without rebuilding.

Step 6: Build EXE
   - Click the "Build EXE" button.
   - Wait for the log to display "Success! EXE created at...". 
   - Once finished, your native Windows app is ready to run!

================================================================================
5. TROUBLESHOOTING & FAQ
================================================================================

Q: The app crashes or shows an error on startup?
A: The target PC might be missing the "WebView2 Runtime". It is pre-installed 
   on Windows 10 and 11. If missing, download it from Microsoft's official website:
   https://developer.microsoft.com/en-us/microsoft-edge/webview2/

Q: The window opens but shows a blank screen?
A: Ensure your main HTML file is named exactly "index.html" and all file paths 
   (for images/CSS) are relative to the folder.

Q: My antivirus flags the generated EXE as a virus.
A: This is a common "False Positive" for self-extracting executables (because it 
   unpacks files during runtime). Since the EXE is built locally by you, it is 
   100% safe. You may need to add it to your antivirus exclusion list.

Q: Can I edit the HTML files after making the EXE?
A: If you used the "Single EXE" mode, you cannot easily edit the files without 
   rebuilding. If you want to edit files later, uncheck the "Embed" box during 
   build to keep the files in an external "www" folder.

================================================================================
6. CONTACT & SUPPORT
================================================================================

For more information, updates, or support, please visit our website:
Website: https://geotech.site.je

Thank you for choosing GeoTechnology!
Building the future, one app at a time.

================================================================================
