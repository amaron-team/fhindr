# 1.1.2

- Fixed bug where previous button wasn't working properly for servers that use the prev keyword instead of previous
- Optimized some modal scaling when using high OS scaling
- Prevent application from trying to update on macOS if application is not trusted

# 1.1.1

- Fixed scaling issues when OS scaling was not set to 100%
- Made sure selectable resources become scrollable instead of stacking when there are too many to display on screen at once
- Fixed bug where no resource would be selected if the user clicked away before confirming selection

# 1.1.0

- Added Include, revinclude & everything query support
- Added option to only store credentials for the current session instead of persisting after restart
- Added option to export selected fields of a query result to excel
- Added additional headers in backend calls to prevent caching issues
- Optimized JSON viewer for large datasets
- Fixed bug where saved credentials could only be changed, not removed
- Fixed bug where next page would still be clickable even if there was no next page available
- Switched separator from | to , for combined array results
- Improved small UI details
- Added support for resource parameter (required for some FHIR repositories)

# 1.0.2

- Updated color scheme + AI models

# 1.0.1

- Fixed small bug where lastupdated sort would not be filled in automatically before using AI generator

# 1.0.0 

***Initial release version***


# 0.0.1

***Internal development version***
