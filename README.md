# User Configuration Manager

A small settings manager built with Python dictionaries — add, update, delete, and view user settings with input validation.

## Features

- **add_setting:** adds a key-value pair to the settings dictionary, with duplicate-key and format checks
- **update_setting:** updates an existing setting, validating the key exists and the value format is correct
- **delete_setting:** removes a setting by key, with a not-found message
- **view_settings:** displays all settings with capitalized keys, or a "no settings" message

## How to Run

```bash
python main.py
```

## What I Learned

1. **f-strings:** variables need `{}` — everything else is literal text
2. **Indentation decides everything:** an assignment placed in the wrong block silently changes behavior (stored value vs returned message)
3. **Dict operations:** assign to store, `del` to remove — and compare like types (a dict is never equal to `''`)
4. **Exact output matters:** the tests compare spacing, punctuation, and trailing newlines — one stray space fails a test
5. **Read failures carefully:** each failing test said exactly what was wrong; the skill is reading the feedback precisely

---

*Built as part of my Software Engineering learning journey at SSUET.*
