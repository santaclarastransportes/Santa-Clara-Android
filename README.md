# Santa Clara Transportes — projeto Android

Este projeto abre o site oficial dentro de um app Android usando WebView.

## Gerar APK de teste
1. Envie esta pasta para um repositório GitHub seu.
2. Deixe a branch principal com o nome `main`.
3. Abra a aba Actions do repositório e execute **Build Santa Clara Android app** (ou faça um push na `main`).
4. Abra a execução concluída e baixe o artefato `santa-clara-android-build`.
5. O APK de teste estará em `app/build/outputs/apk/debug/` dentro do artefato.

## Publicação na Google Play
A Play Store exige um Android App Bundle (AAB) assinado e a configuração de dados, política de privacidade e ficha do app. O workflow gera um AAB, mas ele ainda precisa ser assinado com uma chave de publicação antes do envio. Não publique a chave privada no repositório.

## Observações importantes
- URL do site: https://santaclarastransportes.github.io/Santa-Clara-Transportes-Virtual/
- Nome do app: Santa Clara Transportes
- ID Android: `br.com.santaclara.transportes`
- Teste login, Firebase, criação/baixamento de notas PNG, WhatsApp e navegação no app antes da publicação. Alguns fluxos do site podem exigir ajustes específicos para WebView.
- Este projeto-fonte não é um APK já compilado.
