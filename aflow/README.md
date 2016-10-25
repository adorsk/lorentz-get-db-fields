1. Browse to http://aflowlib.duke.edu/aflowwiki/doku.php?id=documentation:all_keywords
2. In browser console, run:
  ```Array.prototype.slice.call(document.querySelectorAll('.toc .level3 a')).map(a => a.innerHTML).join("\n")```

