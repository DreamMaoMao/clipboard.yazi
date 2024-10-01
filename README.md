# win-clipboard.yazi
Since clipboard tool copies files to a temporary directory every time, it is very slow to copy large files, and the directory is not automatically cleaned, and the temporary directory will gradually occupy a huge disk space. This plug-in only generates temporary file objects according to the path, and the file memory does not occupy the memory and disk space. Copying large files is also faster



## Config

> [!NOTE]
> You need yazi 3.x for this plugin to work.


## Configuration

Copy or install this plugin and add the following keymap to your `manager.prepend_keymap`:

```toml
on = "<C-y>"
run = ["plugin win-clipboard"]
```

