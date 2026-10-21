# Aseul

**Ferramenta gratuita para Windows que mostra num relance, na barra de tarefas, quanto você já usou do Claude e do Codex.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · Português (Brasil) · [Français](README.fr.md)

> Este documento é uma tradução. Em caso de divergência, a [versão em coreano](README.ko.md) prevalece.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/aseul?lang=pt)

![Tela do Aseul](images/aseul-en.png)

## Visão geral

O Claude e o Codex têm um limite de 5 horas e um limite semanal. Você provavelmente já esbarrou em um deles no meio do trabalho, ou abriu uma página de uso só para ver quanto ainda restava.

O Aseul coloca um **pequeno medidor circular** na barra de tarefas, ao lado do relógio. Um círculo por serviço: o anel externo é o uso semanal e o interno, o uso de 5 horas. Cada anel se preenche no sentido horário a partir das 12 horas conforme você usa, e vai do verde ao vermelho à medida que se aproxima do limite. Uma olhada basta para saber se está no limite.

Clique no medidor para abrir a janela de status com o uso exato, o tempo até o próximo reinício e o seu uso nos últimos 7 dias. Fechar a janela deixa o medidor na barra de tarefas, ainda se atualizando.

## Principais recursos

- **Medidor circular na barra de tarefas** — um anel duplo por serviço (externo = semanal, interno = 5 horas). O círculo da esquerda é o Claude e o da direita, o Codex.
- **Cinco faixas de cor** — cada anel é dividido em cinco faixas de 20 %: verde, verde-limão, amarelo, laranja e vermelho. As faixas vazias aparecem esmaecidas, então você sempre vê qual cor vem a seguir.
- **Atualização automática** — verifica o uso do Claude e do Codex regularmente para mantê-lo em dia.
- **Números ao passar o mouse** — passe o mouse sobre o medidor para ver uma linha por serviço, como `Claude : 5% / 50%` (5 horas / semanal).
- **Janela de status** — barras de uso de 5 horas e semanal por serviço, com o tempo restante até cada reinício.
- **Histórico de 7 dias** — uma barra por dia mostrando o uso semanal e quanto foi usado naquele dia.
- **Acompanha o tema da barra de tarefas** — numa barra de tarefas clara o medidor fica sobre um painel de LED preto; numa escura aparecem só os anéis. A troca de tema vale na hora.
- **Só os serviços que você usa** — os círculos são desenhados apenas para os serviços conectados. Se você usa só o Codex, vê só o círculo do Codex.
- **Iniciar com o Windows** — liga e desliga pelo menu do botão direito. O instalador deixa ligado.
- **22 idiomas** — segue o idioma de exibição do Windows.

## Download / Instalação

| Tipo | Link |
|---|---|
| Instalador | [Baixar](https://down.kilho.net/aseul?lang=pt) |
| Portátil (ZIP) | [Baixar](https://down.kilho.net/aseul?lang=pt&nosetup) |

O instalador abre o Aseul assim que termina e liga Iniciar com o Windows. Na versão portátil, descompacte o ZIP e execute `Aseul.exe`.

## Como usar

### Primeiros passos

1. Verifique se você está conectado ao **Claude Code** ou ao **Codex**. O Aseul lê o seu uso por meio desse login (veja "Requisitos" abaixo).
2. Execute o Aseul. Em instantes aparece um **medidor circular** na barra de tarefas, logo à esquerda da área de notificação.
3. Olhe o medidor. O anel externo é o uso semanal e o interno, o de 5 horas. Quanto mais cheio e mais perto do vermelho, menos resta.
4. Para ver os números exatos, **passe o mouse** sobre o medidor ou **clique** nele para abrir a janela de status.
5. Feche a janela de status pelo botão de fechar ou com **Esc**. O medidor continua lá, se atualizando.

### Elementos da tela

**Medidor da barra de tarefas**

| Elemento | Significado |
|---|---|
| Círculo esquerdo / direito | Claude / Codex (só serviços conectados) |
| Anel externo | Uso semanal |
| Anel interno | Uso de 5 horas |
| Cor do anel | 0–20 % verde, 20–40 % verde-limão, 40–60 % amarelo, 60–80 % laranja, 80–100 % vermelho |
| Passar o mouse | `% de 5 horas / % semanal` por serviço |
| Clique | Abre a janela de status |
| Botão direito | Menu (tabela abaixo) |

**Menu do botão direito**

| Menu | O que faz |
|---|---|
| **Abrir janela de status** | Abre a janela de status — o mesmo que clicar no medidor |
| **Iniciar com o Windows** (marcar) | Inicia automaticamente ao entrar no Windows |
| **Criado por Kilho Oh** | Abre o site |
| **Sair** | Pergunta "Tem certeza de que deseja sair?" e fecha |

**Janela de status**

| Elemento | Significado |
|---|---|
| Nome do serviço | Claude, Codex |
| Barras **5 h** · **Semanal** | Uso — nas mesmas cores do medidor, mais fortes conforme enchem |
| % | Uso atual |
| **Reinicia em …** | Tempo até esse limite voltar a 0 |
| Gráfico de 7 dias | Aparece no lugar ao passar o mouse sobre um serviço |

### Dicas para situações comuns

**Conferir o que resta antes de uma tarefa longa**
Passe o mouse sobre o medidor para ver na hora o uso de 5 horas / semanal, como `Claude : 35% / 72%`. Se o uso semanal estiver perto da faixa vermelha, dá para deixar os trabalhos grandes para depois do reinício.

**Saber quando um limite reinicia**
Clique no medidor para abrir a janela de status. À direita das barras 5 h e Semanal aparece o tempo restante, como **Reinicia em 2 d 21 h**.

**Ver em quais dias desta semana você mais usou**
Na janela de status, passe o mouse sobre um serviço (Claude ou Codex) para mostrar o gráfico dos últimos 7 dias. Há uma barra por dia, com hoje na extrema direita. A altura da barra é o uso semanal daquele dia; a parte superior mais forte é quanto subiu naquele dia. Passe o mouse sobre uma barra para ver a data, o uso semanal e o aumento do dia, como `10/15(qui) · 56% (+12%)`.

**Usar só o Claude ou só o Codex**
Não há nada para configurar. Só os serviços conectados ganham um círculo no medidor e uma seção na janela de status.

**Usar uma barra de tarefas clara**
Um painel de LED preto fica atrás do medidor para que as cores dos anéis fiquem nítidas. Mude para escuro e o painel some, deixando só os anéis. As trocas de tema valem na hora.

**Mudar o tamanho da barra de tarefas**
Quando a altura da barra de tarefas muda, por exemplo com botões pequenos ou uma barra de duas linhas, o medidor se redesenha na hora para se ajustar. Os círculos têm o tamanho de um ícone da bandeja, então ficam nítidos em monitores de alta resolução.

**Mostrar o medidor sempre que o PC liga**
Botão direito no medidor → marque **Iniciar com o Windows**. O instalador já deixa ligado. Clique de novo para desligar.

**Depois de entrar de novo no Claude Code ou no Codex**
Não há nada a fazer no Aseul. A próxima verificação pega os novos valores e o medidor continua. Até lá, a janela de status mostra esmaecidos os últimos valores recebidos.

**Executar o Aseul antes de fazer login**
Se você não estiver conectado nem ao Claude Code nem ao Codex, o Aseul mostra "Nenhuma IA conectada." e fecha. Entre em qualquer um dos dois e execute-o de novo.

**Encontrar de novo a janela de status**
A janela de status não cria um botão próprio na barra de tarefas. Clicar no medidor a abre no centro do monitor onde ele está, ou a traz para a frente se já estiver aberta. Executar o Aseul uma segunda vez também abre a janela de status, em vez de iniciar outra cópia.

**Fechar o Aseul por completo**
Botão direito no medidor → **Sair** → **Sim**. Fechar só a janela de status não encerra o programa; o medidor continua.

## Configuração

Não há janela de configuração. A única opção é **Iniciar com o Windows** no menu do botão direito; todo o resto segue o sistema automaticamente.

| Item | Segue |
|---|---|
| Iniciar com o Windows | Ligado no instalador, desligado no portátil — muda pelo menu do botão direito |
| Serviços exibidos | Serviços conectados (Claude, Codex) |
| Aparência do medidor | Tema claro / escuro da barra de tarefas |
| Tamanho do medidor | Tamanho do ícone da bandeja (escala da barra de tarefas) |
| Janela de status | Sempre escura |
| Idioma da interface | Idioma de exibição do Windows (22 idiomas; caso contrário, inglês) |

## Requisitos

- Windows 10 · Windows 11 (64 bits)
- É preciso estar conectado ao **Claude Code** ou ao **Codex**.
  - Claude: conectado ao Claude Code com uma conta Claude
  - Codex: conectado ao Codex com uma conta ChatGPT (o login por chave de API não tem dados de uso, por isso não aparece)
- É preciso conexão com a internet para obter o uso.
- Nenhum runtime extra é necessário. O instalador usa permissões de administrador só durante a instalação.

## Atualizações

O Aseul **não** se atualiza sozinho. Ao iniciar, verifica se há uma versão nova e mostra um aviso; ao pressionar **Sim**, a página de download é aberta e o programa é encerrado. As novas versões são publicadas manualmente após verificação interna e anunciadas na [página do Aseul](https://kilho.net/aseul). Veja o [aviso sobre a política de atualização](https://en.kilho.net/archives/notice/2940).

## Licença

O Aseul é **freeware**. Pode ser usado em qualquer lugar — no escritório, em casa, em órgãos públicos ou na escola — gratuitamente e sem restrições, e pode ser redistribuído livremente.

## Links

- Site: <https://kilho.net/aseul>
- Fórum: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
