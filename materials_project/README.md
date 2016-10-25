1. run:

  ```
  git clone https://github.com/materialsproject/mapidoc.git
  for F in $(find mapidoc/materials -type f); do echo $F | sed 's/mapidoc\/materials\///' | sed 's/README\.md//'; done | sort | uniq > fields.txt
  ```

