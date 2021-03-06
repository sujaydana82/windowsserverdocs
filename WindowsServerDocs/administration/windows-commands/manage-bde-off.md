---
title: manage-bde off
description: Reference topic for **** -

ms.prod: windows-server


ms.technology: manage-windows-commands

ms.topic: article
ms.assetid: 0a27c119-d385-45e5-89fe-e311d4429876
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/16/2017
---

# manage-bde: off



Decrypts the drive and turns off BitLocker. All key protectors are removed when decryption is complete.

## Syntax

```
manage-bde -off [<Volume>] [-computername <Name>] [{-?|/?}] [{-help|-h}]
```

#### Parameters

|Parameter|Description|
|---------|-----------|
|\<Volume>|A drive letter followed by a colon, a volume GUID path, or a mounted volume.|
|-computername|Specifies that Manage-bde.exe will be used to modify BitLocker protection on a different computer. You can also use **-cn** as an abbreviated version of this command.|
|\<Name>|Represents the name of the computer on which to modify BitLocker protection. Accepted values include the computer's NetBIOS name and the computer's IP address.|
|-? or /?|Displays brief Help at the command prompt.|
|-help or -h|Displays complete Help at the command prompt.|

## Examples

To illustrates using the **-off** command to turn off BitLocker on drive C.
```
manage-bde –off C:
```

## Additional References

- [Command-Line Syntax Key](command-line-syntax-key.md)
-   [Manage-bde](manage-bde.md)