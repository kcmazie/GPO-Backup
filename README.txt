# GPO-Backup
Backs up all group policy settings from the current domain.

         File Name : GPO-Backup.ps1
   Original Author : Kenneth C. Mazie (kcmjr AT kcmjr DOT com)
                   :
       Description : Backs up all group policy settings from current domain. Creates seperate
                   : folders for each policy using the display name arther than the GUID. Emails results
                   :
             Notes : Normal operation is with no command line options.
                   : Optional arguments:
                   : -Console $true (enables local console output)
                   : -Debug $true (redirects email results to debug user)
                   : See example XML file at bottom of script. XML config must be in the same folder as
                   : script and named identically.
                   :
          Warnings : Can be a security risk. Make sure backups go to a secure location.
                   :
             Legal : Public Domain. Modify and redistribute freely. No rights reserved.
                   : SCRIPT PROVIDED "AS IS" WITHOUT WARRANTIES OR GUARANTEES OF
                   : ANY KIND. USE AT YOUR OWN RISK. NO TECHNICAL SUPPORT PROVIDED.
                   : That being said, please report any bugs you find!!
                   :
           Credits : Code snippets and/or ideas came from many sources including but
                   : not limited to the following:
                   :
                   :
    Last Update by : Kenneth C. Mazie
   Version History : v1.00 - 01-16-19 - Original
                   : v2.00 - 00-00-00 -
                   :
