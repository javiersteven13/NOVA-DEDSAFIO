# NOVA authentication

NOVA will not require its own Microsoft Entra application.

## Login model
1. NOVA synchronizes the DEDSAFIO AMIGOS client files.
2. NOVA verifies the local Minecraft/Forge/mod files.
3. NOVA hands the player off to the official Minecraft Launcher for Microsoft/Xbox authentication.
4. The player starts the Forge installation from the official launcher.

This avoids requiring the NOVA owner to create and maintain a custom Entra client registration.

## Important
- NOVA must never collect or store Microsoft passwords.
- NOVA must not bypass Minecraft/Microsoft authentication.
- The public server address is rails-xm.tun.ply.gg.
