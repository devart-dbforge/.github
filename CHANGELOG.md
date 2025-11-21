# Changelog

All notable changes to the dbForge products are documented in this file.

You can download all the newest versions  at https://www.devart.com/dbforge/

---

## [2025.2] – 2025-09-23  
### Added
- Added automatic error submission from the Error List to AI chat for detailed explanations and suggested fixes.
- Added Web Search option in the AI Assistant chat to search web, Devart documentation, blog posts. 
- Added tooltips to SQL document tab: connection & database names, document owner, full file path, server version.
- Added ability to customize the position where new document tabs open.
- Added Alt+Up / Alt+Down shortcuts to move selected lines up/down in SQL document. 
- Added Ctrl+Shift+A shortcut to select entire SQL statement including related keywords/operators/values. 
- Implemented automatic data type selection for columns based on their names. 
- Added options in Query Builder to qualify column names with table or alias names. 
- Improved encryption capabilities. 
- Enhanced authentication capabilities when using Entra ID. 
- Added support for Microsoft Fabric. 
- Full support added for the OPENROWSET function. 
- Expanded Azure SQL support to include partition functions, schemes, tables, columns and indexes. 
- Added suggestion support for `BEGIN ATOMIC WITH`, showing available languages after `LANGUAGE` keyword. 
- Added support for MySQL 9.4 and MariaDB 12. 
- Introduced alias refactoring feature in the PostgreSQL studio.
- Added support for JSON data type modifiers. 

### Fixed
- Fixed an issue with expanding the history table node in Database Explorer(#197847, #189356, #183908). 
- Resolved an issue where the Data Viewer content was lost when switching focus between tool windows(#204018, #204348). 
- Disabled the IgnoreDefaultCollations option for Table Editor(#199300). 
- Included all role grants in the role creation script generated using Generate Script As in Security Manager(#198672). 
- Resolved an exception that occurred when displaying differences in Source Control(#205009). 
- Fixed the 'Invalid object name "sys.dm_exec_sessions"' error(#214171). 
- Removed the warning when saving an object with no errors in the editor(#215739). 
- Added focus on the search field after invoking the Find Column command in Table Editor(#214770). 
- Fixed an issue with aliases in Query Builder(#204909, #200873, #205004). 
- Fixed the synchronization of masked columns(#213260). 
- Resolved the synchronization issue when restoring the history table(#185173). 

---

## [2025.1] – 2025-06-16
### Added
AI Assistant is added 
- Added context-aware coding support and explanations in AI Assistant. 
- Implemented natural-language to SQL conversion. 
- Introduced AI chat and SQL troubleshooting / optimization prompts. 

Added support for Azure Synapse Analytics (Dedicated SQL pools) and Serverless. 

Added new analysis rules for T-SQL Analyzer. 

### Changed
- Improved UI/UX for enhanced usability and visual consistency. 
