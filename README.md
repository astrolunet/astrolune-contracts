# Astrolune Contracts

Smart contracts for the Astrolune ecosystem, written in Trocto v0.3.

## Contracts

### Lune DNS
- `lune_dns/registry.tc` — Domain registration, renewal, transfer
- `lune_dns/registrar.tc` — Commit-reveal registration scheme
- `lune_dns/resolver.tc` — Typed DNS records (6 types)
- `lune_dns/treasury.tc` — Fee collection and distribution
- `lune_dns/marketplace.tc` — Escrow-based domain sales
- `lune_dns/service_record.tc` — SERVICE record management

### Hosting
- `hosting/provider_registry.tc` — Storage/hosting provider registration
- `hosting/storage_agreement.tc` — Storage contracts

### Share
- `share/content_offer.tc` — Paid content offers
- `share/retrieval_escrow.tc` — Atomic payment escrow

### Proxy
- `proxy/proxy_registry.tc` — Proxy node registry

### Standard Library
- `stdlib/ownership.tc` — Ownership pattern

## Compile

```bash
trocto lune_dns/registry.tc -o registry.bin
```

## License

MIT
