# PRL

## Some suggestions when writing TeX codes (To be added)

[Reference](http://stackoverflow.com/a/6190412)

* Use separate line for each sentance.
* Put chapters in separate files if necessary.
* No trailing space.
* Use non-breaking space `~` before citation:
```TeX
See~\cite{Watson68}
```
* Use `\@` before period `.` to indicate the end of a sentance.
* Label management: use format like `chap-intro`, `fig-earth` and `tab-moon`. Be explicit.
* In figures and tables, put `\label{}` after the caption to ensure a corrrect reference.
* When writing in English, use `cf.` to indicate a comparison, whereas in French `cf.` can also mean ``voir''.
