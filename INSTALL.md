# Instalação do tema

Este guia explica como instalar e ativar o tema inspirado no Visual Studio Code no **Notepad++**.

## Requisito

O Notepad++ carrega temas a partir de arquivos `.xml`. **Atualmente, este repositório não contém o arquivo XML do tema**; portanto, você precisará obter esse arquivo separadamente antes de seguir os passos abaixo. O `screenshot.png` é apenas uma prévia e não pode ser instalado como tema.

## Passo a passo

1. **Obtenha o arquivo XML do tema.** Confirme que ele é o arquivo de tema do Notepad++ e que termina em `.xml`. Se não estiver disponível para download no projeto, solicite-o à pessoa responsável pelo repositório.
2. **Feche o Notepad++.** Isso ajuda a garantir que o aplicativo reconheça o arquivo ao iniciar novamente.
3. **Abra a pasta de temas do Notepad++:**
   - Instalação padrão no Windows: cole `%AppData%\Notepad++\themes\` na barra de endereços do Explorador de Arquivos.
   - Instalação portátil: abra a pasta onde está o Notepad++ e entre em `themes`.
4. **Copie o arquivo `.xml` para essa pasta.** Se a pasta `themes` não existir, crie-a.
5. **Inicie o Notepad++** (ou reinicie-o, se já estiver aberto).
6. No menu, acesse **Configurações > Configurador de Estilo...** (*Settings > Style Configurator...*).
7. Em **Selecionar tema** (*Select theme*), escolha o tema e clique em **Salvar e Fechar** (*Save & Close*).

## Se o tema não aparecer

- Confira se o arquivo `.xml` está diretamente dentro da pasta `themes` correta.
- Verifique se o arquivo não foi baixado com uma extensão duplicada, como `.xml.txt`.
- Reinicie o Notepad++ e abra novamente o **Configurador de Estilo**.
- Confirme que o arquivo é um tema compatível com o Notepad++.
