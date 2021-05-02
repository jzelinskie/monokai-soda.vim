# monokai soda

A "soda ash" variant of Monokai.

Built on the wonderful [colorbuddy.nvim]

[colorbuddy.nvim]: https://github.com/tjdevries/colorbuddy.nvim

## install

Use your package manager of choice, just remember to add the requirement on colorbuddy.

Here's an example using [packer]:

[packer]: https://github.com/wbthomason/packer.nvim

```lua
local packer = require('packer').startup {
  function(use)
    use { 'jzelinskie/monokai-soda.vim', requires = 'tjdevries/colorbuddy.vim' }
  end,
}
```
