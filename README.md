<p align="center">
  <img src="media/logo.png" width="260">
</p>

<h1 align="center">SIMEI</h1>

<p align="center">
  <b>Sistema Inteligente para Manobras Elétricas Industriais</b>
</p>

<p align="center">
  <b>v0.1.0</b> • 🚧 Em desenvolvimento
</p>

---

# 📖 Visão Geral

O **SIMEI (Sistema Inteligente para Manobras Elétricas Industriais)** é uma plataforma didática desenvolvida para o treinamento de procedimentos operacionais em instalações elétricas industriais.

O objetivo do projeto é permitir que operadores executem sequências de manobra em um ambiente seguro, compreendam a lógica dos intertravamentos elétricos e recebam feedback imediato durante a operação, sem qualquer interferência em instalações reais.

---

# ⚠️ O Problema

O treinamento prático de manobras elétricas normalmente apresenta limitações relacionadas à disponibilidade das instalações, aos requisitos de segurança e à necessidade de acompanhamento de profissionais experientes.

Esses fatores reduzem as oportunidades de treinamento prático e dificultam o desenvolvimento da experiência operacional necessária para a execução segura dos procedimentos.

---

# 💡 Solução Proposta

O SIMEI utiliza uma bancada didática para reproduzir cenários operacionais de maneira segura e controlada.

Nesta primeira versão, o sistema já é capaz de:

- Interpretar comandos enviados pelo operador;
- Validar a sequência de manobras por meio de intertravamentos;
- Representar visualmente o estado dos dispositivos;
- Emitir sinalização sonora em condições de erro;
- Fornecer feedback operacional em tempo real.

---

# 🎥 Demonstração

A primeira validação física do **SIMEI v0.1.0** foi concluída com sucesso.

A demonstração apresenta a execução da sequência operacional, a resposta dos dispositivos da bancada e a atuação da lógica de intertravamentos.

🔗 **Primeira validação física:**

https://www.linkedin.com/posts/juan-arins-232a10224_engenhariaelaeztrica-automaaexaetoindustrial-ugcPost-7486192123768320001-6Iyo/

---

# 🚀 Roadmap

## ✅ Concluído

- Estrutura inicial do projeto;
- Arquitetura do sistema;
- Identidade visual;
- Firmware inicial;
- Comunicação Serial;
- Lógica de intertravamentos;
- Modos de operação guiado e avaliação;
- Feedback visual e sonoro;
- Montagem do primeiro protótipo físico;
- Primeira validação física;
- Documentação técnica;
- Organização do repositório.

## 🔄 Próximas etapas

- Desenvolvimento da Interface Homem-Máquina (IHM);
- Integração entre a IHM e o protótipo físico;
- Expansão dos cenários operacionais;
- Simulação de posição de TAP;
- Simulação de tensão e corrente;
- Validação das condições de paralelismo entre transformadores;
- Registro das operações executadas;
- Evolução da plataforma para ESP32.

---

# 🛠 Tecnologias Utilizadas

- Arduino Uno;
- Linguagem C++;
- Comunicação Serial.

---

# 📂 Estrutura do Projeto

```text
SIMEI/
│
├── docs/
│   ├── Diário de Bordo
│   ├── Especificação Técnica do Protótipo
│   └── Levantamento de Materiais
│
├── media/
│   ├── logo.png
│   └── SIMEI.mp4
│
└── README.md
```

---

# 📚 Documentação

O desenvolvimento do projeto é acompanhado por meio de documentação contínua, incluindo:

- Diário de Bordo;
- Especificação técnica do protótipo;
- Levantamento de materiais;
- Registro das etapas de desenvolvimento;
- Demonstrações do sistema.

---

# 👨‍💻 Desenvolvedor

**Juan Augusto Budal Arins Teixeira**

Graduando em Engenharia Elétrica.

Projeto pessoal voltado ao desenvolvimento de soluções didáticas para treinamento operacional em instalações elétricas industriais.

🔗 **LinkedIn**

https://www.linkedin.com/in/juan-arins-232a10224/

---

# 📌 Status do Desenvolvimento

| Etapa | Status |
|:-------------------------------|:------:|
| Planejamento | ✅ |
| Arquitetura inicial | ✅ |
| Firmware inicial | ✅ |
| Protótipo físico | ✅ |
| Validação física | ✅ |
| Interface Homem-Máquina | ⏳ |
| Expansão dos cenários | ⏳ |
| Testes integrados | ⏳ |

**Legenda**

- ✅ Concluído
- 🚧 Em desenvolvimento
- ⏳ Planejado

---

**Versão atual:** `v0.1.0`

A primeira validação física foi concluída. O projeto segue para a etapa de desenvolvimento da Interface Homem-Máquina (IHM) e expansão dos cenários operacionais.