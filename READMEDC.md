# Avaliação do Diário de Campo Individual (Intervenção)

Formulário interativo para avaliar o Diário de Campo Individual da intervenção, baseado na rubrica em planilha. Abre direto no navegador, sem cadastro e sem instalação, em computador, tablet e celular.

## Como usar

1. Abra o endereço da página no navegador.
2. Preencha disciplina, aluno(a), professor(a) e data.
3. Em cada uma das 8 seções, toque na opção que corresponde à avaliação de cada subitem. A caixa de observação aparece logo depois da escolha.
4. Na tela **Final**, confira a nota e baixe o PDF, a planilha (CSV) ou o arquivo de dados (.json).

Tocar de novo na opção marcada desmarca o subitem. Subitem sem avaliação vale zero.

## Rubrica

| Seção | Valor |
| --- | --- |
| 1. Identificação e formatação | 0,50 |
| 2. Descrição das atividades realizadas | 3,00 |
| 3. Objetivos | 1,00 |
| 4. Impressões diante dos fenômenos observados | 2,00 |
| 5. Principais aprendizados | 1,00 |
| 6. Desafios encontrados | 1,00 |
| 7. Registro fotográfico | 0,50 |
| 8. Qualidade da escrita e autoria individual | 1,00 |
| **Nota total** | **10,00** |

São 14 subitens. Cada opção vale uma parte do valor do subitem:

| Nível | Percentual |
| --- | --- |
| Excelente | 100% |
| Ótimo | 85% |
| Muito Bom | 70% |
| Bom | 60% |
| Regular | 40% |
| Insuficiente | 20% |
| Ausente | 0% |

A **nota final** do Diário de Campo é a nota total multiplicada por 4 e dividida por 10, com máximo de 4,00. O cálculo é idêntico ao da planilha: as notas dos subitens são somadas sem arredondamento e o arredondamento para duas casas ocorre apenas na exibição.

## Privacidade

Todas as avaliações ficam guardadas apenas no navegador do aparelho em uso (armazenamento local). A página não envia nenhuma informação pela internet e não usa serviços externos. Para guardar ou levar as avaliações a outro aparelho, use o PDF, o CSV ou a cópia de segurança (.json), que pode ser importada de volta pelo menu **Avaliações**.

Limpar os dados de navegação do aparelho apaga as avaliações guardadas. Por isso, baixe uma cópia de segurança quando precisar preservá-las.

## Arquivos

- `index.html`: o formulário completo (HTML, CSS e JavaScript em um único arquivo, sem dependências).

## Publicação no GitHub Pages

1. Envie `index.html` e `README.md` para a raiz de um repositório público.
2. Em **Settings > Pages**, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`.
3. Aguarde alguns minutos. O endereço será `https://USUARIO.github.io/NOME-DO-REPOSITORIO/`.

O formulário também funciona aberto como arquivo local, em qualquer navegador comum.
