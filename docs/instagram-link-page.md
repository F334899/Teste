# Página de Links (Link-in-Bio) — Instagram @flaviane.caler

Registro da estrutura e decisões desta conversa, para retomada e refinamento futuro.

## Identidade visual confirmada

- **Paleta real da marca:** fundo ivory/nude (~`#F8F2EA`) + mauve/marrom-nude `#99665F` como cor de destaque. A versão anterior "Luxury Office" (verde-floresta + dourado) foi descartada — não é a identidade real da Dra. Flaviane.
- **Logo oficial:** monograma circular "C"+"F", wordmark "FLAVIANE CALER" + subtexto "ADVOCACIA ESPECIALIZADA EM DIREITO MÉDICO E DA SAÚDE". Arquivo fonte usado nesta sessão: `/root/.claude/skills/synced/legal-branding-strategist/templates/logo_oficial.png` (fundo mauve sólido). Foi gerada uma versão recortada e com fundo transparente (traço em mauve) para uso sobre fundo ivory.
- **Tipografia:** Cormorant Garamond (display/serifa) + Montserrat (texto/sans), via Google Fonts.
- **Mensagem pública:** especialização comunicada como **somente "Direito da Saúde"** — a pedido dela, sem mencionar Oncológico/Previdenciário em textos voltados ao público (mesmo que esses temas apareçam nos artigos do blog).

## Página publicada (Claude Artifact)

- **URL final (Opção 1 — Cartões, escolhida como definitiva):**
  https://claude.ai/code/artifact/73f0c4ef-adf4-4215-90b1-c7c3d596bd92
  - Privada por padrão — precisa compartilhar pelo menu do próprio artifact antes de divulgar na bio.
  - Favicon: ⚖️
- **Variações alternativas geradas (não descartadas, mas não escolhidas):**
  - "Flaviane Caler Minimalista" — lista limpa sem caixas: https://claude.ai/code/artifact/40745138-7495-47a8-8d62-65ce1804e198
  - "Flaviane Caler Ambiente" — painel translúcido sobre fundo atmosférico: https://claude.ai/code/artifact/b8c8d563-34fd-4f54-b11e-6827e3149bb7

### Estrutura da página (Opção 1)

1. Logo (traço mauve, sem fundo)
2. Texto de acolhimento: "Seja bem-vindo(a)" + breve apresentação (Dra. Flaviane Bilhar Caler, Direito da Saúde)
3. Links de contato: WhatsApp, Agendar consulta (Google Calendar), Instagram, Blog, E-mail
4. Seção "E-books gratuitos"
5. Rodapé: "Direito da Saúde"

### Contatos incluídos

| Canal | Valor |
|---|---|
| WhatsApp | +55 49 98806-1881 → `https://wa.me/5549988061881` |
| Agendamento | `https://calendar.app.google/xs8iEZTafCyiAeDQ8` (Google Calendar) |
| Instagram | `@flaviane.caler` |
| Blog | `https://blog.direitodasaudenapratica.com.br/` — **atenção:** este blog é de um colega dela, ela só posta lá; não é domínio próprio |
| E-mail | `admflavianecaler@gmail.com` |

### E-books

- 1º e-book já incluído: **"Tratamento Negado pelo SUS? Saiba o que fazer"**
  PDF no Google Drive dela (arquivo `ebook_01_tratamento_negado_SUS.pdf`, owner `draflavianecaler@gmail.com`):
  `https://drive.google.com/file/d/1IlYNsDO1qPtHMEjSgGdrvJUfldxFDGbH/view?usp=drive_link`
- Ela mencionou ter **mais 2 e-books prontos** localmente, ainda vai subir para o Drive e enviar os links.

## Arquivos de trabalho (scratchpad da sessão, não versionados no repo)

Os HTMLs fonte ficam no scratchpad temporário desta sessão (não persistem entre sessões):
- `flaviane-links.html` — versão final publicada (Opção 1)
- `template.html` — gerador com placeholder `__LOGO_B64__`, usado para reinjetar o logo em base64
- `logo_t_b64.txt` — base64 do logo com fundo transparente (mauve on transparent), versão em uso
- `flaviane-links-minimal.html` / `template_minimal.html` — Opção 2 (Minimalista)
- `flaviane-links-ambiente.html` / `template_ambiente.html` — Opção 3 (Ambiente)

Se uma sessão futura precisar editar a página, os arquivos HTML publicados podem ser lidos direto do Artifact (`action: "read"` na URL acima) — não é necessário depender do scratchpad antigo.

## Próximos passos em aberto

1. **Link customizado (Bitly):** ela quer configurar `bit.ly/flavianecaler` (ou similar) apontando para o link do artifact. Passo a passo já foi explicado; configuração ainda não foi feita do lado dela (requer conta própria, sem acesso via ferramenta).
2. **Domínio próprio:** ela decidiu que faz sentido comprar um domínio próprio (ex. `flavianecaler.com.br`) para ter um redirecionamento com a marca dela, já que o blog atual não é dela. Ainda não comprou.
3. **Blog próprio:** ela quer lançar um blog independente do colega. Direcionamento dado nesta conversa:
   - Usar CMS de verdade (ex. WordPress) em domínio próprio, para SEO.
   - Separar conteúdo por público — pacientes/família (linguagem simples) vs. colegas de Direito (técnico) — mesma lógica da skill `blog-direito-saude`.
   - Usar os e-books como isca de captura de e-mail (lead magnet).
   - Plataforma e estrutura de conteúdo ainda não definidas — ponto de partida para a próxima conversa.
