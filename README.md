# Duet Night Abyss - Tradução PT / PT Translation

## ⚠️ AVISOS IMPORTANTES / IMPORTANT WARNINGS

**PT:**
Esta é uma tradução feita por fã que criei para que minha namorada pudesse jogar o jogo. Esta é uma modificação de arquivos `.pak` que traduz o jogo para Português (PT).

**IMPORTANTE:** Esta tradução **APENAS** traduz o jogo e nada mais. Use por sua própria conta e risco, pois isso provavelmente viola os Termos de Serviço (TOS) do jogo. Não tenho intenção de atualizar ou melhorar esta tradução - estou apenas aguardando uma tradução oficial.

**EN:**
This is a fan-made translation that I created so my girlfriend could play the game. This is a `.pak` file editing project that translates the game to Portuguese (PT).

**IMPORTANT:** This translation **ONLY** translates the game and nothing else. Use at your own risk, as this is probably against the game's Terms of Service (TOS). I don't intend to update or improve this translation - I'm just waiting for an official translation.

---

## 📦 Instalação / Installation

### PT:

**⚠️ RECOMENDAÇÃO:** É recomendado que o jogo esteja na versão mais recente antes de instalar a tradução. Certifique-se de que o jogo está atualizado através do launcher oficial.

1. **Localize a pasta do jogo:**

   - Navegue até a pasta de instalação do Duet Night Abyss
   - Siga a estrutura do projeto para encontrar o local correto
2. **Copie o arquivo .pak:**

   - Copie o arquivo `1.0.99.1_Script_WindowsNoEditor_710099_P.pak` para:

   ```
   Duet Night Abyss\DNA Game\EM\EMPatches\Paks\Global\Default\WindowsNoEditor\PC_OBT_Global_Pub\Patch\710012\
   ```

4. **Configure o executável:**

   - Vá até: `Duet Night Abyss\DNA Game\EM\Binaries\Win64`
   - Encontre o arquivo `EM-Win64-Shipping.exe`
   - Crie um atalho (shortcut) para o executável
   - Clique com o botão direito no atalho e vá em "Propriedades" (Properties)
   - No campo "Destino" (Target), adicione ` -fileopenlog` no final
   - Exemplo: `"C:\...\EM-Win64-Shipping.exe" -fileopenlog`
   - <img width="368" height="136" alt="image" src="https://github.com/user-attachments/assets/91ab0368-f392-493e-b342-8a751905082e" />


5. **Execute como Administrador:**

   - ⚠️ **IMPORTANTE:** Você deve executar o atalho como Administrador, caso contrário o jogo poderá falhar ao obter a versão (aconteceu comigo uma vez)
   - Clique com o botão direito no atalho e selecione "Executar como administrador" (Run as administrator)
   - Ou configure o atalho para sempre executar como administrador: Clique com o botão direito no atalho → Propriedades → Aba "Compatibilidade" → Marque "Executar este programa como administrador"

6. **⚠️ Nota sobre atualizações do jogo:**

   - Se o jogo for atualizado, esta tradução pode parar de funcionar
   - Você pode precisar remover o arquivo `.pak` traduzido para o jogo funcionar novamente

### EN:

**⚠️ RECOMMENDATION:** It is recommended that the game is at the latest version before installing the translation. Make sure the game is updated through the official launcher.

1. **Locate the game folder:**

   - Navigate to the Duet Night Abyss installation folder
   - Follow the project structure to find the correct location

3. **Copy the .pak file:**

   - Copy the file `1.0.99.1_Script_WindowsNoEditor_710099_P.pak` to:

   ```
   Duet Night Abyss\DNA Game\EM\EMPatches\Paks\Global\Default\WindowsNoEditor\PC_OBT_Global_Pub\Patch\710012\
   ```

4. **Configure the executable:**

   - Go to: `Duet Night Abyss\DNA Game\EM\Binaries\Win64`
   - Find the file `EM-Win64-Shipping.exe`
   - Create a shortcut to the executable
   - Right-click the shortcut and go to "Properties"
   - In the "Target" field, add ` -fileopenlog` at the end
   - Example: `"C:\...\EM-Win64-Shipping.exe" -fileopenlog`
   - <img width="368" height="136" alt="image" src="https://github.com/user-attachments/assets/588fe477-f74f-4dea-a2cc-9ada43341207" />


5. **Run as Administrator:**

   - ⚠️ **IMPORTANT:** You must run the shortcut as Administrator, otherwise the game may fail to get the version (happened to me once)
   - Right-click the shortcut and select "Run as administrator"
   - Or configure the shortcut to always run as administrator: Right-click the shortcut → Properties → "Compatibility" tab → Check "Run this program as an administrator"

6. **⚠️ Note about game updates:**

   - If the game is updated, this translation may stop working
   - You may need to remove the translated `.pak` file for the game to work again

---

## 📁 Estrutura do Projeto / Project Structure

### PT:

A pasta `pakFiles` contém tudo que está dentro do arquivo `.pak`. Se você quiser entender melhor a estrutura ou fazer modificações, pode explorar essa pasta.

### EN:

The `pakFiles` folder contains everything that is inside the `.pak` file. If you want to better understand the structure or make modifications, you can explore this folder.

---

## 🔧 Melhorias e Modificações / Improvements and Modifications

### PT:

Se alguém quiser melhorar ou modificar o arquivo `.pak`, fique à vontade! Aqui estão algumas informações úteis:

**Para descompilar arquivos Lua:**

- Use: `java -jar unluac.jar base file > readable file`
- Isso permite ler o código binário e editar os arquivos Lua
- Você pode encontrar o `unluac.jar` online

**Para recompilar arquivos Lua:**

- Use: `luac.exe -o <output file name>.luac <input file name>.lua`
- Isso converte o arquivo de volta para binário
- Eu mudei a extensão final de `.luac` para `.lua` para corresponder à estrutura do jogo
- Você pode encontrar o `luac.exe` online

**Para reempacotar os arquivos:**

- Você precisará do **UnrealPak 4.27.2** para reempacotar os arquivos
- Você pode encontrar o UnrealPak 4.27.2 online

### EN:

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

## 🗑️ Desinstalação / Uninstallation

### PT:

Para remover a tradução e voltar ao jogo original:

1. Delete o arquivo `1.0.99.1_Script_WindowsNoEditor_710099_P.pak` da pasta:
   ```
   Duet Night Abyss\DNA Game\EM\EMPatches\Paks\Global\Default\WindowsNoEditor\PC_OBT_Global_Pub\Patch\710012\
   ```

2. (Opcional) Remova o parâmetro `-fileopenlog` do atalho do executável se não precisar mais dele

### EN:

To remove the translation and return to the original game:

1. Delete the file `1.0.99.1_Script_WindowsNoEditor_710099_P.pak` from the folder:
   ```
   Duet Night Abyss\DNA Game\EM\EMPatches\Paks\Global\Default\WindowsNoEditor\PC_OBT_Global_Pub\Patch\710012\
   ```

2. (Optional) Remove the `-fileopenlog` parameter from the executable shortcut if you don't need it anymore

---

## 🔍 Troubleshooting / Solução de Problemas

### PT:

**O jogo falha ao obter a versão:**
- Certifique-se de que está executando o atalho como Administrador
- O jogo precisa de permissões de administrador para atualizar a versão

**O jogo não inicia após instalar a tradução:**
- Remova o arquivo `.pak` traduzido e tente iniciar o jogo novamente pelo launcher
- Restaure os arquivos originais do backup se necessário
- Certifique-se de que está executando como Administrador
- Tente novamente

**A tradução não aparece no jogo:**
- Verifique se o arquivo `.pak` está no local correto
- Certifique-se de que adicionou o parâmetro `-fileopenlog` ao executável
- Certifique-se de que está executando como Administrador

**O jogo foi atualizado e não funciona mais:**
- Remova o arquivo `.pak` traduzido até que uma nova versão seja disponibilizada (se houver)

**⚠️ Nota sobre permissões:**
- Na primeira vez que abri o `EM-Win64-Shipping.exe`, o jogo pediu algumas permissões estranhas. Eu não sei o porquê, mas neguei essas permissões e o jogo funcionou normalmente mesmo assim.

### EN:

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

## 🙏 Créditos / Credits

### PT:

Esta foi minha primeira mod/tradução e gostaria de agradecer algumas pessoas que me ajudaram no processo:

- **[Waifus-Grace/DNA-Mods](https://github.com/Waifus-Grace/DNA-Mods)** - Aprendi muito com os arquivos deles
- **Discord Wuthering Waves PTBR | Gabriel Ikid** - Consegui fazer algumas perguntas e obter direcionamentos sobre minha tradução
- **voath5 no NexusMods** - Respondeu algumas das minhas perguntas

**⚠️ Aviso:** Não conheço bem essas pessoas e você deve confiar nelas por sua própria conta e risco.

### EN:

This was my first mod/translation and I would like to give thanks to some people who helped me in the process:

- **[Waifus-Grace/DNA-Mods](https://github.com/Waifus-Grace/DNA-Mods)** - I learned a lot from their files
- **Wuthering Waves PTBR Discord | Gabriel Ikid** - I was able to ask some questions and get directions on my translation
- **voath5 on NexusMods** - Answered some of my questions

**⚠️ Warning:** I don't know these people well and you should trust them at your own risk.

---

## 📝 Notas Finais / Final Notes

### PT:

Esta é uma tradução amadora feita com Google Translate, então possui muitos erros. Se encontrar erros ou quiser contribuir, sinta-se à vontade para fazer um fork e melhorar!

Se tiver dúvidas, sinta-se à vontade para me contatar no Discord: **imthemoon**

### EN:

This is an amateur translation made with Google Translate, so it has many errors. If you find errors or want to contribute, feel free to fork and improve!

If you have questions, feel free to reach me on Discord: **imthemoon**
