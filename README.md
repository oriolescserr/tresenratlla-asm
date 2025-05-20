# Pràctica 2 - Joc del Tres en Ratlla (Simulador Von Neumann)

**Assignatura:** Estructura de Computadors 2  
**Quadrimestre:** 2n, Curs 2024/25  
Grau: Enginyeria Informàtica (Universitat de Lleida - Campus Igualada)  
**Alumne:** Oriol Escolà Serra  
**Nota obtinguda:** 10/10
**Pes a l’assignatura:** 15%

## Objectiu

Desenvolupar un programa en llenguatge ensamblador per al Simulador KIT Von Neumann, implementant el joc clàssic del Tres en Ratlla amb interacció mitjançant teclat i pantalla, optimitzat al màxim nivell i complint amb tots els requisits obligatoris i opcionals.

## Instal·lació i execució

1. Descarrega el simulador des del repositori: https://github.com/jvilaplana/SimuladorVonNeumann.
2. Descomprimeix el fitxer ZIP en una carpeta de treball.
3. Obre i edita els fitxers `.ens` amb un editor.
4. Compila el programa:
   
   ```bash
   Ensambla.exe nom-del-fitxer.ens
   ```
6. Executa el simulador:
   
   ```bash
   VonNeuman.exe
   ```

## Característiques del joc

- Neteja automàtica de pantalla i buffer del teclat a l'inici.
- Dibuix d’un tauler 3x3 amb coordenades clares.
- Entrada de coordenades per part de cada jugador.
- Validació de coordenades i comprovació de caselles ocupades.
- Impressió del símbol corresponent: X per al jugador 1 i O per al jugador 2.
- Comprovació de 3 en ratlla en totes les direccions.
- Detecció de final de partida i tauler ple.
- Missatge de guanyador personalitzat.

### Extres implementats

- Entrada del nom dels jugadors al començament de la partida.
- Opció de jugar una altra partida un cop finalitzada la primera, reiniciant totes les dades.
- Codi altament comentat i estructurat en procediments modulars per facilitar la lectura i manteniment.
- Optimització del rendiment i l'eficiència del codi.

## Autor

Oriol Escolà Serra  
Estudiant d’Enginyeria Informàtica  
Universitat de Lleida – Campus Igualada  
LinkedIn: https://www.linkedin.com/in/oriolescserr

## Llicència

Aquest projecte està desenvolupat amb finalitats educatives.  
No es permet copiar aquest codi per a entregues acadèmiques sense autorització prèvia.
