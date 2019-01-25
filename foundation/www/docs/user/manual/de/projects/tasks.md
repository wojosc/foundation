<!-- add-breadcrumbs -->
# Vorgänge


Ein Projekt wird in Vorgänge unterteilt. In ERPNext können Sie auch Abhängigkeiten zwischen Vorgängen erstellen.

<img class="screenshot" alt="Aufgabe" src="{{docs_base_url}}/assets/img/project/task.png">

### Status des Vorgangs

Ein Vorgang kann folgende Stati haben: "Offen", "In Arbeit", "Wartet auf Überprüfung", "Geschlossen" und "Abgebrochen".

<img class="screenshot" alt="Aufgabe - Status" src="{{docs_base_url}}/assets/img/project/task_status.png">

* Standardmäßig sollte jeder neu erstellte Vorgang den Status "Offen" haben.
* Wenn ein Zeitprotokoll für einn Vorgang gebucht wird, ändert sich Status zu "In Arbeit".

### Abhängige Vorgänge

Sie können eine Liste von abhängigen Vorgängen im Bereich "Hängt ab von" erstellen.

<img class="screenshot" alt="Anhängigkeiten" src="{{docs_base_url}}/assets/img/project/task_depends_on.png">

* Sie können einen übergeordneten Vorgang erst dann schließen, wenn die äbhängigen Vorgänge geschlossen wurden.
* Wenn sich die in Abhängigkeit stehenden Vorgänge verzögern und sich mit dem voraussichtlichen Startdatum der übergeordneten Aufgabe überlappt, aktualisiert das System den übergeordneten Vorgang.

### Zeitmanagement

ERPNext verwendet [Zeitprotokolle](/docs/user/manual/de/projects/time-log.html) um den Fortschritt eines Vorgangs mitzuprotokollieren. Sie können mehrere unterschiedliche Zeitprotokolle zu jedem Vorgang erstellen. Das aktuelle Start- und Enddatum kann dann zusammen mit der auf dem Zeitprotokoll basierenden Kostenberechnung aktualisiert werden.

* Um ein zu einem Vorgang erstelltes Zeitprotokoll anzuschauen, klicken Sie auf "Zeitprotokolle".

<img class="screenshot" alt="Aufgabe - Zeitprotokoll ansehen" src="{{docs_base_url}}/assets/img/project/task_view_time_log.png">

<img class="screenshot" alt="Aufgabe - Liste der Zeitprotokolle" src="{{docs_base_url}}/assets/img/project/task_time_log_list.png">

* Sie können ein Zeitprotokoll auch direkt erstellen und mit einem Vorgang verknüpfen.

<img class="screenshot" alt="Aufgabe - Zeitprotokoll verknüpfen" src="{{docs_base_url}}/assets/img/project/task_time_log_link.png">

### Vorgangsmanagement

Sie können [Aufwandsabrechnungen](/docs/user/manual/de/human-resources/expense-claim.html) mit einem Vorgang verbuchen. Das System aktualisiert den Gesamtbetrag der Auslagenabrechnung im Abschnitt Kostenberechnung.

* Um eine Auslagenabrechnung, die zu einem Vorgang erstellt wurde, anzuschauen, klicken Sie auf "Aufwandsabrechnung".

<img class="screenshot" alt="Aufgabe - Aufwandsabrechnung ansehen" src="{{docs_base_url}}/assets/img/project/task_view_expense_claim.png">

* Sie können eine Auslagenabrechnung auch direkt erstellen und sie mit einem Vorgang verknüpfen.

<img class="screenshot" alt="Aufgabe - Aufwandsabrechnung verknüpfen" src="{{docs_base_url}}/assets/img/project/task_expense_claim_link.png">

* Der Gesamtbetrag der Auslagenabrechnung zu einem Vorgang wird unter "Gesamtbetrag der Auslagenabrechnungen" im Abschnitt Kostenabrechnung angezeigt.

<img class="screenshot" alt="Aufgabe - Gesamtsumme Aufwandsabrechnung" src="{{docs_base_url}}/assets/img/project/task_total_expense_claim.png">

{next}

