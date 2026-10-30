ATTENTION! Must read BEFORE updating to v2.0.0. Data breaking update!

Dear user,

Salva has been completely revamped for version 2.0.0. We've made major changes, added a lot of new features and functionality, which required an upgrade to the app's data schema. Unfortunately, your previous transactions, including any backups you have created, are not compatible with this new version. DO NOT PANIC! Your data is still safe and migratable to the new version.

A small migration assistant app is available. It will take a Salva backup file and convert it to match the new schema. To receive this app, please send an email to our developer account (vandanvisions@gmail.com). We will supply a share link that you can use to download the .apk file to your phone. Install the app, use it to convert your Salva backup, then restore your data from the new, converted backup. You can safely uninstall the migration assistant app after that.

To successfully migrate your data to the new version, please follow these steps strictly and in this precise order: 

1. CRITICAL: First and foremost, create a backup of your data.
   (Side menu -> Backup -> Local / Google Drive)
2. Long-press your app icon on your phone and go to **App Info**.
3. Tap **Storage & Cache**.
4. Tap **Clear Storage** (or **Clear Data**). _Must be done BEFORE uninstalling old version!_
5. **Uninstall** the app.
6. Restart your phone (this forces Android to drop any active memory-cached app data bindings).
7. Install the provided Salva Migration Assistant app.
8. Convert your data backup file using the migration assistant app.
   (Uninstall the migration assistant after.)
9. Install the new version of Salva (2.0.0)
10. Restore your data from the new, converted backup.
    (Restore -> Local / Google Drive)

If you have already updated to V2.0.0 and your app is crashing on launch, don't panic, your data is still in the app's internal storage directory. We can provide you with Salva (1.5.3).apk so you can successfully rollback to the older, working version of the app. After downgrading to the previous version, your app should work properly again. Now you can proceed with the steps above.

**2.0.0** Change Log:
- Added new "Linker" feature that allows linking entities to categories such that, if an entity is linked to a category, the category field will auto-fill with the corresponding category on the Add / Edit Transaction page.
- Add Preferences section where the user can select the:
	Theme color
	Transaction card size
	Date format
	Default date filter
	Starting day of week
- Added option to attach images to transactions
- Added option to filter for transactions with image attachments
- Added option to app drawer to export all image attachments
- Added dynamic scroll bar on transaction list to assist with scrolling large lists 
- Added Most Frequent Payee / Debtor on Metrics tab
- Revamped Metrics tab
- Resolved issue where cloning or editing a transaction while on the Calendar page, the transaction list reverted to displaying transactions from the home page instead of current Calendar selection 
- Resolved issue disallowing restricting backup file imports to only .zip
- Improved logic for determining Calendar first and last date
- Corrected logic when calculating number of days in selected period for specific periods
- Corrected sorting directions
- Separated the Debits and Credits totals on the Search page
- Numerous UI improvements
