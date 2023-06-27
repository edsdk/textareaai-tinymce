<p align="center">
    <a href="https://textarea.ai/"><img src="https://textarea.ai/img/favicons/logo-90.png" alt="Textarea.AI" width="90" /></a>
</p>

<h1 align="center" style="margin-top:-20px">Textarea.AI</h1>

<p align="center">
    <strong>ChatGPT plugin for TinyMCE for fast copyrighting and writing texts with AI. </strong>
</p>

<p align="center">
    <a href="https://textarea.ai/">Home page</a> ∙ <a href="https://textarea.ai/doc/install-chat-gpt-tinymce-plugin/">Install</a> ∙ <a href="https://codepen.io/textarea-ai/pen/oNQLYgN">Try Online</a>
</p>

## Intro

This is a **ChatGPT plugin for CKEditor 4**. It can help to generate texts with AI and publish it on your website.

If you have already installed and use [N1ED](https://n1ed.com) plugin, please do not install this one: ChatGPT is included into N1ED. Use this Textarea.AI ChatGPT add-on when you need just a GPT features only.

### Main features:

- Seamless integration with TinyMCE
- Easy installation as CKEditor plugin
- All the power of GPT-4 in your TinyMCE
- Press a toolbar button or Ctrl+Enter everywhere to generate a text! With selection or not, it is very smart.

## Installation

[Download ChatGPT plugin](https://textarea.ai/download/chat-gpt-tinymce.zip)

Copy `chat-gpt` directory into `tinymce/plugins/`.
You will have such file path as result: `tinymce/plugins/chat-gpt/plugin.js`.

### Pass parameters

When you pass parameters to TinyMCE manually as function argument, do the same but inside config structure:
```js
tinymce.init(
  {
     plugins: "chat-gpt",
     apiKey: "TXAIDFLT", // Default key. Get own: https://textarea.ai/dashboard
     toolbar: "TextareaAI TextareaAILess TextareaAIMore | link | undo redo | styleselect | bold italic | alignleft aligncenter alignright alignjustify | outdent indent",
  }
);
```
## Configuration

Please check that you switched the plugin to use your API key, you can get it here: [https://textarea.ai/dashboard](Dashboard).

## Support

Please do not hesitate to ask any questions regarding installation or using sending a letter to [support e-mail](support@helpdesk.edsdk.com).