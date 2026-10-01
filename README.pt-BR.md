# Love Maths course source

[English](README.md)

## Ideia e processo

Fork de Code-Institute-Solutions/love-maths-2.0-sourcecode, revisado em 01/10/2026. Pastas numeradas registram sequência do curso, não história original de produto ou prova de autoria pessoal. Material original intacto.

## Arquitetura e design

Pastas cobrem fundamentos, JavaScript, pergunta/resposta, multiplicação/subtração, ajustes e divisão. Cada etapa é exemplo estático, não aplicação única na raiz. Etapa final revisada: 06-division-challenge/index.html e assets/js/script.js. Registra eventos de operação/envio/Enter, gera operandos 1-25, verifica inteiros e atualiza placar DOM. Divisão multiplica operandos e divide pelo segundo, produzindo inteiro. Sem backend ou persistência nessa etapa.

## Preview local

```bash
cd 06-division-challenge
python3 -m http.server 8000
```

Abra localhost:8000. Não espere index na raiz. Comando não executado nesta atualização; deploy público atual não confirmado.

## Testes e limites

Nada testado aqui. Verifique etapas separadamente, sem tratar pastas iniciais como conjunto final. Na última, confira quatro operações, Enter/botão, foco/placar, vazio/decimal e labels de teclado. parseInt trunca decimais; vazio vira NaN. Referência de curso não comprova aprovação manual/automatizada.

## Capturas

Nenhuma captura nova verificada/adicionada. Assets futuros datados em docs/assets/ devem identificar etapa/estado, não sugerir dashboard original. Preserve assets/créditos upstream.

## Créditos e licença

[Fonte Code Institute](https://github.com/Code-Institute-Solutions/love-maths-2.0-sourcecode) e assets mantêm direitos originais, sem licença adicionada/substituída. README original no [apêndice inglês](README.md#original-readme).
