# Daily Automatic Light Color Adjustment

This blueprint allows you to automatically adjust the color and brightness of selected lights based on the day of the week. The configuration includes the option to specify a fixed time that determines when the settings change for the next day, covering the period until the same time the following day.

## Features

- Adjust lights based on the day of the week.
- Define specific RGB color and brightness for each day.
- Set a daily time threshold to determine the transition between days.
- Optionally enable or disable the adjustment for specific days.
- Use a boolean entity to control when the automation is active (optional).

## Inputs

- `entity_lights`: The lights you want to adjust.
- `boolean_entity`: Optional boolean entity to enable or disable the automation.
- `fixed_start_time`: The time threshold that determines when adjustments apply, covering the period until the same time the following day.
- For each day of the week (Monday to Sunday):
    - Enable or disable the adjustment.
    - Select an RGB color.
    - Set the brightness percentage.

## Example Usage

1.  Choose the lights to adjust and the time threshold.
2.  Configure specific colors and brightness levels for each day of the week.
3.  Optionally, select a boolean entity to control automation activation.

---

# Regolazione Automatica del Colore delle Luci Giornaliero

Questo blueprint permette di regolare automaticamente il colore e la luminosità delle luci selezionate in base al giorno della settimana. La configurazione include la possibilità di specificare un orario fisso che determina quando le impostazioni cambiano, coprendo il periodo fino alla stessa ora del giorno successivo.

## Caratteristiche

- Regola le luci in base al giorno della settimana.
- Definisci un colore RGB specifico e la luminosità per ciascun giorno.
- Imposta una soglia oraria giornaliera per determinare il passaggio tra i giorni.
- Abilita o disabilita l'adeguamento per giorni specifici.
- Usa un'entità boolean per controllare quando l'automazione è attiva (opzionale).

## Input

- `entity_lights`: Le luci che vuoi regolare.
- `boolean_entity`: Entità boolean opzionale per abilitare o disabilitare l'automazione.
- `fixed_start_time`: La soglia oraria che determina l'inizio di un nuovo giorno. Le modifiche hanno effetto da quest'ora fino alla stessa ora del giorno successivo.
- Per ogni giorno della settimana (da Lunedì a Domenica):
    - Abilita o disabilita la regolazione.
    - Seleziona un colore RGB.
    - Imposta la percentuale di luminosità.

## Esempio d'Uso

1.  Seleziona le luci da regolare e la soglia oraria.
2.  Configura colori e livelli di luminosità specifici per ciascun giorno della settimana.
3.  Facoltativamente, seleziona un'entità boolean per controllare l'attivazione dell'automazione.
