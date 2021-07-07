# Aries Mobile SDK - Demo's

This document highlights various mobile apps that have been created using Aries Framework JavaScript and React Native. The point of highlighting these is to show that the Aries Framework JavaScript has the appropriate Technology Readiness Level (TRL) to start building the Aries Mobile SDK.

## [United Nations International Computing Center - UN Digital ID](https://www.unicc.org/news/2021/05/17/uniccs-cto-shashank-rai-presents-un-digital-id-at-hyperledger-social-impact-special-interest-group)
On the 27th of April 2021, the UNICC's Chief Technology Officer Shashank Rai announced plans to create a digital identity infrastructure for all United Nations employees. It aims to solve the data fragmentation problems and broken processes within the United Nations. An important component of that infrastructure is a mobile agent. To build this component, they chose Aries Framework JavaScript.

[Watch the announcement of this initiative here!](https://www.unicc.org/news/2021/05/17/uniccs-cto-shashank-rai-presents-un-digital-id-at-hyperledger-social-impact-special-interest-group)

## [The Linux Foundation - Cardea](https:cardea.app)

Cardea is a fully open source, privacy-perserving ecosystem for digital health credentials initiated by Indicio.tech. The project was recently adopted by The Linux Foundation and an IATA poll concluded that 78% of the participants of the survey will only use a travel health app if they have full control over their data. As Indicio.tech is an active contributer to Aries Framework JavaScript, Cardea is fully based on Aries Framework JavaScript and is one of the first production grade mobile applications built atop the framework.

[Read more about the Cardea project here!](https://cardea.app)
[Cardea Holder Agent repository](https://github.com/thecardeaproject/cardea-mobile-holder)
[Cardea Verifier Agent repository](https://github.com/thecardeaproject/cardea-mobile-verifier)


## Animo Mobile Agent PoC
TODO
## [Chat application](https://www.youtube.com/watch?v=wW4HSZZ2kSk)

This is a simple messaging app that allows to make DIDComm connections and send end-to-end encrypted messages via a mediator service. Although it’s not about the credential exchange, it’s still the foundation for other SSI building blocks. The whole solution actually consists of three standalone apps all of them built with JavaScript and using Aries Framework JavaScript:

- Desktop app built with React and Electron
- Mobile iOS app built with Aries Framework JavaScript and React Native
- Server-side mediator service built with NodeJS

The demo also demonstrates the framework’s independence on transport mechanisms (e.g. HTTP polling could be eventually replaced by WebSockets). Utilization of the JavaScript event system enables developers to build more reactive apps while the usage of a mediator service provides offline message delivery. 

We believe that multi-platform development in JavaScript is a great benefit and could lower the barrier to entry into the whole SSI ecosystem. Now it’s the time to make it easy to use for other developers.

[Watch the chat application demo here!](https://www.youtube.com/watch?v=wW4HSZZ2kSk)
