    # 🌱 Bodenfeuchte Alarm System
    **Version 5.0**

    Intelligente Pflanzenüberwachung – flexibel, zonenbasiert und vollständig konfigurierbar.

    Überwacht einen Bodenfeuchte-Sensor (numerisch). Bei Unterschreiten eines Grenzwerts wird (optional wiederholt) per **Alexa (notify.alexa_media)**, **Anhaltende Benachrichtigung** und/oder **Mobile App** benachrichtigt.

    Optional kann eine **„Feuchtigkeit wieder OK“-Info** gesendet werden, sobald der Wert stabil über dem Grenzwert liegt.

    Alexa-Durchsagen erfolgen nur, wenn sich eine ausgewählte **Person oder ein Device Tracker in einer frei wählbaren Zone** befindet.

    Die Nachtsteuerung wurde erweitert: **Getrennte Nachtmodi für Alexa, Mobile App und Anhaltende Benachrichtigung** ermöglichen maximale Flexibilität.

    Neu in 5.0: **Alexa Lautstärke temporär setzen und danach wiederherstellen** (pro Gerät).

    ---

    <details>
    <summary><b>🌵 Trocken-Alarm</b></summary>

    - Frei definierbarer Grenzwert
    - Hysterese gegen Sensor-Flattern
    - Verzögerung vor Auslösung
    - Wiederholung optional (5–180 Minuten)
    - Cooldown-Schutz gegen Mehrfachauslösung
    - Optimierung: Wiederhol-Loop „schläft“, wenn aktuell kein Kanal senden darf

    </details>

    <details>
    <summary><b>🌿 OK-Rückmeldung</b></summary>

    - Optional aktivierbar
    - Separate Steuerung je Benachrichtigungskanal
    - Verzögerung gegen direktes Zurückspringen

    </details>

    <details>
    <summary><b>🔔 Benachrichtigungskanäle</b></summary>

    - Alexa Trocken EIN/AUS
    - Alexa OK EIN/AUS
    - Anhaltende Benachrichtigung Trocken EIN/AUS
    - Anhaltende Benachrichtigung OK EIN/AUS
    - Mobile Trocken EIN/AUS
    - Mobile OK EIN/AUS
    - Mobile Geräteauswahl per Dropdown (mobile_app)

    </details>

    <details>
    <summary><b>📍 Zonen- & Anwesenheitslogik</b></summary>

    - Alexa nur bei Anwesenheit
    - Frei wählbare Zone
    - Unterstützt Person & Device Tracker

    </details>

    <details>
    <summary><b>🌙 Erweiterte Nachtmodi</b></summary>

    - Separater Nachtmodus für Alexa
    - Separater Nachtmodus für Mobile App
    - Separater Nachtmodus für Anhaltende Benachrichtigung
    - Start- und Endzeit je Kanal definierbar
    - Funktioniert über Mitternacht hinweg

    </details>

    <details>
    <summary><b>🔊 Alexa Lautstärke (neu)</b></summary>

    - Optional: Lautstärke vor Ausgabe setzen
    - Danach pro Gerät wiederherstellen
    - Funktioniert für Trocken & OK

    </details>

    ---
