# Counties To Character Culture(for Hybrid Cultures)
 Trying to get  counties to character culture via this mod 
 Normally type this in debug mode : 
effect = {
            set_global_variable = { name = char_culture value = root.culture }
        }
        What this does is it stores the root culture that is any culture your character belongs to even hybrid cultures.
 Then you type in this :
        effect = {
            script_effect = { name = set_culture_to_global_var }
        }
        And this applies your characters cultures to all the counties your character holds