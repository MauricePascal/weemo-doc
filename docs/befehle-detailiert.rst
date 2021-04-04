*******
Befehle
*******

.. contents:: Inhalte

Befehle eingeben
================

Befehle werden eingegeben, indem man ``w#befehl Argumente`` eingibt.

Alle Befehle
============

Nützliches
----------

userinfo
^^^^^^^^

``w#userinfo <User>``

Zeigt Informationen über das Mitglied an.
Sollte ``User``  nicht angegeben werden, wird der eigene Account genommen.

**Parameter**

* **User** - Name oder Erwähnung des Mitglieds, dessen Infos man sehen möchte.

**Benötigte Rechte**

* Weemo:

  * Links einbetten

* Mitglied: *keine*

**Beispiel**

``w#userinfo @Weemo``

``w#userinfo Tina``

``w#userinfo``

serverinfo
^^^^^^^^^^

``w#serverinfo``

Zeigt Informationen über den Server an.

**Parameter:** *keine*

**Benötigte Rechte**

* Weemo:

  * Links einbetten

* Mitglied: *keine*

**Beispiel**

``w#serverinfo``

roleinfo
^^^^^^^^

``w#roleinfo [Rolle]``

Zeigt Informationen über die Rolle an.

**Parameter**

* **Rolle** - Name oder Erwähnung der Rolle, dessen Infos man sehen möchte.

**Benötigte Rechte**

* Weemo:

  * Links einbetten

* Mitglied: *keine*

**Beispiel**

``w#userinfo @Admin``

``w#userinfo Mitglied``

.. warning:: Falls der Befehl über die Erwähnung der Rolle eingegeben wird, so werden alle Mitglieder mit dieser Rolle benachrichtigt.

channelinfo
^^^^^^^^^^^

``w#channelinfo [#Textkanal]``

Zeigt Informationen über den Textkanal an.

**Parameter**

* **#Textkanal** - Erwähnung des Textkanals, dessen Infos man sehen möchte.

**Benötigte Rechte**

* Weemo:

  * Links einbetten
  * Nachrichten lesen (für den erwähnten Kanal)

* Mitglied: *keine*

**Beispiel**

``w#channelinfo #bot-befehle``

emoteurl
^^^^^^^^

``w#emoteurl [Emote]``

Zeigt die URL eines Discord-Emotes an, mit der der Emote heruntergeladen werden kann.

**Parameter**

* **Emote** - Das Emote, dessen URL man haben möchte. Muss ein Server-Emoji sein, Discord Eigene Emojis werden nicht erkannt.

**Benötigte Rechte**

* Weemo:

  * Links einbetten

* Mitglied: *keine*

**Beispiel**

``w#userinfo 🐙``

.. note:: Die Discord-Eigenen Emojis können von folgender Seite heruntergeladen werden: https://twemoji.twitter.com/

avatar
^^^^^^
``w#avatar <User>``

Gibt den Link zum Profilbild des Nutzers zurück.
Sollte ``User``  nicht angegeben werden, wird der eigene Account genommen.

**Parameter**

* **User** - Name oder Erwähnung des Mitglieds, dessen  man sehen möchte.

**Benötigte Rechte**

* Weemo:

  * Links einbetten

* Mitglied: *keine*

**Beispiel**

``w#avatar @Weemo``

``w#avatar Tina``

``w#avatar``

Fun
---

Profil
----------

Konto
-----

Serverpunkte
------------

Serververwaltung
----------------

Musik
-----

Anime
-----

Weemo
-----

Private Sprachkanäle
--------------------

Bildgeneration
--------------

Spielstatistiken
----------------
