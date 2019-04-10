# ASP.NET Core 2.1 Angular SPA on .NET 4.7

This is to test out NSwag integration v11.19.1 with ASP.NET Core 2.1 with Angular SPA client on .NET 4.7.

This was created using the ASP.NET Core wizard in VS 2017 (15.8.4) selecting the Angular option (so using the ASP.NET Core Angular SPA template).

**Update** - Using NSWag v12.1.0 has resolved this issue.  Commit https://github.com/nicholas-brooks/nswag-aspnetcore-netfull-issue/commit/8944968793f47e4d7871044371d0154cc5dd34d4 has the changes necessary to use NSWag 12.1.0.

## Modifications from the generated Template

 - Upgraded to angular6 and typescript 2.7
 - Added NSwag (v11.19.1) and swagger integration to app and clientapp.

Easiest way to see the differences is to diff the commits.


## Credits

 - Jason Taylor (@jasongtau) for ASP.NET Core, Angular and NSWag integration (https://github.com/JasonGT/CodingFlowBuildingSpaSeries)
