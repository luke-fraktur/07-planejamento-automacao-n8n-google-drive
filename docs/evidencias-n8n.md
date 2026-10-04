# Evidências iniciais do desafio de n8n

A pasta do Google Drive contém sete capturas de tela, modificadas em 04/09/2026, que formam o material do desafio. A primeira imagem apresenta o título parcialmente visível como “Desafio Criativo: Planejando Automações com ...”. O acesso à pasta é público para leitura e a solução deverá priorizar Google Drive, conforme solicitação do aluno.

Ainda é necessário extrair o conteúdo completo das sete capturas antes de definir a arquitetura final.

Aluno: Lucas Oliveira Soares de Freitas
Data de referência solicitada anteriormente: 13/08/2026
Projeto-base: Agência Escala Pro
Fonte do desafio: https://drive.google.com/drive/folders/1gRQiyBcFx2-XivoAYxtUiy60SyjODWAK?usp=sharing

## IDs identificados por nome de arquivo
- 074957: 1rVzP-FTMDji1elMpTCOPeahMRpA1lTMU
- 075039: 1Q_TJ8MrbsBfuhvop8LusV9iYjUgiztUT
- 075051: 1_WKlW6OE-DN9iXpyaSKmfW804wDXA4LO
- 075105: 1DjIh-zBP4jGdkKG6QKBlC1ttE5BI4hPi
- 075111: 1NMRqOYWo8YyhaEw8WKQAm2IUC0A9PpfV
- 075119: 1QL46tI4y1NqGN8BfDbmCYM66X_7cd6Wr
- 075127: 1xUCs7rECSzlyju2-fveYeY-GLQhyIEos

## Estado
Somente as duas primeiras imagens foram baixadas localmente; o download sequencial sofreu tempo limite. Prosseguir por navegação/visualização individual para evitar perda de conteúdo.

## Conteúdo confirmado das imagens 01 e 02

### Imagem 01 — Visão geral
Título: **Desafio Criativo: Planejando Automações com N8N Usando Apenas Bons Prompts**. O exercício orienta o participante a planejar uma automação em n8n a partir de um prompt claro e estruturado. O material destaca que um bom prompt nasce de intenção clara, contexto e instruções específicas; cada etapa acrescenta uma peça ao prompt final.

### Imagem 02 — Passo 1: Defina a automação desejada
A etapa solicita responder: qual tarefa repetitiva será automatizada; quem utilizará ou será impactado pela automação; e qual resultado deve acontecer. O modelo apresentado é:

> Quero criar uma automação no N8N para [processo].
>
> Público ou responsável:
> [quem utilizará]
>
> Resultado esperado:
> [resultado desejado]

O exemplo preenchido usa o registro automático de leads recebidos por formulário, com a equipe comercial como responsável, salvando os dados em uma planilha e enviando uma notificação ao time de vendas.

A solução escolhida será adaptada para **Google Drive**, usando uma pasta monitorada como origem e organização central dos arquivos.

### Imagem 03 — Passo 2: Adicione contexto e regras
A etapa solicita informar os sistemas envolvidos, as etapas do fluxo e as restrições importantes. As perguntas são: quais ferramentas ou serviços participam da automação; quais etapas devem acontecer em sequência; e se existe alguma regra, validação ou exceção.

Modelo:
> Ferramentas envolvidas:
> [lista de ferramentas]
>
> Fluxo desejado:
> 1. [etapa 1]
> 2. [etapa 2]
> 3. [etapa 3]
>
> Regras importantes:
> [restrições, validações ou exceções]

Exemplo: Google Forms, Google Sheets e Gmail; receber nova resposta, registrar dados na planilha e enviar e-mail de confirmação; ignorar registros sem e-mail válido.

### Imagem 04 — Passo 3: Monte o prompt final
A etapa reúne todas as peças anteriores em um único prompt completo. A revisão deve verificar se o objetivo está claro, se as etapas estão em ordem e se regras e restrições foram informadas.

Modelo:
> Atue como um especialista em N8N.
>
> Crie uma automação para [processo].
>
> Público:
> [público]
>
> Ferramentas envolvidas:
> [ferramentas]
>
> Fluxo:
> [etapas]
>
> Regras:
> [regras]
>
> Explique quais nós do N8N devem ser utilizados e a lógica de funcionamento do workflow.

### Imagem 05 — Exemplo preenchido
O exemplo final reapresenta a automação de registro de leads de formulário. O prompt deve indicar: atuação como especialista em N8N; processo de registrar leads recebidos por formulário; público/equipe comercial; ferramentas Google Forms, Google Sheets e Gmail; fluxo de receber resposta, salvar dados na planilha e enviar e-mail de confirmação; regra de ignorar registros sem e-mail válido; e explicação dos nós n8n e da lógica do workflow.

### Imagem 06 — Como entregar seu desafio
A entrega deve ser salva como arquivo `.txt` ou `.md`. A orientação destaca o **Google Drive como opção mais simples**: fazer upload do arquivo no Drive; abrir o menu Compartilhar; em Acesso geral selecionar “Qualquer pessoa com o link”; copiar o link e colá-lo no campo de submissão da DIO. A captura também menciona Git/GitHub como alternativa para versionamento.

### Imagem 07 — Alternativa GitHub
A alternativa de versionamento orienta criar um repositório público, adicionar o arquivo `.md` pelo recurso “Add file > Upload files”, abrir o arquivo no GitHub, copiar a URL do navegador e colar o link no campo de submissão da DIO. A dica informa que o Markdown já é renderizado de forma adequada no GitHub, sem configuração extra.

## Extração concluída
As sete imagens foram lidas. A entrega escolhida para este trabalho será um arquivo Markdown hospedável no Google Drive, com um prompt final completo e profissional, além de uma seção prática explicando os nós n8n e o fluxo recomendado.
