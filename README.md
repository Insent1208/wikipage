# wikipage
Wiki-Para_Server

## Recursos Importantes
- **Configuración de Modelos (Espadas/Hachas) (Nexo)**: `c:\Users\Insent\Desktop\DRAKONIA-SFTP\plugins\Nexo\pack\assets\minecraft\items`
- **Configuración de Mobs (MythicMobs)**: `c:\Users\Insent\Desktop\DRAKONIA-SFTP\plugins\MythicMobs\mobs`
- **Configuración de Spawns (RandomSpawns)**: `c:\Users\Insent\Desktop\DRAKONIA-SFTP\plugins\MythicMobs\randomspawns`
- **Configuración de Accesorios (MMOItems)**: `c:\Users\Insent\Desktop\DRAKONIA-SFTP\plugins\MMOItems\item`

## Guía de Extracción de Texturas
Para encontrar la textura correcta de un accesorio y su nombre en el juego:

1. **MMOItems**: Ir a `plugins/MMOItems/item/` y abrir el archivo del accesorio (ej. `ring.yml`).
2. Buscar el item (ej. `DADO_MALDITO`) y anotar:
    - `material` (ej. `BLACK_DYE` o `TINTE_NEGRO`)
    - `custom-model-data` (ej. `20041`)
    - `name` (Nombre a mostrar en la Wiki, ej. `Dado Maldito`)
3. **Nexo**: Ir a `plugins/Nexo/items/` y abrir el archivo correspondiente al material (ej. `tinte_negro.yml`).
4. Buscar el `custom_model_data` (ej. `20041`).
5. Encontrar la ruta del modelo en `Pack -> model` (ej. `tinte_negro:item/lesser_melee_crit_chance`).
6. El nombre de la imagen PNG es el último nombre de la ruta (ej. `lesser_melee_crit_chance.png`).
7. Buscar esta imagen en `plugins/Nexo/pack/assets/[namespace]/textures/item/` y copiarla a la wiki.
