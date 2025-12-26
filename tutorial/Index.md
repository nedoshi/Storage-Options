# Storage Options Documentation Index

This repository contains comprehensive guides for storage options across Red Hat OpenShift platforms.

## Documentation Structure

### Getting Started
- **[README.md](../README.md)** - Overview and quick start guide
- **[OpenShift Storage Guide](openshift_storage_guide.md)** - Complete setup guide for ROSA and ARO storage

### Platform-Specific Guides

#### Azure Red Hat OpenShift (ARO)
- **[ARO Storage Guide](aro_storage_guide.md)** - Comprehensive beginner's guide to ARO storage
  - Basic concepts and terminology
  - Complete storage flow explanation
  - Step-by-step configuration examples
  - Real-world use cases
  - Quick reference section

- **[ARO Backup & Restore](aro_backup_restore.md)** - Cross-cluster backup and restore with OADP (Velero)
  - Architecture and setup
  - Configuration steps
  - Validation procedures

### Reference Materials
- **[Storage Vendor Solutions](storage_vendor_openshift_support.md)** - Enterprise storage vendor solutions
  - Red Hat OpenShift Data Foundation (ODF)
  - Portworx by Pure Storage
  - NetApp Trident
  - Dell EMC, Pure Storage, IBM, VMware solutions
  - Vendor comparison matrix

## Quick Navigation by Use Case

### I need to understand storage basics
→ Start with [ARO Storage Guide](aro_storage_guide.md) - Basic Concepts section

### I need to set up storage for ROSA
→ See [OpenShift Storage Guide](openshift_storage_guide.md) - ROSA Storage Setup section

### I need to set up storage for ARO
→ See [ARO Storage Guide](aro_storage_guide.md) - Step-by-Step Configuration section

### I need to configure backup/restore
→ See [ARO Backup & Restore](aro_backup_restore.md)

### I'm evaluating enterprise storage vendors
→ See [Storage Vendor Solutions](storage_vendor_openshift_support.md)

### I need a quick reference
→ See [ARO Storage Guide](aro_storage_guide.md) - Quick Reference section

## Storage Options Overview

### ROSA (AWS)
- **EBS GP3/IO2** - Block storage for databases and high-performance workloads
- **EFS** - Shared file storage for multi-pod access
- **FSx** - High-performance file systems

### ARO (Azure)
- **Azure Disk** - Block storage (Premium/Ultra SSD)
- **Azure Files** - Shared file storage (SMB/NFS)
- **Azure NetApp Files** - Enterprise-grade file storage
- **Azure Blob** - Object storage for large datasets

### Enterprise Solutions
- **OpenShift Data Foundation (ODF)** - Unified storage platform
- **Portworx** - Application mobility and DR
- **NetApp Trident** - Advanced data management
- **Other vendors** - Dell EMC, Pure Storage, IBM, VMware

