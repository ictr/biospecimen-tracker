# biospecimen-tracker

A barcode-based tracking system for the processing of biospecimen from multiple centers

https://www.quartz.bio/ looks like a commercial company that offers such a service.

## Design goals (features on top of existing barcode system)

### Data structure

1. Use real database for performance considerations
2. Providing API for remote access.
 
### Web interface

0. Display sample sheets (for specific projects)
1. Users have permission to access certain projects and have different roles.
2. Users can upload sample sheets.
3. Diagrams to link records
4. Download sample sheets

### Command line tool

0. existing features for adding etc.
1. Working with remote data source

