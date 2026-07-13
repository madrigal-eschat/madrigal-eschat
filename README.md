How's it goin? I'm a kinky nerd girl from the UK and on _this_ github profile I have four goals:

1. Take over the world with a message format for events which occur during software development.
2. Hook up the code editor and hosting system message producers developed for 1. to a bridge to Intiface Central so I can vibe code while I vibe code
3. Get buttplug vibrations when I'm playing video games on my Steam Deck
4. Do all this, or at least get the bones in place, before Anthropic goes out of business or puts their prices up too high.

You can find me on Fetlife or in Cuff-Link #ukbdsm.

## To Business

* Dev Events is an informational message format based upon [Cloud Events](https://cloudevents.io/) (specifically the [MQTT binding](https://github.com/cloudevents/spec/blob/main/cloudevents/bindings/mqtt-protocol-binding.md)) for events which occur in Software Development workflows. It attempts to abstract over all possible code editors, hosting platforms and CI systems.
  * [dev-events-mqtt](https://github.com/madrigal-eschat/dev-events-mqtt) is the repo which contains the standard, ecosystem roadmap, and will eventually have some turnkey templates/docker compose files/etc for deploying parts of the ecosystem.
  * [dev-events-haptics-bridge](https://github.com/madrigal-eschat/dev-events-haptics-bridge) is a configurable bridge to receive haptic feedback in response to dev-events
  * [dev-events-jetbrains-publisher](https://github.com/madrigal-eschat/dev-events-jetbrains-publisher) is a plugin for Jetbrains IDEs for producing Dev Events
* [decky-toy-haptics](https://github.com/madrigal-eschat/decky-intiface) is a Decky Loader plugin to provide a one-click install Steam Deck game-mode interface for routing game haptics to your intimate devices.
  * [linux-game-haptics-router](https://github.com/madrigal-eschat/linux-game-haptics-router) is the underlying command-line haptics-to-buttplug forwarder, written in rust and using a combination of EBPF and evdev events to snoop on haptic feedback data.
* [WearTrack](https://github.com/madrigal-eschat/WearTrack) is a self-hostable PWA for incrementally increasing (or encouraging the maintenance of a status quo of) the frequency / duration for which you wear intimate items. 
