# Clipper — downloads

Instaladores do **Clipper para Windows** (versão de testes, para convidados).

## Instalar
1. Baixe o `Clipper-Setup-<versão>.exe` da [última versão](https://github.com/Gipsy7/clipper-releases/releases/latest).
2. Abra o arquivo. O Windows pode avisar "aplicativo não reconhecido", porque o instalador ainda não tem assinatura digital: clique em **Mais informações → Executar assim mesmo**.
3. O Clipper abre pelo Menu Iniciar. Não precisa de administrador.

Seus vídeos, cortes e ajustes ficam em `%LOCALAPPDATA%\Clipper\data` e continuam ao atualizar. O app avisa em **Ajustes → Sobre** quando há versão nova.

## O que mais tem aqui
- `latest.json`: o app consulta para avisar de versão nova.
- Release `modelos-v1` → `en_pt-br.zip`: modelo de tradução inglês → português do Brasil, baixado pelo app na primeira tradução de legenda. É o [Helsinki-NLP/opus-mt-tc-big-en-pt](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-en-pt) convertido para CTranslate2, sob a licença **CC-BY 4.0** (Tiedemann & Thottingal, *OPUS-MT — Building open translation services for the World*, EAMT 2020).

As licenças dos programas incluídos no instalador (FFmpeg GPL v3, Deno e bibliotecas) vêm no próprio instalador (`LICENCAS.txt`).

YouTube é marca registrada do Google LLC. O Clipper não é afiliado ao YouTube nem ao Google.
