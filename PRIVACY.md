# Política de privacidad de Kinetext

*Última actualización: 27 de noviembre de 2026* · [English below](#kinetext-privacy-policy)

Kinetext es un editor de texto y código para macOS desarrollado por Jordi Sánchez Fernández ([jorch.es](https://jorch.es)). Esta política explica qué datos maneja la aplicación y adónde van.

## Resumen

- Kinetext **no tiene cuentas, publicidad, analítica ni telemetría**. No envía al desarrollador ningún dato tuyo ni de tu uso.
- Tus ficheros, notas y ajustes se quedan **en tu Mac**.
- El **dictado por voz** se transcribe **en tu Mac** con Whisper; el audio no sale del equipo ni se guarda.
- Solo si usas **Claude**, el contenido que le das se envía a **Anthropic** con tu propia cuenta de Claude, y Kinetext te lo pide antes.

## Datos que se quedan en tu Mac

- **Ficheros y proyectos** que abres: Kinetext los lee y escribe donde están, sin copiarlos a ningún servidor.
- **Ajustes, sesión, ficheros recientes, notas y cambios sin guardar**: se guardan en el almacenamiento local de la aplicación.
- **Audio del micrófono**: solo mientras dictas. Se transcribe en el Mac y se descarta; nunca se envía ni se graba en disco.

## Datos que salen del Mac

| Cuándo | Qué se envía | A quién | Para qué |
|---|---|---|---|
| Usas Claude (tras aceptar el aviso) | Lo que escribes en el chat, los ficheros, carpetas y fragmentos que mencionas o que Claude lee del proyecto y la salida de las órdenes que ejecuta | Anthropic, con tu cuenta de Claude | Que Claude responda. Lo trata la [política de privacidad de Anthropic](https://www.anthropic.com/legal/privacy) |
| La primera vez que usas Claude | Una petición de descarga (tu IP) | Visual Studio Marketplace (Microsoft) | Descargar la extensión Claude Code |
| La primera vez que dictas | Una petición de descarga (tu IP) | Hugging Face | Descargar el modelo de Whisper (~1,6 GB) |
| Al abrir, si «Buscar actualizaciones» está activo | Una petición del manifiesto de versiones (tu IP) | GitHub | Saber si hay una versión nueva |
| Operaciones de Git que tú lanzas (push, pull, fetch) | Lo propio de Git | Los servidores remotos que configures | Sincronizar tus repositorios |

Kinetext no comparte, vende ni cede datos a nadie más.

## Tu control

- **Claude**: puedes retirar el permiso en *Ajustes → Claude → Envío de datos a Anthropic aceptado*, o desactivar Claude por completo con *Usar Claude*.
- **Dictado**: se desactiva en *Ajustes → Dictado por voz*. macOS te deja retirar el acceso al micrófono en *Ajustes del Sistema → Privacidad y seguridad → Micrófono*.
- **Actualizaciones**: se desactiva *Buscar actualizaciones al abrir* en *Ajustes → General*.
- **Borrar tus datos**: desinstala la aplicación y borra las carpetas `es.jorch.kinetext` de `~/Library/Application Support`, `~/Library/WebKit` y `~/Library/Caches`. Lo que hayas enviado a Anthropic se gestiona desde tu cuenta de Claude.

## Menores

Kinetext es una herramienta de propósito general y no está dirigida a menores de 13 años. No recoge datos de ningún usuario para el desarrollador.

## Cambios y contacto

Si esta política cambia, se publicará aquí con la nueva fecha. Para cualquier duda, usa el formulario de contacto de [jorch.es](https://jorch.es).

---

# Kinetext privacy policy

*Last updated: 27 November 2026*

Kinetext is a text and code editor for macOS developed by Jordi Sánchez Fernández ([jorch.es](https://jorch.es)). This policy explains what data the app handles and where it goes.

## Summary

- Kinetext has **no accounts, advertising, analytics or telemetry**. It sends the developer no data about you or how you use it.
- Your files, notes and settings stay **on your Mac**.
- **Voice dictation** is transcribed **on your Mac** with Whisper; the audio never leaves the computer and is not stored.
- Only if you use **Claude** is the content you give it sent to **Anthropic**, under your own Claude account, and Kinetext asks you first.

## Data that stays on your Mac

- **Files and projects** you open: Kinetext reads and writes them in place and copies them to no server.
- **Settings, session, recent files, notes and unsaved changes**: kept in the app's local storage.
- **Microphone audio**: only while you dictate. It is transcribed on the Mac and discarded; it is never sent or written to disk.

## Data that leaves your Mac

| When | What is sent | To whom | Why |
|---|---|---|---|
| You use Claude (after agreeing to the notice) | What you type in the chat, the files, folders and snippets you mention or that Claude reads from the project, and the output of the commands it runs | Anthropic, under your Claude account | So Claude can answer. Handled under [Anthropic's privacy policy](https://www.anthropic.com/legal/privacy) |
| The first time you use Claude | A download request (your IP) | Visual Studio Marketplace (Microsoft) | Download the Claude Code extension |
| The first time you dictate | A download request (your IP) | Hugging Face | Download the Whisper model (~1.6 GB) |
| On launch, if "Check for Updates" is on | A request for the release manifest (your IP) | GitHub | Find out whether a new version exists |
| Git operations you start (push, pull, fetch) | What Git sends | The remotes you configure | Sync your repositories |

Kinetext shares, sells or hands over data to no one else.

## Your control

- **Claude**: withdraw permission in *Settings → Claude → Sending Data to Anthropic Accepted*, or turn Claude off entirely with *Use Claude*.
- **Dictation**: turn it off in *Settings → Voice Dictation*. macOS lets you revoke microphone access in *System Settings → Privacy & Security → Microphone*.
- **Updates**: turn off *Check for Updates on Launch* in *Settings → General*.
- **Deleting your data**: uninstall the app and delete the `es.jorch.kinetext` folders in `~/Library/Application Support`, `~/Library/WebKit` and `~/Library/Caches`. What you sent to Anthropic is managed from your Claude account.

## Children

Kinetext is a general-purpose tool and is not directed at children under 13. It collects no user data for the developer.

## Changes and contact

If this policy changes, the new version will be published here with its date. For any question, use the contact form at [jorch.es](https://jorch.es).
