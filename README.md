# Guia básico de marcação markdown
Este guia oferece um passo a passo detalhado sobre como utilizar a marcação markdown para formatação de texto em documentos. iniciando desde os conceitos básicos, como títulos e parágrafos, até tópicos mais avançados, como tabelas, notas de rodapé e alertas. Cada topico é acompanhado por uma descrição simples e exemplos práticos em markdown, permitindo que os usuários aprendam e apliquem rapidamente a marcação markdown em seus próprios documentos.

## Títulos
São usados para criar diferentes níveis de títulos em um documento Markdown

Exemplo:

# Título 1
## Título 2
### Título 3

## Parágrafos
Simplesmente escreva seu texto como parágrafos normais. Não é necessário nenhum tipo demarcação adicional

Exemplo:

Aqui temos um paragrafo.

## Listas 
Permitem criar listas ordenadas ou não ordenadas

Exemplo de não ordenada:
* Item 1
* Item 2
* Item 3
* Item 4

Exemplo de ordenada:

1. Item 1
2. Item 2
3. Item 3
4. Item 4

## Links
Criam links para outras páginas web

Exemplo:

[https://www.youtube.com/](URL) para criar um link

## Imagens
Inserem imagens em um documento Markdown

Exemplo:

![Imagem](URL.da_imagem)
![a](https://github.com/BiluTeteia/atv002/assets/40745516/fd35f654-0a36-482c-aff6-692f800ce6ec)

## Ênfase
Permitem enfatizar texto, como itálico, negrito, tachado, subscrito, sobrescrito

Exemplo:

_Texto em itálico_

**Texto em negrito**

~~Texto tachado~~

Texto <sub>subscrito</sub>

Texto <sup>sobrescrito</sup>

## Citações em bloco
São usados para destacar uma citação ou  bloco de texto

Exemlo: 

> Isso é uma citação em bloco

## Linhas Horizontais

São usadas para criar uma linha horizontal para separar seções do documento

Exemplo:

---


## Código
Permitem inserir blocos de código ou destacar código dentro do texto

Exemplo:

```
idade = 18
console.log(`A idade é ${idade}`)
```
## Tabelas
| Cabeçalho 1 | Cabeçalho 2 |
|-------------|-------------|
| Dado 1      | Dado 2      |

## Listas de tarefas
Criam listas de tarefas que podem ser marcadas como concluídas ou pendentes

Exemplo:

- [x] Tarefa concluída
- [ ] Tarefa pendente

## Referências e notas de rodapé
Permitem adicionar notas de rodapé para fornecer mais informações sobre o conteúdo do documento

Exemplo:

Aqui é um exemplo de marcação de rodapé[^1]

A aula é com o Ricardo[^2]

[^1]: Rodapé: conteúdo inferior do texto
[^2]: Ricardo: Professor da turma de Git
## Alertas
São usados para destacar informações importantes, como notas, avisos ou mensagens

Exemplo:

> **Note**
> Esta é uma nota

> [!NOTE]
> Destaca informações que os usuários devem levar em consideração, mesmo durante a leitura superficial

> [!IMPORTANT]
> Informações cruciais necessárias para o sucesso dos usuários


> [!WARNING]
> Conteúdo crítico que exige atenção imediata do usuário devido a riscos potenciais
