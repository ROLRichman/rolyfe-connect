# RO’Lyfe Connect v0.1.0
Experimental local-only release. No cloud accounts, public rooms, automatic discovery, long-distance relay, group calls or stored conversation history. One approved pairing at a time. Seven editions use compatible WebRTC signaling; Connect is a directory and a peer, not a central receiver of other conversations. Local-only Family Circle names, emergency contact and theme persist in browser storage; no personal data is embedded in source. SOS is peer-only, not emergency services.
## Provenance
AirLink v0.3.1 index blob 09c4a8299fd3d6d74778aee58b31082cb8190562; preserves existing pairing, WebRTC voice/text/SOS functions. New chat-first layout, brand links, and per-app offline cache. Original README retained.
## Required tests
Load online on two devices, wait for cache, disable internet but keep a reachable local network. Pair Connect with AirLink, then another edition; send text and voice both directions. Confirm unrelated third device receives nothing. Test SOS acknowledgment, refresh requiring new pairing, screen lock, theme, local contact persistence, link copying and offline reload. Physical and deployment checks pending.
## Future online architecture
Dedicated backend, explicit account and device enrollment, server-enforced conversation membership and invite acceptance, minimal data retention, abuse controls, revocation, and security review before launch. No automatic access to brand conversations. Online signaling and optional relay must remain separate from the offline mode. Native trusted-device reconnect requires installed apps and consent.
