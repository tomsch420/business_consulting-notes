# Real estate management: standing rules
- The code lives in business_consulting.real_estate and reuses Money, Account, Party, BankTransaction, Camt053Format, PartyRegister, Recurrence and BankCalendar rather than copying them.
- A portfolio is declared, not read: a Claude skill writes the landlord's Python file from conversation, as start-mandate writes a mandate.
- Bank data comes from camt.053 exports first; FinTS (R9) only fetches the same statements.
- Consistency problems and arrears are findings reported to the landlord, never exceptions that stop a run.
- A payer is matched by name or IBAN through PartyRegister; a partial match is refused and reported, never guessed.
- Each law a check rests on is linked to gesetze-im-internet.de in its docstring.
- The plan is the roadmap: doc/real_estate_roadmap.md only links to it, and the open points RO1-RO5 stand in section 5 of doc/real_estate_process.md.
