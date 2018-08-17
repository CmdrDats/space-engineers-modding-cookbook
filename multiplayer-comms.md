# Multiplayer communication principles

Cover multiplayer checking, server/client responsibility guidelines, communication principles to make for robust, but efficient MP mods.

Thanks @Phoera on KSH Discord for this handy snippet:
```csharp
        /// <summary>
        /// DS server
        /// </summary>
        public static bool IsDedicated
        {
            get
            {
                return MyAPIGateway.Utilities.IsDedicated;
            }
        }
        /// <summary>
        /// Can draw something
        /// </summary>
        public static bool IsClient
        {
            get
            {
                return !IsDedicated;
            }
        }
        /// <summary>
        /// Can rule them all!
        /// </summary>
        public static bool IsServer
        {
            get
            {
                return IsDedicated || MyAPIGateway.Multiplayer.IsServer;
            }
        }

        public static bool IsMultiplayer
        {
            get
            {
                return MyAPIGateway.Session.SessionSettings.OnlineMode != VRage.Game.MyOnlineModeEnum.OFFLINE;
            }
        }
```
