<div align="center">
  <img src="icon.png" alt="Anticheat Logo" width="128px">
</div>

# 🛡️ Anticheat Module — JainaCore Sovereign Edition

`mod-anticheat` is an active and passive movement verification module adapted for [JainaCore](https://github.com/DarckRovert/JainaCore_Server) / [AzerothCore](https://www.azerothcore.org/) (WotLK 3.3.5a).

> **Distro Oficial:** Módulo de seguridad pasiva mantenido para el ecosistema **JainaCore 3.3.5a**.  
> Basado originalmente en el proyecto open-source [azerothcore/mod-anticheat](https://github.com/azerothcore/mod-anticheat) y el script PassiveAnticheat de lordpsyan.

### ⚔️ Optimizaciones y Parches para JainaCore:
- **Calibración Anti-Falsos Positivos con Playerbots:** Ajustes en `AnticheatScripts.cpp` para evitar desconexiones espurias o sanciones involuntarias sobre bots autónomos durante saltos, tirones o maniobras de combate táctico.
- **Validación Pasiva de Movimiento:** Supervisión de velocidad, teletransporte y desincronización de splines en tiempo real con cero impacto en la latencia (diff de servidor < 5 ms).
- **Integración con Centinela y Logs:** Enrutamiento de alertas de moderación hacia el canal administrativo de la Consola GM de Project Jaina.

---

## Documentación Original del Upstream (AzerothCore)

[English](.github/README.md) | [Español](.github/README_ES.md) | [Svenska](.github/README_SE.md) | [Portuguese](.github/README_pt_BR.md)

### Wiki Oficial
https://github.com/azerothcore/mod-anticheat/wiki

### How to install
1. Place the module under the `modules` folder of your JainaCore / AzerothCore source folder.
2. Re-run cmake and launch a build of the core.
3. Execute the included SQL files in `data/sql/` on your databases.
