Requisitos não funcionais da Steam – uma olhada realista
Os requisitos não funcionais são o que realmente faz (ou quebra) um sistema gigante como a Steam. Não adianta ter mil joguinhos bonitinhos se o negócio cai toda hora, demora uma eternidade pra baixar ou vaza dados dos usuários.
Performance
A Steam lida com milhões de pessoas conectadas ao mesmo tempo, jogos que passam fácil de 100 GB e aqueles picos insanos de acessos nas promoções de verão, inverno, Halloween, etc.
O que eles fazem pra aguentar o tranco:

CDN espalhada pelo mundo inteiro (o conteúdo vem de um servidor pertinho de você)
Balanceamento de carga decente
Muitos servidores em várias regiões
Cache pesado pra não ficar perguntando a mesma coisa mil vezes

Na prática? Durante as grandes promoções rola uma lentidão aqui e ali na loja, fila de compra demora um pouquinho mais, mas o sistema quase nunca tomba de verdade. É aquele tipo de lentidão que a gente já espera e perdoa.
Nota: sólida, com tropeços previsíveis em dias de loucura total.
Escalabilidade
Aqui a Steam manda muito bem. Conforme vão chegando mais usuários e mais jogos, eles simplesmente adicionam mais máquinas, replicam serviços, jogam mais pontos de CDN no mapa. Parece que a arquitetura foi pensada desde cedo pra crescer sem precisar virar tudo do avesso.
É o clássico caso de sistema que escala horizontalmente e respira aliviado quando precisa crescer.
Nota: muito boa, preparada pra continuar dominando o mercado por anos.
Disponibilidade
A plataforma fica no ar 24 horas por dia, todo dia, no mundo inteiro. Quase nunca acontece uma queda total. Quando tem manutenção, normalmente avisam antes e fazem de madrugada. Às vezes algum pedaço específico (tipo o mercado de itens ou o chat) dá problema por algumas horas, mas é raro ver a loja inteira fora do ar.
Eles investem pesado em redundância, servidores espalhados e monitoramento 24/7.
Nota: bem alta, com falhas pontuais que não chegam a ser catastróficas.
Segurança
A Steam guarda coisas sensíveis: dados pessoais, cartão de crédito, inventário de skins que valem centenas (às vezes milhares) de reais.
O que eles usam pra proteger:

Criptografia em vários pontos
Steam Guard (2FA) bem implementado
Sistema antifraude que bloqueia coisas estranhas rapidinho
Confirmação de novos dispositivos
Controle rígido no mercado interno (trade holds, autenticação em troca, etc.)

Claro que tanta proteção às vezes irrita — confirmação extra, espera de 15 dias em trades grandes —, mas considerando o volume de golpes que rola nesse mercado, faz sentido.
Nota: segurança bem levada a sério, na medida certa pro risco que o negócio tem.
Usabilidade
A interface da Steam é daquelas que quem usa todo dia acha super prática, mas quem abre pela primeira vez pode levar um susto.
O que funciona bem:

Biblioteca organizada por vários critérios
Busca rápida e filtros úteis
Integração com amigos, chat, conquistas, tudo num lugar só

O que pesa contra:

Tela inicial lotada de coisas (notificações, destaques, promoções, wishlist, amigos jogando…)
Muita funcionalidade espremida no mesmo cliente
Alguns menus ainda parecem de 2010

Resumo: quem já pegou o jeito ama, mas novato pode achar confuso e meio sobrecarregado no começo.
Resumindo
A Steam é um monstro bem construído. Ela aguenta pancada, cresce sem desespero, quase nunca cai de verdade, protege os dados e o dinheiro dos usuários com unhas e dentes e, mesmo não sendo a interface mais sexy do mundo, entrega o que a maioria dos jogadores precisa no dia a dia.
Os requisitos não funcionais claramente são prioridade lá dentro — e isso explica por que, depois de tantos anos, ela continua sendo a principal plataforma de PC gaming no mundo
