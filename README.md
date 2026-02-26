# AntiSpawnKill

Plugin para **SCP: Secret Laboratory** (EXILED/LabAPI) que protege a jugadores recién spawneados de ser asesinados inmediatamente.

## Funcionalidad

- Otorga invulnerabilidad temporal a jugadores al spawnear.
- Previene spawn-killing en zonas de respawn.
- Duración de protección configurable.
- Compatible con EXILED y LabAPI según configuración de build.

## Configuración

| Opción | Descripción | Default |
|--------|-------------|---------|
| `IsEnabled` | Activa/desactiva el plugin | `true` |
| `Debug` | Muestra logs de depuración | `false` |
| `ProtectionDurationSeconds` | Duración de la protección en segundos | `5` |

## Compilación

```bash
dotnet build .\plugin AntiSpawnKill\AntiSpawnKill.csproj -c EXILED
```

## Instalación

Copiar `AntiSpawnKill-EXILED.dll` a `EXILED/Plugins/` y reiniciar el servidor.
