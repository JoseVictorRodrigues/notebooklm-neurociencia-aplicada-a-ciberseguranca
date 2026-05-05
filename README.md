# Neurociência aplicada à cibersegurança

## Contexto e objetivos

Esse projeto surgiu da ideia de entender melhor por que as pessoas ainda caem em golpes digitais, mesmo com tanta tecnologia de segurança disponível.

Ao invés de olhar só para o lado técnico, a proposta foi explorar o lado humano da segurança: como o cérebro toma decisões, como emoções influenciam nossas ações e de que forma isso é explorado em ataques como phishing.

Os principais objetivos foram:

* entender como o comportamento humano impacta a segurança digital
* identificar como golpes exploram emoções e padrões mentais
* analisar como reduzir erros humanos em ambientes digitais

---

## Curadoria de fontes

Para desenvolver este estudo, foram utilizadas 35 fontes no NotebookLM, incluindo artigos técnicos, estudos acadêmicos e materiais institucionais sobre comportamento humano e segurança digital.

### Fontes principais utilizadas

As fontes abaixo foram as mais relevantes para a construção do projeto:

* https://www.cisa.gov/uscert/ncas/tips/ST04-014
* https://www.ibm.com/br-pt/topics/phishing
* https://pt.wikipedia.org/wiki/Engenharia_social_(segurança)
* https://meucerebro.com/como-o-cerebro-toma-decisoes/
* https://repositorio-aberto.up.pt/bitstream/10216/145534/2/592184.pdf

Essas referências foram fundamentais para entender a relação entre engenharia social, comportamento humano e tomada de decisão.

---

### Outras fontes utilizadas

Além das principais, outras fontes foram analisadas para complementar o estudo:

#### Documentos oficiais

* https://www.gov.br/abin/pnpc
* https://www.ftc.gov/business-guidance/privacy-data-security

#### Referências gerais

* https://pt.wikipedia.org/wiki/A_Arte_de_Enganar
* https://pt.wikipedia.org/wiki/Análise_do_comportamento
* https://pt.wikipedia.org/wiki/Comportamento_humano
* https://pt.wikipedia.org/wiki/Engenharia_social_(ciência_política)

#### Artigos acadêmicos e repositórios

* https://repositorio.bc.ufg.br/handle/ri/20926
* https://repositorio.ufersa.edu.br/content
* https://adelpha-api.mackenzie.br/content
* https://repositorio.ufc.br/bitstream/riufc/49703/1/2019_tcc_ipsilva.pdf
* http://bia.ifpi.edu.br:8080/jspui/bitstream/123456789/1781/1/2023_tcc_frcsilva.pdf

#### Filosofia e comportamento

* https://plato.stanford.edu/entries/hume-moral
* https://plato.stanford.edu/archives/fall2024/entries/kant-moral/

#### Tecnologia e segurança

* https://hoxhunt.com/blog/security-awareness-not-reducing-risk
* https://hoxhunt.com/blog/unprecedented-400-percent-us-tax-phishing-campaign-surge
* https://starti.com.br/blog
* https://www.dentsu.com/2026-media-trends
* https://www.migalhas.com.br/depeso/357488/phishing-vishing-e-smishing-o-que-sao-esses-golpes

#### Neurociência e comportamento

* https://www.psychologytoday.com/us/blog/parenting-neuroscience-perspective/202403/how-your-environment-shapes-your-habits
* https://online.pucrs.br/blog/neurociencia-e-psicologia-guia-comportamento-humano
* https://eduvem.com/blog/tomada-de-decisao-e-cerebro-vieses-cognitivos-lideranca/

#### Relatórios e inteligência

* https://www.europol.europa.eu/newsroom/news/new-2026-iocta-highlights-sophisticated-tactics
* https://www.amnesty.org/en/latest/news/2021/07/the-pegasus-project/
* https://security.berkeley.edu/resources/phish-tank

#### Artigos científicos

* https://www.researchgate.net/publication/389274798_Ethical_AI_and_Privacy_Protection
* https://arxiv.org/html/2507.07406v1
* https://www.sciencedirect.com/science/article/pii/S0164121223002947

---

Ao longo do projeto, essas fontes foram utilizadas no NotebookLM para gerar respostas, comparar informações e construir uma visão integrada entre neurociência e cibersegurança.

---

## Engenharia de prompts e aprendizados

Durante o uso do NotebookLM, ficou claro que a forma como a pergunta é feita influencia diretamente a qualidade da resposta.

### Exemplo de evolução de prompt

**Prompt inicial:**
"Como o cérebro humano influencia decisões em segurança digital?"

**Problema:**
A resposta foi correta, mas muito geral e pouco aplicada.

**Refinamento:**
"Explique como o cérebro influencia decisões em segurança digital com exemplos práticos de phishing"

**Resultado:**
A resposta ficou mais clara, trazendo situações reais e facilitando o entendimento.

---

### Teste de prompts complexos

Também foi feito um teste utilizando múltiplos comandos ao mesmo tempo, como explicar melhor, resumir e simplificar para iniciantes.

Durante esse teste, houve uma falha na resposta, que posteriormente identifiquei como um problema de conexão e não do sistema em si.

Mesmo assim, o experimento mostrou que prompts muito carregados podem dificultar a interpretação e a qualidade das respostas.

A partir disso, passei a dividir as perguntas em etapas, o que melhorou significativamente os resultados.

---

### Principais aprendizados

* prompts mais específicos geram respostas melhores
* dividir perguntas em etapas melhora o resultado
* exemplos práticos aumentam a compreensão
* testar diferentes abordagens faz parte do processo

---

## Miniguia de estudo

### Resumo

A segurança digital não depende apenas de tecnologia, mas também da forma como as pessoas pensam e tomam decisões.

O cérebro tende a agir de forma rápida e automática, e isso é explorado em golpes digitais que utilizam urgência, medo e recompensa para induzir decisões impulsivas.

---

### Como o comportamento é explorado

* decisões rápidas sem análise
* influência de emoções como medo e urgência
* confiança em autoridades e marcas conhecidas
* busca por recompensa imediata

---

### Vieses cognitivos

* viés de autoridade
* aversão à perda
* efeito de familiaridade
* excesso de confiança

---

### Fatores de risco

* cansaço mental
* excesso de informação
* estresse
* comportamento automático

---

### Como reduzir erros

* pausar antes de clicar ou agir
* usar autenticação em duas etapas (MFA)
* evitar reutilização de senhas
* desconfiar de mensagens urgentes ou emocionais

---

### Glossário

* Engenharia social: manipulação psicológica para obter informações
* Phishing: tentativa de enganar usuários para roubar dados
* Viés cognitivo: padrão de pensamento que pode levar a erros de decisão
* Fadiga cognitiva: cansaço mental que afeta a capacidade de análise
* MFA: método de segurança que exige mais de uma forma de verificação

---

### Prompts reutilizáveis

* explique com exemplos práticos
* resuma em tópicos
* explique como se eu fosse iniciante
* compare teoria com situações reais
* liste riscos e soluções

---

## Conclusão

A principal conclusão é que a segurança digital não é apenas um problema técnico.

O comportamento humano tem um papel central nesse processo, e entender como as pessoas pensam pode ser tão importante quanto qualquer ferramenta de proteção.

---

## Aplicação prática

Esse estudo pode ser aplicado em treinamentos de segurança, desenvolvimento de sistemas mais intuitivos e na criação de estratégias que considerem o comportamento humano como fator central da cibersegurança.

