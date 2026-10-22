cat > README.md <<'EOF'
# Staff SRE Platform

A local, GitOps-managed SRE platform for a B2B SaaS application.

## Status

- [ ] Argo CD GitOps bootstrap
- [ ] Platform security baseline
- [ ] Metrics, logs, and traces
- [ ] Sample API
- [ ] SLI/SLO and alerting
- [ ] Temporal operational workflow
- [ ] AI SRE root-cause analysis
- [ ] Incident simulation and recovery tests
- [ ] Fresh-clone bootstrap validation

## Architecture

See `docs/architecture.md`.

## Security

Never commit credentials, tokens, private keys, or plaintext production secrets.
EOF