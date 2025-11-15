# Duet Night Abyss - Tradução PT

> **English version available:** [README_EN.md](README_EN.md)

## ⚠️ AVISOS IMPORTANTES

Esta é uma tradução feita por fã que criei para que minha namorada pudesse jogar o jogo. Esta é uma modificação de arquivos `.pak` que traduz o jogo para Português (PT).

**⚠️ AVISO DE TESTES:** Eu não testei o jogo completamente traduzido, então podem ocorrer bugs dos quais não estou ciente. Se você estiver enfrentando problemas ou crashes, tente mudar o idioma do jogo para ver se o problema persiste.

**IMPORTANTE:** Esta tradução **APENAS** traduz o jogo e nada mais. Use por sua própria conta e risco, pois isso provavelmente viola os Termos de Serviço (TOS) do jogo. Não tenho intenção de atualizar ou melhorar esta tradução - estou apenas aguardando uma tradução oficial.

---

## 📦 Instalação

**⚠️ RECOMENDAÇÃO:** É recomendado que o jogo esteja na versão mais recente antes de instalar a tradução. Certifique-se de que o jogo está atualizado através do launcher oficial.

1. **Localize a pasta do jogo:**

   - Navegue até a pasta de instalação do Duet Night Abyss
   - Siga a estrutura do projeto para encontrar o local correto

2. **Copie o arquivo .pak:**

   - Copie o arquivo `1.0.99.1_Script_WindowsNoEditor_710099_P.pak` para:

   ```
   Duet Night Abyss\DNA Game\EM\EMPatches\Paks\Global\Default\WindowsNoEditor\PC_OBT_Global_Pub\Patch\710012\
   ```

3. **Configure o executável:**

   - Vá até: `Duet Night Abyss\DNA Game\EM\Binaries\Win64`
   - Encontre o arquivo `EM-Win64-Shipping.exe`
   - Crie um atalho (shortcut) para o executável
   - Clique com o botão direito no atalho e vá em "Propriedades" (Properties)
   - No campo "Destino" (Target), adicione ` -fileopenlog` no final
   - Exemplo: `"C:\...\EM-Win64-Shipping.exe" -fileopenlog`
   - <img width="368" height="136" alt="image" src="https://github.com/user-attachments/assets/91ab0368-f392-493e-b342-8a751905082e" />

4. **Execute como Administrador:**

   - ⚠️ **IMPORTANTE:** Você deve executar o atalho como Administrador, caso contrário o jogo poderá falhar ao obter a versão (aconteceu comigo uma vez)
   - Clique com o botão direito no atalho e selecione "Executar como administrador" (Run as administrator)
   - Ou configure o atalho para sempre executar como administrador: Clique com o botão direito no atalho → Propriedades → Aba "Compatibilidade" → Marque "Executar este programa como administrador"

5. **⚠️ Nota sobre atualizações do jogo:**

   - Se o jogo for atualizado, esta tradução pode parar de funcionar
   - Você pode precisar remover o arquivo `.pak` traduzido para o jogo funcionar novamente

---

## 📁 Estrutura do Projeto

A pasta `pakFiles` contém tudo que está dentro do arquivo `.pak`. Se você quiser entender melhor a estrutura ou fazer modificações, pode explorar essa pasta.

---

## 🔧 Melhorias e Modificações

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

---

## 🗑️ Desinstalação

Para remover a tradução e voltar ao jogo original:

1. Delete o arquivo `1.0.99.1_Script_WindowsNoEditor_710099_P.pak` da pasta:
   ```
   Duet Night Abyss\DNA Game\EM\EMPatches\Paks\Global\Default\WindowsNoEditor\PC_OBT_Global_Pub\Patch\710012\
   ```

2. (Opcional) Remova o parâmetro `-fileopenlog` do atalho do executável se não precisar mais dele

---

## 🔍 Solução de Problemas

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

---

## 🙏 Créditos

Esta foi minha primeira mod/tradução e gostaria de agradecer algumas pessoas que me ajudaram no processo:

- **[Waifus-Grace/DNA-Mods](https://github.com/Waifus-Grace/DNA-Mods)** - Aprendi muito com os arquivos deles
- **Discord Wuthering Waves PTBR | Gabriel Ikid** - Consegui fazer algumas perguntas e obter direcionamentos sobre minha tradução
- **voath5 no NexusMods** - Respondeu algumas das minhas perguntas

**⚠️ Aviso:** Não conheço bem essas pessoas e você deve confiar nelas por sua própria conta e risco.

---

## 📝 Notas Finais

Esta é uma tradução amadora feita com Google Translate, então possui muitos erros. Se encontrar erros ou quiser contribuir, sinta-se à vontade para fazer um fork e melhorar!

Se tiver dúvidas, sinta-se à vontade para me contatar no Discord: **imthemoon**

---

## 📄 Licença

Este projeto está licenciado sob uma licença customizada. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

**Nota:** Esta licença se aplica apenas ao trabalho de tradução em si, não aos ativos, código ou conteúdo do jogo que são propriedade dos desenvolvedores do jogo.
