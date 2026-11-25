# Emporio Suite - Android WebView

Projeto Android simples que abre o sistema Base44:

https://emporiosuitehub.base44.app/

## Gerar APK pelo GitHub

1. Crie um repositório no GitHub.
2. Envie todos os arquivos e pastas deste projeto para a raiz do repositório.
3. Use a branch `main`.
4. Abra a aba **Actions**.
5. Se necessário, habilite GitHub Actions para o repositório.
6. Execute **Gerar APK Android** ou faça um commit na branch `main`.
7. Quando terminar, abra a execução e baixe o Artifact `EmporioSuiteHub-APK`.
8. Extraia o ZIP para obter `app-debug.apk`.

## Observações

- Este projeto é um aplicativo Android que encapsula o site em uma WebView; ele não converte o sistema Base44 em código Android nativo.
- O aplicativo precisa de internet para acessar o site.
- O acesso a câmera é solicitado apenas quando a página tenta utilizá-la.
- Teste primeiro em um aparelho Android. Recursos do navegador que dependam de APIs não suportadas em WebView podem exigir ajustes específicos.
- O APK gerado pelo workflow é de depuração (`debug`), não é uma versão assinada para publicação na Play Store.
