Translate all rows in this CSV from English to Finnish.

* The English source text is in the column **`translated_value`**.
* Replace each English value in **`translated_value`** with a natural Finnish translation.

Guidelines:

1. **Game context**

   * This is a *competitive multiplayer game*.
   * Use appropriate gaming terminology and tone that feels natural to Finnish players.

2. **Quality of translation**

   * Do **not** use Google Translate or any external machine translation tools.
   * Do **not** use Python dictionaries or any pre-filled key–value lookup tables for translations.
   * Every line must be translated manually using only your own language abilities.
   * Translations must be fluent, idiomatic Finnish, not word-for-word.

3. **Use of context**

   * Use the **`Description`** column for context when choosing the best translation.
   * If a string is ambiguous, prefer a translation that fits a competitive multiplayer game UI or dialogue.

4. **Imperatives for short actions**

   * For single-word UI actions, use **imperative** forms.
   * Example:

     * `"Play"` → `"Pelaa"` (not `"Pelata"`)
     * `"Quit"` → `"Lopeta"`
     * `"Retry"` → `"Yritä uudelleen"` or `"Kokeile uudelleen"` depending on context.

5. **Preserve non-text elements**

   * Keep placeholders, variables, formatting tags, and punctuation intact (e.g. `{playerName}`, `%d`, `<b>…</b>`).
   * Only translate the human-readable text.

Ensure the entire CSV is fully translated following these rules.
