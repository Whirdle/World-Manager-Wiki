## Guide for using private worlds
Private worlds are currently in beta and only available to selected testers.

Private worlds are for more advanced builders to have as much space and resources as they need whatever they may need. 

World owners have the ability to:
- Choose from different world generation types

- Opt in to mob usage/access mob editing tools

- Opt in to Increased world height limit

- Pin a world to have priority and prevent automatic expiriation

- Trust users

- Kick users

- Download worlds


## Syntax
> `<argument>` indicates a required argument
>
> `[argument]` indicates an optional argument with a default value if its not specified
>
> `subcommand|sc` indicates aliases


## usage
__Creating worlds:__
> `/world create <type> [owner]`
>
> `<type>` specifies the type of world. Available types [here](updatethis)
>
> `[owner]` specifies the owner of the world. Defaults to sender


__(Admin only) Registering worlds:__
> `/world register <directory> [owner]`
>
> `<directory>` specifies the folder to regisrer as a world
>
> `[owner]` specifies the owner of the world. Defaults to sender


__Teleporting to your own world:__
> `/world home|h [#]`
>
> `[#]` specifies which world if you have multiple. Defaults to 1


__Teleporting to other worlds:__
> `/world visit|v|tp <owner> [#]`
>
> `<name>` specifies the user whose world you’re trying to visit
>
> `[#]` specifies which world if the owner has multiple. Defaults to 1


__World info:__
> `/world info|i [world]`
>
> `[world]` specifies the world to fetch information about


__World trusting:__
> `/world trust|t <user>`
>
> `<user>` specifies who you’re trusting to the world

__Removing players:__
> `/world remove <user>`
>
> `<user>` specifies the user to remove trust from

__Kicking:__
> `/world kick|k <user>`
>
> `<user>` specifies who you’re kicking from the world


__(Mod only) List all worlds:__
> `/world list all`


__(Mod only) List users worlds:__
> `/world list user <user>`
>
> `<user>` specifies whose worlds to list


__List own worlds__
> `/world list mine`
