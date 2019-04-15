# DolDoc
A document type to display pretty things.

commands are bracketed with `$`s.
- `<CTRL-l>`: Insert a text widget via menu. automate building of command.
- `<CTRL-t>`: Toggle between interpreted DolDoc and source.

Grammar stright from the os:
```
<DolDocCmd> := $<TwoLetterCmd>[<FlagList][,<ArgList>]$ | $ColorName$
<FlagList> := +|- <FlagCode>[<FlagList>]
<ArgList> := <ArgCode>=<ArgExpression>[,<ArgList>]
```

## Widget help

![doldoc_widget_help](/images/doldoc_widget_help.PNG "Help for the doldoc widget")     
