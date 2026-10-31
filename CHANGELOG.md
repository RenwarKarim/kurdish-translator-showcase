# Changelog

What is new in each version of Kurdish Translator. The source code is private.

## 1.1 (2026-10-31)

- Translate: a model menu at the top right of the Translate page. When the chosen model is busy, over a limit or sends no text for 5 seconds, the next model translates that segment, and the line under the translation names it. Each new segment starts with the chosen model again.
- Kurdish to English: American spellings become British spellings by themselves (realise, colour, practise). The line under the result lists each change.
- Transcribe (English + Kurdish): a new way with ElevenLabs, which writes both languages and finds the speakers in one go. Add an ElevenLabs key in Settings, or drop a transcript that you exported from the ElevenLabs website (.json). Gemini then names the speakers with your template's names and translates the Kurdish parts.
- Transcribe: a turn with English and Kurdish stays one row, with the English in the template's English format and the translation in its Kurdish format.
- Transcribe: the rows follow the house style more closely: no commas in English rows, translations without commas, British spelling, and 30-second marks only from the first row on.
- Transcribe with Gemini: a long recording goes in parts of 20 minutes, and your template's speaker names and first rows guide the model. "Continue the template" starts at the time in your last row.

## 1.0 (2026-10-30)

- A new look, in the style of Google Translate: one translator card with a language bar, clear buttons and icons.
- Trados segments (the default): press Ctrl+V on the page. The tool translates the segment and copies the translation for you. Then press Ctrl+V in Trados.
- The direction follows the text that you paste: English goes to Kurdish, Kurdish goes to English.
- The copy is clean for Trados QA: no extra line breaks, spaces, quotation marks or full stops. The LRM marks of your rules stay.
- Several segments at once: one row for each line, Copy next (Enter), and a TMX file for your translation memory.
- Text and PDF views for whole texts. You can edit a translation before you copy it.
- Clear messages when Google is busy, when the daily limit is used up, or when the key does not work. Add or change your key in Settings.
- Help, the version number and this What's new list. Warnings such as [Output cut off] are never copied.
- The browser asks before you leave the page with an unsaved transcript or edited translation.
- Transcription: the tool finds the speakers itself, also people who join later, and lists who they are (for example S5: paramedic, female). Check the list in step 4: it goes under "Speakers:" in the Word file.
- Transcription: S5 [sic] marks a row where the tool is not sure who speaks. [Many people speaking] marks people who talk at the same time.
- Transcription: rows get … where a word breaks off (her… herself), and no full stop at the end. A clearer rule for the model: broken English from a Kurdish speaker is English, not Kurdish.
