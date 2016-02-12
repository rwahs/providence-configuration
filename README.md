# Providence Configuration
A repository for the local configuration overrides for the RWAHS CollectiveAccess Providence instance.

Read more about [Providence Configuration Files] (http://docs.collectiveaccess.org/wiki/ConfigurationFiles) and their [Syntax] (http://docs.collectiveaccess.org/wiki/Configuration_File_Syntax).

In order to apply this configuration you need to either:

* `define("__CA_LOCAL_CONFIG_DIRECTORY__", "/<path_to_this_directory>");` in *setup.php* _or_
* symlink this directory in to `$COLLECTIVEACCESS_HOME/app/conf/local`
