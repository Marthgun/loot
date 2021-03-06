**************
Initialisation
**************

When LOOT is run, it will attempt to detect which of the supported games are installed. If a :ref:`default game <default-game>` has been set, LOOT will run for it, otherwise it will run for the same game as it last ran for. If the relevant game cannot be detected, or if there is no record of the last game LOOT ran for, it will run for the first detected game.

LOOT can also be launched with the ``--game=<game folder name>`` command line parameter to set the game to run for. If the supplied game folder name is valid, the default and last game values are ignored. The default folder names are ``Oblivion``, ``Skyrim``, ``Fallout3``, ``FalloutNV`` and ``Fallout4``.

If LOOT cannot detect any supported game installs, it will immediately open the :doc:`Settings dialog <settings>`. There you can edit LOOT’s settings to provide a path to a supported game, after which you can select it from the game menu.

Once a game has been set, LOOT will scan its plugins and load the game’s masterlist, if one is present. The plugins and any metadata they have are then listed in their current load order.

If LOOT detects that it is the first time you have run that version of LOOT, it will display a "First-Time Tips" dialog, which provides some information about the user interface that may not be immediately obvious.
