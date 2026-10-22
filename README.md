# Fica o essencial

> Guia gratuito e passo a passo para transformar vídeos do YouTube, de qualquer tema, em relatórios PDF verificáveis, com um prompt que funciona no Claude ou no Gemini.

**Site:** https://rcrdo4750.github.io/fica-o-essencial/

---

## O que é

Uma página única, em português de Portugal e em inglês, que ensina a usar um prompt para resumir vídeos longos.
Escolhes o teu assistente de IA e o dispositivo, copias o prompt e segues os passos até teres o primeiro relatório em PDF.

Funciona com vídeos sobre qualquer assunto: finanças, culinária, bricolage, saúde, estudo, tecnologia.

## Para quem é

- Pessoas sem conhecimentos técnicos que querem aproveitar melhor vídeos longos.
- Quem prefere ler um relatório organizado a ver uma hora de vídeo.
- Quem quer poder confirmar o que o resumo afirma, em vez de confiar às cegas.

## O que o guia inclui

| Secção | Para que serve |
|---|---|
| Exemplo | Um vídeo e um relatório fictícios, para veres o resultado antes de começar |
| Passos | Percursos adaptados à IA e ao dispositivo que escolheres |
| Prompt | O prompt completo, em português e em inglês, com botão de copiar |
| Guardar o PDF | Como guardar o primeiro relatório |
| Transcrição e MP4 | Alternativas quando o assistente não consegue aceder ao vídeo |
| Problemas | Ajuda para os erros mais comuns |
| Partilhar | Botão para enviar o guia a outra pessoa |

## Como usar

1. Abre o [site](https://rcrdo4750.github.io/fica-o-essencial/).
2. Escolhe a língua, o assistente de IA e o dispositivo.
3. Copia o prompt com o botão da barra inferior.
4. Cola o prompt no assistente, junto com o endereço do vídeo.
5. Guarda o relatório em PDF.

## Privacidade

- Não há análises, cookies de rastreio nem pedidos a servidores de terceiros.
- A fonte está embutida na página, por isso não é descarregada de nenhum serviço externo.
- O navegador pode guardar algumas preferências locais (por exemplo, a língua). Ficam no teu dispositivo.
- Os vídeos e os relatórios nunca passam por este site: são tratados no assistente de IA que escolheres.

## Como este repositório funciona

Este repositório só contém o resultado final. É publicado automaticamente e **não deve ser editado à mão**.

1. O guia é escrito e mantido noutro local, onde é gerado como um único ficheiro HTML.
2. Quando esse ficheiro muda, é copiado para aqui como `index.html`.
3. O workflow do GitHub Pages publica o site em poucos segundos.

Alterações feitas diretamente aqui serão substituídas na próxima atualização.

## Estrutura

```text
.
├── index.html                 # O guia completo, num único ficheiro
├── README.md                  # Este ficheiro
└── .github/
    └── workflows/
        └── pages.yml          # Publica o site no GitHub Pages
```

## Créditos e licenças

- Tipo de letra **Bricolage Grotesque**, de The Bricolage Grotesque Project Authors, sob a [SIL Open Font License 1.1](https://scripts.sil.org/OFL). O aviso completo está dentro do `index.html`.
- O guia refere ferramentas de terceiros (por exemplo, geradores de transcrições). Cada uma tem os seus próprios termos de utilização.
- Este conteúdo é fornecido tal como está, sem garantias. Confirma sempre os factos importantes na fonte original.
