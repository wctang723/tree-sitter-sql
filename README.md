# tree-sitter-sql
Just make some minor customization for postgresql for myself.
Refer to the original project here: https://github.com/DerekStride/tree-sitter-sql

## Installation
Change the install_info if using the nvim-treesitter plugin. 

* Set the nvim-treesitter config something like this:
  ```lua
  require('nvim-treesitter.parsers').sql = {
    install_info = {
      branch = 'gh-pages',
      revision = '97fa0d71d9e2f9273097f07ea311c2463b4b0b1e'
      url = 'https://github.com/wctang723/tree-sitter-sql',
      generate = false,
      generate_from_json = false,
      -- queries = 'queries',
  },
  ```
