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

## Two-Letter Commands

![DolDoc_01](/images/DolDoc_01.PNG "Help for the DolDoc Two-Letter Commands")
![DolDoc_02](/images/DolDoc_02.PNG "Help for the DolDoc Two-Letter Commands")
![DolDoc_03](/images/DolDoc_03.PNG "Help for the DolDoc Two-Letter Commands")
![DolDoc_04](/images/DolDoc_04.PNG "Help for the DolDoc Two-Letter Commands")
![DolDoc_05](/images/DolDoc_05.PNG "Help for the DolDoc Two-Letter Commands")
![DolDoc_06](/images/DolDoc_06.PNG "Help for the DolDoc Two-Letter Commands")
![DolDoc_07](/images/DolDoc_07.PNG "Help for the DolDoc Two-Letter Commands")