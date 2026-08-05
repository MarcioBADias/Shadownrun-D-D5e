# Sistema de Matrix, Combate Digital e Inteligências Artificiais (D&D 5e / Shadowrun)

A **Matrix** é o oceano global de dados onde a informação é luz, código e presença digital. Para a maioria dos cidadãos, a Matrix é acessada por meio da Realidade Aumentada (AR) através de visores e *Commlinks*. Mas para **Deckers** e **Technomancers**, a Matrix é explorada via Realidade Virtual de Imersão Total (VR Hot-Sim), onde a mente física é projetada diretamente no ciberespaço.

Este documento detalha o funcionamento da rede, as regras de combate digital, os softwares utilitários/ofensivos, os itens cibernéticos da rede e o sistema completo de **Agentes de IA (Inteligências Artificiais)**.

---

## 1. A Estrutura da Matrix e Níveis de Acesso

Ao entrar na Matrix em modo VR, o mundo físico desaparece e o Decker assume a forma de um **Avatar Digital**. Sistemas e servidores são representados como arquiteturas virtuais (Host Corporativos, Fortalezas de Dados, Grids da Cidade).

### Marcadores de Acesso (MARKS)
Para interagir, roubar dados ou alterar nós de rede, o Decker precisa obter **MARKS** (Marcos de Autorização) no sistema alvo:

* **1 MARK (Acesso de Visitante/Usuário):** Permite ler arquivos públicos, monitorar câmeras sem controle e executar varreduras.
* **2 MARKS (Acesso de Operador/Segurança):** Permite desligar alarmes, alterar comandos de dispositivos e alterar permissões de portas.
* **3 MARKS (Acesso de Administrador/Root):** Permite reformatar o sistema, apagar registros, desligar a rede inteira e ejetar outros usuários.

> **Obtendo MARKS:** O Decker obtém MARKS usando a ação de **Invasão Discreta** (Teste de *Tecnologia* vs. Firewall do Host) ou via **Força Bruta** (Hacks de Combate).

---

## 2. Regras de Combate Digital (Cyber-Combat)

O combate no ciberespaço ocorre em tempo de execução ultra-rápido. Quando o alarme de segurança digital de um Host é acionado, a iniciativa entra em vigor.

### Atributos na Matrix
Enquanto estiver operando em VR na Matrix, seus atributos biológicos normais são substituídos pela sua interface tecnológica:

* **Iniciativa Digital:** $\text{Iniciativa} = \text{Modificador de Inteligência} + \text{Bônus de Proficiência} + 1\text{d}20$.
* **Vida Digital (Pontos de Matriz / Matrix HP):** $\text{Matrix HP} = 10 + \text{Nível de Decker/Technomancer} + \text{Modificador de Inteligência}$.
* **Classe de Defesa Digital (Firewall CA):** $\text{CA Digital} = 10 + \text{Modificador de Inteligência} + \text{Bônus do Cyberdeck}$.

---

### Dano de Matriz vs. Dano Biocinético (Bio-Feedback)

Existem dois tipos de danos aplicados na Matrix dependendo do modo de conexão do hacker:

1. **Dano de Matriz (Matrix Damage):** Afeta a integridade dos programas, do Cyberdeck e dos dispositivos eletrônicos. Quando o *Matrix HP* de um dispositivo cai a 0, ele entra em curto-circuito e fica **Desativado (Brickado)**.
2. **Dano de Bio-Feedback (Choc Neural):** Ocorre quando o Decker está em imersão **VR Hot-Sim** (sem travas de segurança biológica). 
   * Quando o Decker sofre dano de Matriz enquanto em Hot-Sim, ele deve passar em um teste de resistência de **Constituição** ($\text{CD} = 10 + \text{metade do dano sofrido}$).
   * **Falha:** O Decker sofre metade daquele dano como **Dano Psíquico irredutível** no seu corpo físico devido ao choque elétrico direto no cérebro.

---

## 3. Catálogo de Itens e Dispositivos da Matrix

### Tabela de Dispositivos e Hardware de Rede

| Item | Função Principal | Atributo / Bônus | Custo (N$) |
| :--- | :--- | :---: | :---: |
| **Cyberdeck Novatech Hyper-6** | Terminal base para Hackers de Nível 1 ao 4. | +1 na CD de Hack / CA Digital 12 | 3.000 N$ |
| **Cyberdeck Fairlight Excalibur** | Terminal militar avançado para Níveis 5+. | +2 na CD de Hack / CA Digital 14 | 15.000 N$ |
| **Dongle de Criptografia Quântica** | Módulo acoplado ao Cyberdeck. | +2 em salvaguardas contra rastreamento. | 2.500 N$ |
| **Chip de Armazenamento Óptico (Terabyte)**| Armazena payloads de dados e roubos corporativos. | Capacidade massiva offline imune a escutas. | 500 N$ |
| **Transmissor de Sinal Direto (Direct-Link Cable)**| Cabo físico reforçado para invasão local. | Ignora a proteção wireless remota do host. | 300 N$ |

---

## 4. Livraria de Softwares e Execution Scripts

Programas de Hack são instalados no Cyberdeck e consumidos como **Programas Conhecidos / Slots de Hack** da classe Decker.

### 1. Softwares Utilitários e de Suporte

* **Stealth-Code (Software de Mascaramento):**
  * *Efeito:* Enquanto este software estiver ativo no seu Cyberdeck, o ICE de segurança e os Deckers inimigos têm **Desvantagem** em testes de *Investigação* ou *Tecnologia* para detectar sua presença na rede.
* **Decryptor Pro (Software de Quebra de Senha):**
  * *Efeito:* Concede **Vantagem** em testes para obter 1 MARK em um Host ou abrir arquivos protegidos por criptografia de dados.
* **Signal Booster (Amplificador de Banda):**
  * *Efeito:* Aumenta o alcance de execução de todos os seus Hacks de Combate à distância em +18 metros.

### 2. Softwares Ofensivos (Combat Scripts)

* **Black Hammer (Programa de Choque Neural):**
  * *Custo:* 1 Slot de Programa | *Alcance:* 18 metros
  * *Efeito:* Dispara um código destrutivo contra o avatar de um Decker ou IC inimigo. Faça uma jogada de ataque de Hack. Se atingir, causa **$2\text{d}8$ de dano de Matriz** e força o alvo a fazer um teste de Constituição; se falhar, sofre $1\text{d}8$ de dano Psíquico imediato por Bio-Feedback.
* **Data Spike (Pico de Dados):**
  * *Custo:* 1 Slot de Programa | *Alcance:* 24 metros
  * *Efeito:* Envia uma carga maciça de dados incorretos para a placa de rede de um dispositivo inimigo (arma inteligente, drone ou visor). O alvo sofre **$3\text{d}6$ de dano de Matriz**. Se este dano reduzir o *Matrix HP* do dispositivo a 0, o item é **Desativado (Brickado)** instantaneamente.
* **Wormhole (Injeção de Vírus Corrosivo):**
  * *Custo:* 2 Slots de Programa | *Alcance:* 18 metros
  * *Efeito:* Injeta um verme digital em um Host. No início de cada turno do Host ou do Decker inimigo afetado, ele sofre **$1\text{d}10$ de dano de Matriz contínuo** durante 1 minuto (pode tentar um teste de Inteligência no final do turno para expurgar o vírus).

---

## 5. Sistema Detalhado de Agentes de IA e IC (Inteligências Artificiais)

No ciberespaço de Shadowrun, existem duas categorias de inteligências virtuais: **IC (Intrusion Countermeasures / Gelo)**, que são os programas de defesa automatizados dos Hosts corporativos, e os **Agentes de IA (AI Companions)**, programas autônomos que o Decker compra ou programa para auxiliá-lo.

---

### Módulos e Regras de Agentes de IA (AI Companions)

Um Decker pode carregar e executar **1 Agente de IA** ativo em seu Cyberdeck por vez (a partir do 3º Nível). O Agente ocupa 2 Slots de Programa do Cyberdeck e possui sua própria iniciativa e ações no combate digital.

#### Bloco de Estatísticas Padrão do Agente de IA:
* **Matrix HP:** $15 + (5 \times \text{Nível do Decker})$
* **CA Digital:** $12 + \text{Modificador de Inteligência do Decker}$
* **Atributos:** Inteligência 16 (+3), Sabedoria 12 (+1), Destreza 14 (+2)
* **Ações no Combate:** O Agente age na sua mesma contagem de iniciativa digital. Você pode usar uma **Ação Bônus** para dar um comando genérico ao Agente (Atacar, Analisar, Defender).

---

### Tipos e Especializações de Agentes de IA

Ao adquirir ou programar um Agente de IA, você escolhe uma das seguintes matrizes de personalidade e função:

#### 1. Agente Sentinela (Shield-AI "Aegis")
* **Especialidade:** Defesa de rede e neutralização de ameaças.
* **Habilidade - Protocolo Firewall:** Como uma Reação quando o Decker for alvo de uma jogada de ataque de Hack ou programa inimigo, o Aegis se intercala, concedendo **+3 na CA Digital do Decker** ou absorvendo o dano no lugar do Decker.
* **Preço de Venda / Custo de Programação:** 5.000 N$ (Recursos: 2.500 N$ / Tempo: 10 dias).

#### 2. Agente Caçador (Attack-AI "Hunter")
* **Especialidade:** Combate ofensivo digital e caça de IC corporativo.
* **Habilidade - Disparo Paralelo:** O Hunter realiza um ataque de *Data Spike* ($1\text{d}8 + 3$ de dano de Matriz) por turno contra um alvo escolhido pelo Decker sem gastar os slots do Hacker.
* **Preço de Venda / Custo de Programação:** 6.500 N$ (Recursos: 3.250 N$ / Tempo: 13 dias).

#### 3. Agente Rastreador (Sniffer-AI "Snoop")
* **Especialidade:** Varredura de dados, descriptografia e obtenção de MARKS.
* **Habilidade - Auto-Invasão:** O Snoop pode realizar a ação de **Invasão Discreta** para obter MARKS em um Host ou dispositivo inimigo no seu turno utilizando o modificador de *Tecnologia* do Decker.
* **Preço de Venda / Custo de Programação:** 4.500 N$ (Recursos: 2.250 N$ / Tempo: 9 dias).

---

### Os Perigos da Matrix: Tipos de IC Corporativo (Gelo)

Quando um Decker falha em um hack dentro de um Host corporativo ou aciona um alarme, o sistema invoca programas de defesa autônomos conhecidos como **IC (Intrusion Countermeasures)**:

1. **IC Branco (White IC / Passive):** Tenta bloquear acessos, ejetar o Decker do sistema e trancar os arquivos. Não causa dano biológico.
2. **IC Cinza (Gray IC / Defensive):** Lança rajadas de dano de Matriz para quebrar o Cyberdeck do hacker e tenta localizá-lo fisicamente via endereço IP para mandar a segurança corporativa ao local real.
3. **IC Negro (Black IC / Lethal):** A maior ameaça das redes. Ignora as travas de segurança do Cyberdeck e ataca diretamente o sistema nervoso central do Decker via Bio-Feedback, podendo causar parada cardíaca ou morte cerebral no mundo físico.