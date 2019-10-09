Folder contains all files that we got from Zynga by emails or slack. All files are saved as is without any modifications.

Folder structure:
* `configs` - production config files from CouchDB
* `repository-structures` - we asked Zynga to create structure of real repositories. No data, just file names
    * [farm2_locale.tree](repository-structures/farm2_locale.tree) - Farm 2
    * [poker_locale.tree](repository-structures/poker_locale.tree) - Contains Poker and Poker2.  
    Also, there is Key to File Path Mapping [Poker_Poker2 Key to File Path Mapping.txt](repository-structures/Poker_Poker2%20Key%20to%20File%20Path%20Mapping.txt)
    * [zindagi_locale.tree](repository-structures/zindagi_locale.tree) - CrazyCakeSwap
* `jenkins-jobs` - Dump of jenkins jobs 
    * [ccs_translate_config.xml](jenkins-jobs/ccs_translate_config.xml) - CrazyCakeSwap upload source files
    * [ccs_deliver_config.xml](jenkins-jobs/ccs_translate_config.xml) - CrazyCakeSwap download translated files
    * [farm2_translate_config.xml](jenkins-jobs/ccs_translate_config.xml) - Farm 2 upload source files
    * [farm2_deliver_config.xml](jenkins-jobs/ccs_translate_config.xml) - Farm 2 download translated files
* `resource-files` - Real source and translated files for game. Was added here just for demo purposes
