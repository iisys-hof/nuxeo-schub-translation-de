# nuxeo-schub-translation-de
Expanded German Nuxeo language file(s)

The file "messages_de_DE.properties" can be included in the following ways:

Option 1: manipulate the specific language file bundle

    The bundle that contains the official language files is called "nuxeo-platform-lang-ext"
    It can be found in /var/lib/nuxeo/server/nxserver/bundles/ and might have a Hotfix-Suffix
    In this file, replace /web/nuxeo.war/WEB-INF/classes/messages_de_DE.properties

Option 2: use dev mode

    Activate Nuxeo's development mode (via the UI, since the config file does not seem to do anything)
    Replace /var/lib/nuxeo/server/nxserver/messages_de*.properties
    Reload the language files using the UI

Option 3: use Nuxeo Studio

    Put the language file in a new package and install it