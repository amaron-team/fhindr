# 1.2.0

- Added authorization code flow support
- Added option to search on the entire page by pressing ctrl+f
- Added option to open base64 encoded images and pdf files by clicking the data field in the table
- Right-clicking a repository name now gives the option to edit, clone or delete the repo
- Added option to expand the query window by clicking the expand icon
- Added option to see recent query history and resend requests with one click
- Added option to save queries, so they can be resent with one click
- Added clone option to repository configuration
- Added import option when configuring a new repository
- Added export repository configuration options
- Added configurable default search query field
- Added default page size option
- Added FHIR Station tracing options
- Added option to send FHIR queries as POST instead of GET
- Added option to configure custom JWT token extensions
- Added pseudonymization for patient identifiers
- Fixed bug where changing a field in the field selector while not on the main resource tab would automatically switch the selected tab to default
- Fixed bug where a "failed to load public key" error would be thrown during private key JWT authentication when no JWKS url was configured

# 1.1.2

- Fixed bug where previous button wasn't working properly for servers that use the prev keyword instead of previous
- Optimized some modal scaling when using high OS scaling
- Prevent application from trying to update on macOS if application is not trusted
- Fixed bug where hovering over table header could cause columns to be hidden

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


# 0.0.1 - 0.0.X

***Internal development versions***
