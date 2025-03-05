# Twilio Voice AI Assistant with Ultravox

> A powerful Voice AI implementation using Twilio and Ultravox for handling incoming and outgoing calls with AI-powered conversations.

## Watch Tutorial Video

Watch the Implementation Tutorial on YouTube:

<p align="center">
    <a href="https://youtu.be/AbJKBgN_pMU">
        <img src="https://img.youtube.com/vi/AbJKBgN_pMU/0.jpg" alt="Twilio Voice AI Implementation Tutorial" width="560" height="315">
    </a>
</p>

<p align="center">
    <a href="https://www.youtube.com/channel/UCxgkN3luQgLQOd_L7tbOdhQ?sub_confirmation=1">
        <img src="https://img.shields.io/badge/Subscribe-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Subscribe">
    </a>
</p>

## Introduction

This project demonstrates how to build an intelligent voice assistant using Twilio and Ultravox AI. It can handle both incoming and outgoing calls, perfect for customer service, lead qualification, or automated follow-ups.

## Key Features

- **Intelligent Voice Conversations**: Natural language interactions powered by Ultravox AI
- **Dual Mode Support**: Handles both incoming and outgoing calls
- **Contact Information Tracking**: Automatically captures and utilizes caller information
- **Dynamic Context Handling**: Adapts conversation based on call context
- **Professional Voice**: Uses high-quality voice synthesis for natural conversations
- **Customizable Scripts**: Easily modifiable system prompts for different use cases

## Technical Stack

- **Twilio**: Telephony infrastructure
- **Ultravox AI**: Conversational AI engine
- **Express.js**: Web server framework
- **dotenv**: Environment configuration
- **Node.js**: Runtime environment

## System Architecture

1. **Incoming Call Flow**
   - Webhook endpoint for incoming calls
   - Automatic caller information capture
   - Dynamic AI response generation

2. **Outgoing Call Flow**
   - Programmatic call initiation
   - Custom conversation context setting
   - Automated follow-up handling

3. **Environment Configuration**
   - Secure credentials management
   - Easy configuration setup
   - Development/Production environment support

## Setup Instructions

### Prerequisites
- Node.js installed
- Twilio account with:
  - Account SID
  - Auth Token
  - Twilio phone number
- Ultravox API key

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/twilio-voice-ai.git
   cd twilio-voice-ai
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env
   ```

4. Add your credentials to `.env`:
   ```
   ULTRAVOX_API_KEY=your_ultravox_api_key
   ```

### Running the Application

For incoming calls:
```bash
node index.js
```

Make sure to configure your Twilio webhook URL to point to your server's `/incoming` endpoint.

## Known Limitations

- Requires stable internet connection
- Webhook endpoint needs to be publicly accessible
- Call quality depends on network conditions
- Limited to one conversation flow at a time

## Extending the System

The system can be extended by:
- Adding database integration for call logging
- Implementing custom conversation flows
- Adding analytics and reporting
- Integrating with CRM systems

## Need Professional Implementation?

Looking to implement a custom Voice AI solution for your business? Our team at KnoLabs specializes in building AI-powered communication systems.

 [Contact Us for Professional Implementation](https://knolabs.biz/collect-requirement-page)

## Hosting Partners
- [Kamatera - Get $100 Free VPS Credit](https://knolabs.biz/100-dollar-free-credit)
- [Hostinger - Additional 20% Discount](https://knolabs.biz/20-Percent-Off-VPS)

## Documentation
For more information about Ultravox and its capabilities, visit: [Ultravox Documentation](https://docs.ultravox.ai)

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.

# Twilio Voice AI Assistant avec Ultravox

> Implémentation d'un assistant vocal IA utilisant Twilio et Ultravox pour gérer les appels entrants avec des conversations alimentées par l'IA.

## Introduction

Ce projet démontre comment construire un assistant vocal intelligent en utilisant Twilio et Ultravox AI. Ce système gère les appels entrants, idéal pour le service client, la qualification de leads ou les suivis automatisés.

## Caractéristiques principales

- **Conversations vocales intelligentes**: Interactions en langage naturel alimentées par Ultravox AI
- **Capture des informations de contact**: Capture et utilise automatiquement les informations de l'appelant
- **Gestion de contexte dynamique**: Adapte la conversation en fonction du contexte de l'appel
- **Voix professionnelle**: Utilise une synthèse vocale de haute qualité pour des conversations naturelles
- **Scripts personnalisables**: Prompts système facilement modifiables pour différents cas d'utilisation

## Stack technique

- **Twilio**: Infrastructure de téléphonie
- **Ultravox AI**: Moteur de conversation IA
- **Express.js**: Framework de serveur web
- **dotenv**: Configuration d'environnement
- **Node.js**: Environnement d'exécution
- **ngrok**: Tunnel pour exposer le serveur local

## Architecture du système

### Flux d'appel entrant
- Point de terminaison webhook pour les appels entrants
- Capture automatique des informations de l'appelant
- Génération dynamique de réponses IA

## Instructions d'installation

### Prérequis
- Node.js installé
- Compte Twilio avec:
  - SID du compte
  - Token d'authentification
  - Numéro de téléphone Twilio
- Clé API Ultravox

### Installation

1. Cloner le dépôt:
   ```bash
   git clone https://github.com/RollandMELET/kno2gether-twilio-incoming-ultravox-agent.git
   cd kno2gether-twilio-incoming-ultravox-agent
   ```

2. Installer les dépendances:
   ```bash
   npm install
   ```

3. Configurer les variables d'environnement:
   ```
   ULTRAVOX_API_KEY=votre_clé_api_ultravox
   ```

### Exécution de l'application

1. Démarrer le serveur:
   ```bash
   node index.js
   ```

2. Exposer le serveur avec ngrok:
   ```bash
   ngrok http 3000
   ```

3. Configurer le webhook Twilio pour pointer vers votre URL ngrok + "/incoming"
   ```
   https://votre-url-ngrok.app/incoming
   ```

## Limitations connues

- Nécessite une connexion internet stable
- Le point de terminaison webhook doit être accessible publiquement
- La qualité des appels dépend des conditions du réseau
- Limité à un flux de conversation à la fois

## Documentation
Pour plus d'informations sur Ultravox et ses capacités, visitez: [Documentation Ultravox](https://docs.ultravox.ai)

## Licence

Ce projet est sous licence Apache 2.0 - voir le fichier [LICENSE](LICENSE) pour plus de détails.
