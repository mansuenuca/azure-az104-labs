# AZ104-03 - Secure Azure Blob Storage Implementation

##  Objective
Implement a secure and highly available Azure Storage Account to host public-facing content with data protection features enabled.

## Skills Practiced
- Azure Storage Account deployment
- Geo-redundancy configuration (RA-GRS)
- Public access configuration
- Blob container management
- Soft delete configuration
- Blob versioning

## Architecture
Single Storage Account with:
- Public Blob Container
- Geo-redundant storage (RA-GRS)
- Data protection enabled

## Implementation Steps
1. Create Resource Group
2. Deploy Storage Account
3. Configure redundancy (RA-GRS)
4. Enable anonymous blob access
5. Create public blob container
6. Upload and access files via URL
7. Enable soft delete (21 days)
8. Enable blob versioning

## Key Configurations

### Storage Account
- Redundancy: RA-GRS
- Public access: Enabled

### Data Protection
- Soft Delete: Enabled (21 days)
- Versioning: Enabled

### Container
- Name: public
- Access level: Blob (anonymous read access)

## Result
Successfully deployed a secure and highly available storage solution with public content access and data protection mechanisms.

## Notes
- RA-GRS ensures regional failover
- Soft delete prevents accidental deletion
- Versioning allows rollback of file changes
