# Prosty język

Skill (i prompt) do upraszczania treści po polsku. Upraszcza, pomaga przy pracy i uczy. Oparty na Checkliście Prostego Języka Barbary Adamskiej i Kaliny Tyrkiel-Szymańskiej, 2026 (edycja pierwsza: 2022).

Korzystaj z narzędzia przez agenta AI (np. w Cursor, Claude Code lub w podobnych narzędziach) lub przez wklejony prompt w czacie.

## Info

Pamiętaj, że odpowiedzi narzędzia to tylko sugestie. Mogą Ci pomóc w pracy i nauce, ale nie zawsze są poprawne. Zawsze weryfikuj odpowiedzi AI.

## Co jest w folderze

| Plik | Po co |
| --- | --- |
| [SKILL.md](SKILL.md) | instrukcje dla agenta (Cursor, Claude Code, inne skille) |
| [checklist.md](checklist.md) | pełna checklista |
| [fiszki.md](fiszki.md) | uzasadnienia i źródła |
| [examples.md](examples.md) | pary przed / po |
| [prompt.md](prompt.md) | wersja do wklejenia tam, gdzie nie ma skilli |

## Cztery tryby

Na starcie agent pyta (albo rozpoznaje z prośby):

1. **Uprość** — proponuje prostszą wersję i krótkie „co zostało zmienione”
2. **Sprawdź** — audyt checklistą (cytat → reguła → propozycja), a na końcu pytanie: „Czy chcesz zobaczyć przykładową przepisaną wersję?”
3. **Naucz** — jedna fiszka i mini-ćwiczenie
4. **Napisz od zera** — dopyta o odbiorcę, cel i kanał, potem napisze

## Instalacja: Cursor

Skill osobisty (wszystkie projekty):

```bash
git clone <adres-tego-repo> ~/prosty-jezyk
mkdir -p ~/.cursor/skills/prosty-jezyk
cp ~/prosty-jezyk/SKILL.md ~/prosty-jezyk/checklist.md ~/prosty-jezyk/fiszki.md ~/prosty-jezyk/examples.md ~/.cursor/skills/prosty-jezyk/
```

Albo skopiuj cały ten folder do `~/.cursor/skills/prosty-jezyk/`.

Skill tylko w jednym projekcie: ten sam zestaw plików w `.cursor/skills/prosty-jezyk/` w repozytorium projektu.

W Cursorze możesz też napisać: „użyj skilla prosty język” i wkleić tekst.

## Instalacja: Claude Code

```bash
mkdir -p ~/.claude/skills/prosty-jezyk
cp SKILL.md checklist.md fiszki.md examples.md ~/.claude/skills/prosty-jezyk/
```

W projekcie: `.claude/skills/prosty-jezyk/` z tymi samymi plikami.

## Inne IDE ze skillami (np. Copilot)

Wskaż agentowi plik `SKILL.md` (custom instructions / agent skill). Obok muszą leżeć `checklist.md`, `fiszki.md` i `examples.md` — skill do nich odsyła.

## ChatGPT, Gemini i inne czaty bez skilli

1. Otwórz [prompt.md](prompt.md).
2. Skopiuj całość.
3. Wklej jako instrukcję niestandardową, custom GPT albo pierwszą wiadomość systemową.
4. Potem wklej tekst do uproszczenia albo napisz, czego potrzebujesz.

`prompt.md` jest samowystarczalny. Nie wymaga pozostałych plików.

## Autorki

Barbara Adamska, Kalina Tyrkiel-Szymańska, 2026.
