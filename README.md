# Clipper para Windows

O Clipper transforma vídeos do YouTube em **cortes prontos para publicar**: escolha o trecho, aplique uma moldura com o título, coloque legendas automáticas e música, e publique no YouTube, no Instagram ou no TikTok. Tudo roda no seu computador.

> Versão de testes, distribuída para convidados.

**[⬇ Baixar a versão mais recente](https://github.com/Gipsy7/clipper-releases/releases/latest)**: baixe o arquivo `Clipper-Setup-<versão>.exe`.

---

## Sumário
1. [Do que você precisa](#1-do-que-você-precisa)
2. [Instalar](#2-instalar)
3. [Primeiro acesso](#3-primeiro-acesso)
4. [Fazer um corte](#4-fazer-um-corte)
5. [Onde ficam os cortes](#5-onde-ficam-os-cortes)
6. [Publicar](#6-publicar)
7. [Templates e músicas](#7-templates-e-músicas)
8. [Trocar de computador](#8-trocar-de-computador)
9. [Atualizar e desinstalar](#9-atualizar-e-desinstalar)
10. [Perguntas frequentes](#10-perguntas-frequentes)

---

## 1. Do que você precisa
- **Windows 10 ou 11** (64 bits).
- **Internet**: para abrir os vídeos do YouTube e publicar.
- **Espaço livre**: cerca de **1 GB** para o programa, mais **150 MB** quando você usar legendas pela primeira vez. A legenda "Precisa" baixa mais **1,6 GB** na primeira vez que for usada.
- Um computador mais novo deixa tudo mais rápido, mas qualquer PC atual funciona: um corte de 30 segundos costuma ficar pronto em menos de um minuto.

## 2. Instalar
1. Baixe o `Clipper-Setup-<versão>.exe` da [última versão](https://github.com/Gipsy7/clipper-releases/releases/latest) e abra o arquivo.
2. O Windows pode mostrar **"O Windows protegeu o computador"**. Isso acontece com programas novos que ainda não têm assinatura digital paga. Clique em **Mais informações → Executar assim mesmo**.
3. Siga o instalador. Ele não pede senha de administrador e cria o atalho no Menu Iniciar (e, se você marcar, na área de trabalho).
4. Abra o **Clipper** pelo Menu Iniciar.

> Alguns antivírus desconfiam de programas recém-lançados. Se o seu bloquear o Clipper, libere o arquivo ou a pasta `%LOCALAPPDATA%\Programs\Clipper`.

## 3. Primeiro acesso
- O Clipper **não tem conta nem senha**. Na primeira vez, ele pergunta só **como você quer ser chamado** (o nome do seu usuário do Windows já vem preenchido).
- **Tem um código de convite?** Clique em **"Tenho um código de convite"**, cole o código e informe o **e-mail para o qual ele foi gerado**. O código libera o envio automático ao YouTube. Dá para ativar depois, em **Ajustes → Seu perfil**.
- Em seguida, o Clipper oferece um **tutorial de uns 2 minutos**, em que você faz o seu primeiro corte com um vídeo de exemplo. Recomendamos! Se pular, ele fica em **Ajustes → Tutorial**.
- Os botões **?** espalhados pela tela explicam cada recurso.

> Se mais de uma pessoa usa o mesmo computador, cada uma deve usar a própria conta do Windows: assim cada uma tem os próprios cortes.

## 4. Fazer um corte
1. **Abra o vídeo**: cole o link do YouTube no campo do topo e clique em **Abrir**.
2. **Escolha o trecho**: toque o vídeo e marque o começo e o fim do corte (teclas **I** e **O**, ou digite os tempos). **Ouvir trecho** toca só o pedaço escolhido.
   - Sem tempo para procurar? **Melhores momentos** sugere os trechos mais fortes do vídeo. A análise **Rápida** leva segundos; a **Completa** também entende a fala e demora mais.
3. Na coluna da direita, configure o corte:
   - **Visual**: o **template** (a moldura, com título e cores) e o encaixe do vídeo:
     - **Inteiro**: o vídeo todo, sobre um fundo desfocado;
     - **Recortar**: preenche a tela;
     - **Seguir rosto**: acompanha quem está falando, ótimo para podcasts e entrevistas.
   - **Legendas**: legendas automáticas com a palavra falada em destaque.
     - **Revisar texto** permite corrigir antes de gerar.
     - Também dá para **traduzir** a legenda.
     - A qualidade **Rápida** serve para a maioria dos vídeos; a **Precisa** erra menos, mas é mais lenta.
   - **Áudio**: música de fundo da sua biblioteca. Com **"abaixar a música quando alguém fala"**, a voz fica sempre clara.
4. Clique em **Gerar corte**. Ele aparece em **Seus cortes**, com o andamento em tempo real. Pode continuar trabalhando enquanto ele é gerado.

> Dica: nomes que a legenda costuma escrever errado (pessoas, marcas, bordões) podem ir no **Glossário**, em Ajustes.

## 5. Onde ficam os cortes
- Os cortes prontos ficam em **Vídeos\ytClipper**, com o título no nome do arquivo.
- **Mostrar na pasta** (na lista de cortes) abre essa pasta com o arquivo já selecionado, pronto para arrastar para onde você quiser.
- Excluir um corte no Clipper **não apaga** o arquivo da pasta.

## 6. Publicar
Na lista **Seus cortes**, cada corte pronto tem os botões **YouTube**, **Instagram** e **TikTok**.

### YouTube: publicação manual (todo mundo)
O Clipper deixa tudo pronto e você envia pelo YouTube Studio:
1. Confira o **título**, a **descrição** e as **tags**. O crédito da música, quando a licença exige, entra sozinho na descrição.
2. Se quiser, gere opções de **thumbnail** e escolha uma.
3. Clique em **Abrir o YouTube Studio** e depois em **Mostrar o vídeo na pasta**. Arraste o arquivo para a página do Studio.
4. Use os botões **Título**, **Descrição** e **Tags** para copiar e colar no Studio. Lá você escolhe a visibilidade (pode ser pública direto) e publica.
5. Cole o link do vídeo publicado de volta no Clipper, para o corte ficar marcado como publicado.

### YouTube: envio automático (convidados especiais)
Com um código de convite especial, você conecta o canal em **Ajustes → Conexões** e o Clipper envia sozinho. Há um limite de envios por dia; quando ele acaba, a publicação manual continua disponível.

### Instagram (Reels)
Exige uma **conta profissional** (Criador, grátis) e um token gerado no painel de desenvolvedores da Meta. O passo a passo está em **Ajustes → Conexões → Conectar Instagram**. Se preferir, use **Mostrar na pasta** e publique pelo próprio app do Instagram.

### TikTok
O botão **TikTok** abre um assistente:
1. Copie a legenda.
2. Abra o TikTok.
3. Arraste o vídeo da pasta.
4. Cole o link publicado no Clipper.

## 7. Templates e músicas
- **Templates**: a aba Templates tem uma coleção pronta. **Criar rápido** faz um template do seu canal em um minuto, com o seu logo e as suas cores. Depois, dá para mover e redimensionar cada parte no editor visual.
- **Músicas**: importe músicas que você pode usar nos seus vídeos. A Biblioteca de áudio do YouTube Studio e o Pixabay têm faixas grátis. Se a licença exigir crédito, informe o texto: ele vai sozinho para a descrição.

## 8. Trocar de computador
Os seus dados ficam no seu computador. Para levar tudo a outro PC:
1. No computador antigo: **Ajustes → Seus dados → Exportar meus dados**. Marque "incluir os vídeos dos cortes" se quiser levar os arquivos também (o backup fica maior). Salve o `.zip` num pendrive, no Google Drive etc.
2. No computador novo: instale o Clipper e abra **Ajustes → Seus dados → Escolher arquivo de backup**. Depois, **Reiniciar e importar**.
3. Conecte de novo o YouTube e o Instagram: por segurança, as conexões não vão no backup.

> Os dados que já estavam no computador novo ficam guardados numa cópia antes da importação.

## 9. Atualizar e desinstalar
- **Atualizar**: quando houver versão nova, aparece um aviso em **Ajustes → Sobre**. Baixe o instalador novo e instale **por cima**: os seus cortes, templates e ajustes continuam.
- **Desinstalar**: Configurações do Windows → Aplicativos → Clipper → Desinstalar. O desinstalador pergunta se você quer apagar também os seus dados. Responda **Não** se pretende instalar de novo e continuar de onde parou.

## 10. Perguntas frequentes
**O vídeo do YouTube não abre.**
Vídeos privados, com restrição de idade ou de alguns canais não podem ser abertos. Confira se o link abre normalmente no navegador sem estar logado.

**A primeira legenda demorou muito.**
Na primeira vez, o Clipper baixa o modelo de transcrição (150 MB na Rápida, 1,6 GB na Precisa). Das próximas vezes é bem mais rápido.

**O corte ficou "Na fila".**
O Clipper gera no máximo dois cortes ao mesmo tempo, para o computador não travar. O próximo começa assim que um terminar, e dá para cancelar enquanto espera.

**"Não consegui salvar em …: o arquivo está aberto em outro programa".**
Feche o vídeo no player (ou no editor) e clique em **Gerar** de novo.

**Onde estão os meus dados?**
Em `%LOCALAPPDATA%\Clipper\data` (cortes em andamento, templates, músicas, ajustes) e os vídeos prontos em `Vídeos\ytClipper`.

**O antivírus apagou ou bloqueou o Clipper.**
Programas novos sem assinatura digital às vezes são confundidos com ameaças. Restaure o arquivo e adicione `%LOCALAPPDATA%\Programs\Clipper` às exceções.

**Encontrou um problema?**
Fale com quem te convidou e, se possível, mande o arquivo `%LOCALAPPDATA%\Clipper\data\logs\clipper.log`.

---

### Arquivos desta página
- `Clipper-Setup-<versão>.exe`: o instalador.
- `latest.json`: usado pelo Clipper para avisar de versões novas (não precisa baixar).
- Release **modelos-v1** → `en_pt-br.zip`: modelo de tradução inglês → português do Brasil, baixado pelo próprio Clipper na primeira tradução de legenda. É o [Helsinki-NLP/opus-mt-tc-big-en-pt](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-en-pt) convertido, sob a licença **CC-BY 4.0** (Tiedemann & Thottingal, *OPUS-MT — Building open translation services for the World*, EAMT 2020).

As licenças dos programas incluídos (FFmpeg GPL v3, Deno e bibliotecas) vêm no instalador (`LICENCAS.txt`). YouTube é marca registrada do Google LLC; o Clipper não é afiliado ao YouTube nem ao Google.
