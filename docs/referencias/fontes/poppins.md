# Poppins — referência tipográfica

## Registro

- **Fonte:** Poppins
- **Classificação:** referência técnica fornecida pela usuária
- **Data do registro:** 2026-07-27
- **Cliente/projeto:** não informado neste envio; não associar automaticamente a nenhum cliente
- **Link recebido, fixado no commit analisado:** https://github.com/iceikiru/Poppins-font/tree/1358685396d7853794cbc6412a8d0b265e33eeed/files

## Veredito técnico

O link recebido deve ser preservado como referência histórica, mas **não deve ser usado como origem canônica de produção**.

Problemas confirmados no commit `1358685396d7853794cbc6412a8d0b265e33eeed`:

1. O repositório de terceiros está sem atualização desde 2020.
2. O arquivo `index.css` abre 18 blocos `@font-face`, mas fecha apenas 12. Faltam chaves nos blocos 200 normal, 200 itálico, 300 itálico, 400 normal, 500 normal e 700 normal.
3. O CSS referencia arquivos `.otf` inexistentes no commit. Os arquivos `.woff` e `.woff2` existem.
4. O `package.json` aponta para outro repositório (`cbot83/Poppins-font`), sinal de metadados herdados/desatualizados.
5. O campo `MIT` do pacote não deve ser tratado como licença da família tipográfica. A distribuição oficial da Poppins usa a **SIL Open Font License 1.1 (OFL-1.1)**.

## Fontes canônicas recomendadas

- Google Fonts — repositório oficial: https://github.com/google/fonts/tree/main/ofl/poppins
- Licença OFL-1.1: https://github.com/google/fonts/blob/main/ofl/poppins/OFL.txt
- Fontsource: https://fontsource.org/fonts/poppins/install

Para projetos web, preferir uma versão fixada de `@fontsource/poppins` ou arquivos obtidos do repositório oficial do Google Fonts. Ao auto-hospedar, manter uma cópia da licença `OFL.txt` junto aos ativos.

## Regra de memória e uso

- Nome oficial da família: `Poppins`.
- O link de terceiros acima fica registrado somente como referência enviada.
- Não copiar seu `index.css` para produção.
- Não vincular a fonte a Unique, Trinitas ou qualquer outro cliente até que a usuária confirme o cliente ativo.
- Após a confirmação, registrar pesos, estilos e hierarquia tipográfica específicos dentro da pasta/documentação daquele cliente.
