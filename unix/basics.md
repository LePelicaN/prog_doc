
# File manipulation

## Search and replace
`sed -i 's/seached_text/replacement_text/g' file` : replace `searched_text` by `replacement_text` in `file`

`sed '/^search=.*/a text_on_new_line' file` : search for `search=.*` and append `text_on_new_line` after
