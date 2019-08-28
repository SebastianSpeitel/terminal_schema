### Reason

The repo aims to create a JSON schema for the config file of the [Windows Terminal](https://github.com/microsoft/terminal).
Using this schema editors can help you configure your terminal by providing autocompletions and warnings about missing options.

### Based on

The documention this schema is based on can be found [here](https://github.com/microsoft/terminal/blob/master/doc/cascadia/SettingsSchema.md).
I try to keep up to date with changes added there.

### ToDos

There are currently many things left to do. Most of them are marked using schema comments (`"$comment":"TODO"`).

Feel free to contribute.

### Usage

#### VisualStudio
When opening a JSON file in VisualStudio open the schema dropdown and select 
> https://raw.githubusercontent.com/SebastianSpeitel/terminal_schema/master/schema_4.json

by pasting it into it.
After that you should be able to use autocomplete.

Schema version 4 has to be used, because VS doesn't support draft 7 yet.
