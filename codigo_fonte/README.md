# Visual Studio Purple Dark JA

Tema de cores para o Visual Studio Code, com interface escura e detalhes roxos, inspirado no Visual Studio.

## Autor e comunidade

Criado por **José Augusto Lopes Almeida** — [@joseaugusto10](https://github.com/joseaugusto10).

Compartilhado com a **.Net Brasil Community**.

## Cores

- Barra de título e atividades: `#452372`.
- Abas e barra de status: `#301850`.
- Explorador e painéis: `#27242B`.
- Editor e terminal: `#1E1E1E`.
- Realce de sintaxe e suporte a cores semânticas.

## Instalação

1. Baixe `Visual_Studio_Purple_Dark_JA_v1.1.0.vsix` no [repositório](https://github.com/joseaugusto10/visual-studio-purple-dark-ja).
2. No VS Code, abra Extensões (Ctrl+Shift+X).
3. No menu **...**, escolha **Instalar do VSIX...** e selecione o arquivo.
4. Abra **Preferências: Tema de Cores** (Ctrl+K, Ctrl+T) e selecione **Visual Studio Purple Dark JA**.

## Barra de título roxa

Abra as configurações de usuário em JSON e mescle estas opções com as existentes:

```json
{
  "window.titleBarStyle": "custom",
  "window.menuBarVisibility": "compact",
  "workbench.colorTheme": "Visual Studio Purple Dark JA"
}
```

A barra nativa do sistema pode ignorar as cores do tema. Use `custom` para aplicar as cores. Para menus tradicionais, troque `compact` por `classic`.

## Alternativa sem extensão

O arquivo `VSCode_VisualStudio_2026_sem_extensao.json` na raiz contém personalizações de cores. Mescle `workbench.colorCustomizations` e `editor.tokenColorCustomizations` com suas configurações existentes. A extensão inclui o esquema completo de sintaxe e semântica.

## Código-fonte

O manifesto está em `codigo_fonte/package.json` e as cores em `codigo_fonte/themes/VisualStudio2026PurpleDark-color-theme.json`.

Sugestões e problemas podem ser enviados pelas [issues](https://github.com/joseaugusto10/visual-studio-purple-dark-ja/issues).

## Créditos e licença

Tema inspirado no Visual Studio e, conforme a documentação original, no tema PhpStorm v1.2. A licença MIT e o aviso de copyright original estão preservados em `codigo_fonte/LICENSE.txt`.

Esta é uma criação independente, sem afiliação à Microsoft ou à JetBrains. A extensão apenas define cores e não executa código. Ícones e disposição dos menus seguem o VS Code.
