
# WebSphere Chorus Controller IHS Webserver - All-in-One Installation Role

An Ansible automation role for streamlined deployment and configuration of IBM WebSphere Application Server, IBM HTTP Server (IHS), and Chorus Controller components in a single unified installation.

## Overview

This Ansible role automates the complete installation and configuration of:
- **IBM WebSphere Application Server (WAS)** - Java application server
- **IBM HTTP Server (IHS)** - Web server with WebSphere plugin
- **Chorus Controller** - IBM orchestration and management component

Perfect for environments requiring integrated deployment of these IBM enterprise components with minimal manual intervention.
### System Requirements
- RHEL/CentOS 7.x or higher, or Ubuntu 16.04+
- Minimum 8GB RAM (16GB+ recommended)
- Minimum 50GB free disk space
- Root or sudo access

### Required Software
- Ansible 2.9+
- Python 2.7 or 3.6+
- Java Development Kit (JDK) - if not pre-installed

### Network Requirements
- Internet access for package downloads (or pre-staged binaries)
- Firewall access for WebSphere (default: 8080, 8443)
- Firewall access for IHS (default: 80, 443)

**Last Updated:** 2026
**Maintained By:** Vivekandan.K
**Version:** 1.0.0
