# HSK 3 Livre (app Android)

App gratuita para estudar as 298 palavras do HSK 3: lista com pesquisa, flashcards, testes, áudio e ordem dos traços.
Funciona **sem internet** (o vocabulário e os traços estão todos dentro da app).

## Como gerar o APK (grátis, pelo GitHub)

1. Cria uma conta em https://github.com (se ainda não tens).
2. Clica em **New repository**, dá o nome `hsk3-livre`, escolhe **Public** e clica em **Create repository**.
3. Clica em **uploading an existing file**.
4. Descompacta este ZIP no computador e arrasta **todo o conteúdo** da pasta (incluindo a pasta `.github`) para a página. Clica em **Commit changes**.
   - Se a pasta `.github` não aparecer (no Windows, ative “Itens ocultos” no Explorador), cria-a à mão:
     **Add file → Create new file**, escreve o nome `.github/workflows/build-apk.yml` e cola o conteúdo desse ficheiro.
5. Abre o separador **Actions**. A compilação “Criar APK” começa sozinha e demora cerca de 3–5 minutos.
   - Se aparecer um botão verde a pedir para ativar os workflows, clica nele e depois em **Run workflow**.
6. Quando ficar com um ✔ verde, vai à página principal do repositório → **Releases** (à direita) → toca em **HSK3-Livre.apk**.

## Instalar no telemóvel

1. Abre a página **Releases** no Chrome do telemóvel e descarrega `HSK3-Livre.apk`.
2. Abre o ficheiro. Se o Android avisar, permite “Instalar apps desconhecidas” para o Chrome.
3. Instala e abre **HSK 3 Livre**.

## Áudio

A pronúncia usa a voz do próprio telemóvel. Se não ouvires nada:
Definições → Gestão geral / Sistema → Idioma → **Saída de texto para voz** → Motor Google → instala a voz **Chinês (China)**.

## Notas

- O progresso (favoritas, “já sei”, testes) fica guardado no telemóvel.
- Ao atualizar a app com um novo APK, pode ser preciso desinstalar a versão anterior primeiro.
- Vocabulário: lista oficial HSK 3 (HSK 2.0). Traços: Hanzi Writer + Make Me a Hanzi (Arphic Public License).
