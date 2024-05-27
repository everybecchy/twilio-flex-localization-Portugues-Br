# Twilio Flex 2.0 - Localization - Portugues-Br

Simple one-liner plugin that enables Portugues-Br language localization all agents on Flex UI 2.x.

For localization of multiple languages (w/ language switcher), please refer to [Twilio PS - Flex Localization Plugin](https://github.com/twilio-professional-services/plugin-flex-localization)

Credits to Everton Santos for the Portugues-Br translation file

![Flex 2.0 - Portugues-Br - Main](docs/doc1.png)

![Flex 2.0 - Portugues-Br - Teams](docs/doc2.png)

![Flex 2.0 - Portugues-Br - Queue Stats](docs/doc3.png)

---

## Pre-requisites

1. Twilio Flex Account ([Guide](https://support.twilio.com/hc/en-us/articles/360020442333-Setup-a-Twilio-Flex-Account))
2. Node.js v18.x.x ([Guide](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm))
3. Twilio CLI v5.2.2 or above ([Guide](https://www.twilio.com/docs/twilio-cli/quickstart))
4. Twilio CLI Flex Plugin v2.7 or above ([Guide](https://www.twilio.com/docs/flex/developer/plugins/cli))

---

## Getting Started

On your terminal, perform the following:

```
// Clone Project
git clone https://github.com/everybecchy/twilio-flex-localization-Portugues-Br.git

// Change to working directory
cd twilio-flex-localization-Portugues-Br

// Install NPM Packages
npm install

// Local Development
twilio flex:plugins:start

// Deploy to Twilio Flex Instance
// Before you deploy, ensure that `twilio profiles:list` has an active account set.
twilio flex:plugins:deploy --changelog "Deploy Localization of Portugues-Br Language"
twilio flex:plugins:release --plugin twilio-flex-localization-Portugues-Br@0.0.1 --name "Flex UI 2.x - Localization - Portugues-Br" --description "Localization for Flex UI 2.x - Portugues-Br"
```

---

## Credit(s)

Everton Santos for the Portugues-Br Translation

## License

MIT
