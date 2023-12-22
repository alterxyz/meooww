# meooww

Good bye ChatGPT plugin and meooww

再见啦 ChatGPT 插件作为很早就获得了开发者权限的幸运之人, 感谢~

以及你好GPTs

以及喵嗷嗷

简单做一个会让ChatGPT会说喵嗷嗷的插件作为纪念吧哈哈.

---

替换了logo, logo是使用DALL-E简单生成的, prompt如下:

```text
A cute tricolor Maine Coon cat sitting beside two checkboxes, one checked and one empty, in a playful and adorable style, as part of a To-Do list app illustration
```

Plugin for id complete-manifest-6e92cb9c-7234-437a-b765-78802486d9fe not found

本地运行的常见错误. 我们可以看到, 这个插件的id是 complete-manifest-6e92cb9c-7234-437a-b765-78802486d9fe.

```text
Validated manifest
Validated OpenAPI spec
Prompt for ChatGPT
```

这个错误的原因估计是, 我们在本地运行的时候, 会自动加载本地的插件, 但是在ChatGPT上运行的时候, 会自动加载线上的插件.

以及however, 我们成功地在本地加载了这个插件, 只是在ChatGPT上运行的时候, 却出现了这个错误.

![Image description](2023-12-22%20033932.png)

GLHF!~ 冬季安康!~

- [ ] GPTs的尝试

---

Get a todo list ChatGPT plugin up and running in under 5 minutes using Python. This plugin is designed to work in conjunction with the [ChatGPT plugins documentation](https://platform.openai.com/docs/plugins). If you do not already have plugin developer access, please [join the waitlist](https://openai.com/waitlist/plugins).

## Setup locally

To install the required packages for this plugin, run the following command:

```bash
pip install -r requirements.txt
```

To run the plugin, enter the following command:

```bash
python main.py
```

Once the local server is running:

1. Navigate to [ChatGPT](https://chat.openai.com).
2. In the Model drop down, select "Plugins" (note, if you don't see it there, you don't have access yet).
3. Select "Plugin store"
4. Select "Develop your own plugin"
5. Enter in `localhost:5003` since this is the URL the server is running on locally, then select "Find manifest file".

The plugin should now be installed and enabled! You can start with a question like "What is on my todo list" and then try adding something to it as well!

## Setup remotely

### Cloudflare workers

### Code Sandbox

### Replit

## Getting help

If you run into issues or have questions building a plugin, please join our [Developer community forum](https://community.openai.com/c/chat-plugins/20).
