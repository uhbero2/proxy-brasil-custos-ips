# proxy brasileiro: como escolher IPs do Brasil, comparar preço por GB e configurar em minutos

Quem pesquisa “proxy brasileiro” quase nunca quer uma aula sobre redes. Quer resolver uma das três coisas abaixo:

- ver o preço, o frete ou o anúncio exatamente como um usuário em São Paulo vê;
- rodar automação ou scraping em Mercado Livre, Amazon.com.br, Magazine Luiza ou portais de notícias sem levar bloqueio;
- manter contas e testes com um IP local que não pareça “estrangeiro”.

VPN não resolve bem nenhum desses casos. VPN desvia o tráfego do dispositivo inteiro, trabalha com um número limitado de IPs compartilhados e costuma ser detectada rápido por sistemas anti-bot. Proxy faz outra coisa: manda só o tráfego que você escolher por um IP específico, com rotação ou sessão fixa, e normalmente por GB consumido.

A diferença prática é essa. Se você precisa de um IP brasileiro para tarefa técnica, é proxy. Se só quer assistir a um catálogo fechado, VPN é mais simples.

## Onde um IP brasileiro realmente muda o resultado

Não é todo projeto que precisa de saída no Brasil. Estes precisam:

**Preço e estoque local.** Marketplaces brasileiros ajustam valor, frete e disponibilidade por região e por sessão. Coletar de fora entrega uma versão incompleta da página, às vezes com preço em outra moeda ou indisponível para o CEP consultado.

**Verificação de anúncio.** Anunciante só descobre se a campanha aparece para quem está em Curitiba ou Recife se olhar a página com um IP dessas cidades. Geolocalização de navegador não substitui IP.

**SERP local.** Ranking no Google.com.br muda conforme a cidade de origem. Monitoramento de SEO que roda de servidor nos EUA mede um resultado que o cliente brasileiro não vê.

**Social e app.** Instagram, TikTok e APIs mobile tratam IP de datacenter estrangeiro como suspeito quase instantaneamente. IP residencial ou móvel brasileiro passa com muito menos atrito.

**QA e teste de localização.** Verificar se o site carrega certo com o fuso, o idioma e as regras de exibição do Brasil antes de subir.

## Os quatro tipos de proxy brasileiro

Cada tipo resolve um problema diferente, e o preço por GB muda bastante entre eles.

- **Residencial:** IPs de conexões domésticas reais, alocados por ISPs. É o tipo mais confiável contra anti-bot e o mais usado em scraping e verificação de anúncios. Compromisso: menos estável que datacenter.
- **Datacenter:** rápido e barato, ótimo para volume alto em sites que não bloqueiam faixas de datacenter. Em plataformas com proteção agressiva, cai rápido.
- **Mobile (3G/4G/5G/LTE):** IPs de operadoras. É o tipo com maior confiança, indicado quando o alvo combina fingerprint de dispositivo e rede móvel. Também o mais caro.
- **Residencial premium:** mesma origem residencial, mas com IPs filtrados, latência menor e todos os filtros de segmentação incluídos no preço.

DataImpulse trabalha com os quatro. Uma limitação que vale saber antes de comprar: **não há proxy ISP/estático** no catálogo. Se o objetivo é gerenciar muitas contas com um IP fixo e permanente por perfil, esse não é o produto — reviews de terceiros apontam a mesma coisa, e provedores com linha ISP dedicada atendem melhor esse caso específico.

## Quantos IPs brasileiros entram no pool

Em vez de repetir o número global de 90 milhões de IPs em 195 países, vale olhar o recorte do Brasil.

No momento da consulta, a página de **proxies residenciais premium para o Brasil** da DataImpulse exibia cerca de 41 mil IPs ativos em tempo real, com aproximadamente 588 mil IPs únicos nos 30 dias anteriores e 81 mil nas últimas 24 horas. A página de **proxies datacenter no Brasil** mostrava algo em torno de 2,9 mil IPs ativos e 18,6 mil IPs únicos em 30 dias.

Esses números são dinâmicos e mudam de um dia para o outro, então trate como ordem de grandeza, não como estoque garantido. O pool padrão (não premium) não publica contagem por país; ele opera sobre a base global com segmentação por país incluída, e é aí que entram as cidades e estados.

## Quanto custa um proxy brasileiro

O mercado cobra em média de US$ 3 a US$ 8 por GB em proxies residenciais, com mensalidade embutida na maioria dos casos. A DataImpulse posiciona o produto padrão em **US$ 1 por GB**, sem assinatura, com o tráfego comprado não expirando — a mesma característica que a TechRadar destacou como o principal diferencial da empresa em relação a concorrentes como Bright Data, Oxylabs e Decodo.

O restante da tabela de preços:

| Tipo | Faixa de preço | Modelo |
| --- | --- | --- |
| Residencial padrão | US$ 1,00/GB | Pagamento conforme o uso |
| Datacenter | US$ 0,50/GB | Pagamento conforme o uso |
| Mobile (4G/5G) | US$ 2,00/GB | Pagamento conforme o uso |
| Residencial premium | US$ 5,00/GB | Pagamento conforme o uso |
| Volume a partir de 1 TB | US$ 0,80/GB (residencial) | Desconto por volume |

Uma análise independente da grade observou que ela é plana entre 5 GB e cerca de 700 GB: o preço só cai de fato ao atingir 1 TB. Ou seja, 50 GB custam US$ 50 e 200 GB custam US$ 200 — não existe recompensa intermediária por “comprometer” mais de uma vez.

👉 Conferir a grade de preços residencial atual

## Todos os planos disponíveis hoje

O catálogo completo, com os quatro tipos de proxy e todos os níveis publicados na página oficial. A cobrança é feita uma vez, por pacote de tráfego — não há ciclo mensal recorrente nem renovação automática.

| Tipo de proxy | Plano | Tráfego incluído | Preço | Por GB | Link |
| --- | --- | --- | --- | --- | --- |
| Residencial | Intro | 5 GB | US$ 5 | US$ 1,00 | Testar o plano Intro residencial |
| Residencial | Basic | 50 GB | US$ 50 | US$ 1,00 | Ver o plano Basic residencial |
| Residencial | Advanced | 1 TB | US$ 800 | US$ 0,80 | Comparar o plano Advanced |
| Residencial | Custom | 5 TB ou mais | a partir de US$ 4.000 | sob consulta | Pedir cotação residencial |
| Datacenter | Intro | 10 GB | US$ 5 | US$ 0,50 | Testar o plano Intro datacenter |
| Datacenter | Basic | 100 GB | US$ 50 | US$ 0,50 | Ver o plano Basic datacenter |
| Datacenter | Advanced | 1 TB | US$ 450 | US$ 0,45 | Comparar o plano Advanced datacenter |
| Datacenter | Custom | 5 TB ou mais | a partir de US$ 2.250 | sob consulta | Pedir cotação datacenter |
| Mobile | Intro | 2,5 GB | US$ 5 | US$ 2,00 | Testar o plano Intro mobile |
| Mobile | Basic | 25 GB | US$ 50 | US$ 2,00 | Ver o plano Basic mobile |
| Mobile | Advanced | 1 TB | US$ 1.600 | US$ 1,60 | Comparar o plano Advanced mobile |
| Mobile | Custom | 5 TB ou mais | a partir de US$ 8.000 | sob consulta | Pedir cotação mobile |
| Residencial premium | Intro | 1 GB | US$ 5 | US$ 5,00 | Testar o plano premium |
| Residencial premium | Basic | a partir de 10 GB | US$ 50 | US$ 5,00 | Ver o plano Basic premium |
| Residencial premium | Custom | 1.000 GB ou mais | US$ 4.000 | US$ 4,00 | Pedir cotação premium |

Todos os planos compartilham a mesma estrutura: tráfego que não expira, sem assinatura, segmentação por país incluída, acesso por API, autenticação por IP, suporte 24/7 e sessões rotativas e fixas. Os níveis Basic em diante acrescentam suporte humano contínuo; Advanced e Custom incluem gerente de conta dedicado.

## Como configurar a saída pelo Brasil

A configuração é a mesma para qualquer linguagem, e não exige instalar nada.

- **Rotativo:** toda requisição sai por um IP novo. HTTP/HTTPS na porta 823, SOCKS5 na 824.
- **Sessão fixa (sticky):** o mesmo IP se mantém por um período definido em portas entre 10000 e 20000. A duração varia de 1 a 120 minutos, com padrão de 30 minutos quando nenhum intervalo é informado.

O país entra no login ou no endpoint. Exemplo mínimo em Python:

python
login = 'seu_login'
password = 'sua_senha'
hostname = 'gw.dataimpulse.com'
port = 823

proxies = {
    'http': f'http://{login}:{password}@{hostname}:{port}',
    'https': f'http://{login}:{password}@{hostname}:{port}'
}


Para direcionar ao Brasil, a seleção de país é adicionada nas credenciais do usuário na área de controle da conta, e o mesmo vale para cidade, estado, CEP e ASN nos planos que suportam esses filtros.

Um detalhe técnico que economiza tempo: existem dois formatos de endpoint, um para rotação automática e outro para sessão presa. Se o alvo tem login ou carrinho, sticky resolve; se é coleta de páginas públicas em massa, rotação é mais eficiente e reduz a chance de estourar limite do site.

👉 Criar conta e testar com 5 GB

## As armadilhas de custo que não aparecem na landing page

**Segmentação por cidade custa mais no plano padrão.** A própria DataImpulse descreve no blog de preços que o direcionamento por país está incluído, enquanto cidade e ASN são complementos pagos — e a referência pública de mercado para esse extra é o dobro da tarifa por GB. Se o projeto precisa de São Paulo, Rio ou CEP específico, faça a conta com tarifa dobrada, ou considere o residencial premium, onde todos os filtros entram no preço. Vale confirmar com o suporte antes de fechar um orçamento grande.

**O mínimo de compra sobe depois da primeira recarga.** O primeiro depósito pode ser de US$ 5, que dá 5 GB residenciais ou 10 GB de datacenter. A partir da segunda compra, reviews independentes relatam mínimo de US$ 50. Como o tráfego não expira, isso é questão de caixa, não de prazo — mas significa que a menor recarga seguinte equivale a 50 GB residenciais, 25 GB mobile ou 100 GB datacenter.

**Os preços são em dólar.** Conversão e impostos de cartão entram na sua conta, não na deles.

**Não é o fornecedor certo para bancos e órgãos públicos.** O próprio material da empresa posiciona o produto para dados públicos e acesso a conteúdo, não para contornar verificações de instituições financeiras ou sistemas governamentais. Também não há scraper API totalmente gerenciada: quem não é técnico vai achar a plataforma enxuta demais.

## LGPD e o que continua sendo responsabilidade sua

A Lei Geral de Proteção de Dados se aplica ao que você coleta, não ao proxy. Rodar a coleta por um IP brasileiro não muda a natureza dos dados que passam por ali.

Na prática: dado público agregado, pesquisa de preço, verificação de anúncio e monitoramento de reputação costumam ser usos legítimos; contornar autenticação, acessar área restrita ou copiar base protegida não são, e os termos de uso do site-alvo continuam valendo. Se o projeto lida com dado pessoal, o tratamento precisa seguir o que a LGPD exige independentemente da infraestrutura usada.

Do lado do fornecedor, a DataImpulse afirma operar com pool próprio obtido via consentimento dos usuários, sem revenda de rede de terceiros. É a alegação da empresa, e vale como ponto de partida de due diligence, não como garantia.

## Perguntas que aparecem antes da compra

**Proxy brasileiro funciona no Mercado Livre e na Amazon.com.br?** Sim, é o tipo de alvo para o qual proxies residenciais e mobile são indicados. Datacenter tende a durar pouco nessas plataformas.

**Dá para escolher cidade?** Sim, com filtro de cidade, estado, CEP e ASN — pago como extra no residencial padrão e incluído no premium.

**Preciso de assinatura mensal?** Não. O modelo é pagamento conforme o uso, e o tráfego comprado não expira.

**O tráfego não usado se perde no fim do mês?** Não. Esse é justamente o argumento central do provedor, e um review da TechRadar tratou a característica como o que mais separa a empresa da média do mercado.

**Qual tipo escolher para começar?** Datacenter se os alvos não bloqueiam faixas de datacenter e o volume é alto. Residencial na maioria dos projetos sérios. Mobile só onde residencial falha, porque custa o dobro do residencial por GB.

**Existe reembolso?** Há política de 7 dias para novos usuários, conforme a avaliação da AIMultiple. Confirme as condições atuais com o suporte, porque esse tipo de regra muda.

## Vale a pena no seu caso?

A conta é simples. Se você gasta menos de 50 GB por mês, pagar US$ 1/GB sem mensalidade costuma sair mais barato do que qualquer plano por assinatura, porque você não paga por pacote que não termina. É o que a comparação da webscraping.ai concluiu ao apontar esse como o ponto de virada entre os dois modelos.

Se o projeto precisa de direcionamento fino por cidade, tráfego de missão crítica e estabilidade acima da média, o residencial premium a US$ 5/GB com todos os filtros incluídos pode compensar o salto de preço. E se o que você precisa é um IP fixo por perfil de conta, não force: nenhum dos quatro tipos resolve bem esse caso.

Fora isso, um IP brasileiro de qualidade começa com um teste pequeno. Com 5 GB você mede a taxa de sucesso nos seus alvos reais — que é o número que importa, não o preço de tabela.

👉 Começar com 5 GB e testar nos seus alvos
