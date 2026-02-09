# Core Developers Discussion Topics
## Monday, February 23rd, 2026

This document outlines the technical discussion topics for the Phoebus Tools and Services core developers session.

---

## Discussion Format

- **Duration:** Full day session (9:30 AM onwards)
- **Participants:** Core developers and maintainers
- **Goal:** Strategic planning, architecture discussions, and technical decisions

---

## Technical Discussion Topics

### 1. Architecture & Framework

#### 1.1 Phoebus Framework Evolution
- [ ] Future of the RCP (Rich Client Platform) architecture
- [ ] Plugin system improvements and standardization
- [ ] Application lifecycle management
- [ ] Resource management and memory optimization
- [ ] Cross-platform compatibility challenges (Windows, Linux, macOS)

#### 1.2 UI/UX Framework Modernization
- [ ] JavaFX version strategy and roadmap
- [ ] CSS styling and theming improvements
- [ ] Responsive design patterns for different screen sizes
- [ ] Dark mode and accessibility enhancements
- [ ] Custom controls and widget library expansion

#### 1.3 Build System & Dependencies
- [ ] Maven vs Gradle considerations
- [ ] Dependency management and version conflicts
- [ ] Modularization strategy (Java modules/JPMS)
- [ ] Build performance optimization
- [ ] CI/CD pipeline improvements

---

### 2. Middle Layer Services Integration

#### 2.1 Service Architecture
- [ ] Microservices vs monolithic approach for middle layer services
- [ ] REST API standardization across services
- [ ] Authentication and authorization strategy (OAuth2, JWT, LDAP)
- [ ] Service discovery and registration
- [ ] Load balancing and high availability

#### 2.2 Archiver Service
- [ ] Archive Appliance performance tuning
- [ ] Data retrieval optimization strategies
- [ ] Storage backend options (file system, databases, object storage)
- [ ] Historical data migration patterns
- [ ] Real-time vs historical data access patterns

#### 2.3 Olog Integration
- [ ] Attachment handling and storage
- [ ] Search and indexing improvements (Elasticsearch integration)
- [ ] Template system enhancements
- [ ] Integration with other services (ChannelFinder, Alarm)
- [ ] Notification mechanisms

#### 2.4 ChannelFinder Service
- [ ] Channel metadata schema evolution
- [ ] Property and tag management
- [ ] Scalability for large installations (10K+ channels)
- [ ] Synchronization with EPICS IOCs
- [ ] Integration with save/restore functionality

#### 2.5 Alarm Services
- [ ] Alarm configuration management
- [ ] Alarm hierarchy and propagation rules
- [ ] Notification systems (email, SMS, messaging platforms)
- [ ] Alarm history and analytics
- [ ] Integration with Olog for alarm logging

---

### 3. Data Access & Performance

#### 3.1 EPICS Core Java (PVA)
- [ ] Protocol performance optimization
- [ ] Connection management and reconnection strategies
- [ ] Channel subscription memory management
- [ ] Support for new data types and structures
- [ ] Compatibility with EPICS 7 features

#### 3.2 PV Access Layer
- [ ] Unified data access abstraction
- [ ] Support for multiple protocols (CA, PVA, local://, sim://)
- [ ] Caching strategies and data flow
- [ ] Error handling and resilience
- [ ] Performance monitoring and diagnostics

---

### 4. Development Practices & Community

#### 4.1 Code Quality & Standards
- [ ] Coding standards and style guides
- [ ] Code review process improvements
- [ ] Static analysis tools integration
- [ ] Unit testing and test coverage goals
- [ ] Documentation standards

#### 4.2 Release Management
- [ ] Versioning strategy (semantic versioning)
- [ ] Release cycle and timing
- [ ] LTS (Long Term Support) versions
- [ ] Backwards compatibility policies
- [ ] Migration guides and upgrade paths

#### 4.3 Community Engagement
- [ ] Contribution guidelines
- [ ] New developer onboarding
- [ ] Communication channels (GitHub, Matrix, mailing lists)
- [ ] Feature request and issue triage process
- [ ] Collaboration with other EPICS tools (CS-Studio legacy, EDM, etc.)

---

### 5. Security & Deployment

#### 5.1 Security Considerations
- [ ] Secure communication channels (TLS/SSL)
- [ ] Credential management (avoiding hardcoded passwords)
- [ ] Security scanning and vulnerability management
- [ ] Access control and permissions model
- [ ] Audit logging

#### 5.2 Deployment Strategies
- [ ] Containerization (Docker, Kubernetes)
- [ ] Configuration management
- [ ] Monitoring and alerting
- [ ] Disaster recovery and backup strategies

---

### 6. Feature Roadmap & Prioritization

#### 6.1 High-Priority Features
- [ ] Cross-facility collaboration on feature priorities
- [ ] Resource allocation for major features
- [ ] Timeline for major releases

#### 6.2 Long-term Vision
- [ ] Cloud-native deployment options
- [ ] Web-based interfaces vs native applications
- [ ] Mobile support considerations
- [ ] AI/ML integration opportunities
- [ ] Next-generation control system requirements

---

### 7. Technical Debt & Refactoring

- [ ] Identification of major technical debt areas
- [ ] Deprecated API removal strategy
- [ ] Legacy code migration plans

---

## Action Items Template

For each topic discussed, capture:
- **Decision Made:** 
- **Owner:** 
- **Timeline:** 
- **Dependencies:** 
- **Follow-up Required:** 

---

## Meeting Notes

_To be filled during the session on Monday, February 23rd_

---

## References

- [Phoebus Documentation](https://github.com/ControlSystemStudio/phoebus/tree/master/docs)
- [EPICS Website](https://epics-controls.org/)
- [Previous Codeathon Reports](https://epics.anl.gov/meetings/)
