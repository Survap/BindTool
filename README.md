# BindTool

An update on InanZen's AdminTools BindTool command.

----------- DIFFERENCES IN THIS VERSION -----------

1. Using /bgl will now execute commands in 'superadmin' group level. This will allow users to perform specific commands without having the required permission for it.
EXAMPLE:
  - You want players to full heal when using some specific item.
  - You don't want people to have access to /heal command.
  - This will allow them to use /heal only when using specified item.

2. Using [Player] token will replace this with the name.
EXAMPLE:
  - You want players to get kicked when using some item.
  - However, you need to input /kick <Username> for it to work.
  - Now, when using [Player], the command will automatically assume it has to be replaced with the username of the player using the item.
