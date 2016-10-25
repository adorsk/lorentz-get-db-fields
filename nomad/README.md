1. Browse to https://nomad-dev.rz-berlin.mpg.de/nomadmetainfo_public/index.html#/public/section_single_configuration_calculation
2. In browser console, run:
  ```
  Array.prototype.slice.call(document.querySelectorAll('#menu a')).map(a => a.innerText).join("\n")
  ```
