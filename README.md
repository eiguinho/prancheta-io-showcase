# Prancheta.io | Football Management Simulator

> **Status do Projeto:** v1.0.0 (Produção) <br>
> **Live Demo:** [Prancheta.io](https://prancheta-io.vercel.app/)

**Prancheta.io** é um simulador de gerenciamento tático de futebol focado na imersão e na tomada de decisão estratégica em tempo real. Desenvolvido com **React**, **TypeScript** e **Vite**, o projeto resolve desafios complexos de gerenciamento de estado e simulação probabilística em ambiente web.

---

## O Produto

Diferente de simuladores estáticos, o Prancheta.io oferece um **Motor de Eventos Dinâmico** que processa variáveis de fadiga, moral do vestiário e atributos técnicos para gerar partidas imprevisíveis e emocionantes com narração minuto a minuto.

### Principais Funcionalidades:
- **Gestão Tática Interativa (Pitch View):** Interface visual para escalação e definição tática.
- **Simulação em Tempo Real:** Motor de eventos probabilísticos com narração dinâmica.
- **Multicompetições Automáticas:** Calendário inteligente gerenciando Série A e Libertadores simultaneamente.
- **Engine de Carreira:** Sistema de persistência para temporadas, conquistas e histórico de títulos.

---

## Engenharia de Software e Arquitetura

Este repositório funciona como um **Showcase Técnico**. O código-fonte principal é mantido de forma privada para proteção de propriedade intelectual, mas a arquitetura segue padrões rigorosos de engenharia:

### Tech Stack & Patterns:
- **React 19 & Vite:** Utilização das ferramentas mais recentes para um build otimizado e renderização veloz.
- **Separation of Concerns (SoC):** Lógica de negócio 100% isolada em Hooks Customizados (`useGameActions`), garantindo componentes de UI puros e declarativos.
- **Strategy Pattern:** Arquitetura flexível no motor de torneios para lidar com diferentes regras de competição (Pontos Corridos vs Mata-mata).
- **Imutabilidade Estrita:** Gerenciamento de estado complexo garantindo performance e previsibilidade em simulações de longa duração.
- **TypeScript:** Tipagem robusta para todos os modelos de dados do jogo (Times, Atletas e Eventos).

---

## Monitoramento e Performance

Para garantir uma experiência de alto nível (UX), o projeto integra o ecossistema de monitoramento da **Vercel**:
- **Vercel Analytics:** Acompanhamento de engajamento e retenção.
- **Speed Insights:** Monitoramento de performance real e Core Web Vitals.

---

## Autor

**Igor V Silva**  
*Desenvolvedor de Software.*

[LinkedIn](https://www.linkedin.com/in/igor-vinicius-de-jesus-gama-da-silva-04526026a/) | [GitHub Principal](https://github.com/eiguinho)
