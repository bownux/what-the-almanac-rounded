# Proof fixes after the Pass-3 panel (v2 → v2.1 candidate)

v2 (`56e01b5`) is the text under the judge. These four changes answer the residuals the
Pass-3 seats left for the judge. None adds or removes a scene. They are offered as proof
corrections: apply them before typesetting if the judge signs v2, or carry them into a v3 if
the judge rejects.

| # | Raised by | Where | Change | Why |
|---|---|---|---|---|
| 1 | Seat C, blocking #1 and suggestion 1 | ch16, Tamsin's first line at the lectern | "That's the Almanac's. It's for the week's rain, not for the season. It was four in the middle of August. It's up from seven." (was: "It's the highest it's been since the middle of August.") | The book has two different nines: the August season chance (9% [3–17], chance of a normal year's water, ch12) and the 19 October weekly rain chance (9% [5–15], ch16). Seat C read them as one number with two referents. The sheet in ch16 already names its referent; Tamsin now says so aloud, and the series 4 → 7 → 9 matches CONTINUITY. The 5 October sheet's seven percent is the previous week's figure, which is why she says "up from seven". |
| 2 | Seat C, suggestion 3 | ch11, Dellen's ledger | "The third had no heading, only a small unsteady question mark." (was: "The third, with a small unsteady question mark, was left without a heading at all.") | The old sentence could be read as "no heading" and "a question mark" at once. The tick under *Roque, D.* is in the question-mark column, so "I'm a question mark" was already true; the heading is now unambiguous. |
| 3 | Seat C, suggestion 4 | ch08, Odd on the tolls | "In eight weeks." (was: "In seven weeks.") | First sale on a Saturday in the first week of February; in the book's calendar 6 April is a Thursday, so that Saturday is 4 February. 4 February to 31 March is 55 days, a day short of eight weeks. CONTINUITY.md updated. |
| 4 | Seat B, blocking #1 | fiction-audit.json, `narrator.uncertainty_policy` and thread `almanac-wants` | Audit text now says the Almanac claims a want once, in ch16 ("I find that I want it to be on the record that a nine percent is not a zero"), and leaves what that is open. | The audit contradicted the manuscript. Prose unchanged. |

Not changed, with reasons:

- Seat C blocking #2 (Bell Year "seventeen" vs "sixteen"): the Almanac was installed twenty-two
  years before the story; the Bell Year is its fifth year, so seventeen years before; the
  footer was added in the sixth year, after the Bell Year, so "sixteen years" on the wall
  (ch11, ch13). The two counts are different things and both hold. Ages (Dellen 46, Ilka 36)
  sit inside the one-year slack that birthdays give.
- Seat C suggestion 2 (Wren's notebook): it was in v1 (delivered ch11, read ch12), so it does
  not appear in the v1→v2 delta the seat was given.
- Seat C suggestions 5 and 6 (direct-address lines; the ch09 four-beat absolution): voice
  decisions; left to the judge.
