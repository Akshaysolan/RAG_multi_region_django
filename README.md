# Multi-Region Django Application

A production-ready, multi-region Django application with high availability, disaster recovery, and automated failover.

## Architecture

- **HAProxy**: Load balancing and automated failover
- **Django**: Web application with REST API
- **MySQL**: Primary-replica replication with GTID
- **Redis**: Caching and session storage
- **Docker**: Containerized deployment

## Features

- ✅ Multi-region active-active deployment
- ✅ Automated failover with health checks
- ✅ Database read/write splitting
- ✅ GTID-based replication
- ✅ Comprehensive monitoring
- ✅ Disaster recovery testing
- ✅ Performance optimization
- ✅ Security best practices

## Quick Start

```bash
# Clone repository
git clone <repository-url>
cd multi_region_django

# Make scripts executable
chmod +x scripts/*.sh

# Run setup script
./scripts/setup.sh

# Access application
open http://localhost
