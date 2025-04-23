# 1.3.2

- Added support for several new encryption algorithms when using private key authentication
- Expand repository selector by default to have a better overview of all configured repositories
- Added option to expand and minimize repository selector when querying
- Added option to adjust sidebar width by dragging
- Added option to specify assertion audience when using private key authentication
- Prevent data entry modals from closing when clicking away
- Improved error handling to make sure more error details are included
- Fixed bug where clearing the query history would not update in the UI until the modal was reopened

# 1.3.1

- Improved cell values list UI and added copy value buttons
- Re-enabled auto updates on macOS
- Added informational tooltips to search bar icons
- Include full column path in table header when possible
- Fixed bug where clickable links would not always be highlighted in the cell values list
- Fixed bug where a private key would be requested instead of a secret when using the "client secret as basic auth header" authentication without storing credentials

# 1.3.0

- Completely reworked AI integration settings to allow for custom model configurations and added support for several API formats
- Extended backend token information to ensure compatibility with more FHIR servers
- Added support for Basic authentication
- Added option for OAuth client authentication to include credentials as Basic Auth Header or in the request body
- Added separate option for no authentication
- Added option to send paging requests as GET requests when send as POST is configured
- Added option to parse paging request query into the request body when send as POST is configured
- Added certificate validation and enabled it by default. When available, certificates in the OS truststore will be trusted by default
- Added option to disable certificate validation for requests to the FHIR server
- Added option to disable certificate validation for requests to the authentication server
- Added an indication to error handling if the error was generated while requesting an access token or when actually sending the query to the repository
- Added option to automatically determine and use SMART on FHIR scopes based on the query being sent to the repository
- Added option to select what SMART on FHIR version to use
- Added option to interact with a list of all values contained in a cell for cells that contain multiple values
- Added the ability to add a name and description to favorited queries
- Renamed some authentication methods for clarity
- Fixed bug where paging requests could fail for FHIR servers using a custom port
- Fixed bug where paging queries could fail for some repositories when send as POST was configured
- Fixed bug where duplicate query parameters could be overwritten when sending a request with several parameters with the same key
- Improved some rendering logic to only show relevant fields when configuring a repository
- Tweaked several small UI details
- Backend stability improvements and security fixes

# 1.2.3

- Added a simple query builder to the expanded query modal that allows query parameters to be added as key-value pairs
- Added a notification that there are no fields selected instead of showing an empty table when there are no fields selected
- The field selector will now persist custom column order when switching repository instead of resetting back to the default order
- Removed checkboxes for parents instead of showing them as disabled
- Improved some encoding logic that prevented some url encoded characters from being used in the search query field
- Improved search query alignment and spacing
- Fixed bug where a false boolean would sometimes be displayed as an empty cell in the table view
- Fixed bug where metadata could not be requested when send as POST was enabled
- Fixed bug where cloning a repository connection would clone the credentials but not actually save them
- Resolved an issue where the custom page size setting would add the _count parameter to requests that do not support it

# 1.2.2

- Fixed bug where session credential modal could get stuck when entering credentials
- Use token endpoint as audience when generating client assertions instead of the FHIR repo audience           

# 1.2.1

- Added some tooltip icons with extra information about the advanced options, clicking the icon will also copy an example
- Added the ability to include custom HTTP headers in search requests
- Added private key JWT support for Google repositories
- Added some new menu options for opening the release notes and checking for new versions
- Switching repositories will no longer reset the selected resource and query
- Editing or creating a repository connection will now automatically select the repository instead of resetting the selection
- To prevent conflicts with editing, session credentials will now be requested upon initiating the first search request, instead of when selecting the repository
- Fixed bug where search bar could appear as a white box instead of correctly rendering
- Fixed bug where requesting the next page while sending the query as a POST request would not work for some repositories
- Fixed bug where the authentication code flow window could get stuck right before completing the authentication

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
