# Fitxa tècnica: Instal·lació i configuració de Git

## Objectiu

Instal·lar Git en un ordinador, configurar les dades bàsiques de l'usuari i comprovar que el programa funciona correctament.

## Materials

- Ordinador amb connexió a Internet.
- Sistema operatiu Windows, Linux o macOS.
- Connexió a Internet.
- Accés a un repositori de pràctiques.
- Git.

![Esquema del funcionament de Git](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png)

## Procediment

1. Descarregar Git des de la pàgina oficial.
2. Instal·lar Git seguint les opcions recomanades per l'instal·lador.
3. Obrir un terminal o una consola de Git.
4. Comprovar la versió instal·lada amb l'ordre `git --version`.
5. Configurar el nom de l'usuari amb l'ordre `git config --global user.name "Nom Cognom"`.
6. Configurar el correu electrònic amb l'ordre `git config --global user.email "correu@example.com"`.
7. Crear o clonar el repositori de pràctiques.
8. Crear dins del repositori el fitxer `fitxa-tecnica.md`.
9. Afegir-hi la informació de la pràctica.
10. Guardar els canvis i comprovar que el fitxer apareix correctament al repositori.

## Comprovacions

- [ ] Git està instal·lat correctament.
- [ ] La versió de Git es mostra amb `git --version`.
- [ ] El nom d'usuari està configurat.
- [ ] El correu electrònic està configurat.
- [ ] El fitxer `fitxa-tecnica.md` existeix dins del repositori.
- [ ] La imatge es visualitza correctament.
- [ ] El document té totes les seccions requerides.

## Incidències i solucions

| Incidència | Solució |
|---|---|
| Git no està instal·lat | Descarregar i instal·lar Git des de la pàgina oficial. |
| L'ordre `git` no es reconeix | Comprovar la instal·lació i reiniciar el terminal. |
| El nom d'usuari no està configurat | Executar `git config --global user.name "Nom Cognom"`. |
| La imatge no es mostra | Comprovar que l'URL de la imatge és correcte i que hi ha connexió a Internet. |

## Recursos

- [Documentació oficial de Git](https://git-scm.com/doc)
- [Documentació de GitHub](https://docs.github.com/)
- [Descarrega Git](https://git-scm.com/downloads)
```