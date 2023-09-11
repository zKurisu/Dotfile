This is just a perl script for dotfile configuration.

You can set the environment variable `$DOTCONFIG` to store your `config.json` file, which is used to configure this script. The format is below:
```json
{
   "password" : "xxx",
   "config name" : "xxx",
   "description" : "xxx",
   "update time" : "xxx",
   "last push time" : "xxx",
   "last link time" : "xxx",
   "dotfiles" : {
      "nvim" : "xxx",
   },
   "repository" : "xxx",
   "user" : "xxx"
}
```

These dotfiles will be stored in `$HOME/.config/dotfiles` on your local machine.

You can check the usage by:
```
dm --help
```

