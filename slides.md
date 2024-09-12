---
# try also 'default' to start simple
theme: seriph
background: https://cover.sli.dev
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS
css: unocss
fonts:
  serif: Oswald
  sans: Inter

themeConfig:
  primary: '#23a3dd'

title: WTF is OSS?
titleTemplate: "%s"
hideInToc: true
favicon: /favicon.png
---

# WTF is OSS?

Eine kurze Einführung in die Welt der Open Source Software

---

# Was ist Open Source Software?

Open Source Software (OSS) ist Software, deren Quellcode öffentlich zugänglich ist. Nutzer können den Quellcode einsehen, verändern und weiterverteilen. Die Hauptmerkmale von Open Source Software sind:

1.	Freie Verfügbarkeit: Der Quellcode ist für jeden zugänglich, der ihn einsehen oder herunterladen möchte.
2.	Änderbarkeit: Benutzer dürfen den Quellcode modifizieren, um die Software an ihre eigenen Bedürfnisse anzupassen oder zu verbessern.
3.	Weiterverteilung: Die veränderte oder unveränderte Software kann frei weitergegeben werden.
4.	Offene Entwicklung: Die Softwareentwicklung erfolgt oft kollaborativ und öffentlich, mit Beiträgen von Entwicklern aus der ganzen Welt.

Open Source Software steht meist unter speziellen Lizenzen, wie der GNU General Public License (GPL),
der Apache License oder der MIT License, die diese Freiheiten rechtlich absichern.

---

# Rollen in einem OSS Projekt

## Maintainer

Der Maintainer ist für die Pflege und Weiterentwicklung des Projekts verantwortlich. Er entscheidet, welche Änderungen in das Projekt aufgenommen werden und welche nicht. Der Maintainer ist oft auch der Hauptentwickler des Projekts.

## Contributor

Ein Contributor ist ein Entwickler, der Code oder andere Beiträge zum Projekt beisteuert. Contributors können neue Funktionen hinzufügen, Fehler beheben oder Dokumentation schreiben.

## User

Ein User ist jemand, der die Software nutzt, aber nicht aktiv an der Entwicklung beteiligt ist. User können Fehler melden, Verbesserungsvorschläge machen oder das Projekt unterstützen, indem sie es bekannter machen.

---

# Begrisserklärung

## Fork

Ein Fork ist eine Kopie eines Projekts, die von einem Contributor erstellt wird, um Änderungen vorzunehmen, die nicht im Originalprojekt aufgenommen werden. Forks können dazu dienen, neue Funktionen zu testen, Fehler zu beheben oder das Projekt in eine andere Richtung zu entwickeln.

## Pull/Change Request

Ein Pull Request (PR) oder Change Request (CR) ist eine Anfrage an den Maintainer, Änderungen in das Projekt aufzunehmen. Der Contributor erstellt eine Kopie des Projekts, fügt seine Änderungen hinzu und schickt sie an den Maintainer. Dieser kann die Änderungen überprüfen und entscheiden, ob sie in das Projekt aufgenommen werden.
