# Ultimate Packet Radio (UPR) — rodzina aplikacji packet radio

[English version](#english-version)

Ultimate Packet Radio (UPR) to rodzina powiązanych aplikacji i narzędzi dla krótkofalowców
korzystających z packet radio, AX.25 oraz transportu KISS. Projekty są
rozdzielone na osobne repozytoria, ale mają wspólną nazwę, branding i kierunek
rozwoju.

## Projekty

| Projekt | Opis | Repozytorium |
| --- | --- | --- |
| **UPR Node** | Node packet radio dla Linuksa i Raspberry Pi. Obsługuje AX.25, KISS/TCP, podstawowe sesje, digipeater oraz konfigurację przez panel WWW. | Link zostanie uzupełniony |
| **UPR Station** | Samodzielna stacja packet radio z backendem, panelem WWW oraz wariantem desktopowym. Obejmuje m.in. sesje AX.25, KISS, MailBox, beacony, MHeard, digipeater i YAPP. | Link zostanie uzupełniony |
| **UPR Terminal** | Terminal connected-mode packet radio dla AX.25 przez KISS/TCP lub port szeregowy, z pełnoekranowym interfejsem tekstowym i obsługą wielu sesji. | Link zostanie uzupełniony |
| **UPR UI Template** | Referencyjny, niezależny od frameworka szablon interfejsu WWW używany jako punkt wyjścia dla aplikacji rodziny UPR. | Link zostanie uzupełniony |
| **UPR Branding** | Wspólne zasady identyfikacji wizualnej, logo i sposób oznaczania aplikacji należących do rodziny UPR. | Link zostanie uzupełniony |
| **Dokumentacja packet radio** | Materiały dotyczące AX.25, KISS, TNC, connected mode, digipeatingu i diagnostyki, oddzielone od dokumentacji konkretnych aplikacji. | Link zostanie uzupełniony |

## Wspólne założenia

- projekty korzystają z technologii i protokołów stosowanych w packet radio;
- AX.25 jest podstawą komunikacji radiowej, a KISS jednym z obsługiwanych
  sposobów komunikacji z modemem lub TNC;
- poszczególne aplikacje mają różne role i mogą być rozwijane niezależnie;
- wspólny branding i UI Template pomagają zachować spójność całej rodziny;
- funkcje dostępne w konkretnym projekcie należy sprawdzać w jego własnej
  dokumentacji i pliku README.

## Status

Projekty są rozwijane niezależnie i mogą znajdować się na różnych etapach
dojrzałości. Aktualny status, ograniczenia oraz instrukcje uruchomienia są
opisane w repozytoriach poszczególnych aplikacji.

## Dla użytkowników i współtwórców

To repozytorium pełni funkcję strony głównej rodziny Ultimate Packet Radio (UPR). Szczegółowy
kod, konfiguracja, budowanie i zgłaszanie problemów powinny być prowadzone w
odpowiednim repozytorium projektu.

---

<a id="english-version"></a>

# Ultimate Packet Radio (UPR) — packet radio application family

Ultimate Packet Radio (UPR) is a family of related applications and tools for amateur radio
operators using packet radio, AX.25 and KISS transport. The projects are kept
in separate repositories, while sharing a common name, branding and overall
direction.

## Projects

| Project | Description | Repository |
| --- | --- | --- |
| **UPR Node** | A packet radio node for Linux and Raspberry Pi. It supports AX.25, KISS/TCP, basic sessions, digipeating and web-based configuration. | Link to be added |
| **UPR Station** | A standalone packet radio station with a backend, web panel and desktop variant. It includes AX.25 sessions, KISS, MailBox, beacons, MHeard, digipeating and YAPP. | Link to be added |
| **UPR Terminal** | A connected-mode AX.25 packet radio terminal using KISS/TCP or a serial port, with a full-screen text interface and support for multiple sessions. | Link to be added |
| **UPR UI Template** | A framework-neutral reference web interface used as a starting point for UPR applications. | Link to be added |
| **UPR Branding** | Shared visual identity guidelines, logo assets and naming rules for applications in the UPR family. | Link to be added |
| **Packet radio documentation** | Materials covering AX.25, KISS, TNCs, connected mode, digipeating and diagnostics, separated from application-specific documentation. | Link to be added |

## Shared principles

- the projects use technologies and protocols used in packet radio;
- AX.25 is the basis for radio communication, while KISS is one of the
  supported ways to communicate with a modem or TNC;
- individual applications have different roles and can be developed
  independently;
- shared branding and the UI Template help keep the family consistent;
- features available in a particular project should be verified in that
  project's own documentation and README.

## Status

The projects are developed independently and may be at different maturity
levels. Current status, limitations and setup instructions are documented in
the repositories of the individual applications.

## For users and contributors

This repository is the home page for the Ultimate Packet Radio (UPR) family. Detailed code,
configuration, build instructions and issue tracking should be handled in the
repository of the relevant project.
