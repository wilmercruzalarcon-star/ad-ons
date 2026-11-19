# SuperKing Illegal Survival — Java 26.3 (Fabric)

Port del addon Bedrock de SrTheKing. Todo funciona del lado del servidor
(en mundo individual no hace falta nada más que Fabric + Fabric API).

## Qué hace
- Agacharte con un objeto en la mano (o equipado) lo encanta con los encantamientos que le faltan, según tu perfil.
- Menú: `/superking menu` o clic derecho con un palo (palo renombrado «cm» = alterna Supervivencia/Creativo).
- Conservar inventario (regla del mundo) desde el menú; el juego comprueba tus permisos.
- Mensaje de bienvenida una sola vez.

## Compilar
Requiere JDK 25. Si no tienes el wrapper de Gradle, genera una plantilla en https://fabricmc.net/develop
(Minecraft 26.3) y copia dentro `src/`, para usar sus versiones exactas. Luego:

    gradle build

El .jar queda en `build/libs/` (no uses el `-sources`). Ponlo en `.minecraft/mods/` junto a Fabric API.

## Créditos
Ver CREDITOS.txt del pack original (HoldToEnchant, KeepInventory de Mikayil022, Creative Mode de VoxenMC2).
Los permisos de redistribución de esos packs no están verificados.
