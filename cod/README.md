1. Browse to http://www.crystallography.net/archives/doc/CODDictionary.xml 
2. In browser console, run:
  ```
  Array.prototype.slice.call(document.querySelectorAll('#menu a')).map(a => a.innerText).join("\n")
  ```
