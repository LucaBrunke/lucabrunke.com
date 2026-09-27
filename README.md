# lucabrunke.com

Redirects every address on lucabrunke.com to https://lucabrunke.eu (the site itself lives in
[lucabrunke.github.io](https://github.com/LucaBrunke/lucabrunke.github.io)).

`404.html` is identical to `index.html`, so old WordPress links (e.g. `/blog/...`) are caught too
and sent to the closest matching page. Edit the mapping in the `<script>` block of both files.
