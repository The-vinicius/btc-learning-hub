# 📚 Recursos sobre Bitcoin em Português (BR)

Uma curadoria de links, vídeos, artigos, podcasts e ferramentas para aprender e usar Bitcoin em português. Livre de shitcoins. Sempre em construção.

---

## 🟠 1. Por onde começar
- Introduções, guias rápidos e vídeos para iniciantes

## 📖 2. Conteúdo de aprofundamento

### 2.1 Vídeos
- [Bitcoin e a Ameaça Quântica (Um Dossiê Técnico)](https://www.youtube.com/watch?v=DgEqFPc24C4)
### 2.2 Leituras online
### 2.3 Livros

- [Mastering Bitcoin: Programming the Open Blockchain (3rd Edition) - por Andreas M. Antonopoulos, David A.](https://github.com/bitcoinbook/bitcoinbook)
  
### 2.4 Cursos
- [Jornada para aprender sobre o blockchain do Bitcoin](https://www.youtube.com/watch?v=vXPlzLNIObs&list=PLmDINmHIqrRon7iFo3p0bdZDMYoZ3lKUV)
### 2.5 Podcasts e áudios

## 💬 3. Comunidade

### 3.1 Fóruns e grupos
### 3.2 Telegram / Discord
### 3.3 Eventos e Meetups
### 3.4 Repositórios

- [Lightning Network Limitations – por renepickhardt](https://github.com/renepickhardt/Lightning-Network-Limitations)  
  Repositório contendo Notebooks e artigos que investigam as limitações técnicas do protocolo da Lightning Network do Bitcoin, com foco na escalabilidade de pagamentos. O conteúdo é voltado para análises teóricas e práticas sobre gargalos e restrições da rede.

## 🛠️ 4. Tutoriais e Ferramentas

### 4.1 Full node
### 4.2 Lightning Network
### 4.3 Autocustódia e privacidade

## 💰 5. Como adquirir Bitcoin

### 5.1 P2P / Off-Exchange

- [Spike to Spike](https://spiketospike.com/)
  Plataforma P2P para negociação privada de Bitcoin (BTC) e Tether (USDT)
  
### 5.2 Exchanges com custódia
### 5.3 Serviços sem KYC

**KYCNotMe**: Inúmeros serviços sem KYC - [Site](https://kycnot.me/)


## 🧾 6. Bitcoin para empresas e autônomos

## 🛒 7. Onde gastar Bitcoin no Brasil

## 📚 8. Glossário essencial

Esta seção define termos e conceitos essenciais nos ecossistemas do Bitcoin e da Lightning Network. Está dividida em duas subseções: Fundamentos do Bitcoin (8.1) e Tecnologia da Lightning Network (8.2). Seja você iniciante ou alguém buscando aprofundar seu conhecimento, este glossário é sua referência principal.

---

### 8.1 Bitcoin

**Bitcoin (BTC):**  
Uma moeda digital descentralizada inventada em 2008 por Satoshi Nakamoto. Permite transações ponto a ponto sem intermediários, protegida por criptografia e registrada em um livro-razão público chamado blockchain.

**Satoshi Nakamoto:**  
O(s) criador(es) pseudônimo(s) do Bitcoin. Sua identidade permanece desconhecida até hoje.

**Blockchain:**  
Um livro-razão digital somente de adição, criptograficamente seguro e composto por blocos. Cada bloco contém uma lista de transações e está vinculado ao bloco anterior por meio de um hash.

**Bloco:**  
Um contêiner para um lote de transações de Bitcoin, incluindo uma referência ao bloco anterior e um nonce usado na prova de trabalho.

**Bloco Gênesis:**  
O primeiro bloco da blockchain do Bitcoin, minerado por Satoshi Nakamoto em janeiro de 2009.

**Mineração:**  
O processo de criação de novos blocos por meio da resolução de cálculos computacionais complexos, verificação de transações e segurança da rede.

**Hashrate:**  
O poder computacional total usado pela rede Bitcoin para minerar e processar transações.

**Nonce:**  
Um número usado uma vez na mineração, ajustado pelos mineradores para encontrar um hash abaixo de uma determinada dificuldade alvo.

**Ajuste de Dificuldade:**  
Ocorre aproximadamente a cada 2.016 blocos (~2 semanas) para garantir que os blocos sejam minerados a cada 10 minutos, ajustando a dificuldade conforme o hashrate da rede.

**Halving:**  
Um evento a cada 210.000 blocos (~4 anos) que reduz pela metade a recompensa de bloco, diminuindo a emissão de novos bitcoins.

**Oferta Total:**  
Limitada a 21 milhões de bitcoins, garantindo escassez e desinflação ao longo do tempo.

**Chave Privada:**  
Um número secreto de 256 bits usado para assinar transações. Quem possui a chave privada controla os bitcoins associados.

**Chave Pública:**  
Gerada a partir da chave privada, é usada para derivar um endereço Bitcoin e validar assinaturas digitais.

**Endereço Bitcoin:**  
Uma versão hash da chave pública usada para receber pagamentos. Formatos incluem Legacy (P2PKH), Script (P2SH) e SegWit (Bech32).

**Carteira (Wallet):**  
Software ou hardware que armazena chaves privadas. Tipos incluem carteiras móveis, desktop, hardware, papel e web.

**Frase Semente (Seed Phrase):**  
Um backup legível por humanos da carteira, geralmente com 12 ou 24 palavras. Usada para recuperar chaves privadas.

**Transação (TX):**  
Uma mensagem digital assinada com uma chave privada que instrui a rede Bitcoin a transferir fundos.

**TXID (ID de Transação):**  
Um identificador único para uma transação Bitcoin, geralmente o hash dos dados da transação.

**Taxa (Taxa de Mineração):**  
Um valor pago aos mineradores para priorizar uma transação. As taxas são baseadas no tamanho em bytes, não no valor transferido.

**SegWit (Segregated Witness):**  
Uma atualização que separa os dados de assinatura dos dados da transação, reduzindo o tamanho da transação e melhorando a escalabilidade.

**Taproot:**  
Uma grande atualização que melhora a privacidade, eficiência e funcionalidades de contratos inteligentes, habilitando assinaturas Schnorr e MAST (Merkelized Abstract Syntax Trees).

**Bech32:**  
Um formato de endereço compatível com SegWit, começando com “bc1”, que melhora a detecção de erros e a eficiência.

**Multisignature (Multisig):**  
Uma configuração que requer múltiplas chaves privadas para autorizar uma transação Bitcoin (ex: 2 de 3).

**Time Lock / Timelock:**  
Um script que restringe quando uma transação pode ser gasta. Usado em contratos inteligentes e na Lightning Network.

**Bloco Órfão:**  
Um bloco válido que não é incluído na cadeia principal porque outro bloco foi aceito na mesma altura.

**Poeira (Dust):**  
Uma quantidade de Bitcoin muito pequena para ser gasta, pois a taxa superaria o valor transferido.

**Transação Coinbase:**  
A primeira transação de um bloco, criada pelo minerador, que inclui a recompensa do bloco.

**Endereço de Troco:**  
Um endereço usado para retornar o Bitcoin restante ao remetente após uma transação, semelhante ao troco em dinheiro.

**RBF (Replace-by-Fee):**  
Permite que uma transação seja reenviada com uma taxa maior para acelerar a confirmação.

**CPFP (Child Pays for Parent):**  
Um método de aumento de taxa onde uma nova transação (filha) incentiva os mineradores a confirmar uma transação pai com baixa taxa.

**Nó Completo (Full Node):**  
Um nó que valida totalmente todas as transações e blocos do Bitcoin. Ajuda a impor as regras de consenso da rede.

**Nó Podado (Pruned Node):**  
Um nó completo que descarta dados antigos de blocos após a validação para economizar espaço.

**SPV (Verificação Simplificada de Pagamentos):**  
Um método leve de verificação de transações sem baixar toda a blockchain, usado por carteiras móveis.

**Armazenamento a Frio (Cold Storage):**  
Manter chaves privadas offline para proteger contra hackers, geralmente usando carteiras de hardware ou papel.

---

### 8.2 Lightning Network

**Lightning Network (LN):**  
Uma solução de escalabilidade de segunda camada construída sobre o Bitcoin que permite transações rápidas, de baixo custo e fora da blockchain principal, por meio de canais de pagamento bidirecionais.

**Canal de Pagamento:**  
Um acordo temporário fora da cadeia entre duas partes que permite múltiplas transações. Apenas a abertura e o fechamento são registradas na blockchain.

**Transação de Compromisso:**  
Uma transação que representa o estado atual de um canal Lightning. Cada atualização cria uma nova transação de compromisso assinada por ambas as partes.

**Chave de Revogação:**  
Um mecanismo que permite a uma parte invalidar um estado anterior do canal, usado para punir tentativas de fraude.

**HTLC (Contrato de Bloqueio com Hash e Tempo):**  
Usado para roteamento de pagamentos de forma segura na Lightning, combinando hashlocks e timelocks.

**Nó de Roteamento:**  
Um nó da Lightning que retransmite pagamentos entre outros nós em troca de uma pequena taxa.

**Hop:**  
Cada nó intermediário pelo qual um pagamento Lightning passa antes de chegar ao destinatário.

**Reserva de Canal:**  
A quantidade mínima de satoshis que um usuário deve manter em um canal, impedindo encerramentos não cooperativos.

**Limite de Poeira:**  
A quantidade mínima de satoshis que pode ser incluída em uma atualização de canal para evitar saídas economicamente inviáveis.

**Fatura (Invoice):**  
Uma string codificada em BOLT11 que especifica o valor, tempo de expiração, dicas de roteamento e hash de pagamento.

**Preimage:**  
Um valor secreto usado para desbloquear um pagamento HTLC. Revelar o preimage comprova que o pagamento foi efetuado.

**Onion Routing:**  
Uma técnica de privacidade usada na Lightning para ocultar o caminho completo de um pagamento, criptografando as instruções de cada hop.

**Protocolo Sphinx:**  
O protocolo criptográfico que permite o onion routing na Lightning.

**Saídas Âncora (Anchor Outputs):**  
Um mecanismo que permite aos participantes de canal anexar taxas de transação posteriormente, tornando a estimativa de taxa mais flexível.

**Canais Taproot:**  
Futuros canais Lightning utilizando os recursos de privacidade e eficiência do Taproot.

**Canais de Financiamento Duplo:**  
Canais Lightning onde ambos os participantes contribuem com fundos na fase de abertura, melhorando a liquidez bilateral.

**Splicing:**  
Recurso proposto que permite adicionar ou remover fundos de um canal sem fechá-lo.

**Watchtower:**  
Um serviço que monitora a blockchain em nome de nós Lightning offline para detectar e punir fraudes.

**Backup Estático de Canal (SCB):**  
Um arquivo que permite a recuperação de fundos Lightning se um nó ou carteira for perdido. Armazena informações sobre parceiros de canal e saldos.

**Política de Taxas:**  
A estratégia de um nó de roteamento para cobrar taxas fixas e proporcionais ao encaminhar pagamentos.

**Taxa Base:**  
Uma taxa fixa em satoshis cobrada por pagamento, independentemente do valor.

**Taxa Proporcional:**  
Uma taxa percentual cobrada com base no valor encaminhado (ex: 0,01%).

**Gestão de Liquidez:**  
A prática de equilibrar a capacidade de entrada e saída nos canais para manter a capacidade de roteamento.

**Loop (Lightning Loop):**  
Um serviço que permite trocas não-custodiais entre Lightning e Bitcoin on-chain para gerenciar liquidez.

**Amboss / 1ML / Terminal Web:**  
Ferramentas populares para visualizar a topologia e estatísticas de nós da Lightning Network.

**LSP (Provedor de Serviço Lightning):**  
Um serviço que oferece liquidez, gerenciamento de canais ou suporte de infraestrutura para usuários ou comerciantes na Lightning Network.

**BOLT (Basis of Lightning Technology):**  
Um conjunto padronizado de especificações para implementações Lightning, garantindo interoperabilidade.

**Canais Zero-Conf:**  
Canais usados imediatamente após o financiamento, sem esperar confirmações on-chain — mais arriscado, mas mais rápido.

**Canal Wumbo:**  
Um canal maior que o limite padrão de 0,167 BTC, usado por usuários avançados ou serviços de grande escala.

## 👶 9. Bitcoin para crianças e famílias

## 🙋 10. Como contribuir com esta lista
