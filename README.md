# IP Location Omegle

[![Autor: Max Muller](https://img.shields.io/badge/Autor-Max%20Muller-blue)]()
[![JavaScript](https://img.shields.io/badge/Linguagem-JavaScript-yellow)]()

Apenas uma brincadeira acadêmica para ver a localização IP das pessoas no Omegle.

https://www.omegle.com/

## Sobre o Projeto
**IP-Location-Omegle** é uma ferramenta educacional desenvolvida em JavaScript que demonstra como capturar IPs públicos obtidos via WebRTC (ICE Candidates) e consultar informações de geolocalização utilizando a API do **ipgeolocation.io**.

O objetivo deste projeto é apresentar conceitos de:
- WebRTC e interceptação de *ICE Candidates*
- Manipulação e sobreposição de `RTCPeerConnection`
- Requisições assíncronas (`fetch`)
- Integração com APIs externas de geolocalização

> **Uso estritamente educacional.**  
> Não utilize este código para fins inadequados, invasivos ou que violem privacidade.

---

## Tecnologias Utilizadas
- **JavaScript (ES6+)**
- **WebRTC**
- **Fetch API**
- **ipgeolocation.io API**

---

## Como Usar

  1. Crie uma conta gratuita em https://ipgeolocation.io/

  2. Copie sua API Key e substitua no código:

let apiKey = "SUA-API-KEY-AQUI";


  3. Injete o script no navegador enquanto utiliza o Omegle ou qualquer serviço WebRTC.

## Aviso Legal

Este projeto é apenas para fins educacionais, com objetivo de estudo sobre:

  - Funcionamento interno de WebRTC

  - Segurança e privacidade em comunicação peer-to-peer

  - APIs de geolocalização

O uso indevido é de responsabilidade exclusiva do usuário.

## Possíveis Melhorias Futuras

  - Exportação dos dados capturados em JSON

  - Interface gráfica (Dashboard UI)

  - Detecção de múltiplos peers simultâneos

  - Logs estruturados ou integração com banco de dados

  - Ferramenta CLI para testes locais

## Autor

Max Muller
Desenvolvedor e professor, especializado em tecnologias web, automação e segurança da informação.


Se este projeto ajudou você a evoluir, deixe uma ⭐ e compartilhe o conhecimento. Obrigado por usar este repositório!

![octocat-1688651144641](https://github.com/MMVonnSeek/IP-Location-Omegle/assets/89359847/4fd17e18-8563-43b7-a985-11c4547a2b17)
