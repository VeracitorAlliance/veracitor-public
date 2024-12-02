---
title: "Personal_OpSec"
date: 2024-12-01
---

# Security Protocols for Veracitor Alliance Personnel

## Critical Security Measures

### Digital Security
- Use organization-provided hardened devices only
- Hardware security keys mandatory for 2FA
- End-to-end encrypted email via ProtonMail
- Signal for all communications
- Hardened OS configurations (Qubes OS for technical staff)
- No personal devices for work
- VPN mandatory (WireGuard protocol)
- No cloud storage - local encrypted only
- Regular security audits and updates

### Physical Security
- Office access via multi-factor authentication
- Clean desk policy
- Shred all documents
- No sensitive discussions in public
- Vary routes to/from office
- Security cameras at entries
- Regular sweeps for surveillance devices
- Secure visitor protocols
- No sensitive work in public spaces

### Travel Security 
- Burner devices for field work
- No sensitive data on travel devices
- Physical security locks on doors/windows
- Hotel room sweeps
- No discussing work in public/transit
- Avoid predictable patterns
- Check for surveillance
- Emergency extraction plans
- Regular check-ins required

### Counter-Intelligence
- Monitor for surveillance indicators
- Report suspicious contacts/incidents
- Brief family on security protocols
- Social media lockdown
- OPSEC training quarterly
- Threat awareness updates
- Incident response procedures
- Cover story development
- Avoiding honey traps

### Data Protection
- Full disk encryption
- USB disabled by default
- Air-gapped systems for sensitive data
- Regular backups (encrypted)
- Secure erasure protocols
- Need-to-know access only
- Audit logs required
- Incident response plan
- Data classification policy

### Response Protocols
- Incident reporting chain
- Emergency contacts list
- Safe house locations
- Duress codes established
- Evidence preservation
- Legal contact procedures
- Media response plan
- Family notification protocol
- Regular drills required

## Implementation
- Mandatory security training
- Written acknowledgment required
- Regular protocol reviews
- Quarterly security updates
- Compliance monitoring
- Incident reviews/updates
- Security culture emphasis

## Resources
- Security team contacts
- Emergency procedures
- Secure communications guide
- Incident report forms
- Legal/compliance contacts
- Training materials
- Update schedule

# Comprehensive Security Protocols for Veracitor Alliance Personnel

## Introduction

This document outlines critical security protocols for Veracitor Alliance personnel, with particular attention to threats from state-level actors and private security contractors. These measures are mandatory for all board members, staff, and field operatives.

## Digital Security Framework

### Authentication and Access Control
Security begins with robust authentication practices. All personnel must implement:

- Multiple hardware security keys (minimum 3)
  - Primary YubiKey maintained on person
  - Backup key stored in secure location
  - Emergency key stored with security team
  - All keys must support FIDO2/WebAuthn
  - Keys must be registered with biometric backup

- Password Requirements
  - Minimum 20 characters
  - Multiple language character sets
  - Changed upon any suspected compromise
  - Never reused across systems
  - Stored only in approved password manager
  - Regular entropy validation

### Device Security

#### Approved Devices
- Organization-provided devices only
- No personal devices for work purposes
- No cross-contamination between work/personal
- All devices must be:
  - Full disk encrypted (LUKS/VeraCrypt)
  - BIOS password protected
  - Secure boot enabled
  - TPM verification active
  - Running approved OS builds

#### Operating System Standards
- Technical Staff: Qubes OS with security template
- General Staff: Hardened Linux distribution
- Field Operations: Tails OS for sensitive work
- All systems must maintain:
  - Real-time threat monitoring
  - Application sandboxing
  - Network isolation
  - Regular security patches
  - Automated backups

### Communications Security

#### Email Protocols
- ProtonMail with advanced security features
- PGP encryption mandatory for all emails
- Regular key rotation schedule
- No external email forwards
- Automated phishing detection
- Regular account security audits

#### Messaging Requirements
- Signal for all internal communications
- Custom key verification required
- Disappearing messages enabled
- No message screenshots
- Regular security number verification
- Separate devices for secure comms

### Network Security

#### VPN Requirements
- WireGuard protocol only
- Multi-hop connections mandatory
- No split tunneling
- Regular server rotation
- Traffic obfuscation enabled
- Kill switch mandatory

#### Internet Usage
- Tor Browser for research
- No public WiFi
- Mobile hotspot for emergency only
- Regular DNS leak testing
- Browser fingerprint randomization
- JavaScript disabled by default

## Physical Security Measures

### Office Security

#### Access Control
- Multi-factor physical access
- Biometric verification required
- Mantrap entrance system
- Security cameras with AI monitoring
- Regular access log audits
- Visitor escort mandatory

#### Workspace Security
- Clean desk policy enforced
- Screen privacy filters required
- No sensitive materials visible
- Regular bug sweep schedule
- White noise generators active
- No windows facing workstations

### Travel Security

#### Pre-Travel Procedures
- Route randomization required
- Security team briefing mandatory
- Threat assessment review
- Safe house locations memorized
- Emergency contact verification
- Cover story preparation

#### During Travel
- Burner devices only
- No sensitive data carried
- Regular check-in schedule
- Counter-surveillance awareness
- Hotel room security measures
- Public area security protocols

## Counter-Intelligence Practices

### Surveillance Detection
- Regular counter-surveillance training
- Indication and warning systems
- Pattern analysis awareness
- Technical surveillance countermeasures
- Regular security sweeps
- Anomaly reporting procedures

### Social Engineering Defense
- Social media lockdown protocols
- Personal information compartmentalization
- Regular OSINT self-assessment
- Relationship security measures
- Cultural awareness training
- Honey trap awareness

## Incident Response

### Emergency Procedures
- Immediate response protocols
- Secure communication channels
- Evidence preservation methods
- Legal team activation
- Media response coordination
- Family notification system

### Documentation Requirements
- Incident logging procedures
- Chain of custody protocols
- Digital evidence handling
- Physical evidence procedures
- Witness statement protocols
- Timeline reconstruction methods

## Training and Compliance

### Required Training
- Quarterly security updates
- Monthly awareness briefings
- Weekly security bulletins
- Practical exercise drills
- Scenario-based training
- Technical skills verification

### Compliance Monitoring
- Regular security audits
- Protocol adherence checks
- Security culture assessment
- Violation reporting system
- Corrective action procedures
- Performance improvement plans

## Security Resources

### Emergency Contacts
- Security team hotline
- Legal response team
- Medical support contacts
- Technical assistance
- Family liaison officer
- Media response coordinator

### Documentation Access
- Security protocol updates
- Training materials
- Incident report forms
- Security assessment tools
- Audit checklists
- Emergency procedure guides

## Implementation Requirements

All personnel must:
- Acknowledge these protocols in writing
- Complete all required training
- Maintain security clearance
- Report any violations
- Participate in security drills
- Update emergency contacts quarterly

## Regular Updates

This document is reviewed and updated quarterly. All personnel must:
- Review updates within 24 hours
- Acknowledge changes in writing
- Implement new procedures immediately
- Report any implementation issues
- Suggest improvements as needed
- Maintain awareness of changes

*Note: This document is classified as SECURITY SENSITIVE. Handle accordingly.*

---

# Note on Transparency

While security protocols typically remain confidential to protect operational effectiveness, Veracitor Alliance believes in radical transparency about our security posture. We share these measures publicly to demonstrate our commitment to protecting truth-seekers and to help other organizations enhance their security against state-level threats. This transparency serves multiple purposes: it builds trust with our community, helps other civil society organizations improve their security practices, and signals to adversaries that we take protection of our personnel and mission seriously. However, our actual implementation details, specific hardware configurations, and current deployment strategies remain confidential.

Remember: Security through obscurity is a weak defense. True security comes from robust, well-implemented protocols combined with constant vigilance and adaptation.

---

Last Updated: December 2024  
Security Classification: INTERNAL USE ONLY (We're all in it now...)  
Distribution: NEED TO KNOW BASIS (Everyone needs to know) 
