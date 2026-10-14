# Zyphora8

Emulador Android nativo de CHIP-8, sem WebView. O código-fonte completo está em `Zyphora8-Android-Fonte.zip`.

Inclui 50 programas/ROMs: 49 do CHIP-8 Archive, cuja página declara licença CC0, e uma demo original. O catálogo e autores estão dentro do projeto em `app/src/main/assets/games.json` e `ROM-CREDITS.md`.

O GitHub Actions compila um APK debug e o publica na aba Releases quando o build passa. Esta versão implementa CHIP-8 clássico; ROMs Super-CHIP/XO-CHIP podem não funcionar. APK de debug usa assinatura temporária do CI, então uma atualização pode exigir remover a versão anterior.
