# Code Blocks

Pre-formatted code blocks are used for writing about programming or markup source code. Rather than forming normal paragraphs, the lines of a code block are interpreted literally.

Here is an example:

```
This is a code block
```

To produce a code block in Markdown, simply indent every line of the block by at least 4 spaces or 1 tab.

For example:

```

This is a normal paragraph:

    This is a code block.
```

You can also create code block separated by:

    ```

### Inline code blocks

Inline code blocks can be written using: `

For example:

    This is a `inline code block`

### Syntax highlighting

You can define the language to be used for syntax highlighting by adding the name on the opening tag. Example:

    ```js
    var a = {};
    ```

```

$ yum install -y yum-utils device-mapper-persistent-data lvm2
$ yum-config-manager --add-repo http://mirrors.aliyun.com/docker-ce/linux/centos/docker-ce.repo
$ yum makecache fast
$ yum -y install docker-ce
$ systemctl enable docker
$ systemctl start docker

```