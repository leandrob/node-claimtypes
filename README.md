Standar ClaimTypes for Node.js
=============
claimtypes is a collection of standar claimTypes for Node.js

## Installation

```bash
$ npm install claimtypes
```

## Usage

```javascript
var claimtypes = require('claimtypes');

var emailClaimType = claimtypes.email;

// Microsoft Specific ClaimTypes
var windowsAccountNameClaimType = claimTypes.microsoft.windowsAccountName;
```

## ClaimTypes Included

* `actor` is 'http://schemas.xmlsoap.org/ws/2009/09/identity/claims/actor'.
* `anonymous` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/anonymous'.
* `authentication` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/authenticated'.
* `authorizationDecision` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/authorizationdecision'.
* `country` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/country'.
* `dateOfBirth	` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/dateofbirth'.
* `denyOnlySid	` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/denyonlysid'.
* `dns	` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/dns'.
* `email` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/email'.
* `gender` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/gender'.
* `givenName` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/givenname'.
* `hash` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/hash'.
* `homePhone` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/homephone'.
* `locality` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/locality'.
* `mobilePhone` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/mobilephone'.
* `name` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/name'.
* `nameIdentifier` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/nameidentifier'.
* `otherPhone` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/otherphone'.
* `postalCode` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/postalcode'.
* `rsa` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/rsa'.
* `sid` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/sid'.
* `spn` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/spn'.
* `stateOrProvince` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/stateorprovince'.
* `streetAddress` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/streetaddress'.
* `surname` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/surname'.
* `system` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/system'.
* `thumbprint` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/thumbprint'.
* `upn` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/upn'.
* `uri` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/uri'.
* `webpage` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/webpage'.
* `x500DistinguishedName` is 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/x500distinguishedname'

### Microsoft Specific Claim Types

* `authenticationInstant` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/authenticationinstant'.
* `authenticationMethod` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/authenticationmethod'.
* `cookiePath` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/cookiepath'.
* `denyOnlyPrimaryGroupSid` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/denyonlyprimarygroupsid'.
* `denyOnlyPrimarySid` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/denyonlyprimarysid'.
* `denyOnlyWindowsDeviceGroup` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/denyonlywindowsdevicegroup'.
* `dsa` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/dsa'.
* `expiration` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/expiration'.
* `expired` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/expired'.
* `windowsAccountName` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/windowsaccountname'.
* `windowsDeviceClaim` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/windowsdeviceclaim'.
* `windowsDeviceGroup` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/windowsdevicegroup'.
* `windowsFqbnVersion` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/windowsfqbnversion'.
* `windowsSubAuthority` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/windowssubauthority'.
* `windowsUserClaim` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/windowsuserclaim'.
* `userData` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/userdata'.
* `version` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/version'.
* `serialNumber` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/serialnumber'.
* `primaryGroupSid` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/primarygroupsid'.
* `primarySid` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/primarysid'.
* `role` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/role'.
* `groupSid` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/groupsid'.
* `isPersistent` is 'http://schemas.microsoft.com/ws/2008/06/identity/claims/ispersistent'


