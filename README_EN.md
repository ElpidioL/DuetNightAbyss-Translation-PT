# Duet Night Abyss - PT Translation

> **Versão em Português disponível:** [README.md](README.md)

## ⚠️ IMPORTANT WARNINGS

This is a fan-made translation that I created so my girlfriend could play the game. This is a `.pak` file editing project that translates the game to Portuguese (PT).

**⚠️ TESTING WARNING:** I did not fully test the game translated, so bugs may happen that I'm not aware of. If you are experiencing issues or crashes, you may try changing the language to see if the problem persists.

**IMPORTANT:** This translation **ONLY** translates the game and nothing else. Use at your own risk, as this is probably against the game's Terms of Service (TOS). I don't intend to update or improve this translation - I'm just waiting for an official translation.

---

## 📦 Installation

**⚠️ RECOMMENDATION:** It is recommended that the game is at the latest version before installing the translation. Make sure the game is updated through the official launcher.

1. **Locate the game folder:**

   - Navigate to the Duet Night Abyss installation folder
   - Follow the project structure to find the correct location

2. **Copy the .pak file:**

   - Copy the file `1.0.99.1_Script_WindowsNoEditor_710099_P.pak` to:

   ```
   Duet Night Abyss\DNA Game\EM\EMPatches\Paks\Global\Default\WindowsNoEditor\PC_OBT_Global_Pub\Patch\710012\
   ```

3. **Configure the executable:**

   - Go to: `Duet Night Abyss\DNA Game\EM\Binaries\Win64`
   - Find the file `EM-Win64-Shipping.exe`
   - Create a shortcut to the executable
   - Right-click the shortcut and go to "Properties"
   - In the "Target" field, add ` -fileopenlog` at the end
   - Example: `"C:\...\EM-Win64-Shipping.exe" -fileopenlog`
   - <img width="368" height="136" alt="image" src="https://github.com/user-attachments/assets/588fe477-f74f-4dea-a2cc-9ada43341207" />

4. **Run as Administrator:**

   - ⚠️ **IMPORTANT:** You must run the shortcut as Administrator, otherwise the game may fail to get the version (happened to me once)
   - Right-click the shortcut and select "Run as administrator"
   - Or configure the shortcut to always run as administrator: Right-click the shortcut → Properties → "Compatibility" tab → Check "Run this program as an administrator"

5. **⚠️ Note about game updates:**

   - If the game is updated, this translation may stop working
   - You may need to remove the translated `.pak` file for the game to work again

---

## 📁 Project Structure

The `pakFiles` folder contains everything that is inside the `.pak` file. If you want to better understand the structure or make modifications, you can explore this folder.

---

## 🔧 Improvements and Modifications

If someone wants to improve or modify the `.pak` file, feel free! Here's some useful information:

**To decompile Lua files:**

- Use: `java -jar unluac.jar base file > readable file`
- This allows you to read the binary code and edit the Lua files
- You can find `unluac.jar` online

**To recompile Lua files:**

- Use: `luac.exe -o <output file name>.luac <input file name>.lua`
- This converts the file back to binary
- I changed the final file extension from `.luac` to `.lua` to match the game structure
- You can find `luac.exe` online

**To repack the files:**

- You will need **UnrealPak 4.27.2** to repack the files
- You can find UnrealPak 4.27.2 online

---

## 🗑️ Uninstallation

To remove the translation and return to the original game:

1. Delete the file `1.0.99.1_Script_WindowsNoEditor_710099_P.pak` from the folder:
   ```
   Duet Night Abyss\DNA Game\EM\EMPatches\Paks\Global\Default\WindowsNoEditor\PC_OBT_Global_Pub\Patch\710012\
   ```

2. (Optional) Remove the `-fileopenlog` parameter from the executable shortcut if you don't need it anymore

---

## 🔍 Troubleshooting

**Game fails to get version:**
- Make sure you're running the shortcut as Administrator
- The game needs administrator permissions to update versions I guess

**Game won't start after installing the translation:**
- Remove the translated `.pak` file and try starting the game again
- Restore original files from backup if necessary
- Make sure you're running as Administrator

**Translation doesn't appear in the game:**
- Check if the `.pak` file is in the correct location
- Make sure you added the `-fileopenlog` parameter to the executable
- Make sure you're running as Administrator

**Game was updated and doesn't work anymore:**
- Remove the translated `.pak` file until a new version is available (if any)

**⚠️ Note about permissions:**
- The first time I opened `EM-Win64-Shipping.exe`, the game asked for some weird permissions. I don't know why, but I denied them and the game worked normally anyway.

---

## 🙏 Credits

This was my first mod/translation and I would like to give thanks to some people who helped me in the process:

- **[Waifus-Grace/DNA-Mods](https://github.com/Waifus-Grace/DNA-Mods)** - I learned a lot from their files
- **Wuthering Waves PTBR Discord | Gabriel Ikid** - I was able to ask some questions and get directions on my translation
- **voath5 on NexusMods** - Answered some of my questions

**⚠️ Warning:** I don't know these people well and you should trust them at your own risk.

---

## 📝 Final Notes

This is an amateur translation made with Google Translate, so it has many errors. If you find errors or want to contribute, feel free to fork and improve!

If you have questions, feel free to reach me on Discord: **imthemoon**

---

## 📄 License

This project is licensed under a custom license. See the [LICENSE](LICENSE) file for details.

**Note:** This license applies only to the translation work itself, not to any game assets, code, or content owned by the game developers.

