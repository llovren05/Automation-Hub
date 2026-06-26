Features:
- 🔗 Blockchain Ops — Multi-chain transaction automation
- ⚡ Task Engine — Priority-based task queue with retry logic
- 📊 Structured Logging — JSON logs with context propagation
- 🐳 Docker Ready — Multi-stage builds for prod & dev
- 🔒 Type Safe — Full mypy strict mode

Quick Start:
git clone https://github.com/llovren0/automation-hub.git
cd automation-hub
cp .env.example .env

Docker:
make dev
kabuto run
kabuto status
make docker-build
make docker-run


Development:
make dev        # Install dev deps + pre-commit
make lint       # Run linter
make format     # Format code
make test       # Run tests
make typecheck  # Type checking
