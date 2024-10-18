# Daily Automatic Light Color Adjustment

## Description

This Home Assistant blueprint adjusts the color and brightness of selected lights based on the day of the week. The automation allows you to configure color, brightness, and time periods for each day of the week. It runs every minute and adjusts the lights accordingly. The time period can be set based on a fixed time or sunrise/sunset, with optional offsets.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fdriin0%2Fdaily-light-adjustment-blueprint%2Fblob%2Fmain%2Fdaily_automatic_light_color_adjustment.yaml)

## Features

- Automatically adjusts lights every day based on customizable time periods and colors.
- Supports optional `input_boolean` to control whether the automation is active.
- Allows setting different colors and brightness levels for each day of the week.
- Supports both fixed time or sunrise/sunset as starting and ending times for the automation period.
- Configurable sunrise/sunset offsets to fine-tune the timing of the automation.
- Adjustments take effect from a defined threshold time (default: 12:00 PM) each day.

## Inputs

- **Lights to adjust**: Select the lights that will be automatically adjusted.
- **Optional boolean entity**: Select an `input_boolean` to control whether the automation is active (optional).
- **Threshold Time**: The time from which daily changes take effect until the same time on the next day.
- **Start Time Type**: Select the start time type: Fixed Time, Sunrise, or Sunset.
- **Start Time for Automation**: Specify a fixed start time if you select "Fixed Time".
- **End Time Type**: Select the end time type: Fixed Time, Sunrise, or Sunset.
- **End Time for Automation**: Specify a fixed end time if you select "Fixed Time".
- **Sunrise Offset**: Offset (in minutes) for sunrise.
- **Sunset Offset**: Offset (in minutes) for sunset.
- **Enable \[Day\]**: Enable or disable the automation for each day (Monday-Sunday).
- **\[Day\] RGB Color**: RGB color for each day.
- **\[Day\] Brightness (percent)**: Brightness level (percentage) for each day.

## Conditions

- The automation only runs if the optional `input_boolean` is active (if provided).
- The automation runs within the specified time range (start time to end time) every day.

## Installation

1.  Go to your Home Assistant dashboard.
2.  Navigate to **Settings** > **Automations & Scenes** > **Blueprints**.
3.  Click on the **Import Blueprint** button and paste the blueprint URL.
4.  Configure the blueprint according to your needs and create an automation.

---

# Regolazione Automatica del Colore delle Luci su Base Giornaliera

## Descrizione

Questo blueprint per Home Assistant regola il colore e la luminosità delle luci selezionate in base al giorno della settimana. L'automazione permette di configurare colore, luminosità e periodi di tempo per ogni giorno della settimana. Si esegue ogni minuto e regola le luci di conseguenza. Il periodo di tempo può essere impostato su un'ora fissa o alba/tramonto, con offset opzionali.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fdriin0%2Fdaily-light-adjustment-blueprint%2Fblob%2Fmain%2Fdaily_automatic_light_color_adjustment.yaml)

## Funzionalità

- Regola automaticamente le luci ogni giorno in base a periodi di tempo e colori personalizzabili.
- Supporta un `input_boolean` opzionale per controllare se l'automazione è attiva.
- Consente di impostare colori e livelli di luminosità diversi per ogni giorno della settimana.
- Supporta sia orari fissi che alba/tramonto come orario di inizio e fine del periodo di automazione.
- Offset configurabili per alba/tramonto per regolare con precisione l'orario dell'automazione.
- Le modifiche prendono effetto dall'orario soglia definito (predefinito: 12:00) ogni giorno.

## Input

- **Luci da regolare**: Seleziona le luci che saranno regolate automaticamente.
- **Entità boolean opzionale**: Seleziona un `input_boolean` per controllare se l'automazione è attiva (opzionale).
- **Ora Soglia**: L'ora a partire dalla quale le modifiche giornaliere prendono effetto fino alla stessa ora del giorno successivo.
- **Tipo di Ora di Inizio**: Seleziona il tipo di ora di inizio: Ora Fissa, Alba o Tramonto.
- **Ora di Inizio per l'Automazione**: Specifica un'ora di inizio fissa se selezioni "Ora Fissa".
- **Tipo di Ora di Fine**: Seleziona il tipo di ora di fine: Ora Fissa, Alba o Tramonto.
- **Ora di Fine per l'Automazione**: Specifica un'ora di fine fissa se selezioni "Ora Fissa".
- **Offset Alba**: Offset (in minuti) per l'alba.
- **Offset Tramonto**: Offset (in minuti) per il tramonto.
- **Abilita \[Giorno\]**: Abilita o disabilita l'automazione per ogni giorno (Lunedì-Domenica).
- **Colore RGB \[Giorno\]**: Colore RGB per ogni giorno.
- **Luminosità \[Giorno\] (percentuale)**: Livello di luminosità (percentuale) per ogni giorno.

## Condizioni

- L'automazione si esegue solo se l'`input_boolean` opzionale è attivo (se fornito).
- L'automazione viene eseguita all'interno dell'intervallo di tempo specificato (ora di inizio a ora di fine) ogni giorno.

## Installazione

1.  Vai alla tua dashboard di Home Assistant.
2.  Naviga su **Impostazioni** > **Automazioni & Scene** > **Blueprints**.
3.  Clicca sul pulsante **Importa Blueprint** e incolla l'URL del blueprint.
4.  Configura il blueprint secondo le tue esigenze e crea un'automazione.
