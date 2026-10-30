# Product brief — Cabin Guest App

## Problem statement
Guests of a short-term rental cabin need reliable basic information at each moment of the stay, and the host needs to stop answering the same questions by message.

## Goals
1. Give guests one link with the essential and most frequently asked information for before, during and around the stay.
2. Reduce repetitive host messages.
3. Raise the perceived quality of check-in and communication.

## Non-goals
- Booking or payments (handled by the rental platform).
- Interactive Q&A or real-time chat with the host (kept on the platform).

## Requirements (MoSCoW)

| Priority | Requirement |
|---|---|
| Must | Readable and usable on a phone screen with a slow connection |
| Must | Arrival, check-in, house rules and emergency contacts on the landing page |
| Must | Content covers the questions guests ask most often |
| Must | No access codes on the site; codes reach booked guests through the platform welcome message |
| Should | Tourist guide reachable in one tap from the landing page |
| Should | Content editable by the host without a developer |
| Could | English version |
| Won't (now) | User accounts or login per guest |

## Acceptance criteria (examples)

- Given a guest on a phone, when they open the link, then they find check-in steps without scrolling past more than one screen.
- Given a guest on the landing page, when they tap the tourist guide icon, then the tourist guide opens and offers a way back.
- Given someone who receives a forwarded link, when they open any page, then they find no lockbox, door or alarm code.

## Success metrics
See the README section "How I would measure success".
