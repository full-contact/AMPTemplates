# AMP Templates
For the AMP community to share Generic Module templates.

# Making generic module templates
See the wiki article for the module: https://github.com/CubeCoders/AMP/wiki/Configuring-the-'Generic'-AMP-module

You can also use the online configurator at https://config.getamp.sh/ to help with building templates.

# Sharing Templates
Right now the following restrictions apply to templates that may be publicly shared via this repository (some of these will be relaxed over time):

 - The application must not require any login/authentication in order to download (except for SteamCMD logins).
 - If the application does not have a Linux version you should add a Proton download via SteamCMD to support it if possible.
 - Applications that have customizable settings must use a Settings Manifest.
 - Only applications that expose some kind of Console that AMP is able to pick up.
 - Do not invoke any shell scripts/batch files. You must only launch actual executables.
 
# To share a template

Create a pull request containing the following files in the top-level directory of the repository:

    *APPLICATIONAME*.kvp
    *APPLICATIONAME*config.json
    *APPLICATIONAME*metaconfig.json (Optional)

With the names fully lower-cased.

For example, `valheim.kvp`, `valheimconfig.json`, `valheimmetaconfig.json`

Do not use any directories and include no-other files.

