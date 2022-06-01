# IIS URL Reservation 
URL Reservation Problem
```
http://localhost/Reports
http://localhost/Reportserver
```
Above both URL reserved for SQL Reporting Services
## How to GET URL Reservation List
```
netsh http show urlacl
```
Ref URL: https://docs.microsoft.com/en-us/sql/reporting-services/install-windows/about-url-reservations-and-registration-ssrs-configuration-manager?view=sql-server-ver16

## How to Delete URL Reservation
```
netsh http delete urlacl url=http://+:80/Reports
```
Ref URL:https://docs.microsoft.com/en-us/dotnet/framework/wcf/feature-details/how-to-replace-the-wcf-url-reservation-with-a-restricted-reservation
