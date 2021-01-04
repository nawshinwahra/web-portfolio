Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Try the new cross-platform PowerShell https://aka.ms/pscore6

PS C:\Users\wahra> cd H:
PS H:\> ls


    Directory: H:\


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
da----        12/13/2020  12:58 PM                BAT
d-----          5/6/2019  10:54 AM                libery
da----         6/15/2019  11:56 AM                medicine supplychain tracibility
d-----         4/24/2019   8:33 PM                My Backups
d-----         9/19/2020  11:33 AM                New folder
d-----         10/6/2020   6:41 PM                New folder (2)
da----         6/15/2019  11:56 AM                Online_Voting_System
d-----          1/4/2021  11:23 AM                programing hero
d-----        12/16/2020  12:13 PM                recuitment
da----         6/15/2019  11:57 AM                thesis
da----         6/15/2019  11:56 AM                thesis doc
d-----         12/8/2018   9:41 PM                unity
da----         6/15/2019  11:56 AM                visio file
d-----         9/22/2020   7:43 PM                zingobin
-a----          5/8/2019  12:42 AM         389731 INTRODUCTION.docx
-a----         5/11/2019   3:11 PM        4868942 medicine supplychain tracibility.zip
-a----         12/1/2006  11:37 PM         904704 msdia80.dll


PS H:\> cd /programing hero\module-3
Set-Location : A positional parameter cannot be found that accepts argument 'hero\module-3'.
At line:1 char:1
+ cd /programing hero\module-3
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : InvalidArgument: (:) [Set-Location], ParameterBindingException
    + FullyQualifiedErrorId : PositionalParameterNotFound,Microsoft.PowerShell.Commands.SetLocationCommand



PS H:\>
PS H:\>
PS H:\>
PS H:\> ls


    Directory: H:\


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
da----        12/13/2020  12:58 PM                BAT
d-----          5/6/2019  10:54 AM                libery
da----         6/15/2019  11:56 AM                medicine supplychain tracibility
d-----         4/24/2019   8:33 PM                My Backups
d-----         9/19/2020  11:33 AM                New folder
d-----         10/6/2020   6:41 PM                New folder (2)
da----         6/15/2019  11:56 AM                Online_Voting_System
d-----          1/4/2021  11:23 AM                programinghero
d-----        12/16/2020  12:13 PM                recuitment
da----         6/15/2019  11:57 AM                thesis
da----         6/15/2019  11:56 AM                thesis doc
d-----         12/8/2018   9:41 PM                unity
da----         6/15/2019  11:56 AM                visio file
d-----         9/22/2020   7:43 PM                zingobin
-a----          5/8/2019  12:42 AM         389731 INTRODUCTION.docx
-a----         5/11/2019   3:11 PM        4868942 medicine supplychain tracibility.zip
-a----         12/1/2006  11:37 PM         904704 msdia80.dll


PS H:\> cd programinghero
PS H:\programinghero> ls


    Directory: H:\programinghero


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----          1/4/2021  11:22 AM                module-2
d-----          1/4/2021  11:25 AM                module-3


PS H:\programinghero> cd module-3
PS H:\programinghero\module-3> git clone https://github.com/ProgrammingHero1/complete-web-development-bangla-resources.git

Cloning into 'complete-web-development-bangla-resources'...
remote: Enumerating objects: 34, done.
remote: Counting objects: 100% (34/34), done.
remote: Compressing objects: 100% (34/34), done.
remote: Total 107 (delta 1), reused 28 (delta 0), pack-reused 73 eceiving objects:  96% (103/107), 59.05 MiB | 412.00 KiReceiving objects
Receiving objects: 100% (107/107), 59.29 MiB | 333.00 KiB/s, done.
Resolving deltas: 100% (2/2), done.
PS H:\programinghero\module-3>