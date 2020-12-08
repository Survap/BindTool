# BindTool

An update on InanZen's AdminTools BindTool command. 

Modified by Tsviets.

----------- DIFFERENCES IN THIS VERSION -----------

1. Using /bgl will now execute commands in 'superadmin' group level. This will allow users to perform specific commands without having the required permission for it.

-- EXAMPLE:
  - You want players to full heal when using some specific item.
  - You don't want people to have access to /heal command.
  - This will allow them to use /heal only when using specified item.
  - You can set a permission name upon using /bgl to allow/disallow usage for certain groups.

2. Using [Player] token will let you add commands that automatically replace this token with the player's username.

-- EXAMPLE:
  - You want players to get kicked when using some item.
  - However, you need to input /kick "Username" for it to work.
  - Now, when using [Player], the command will automatically assume it has to be replaced with the username of the player using the item.


NOTE: This features are only limited to /bgl command. Other commands from this plugin shouldn't have a need for this.
