# Home-Assistant
Home Assistant Configuration

The time has come to restart my home assistant journey with a brand new config layout.

I will be using Franck's config as inspiration to be more organised as my smart home evolves. Franck's repository can be found at https://github.com/frenck/home-assistant-config

I typically use Node-Red for my automations.

The development branch is to be used to test configs before merging with the master which is to be seen as the production version.

Name convention for files.
    If an entity folder can hold files for multiple types or locations then use the following:
        type_location_description
    eg: Shelly folder could contain lights, switches etc.
        light_kitchen_downlights
    for all others use:
        location_description
    If description requires multiple words then separate with '_' & lower case should be used.
    
With Home Assistant making further changes towards the .storage folder some of the configuration entries in this repository might change in favour of moving to the .storage method.