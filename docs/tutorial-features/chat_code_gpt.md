---
sidebar_position: 1
---
# CodeGPT Chat

The CodeGPT Chat feature enhances your development experience by allowing you to engage in conversations with a Large Language Models (LLM) directly within your text editor. This tutorial will guide you through the steps to make the most of this powerful tool.

## How to Use:
- Open the Chat Tab
- Navigate to the tools tab and click on `Chat` By default, `Gemini-2.5-Flash` will answer on the chat.
- Once the chat tab opens, you can start a conversation by typing a message and hitting `Enter`.
- If you request code, copy or paste it directly into the file with the `Insert code` button which is the arrow on the top right of the code.
- You can clean the chat by clicking on `New chat` button or `Reload` the question

<p align="center">
    <img src="https://github.com/user-attachments/assets/e4c4e54d-9421-4fe7-84d3-d0998e1144ce" width="450" height="250">
</p>

:::note CodeGPT Chat conversation
<p align="center">
      <img width="750" height="550" src="https://github.com/user-attachments/assets/099fe893-08e3-4c31-a845-5f117a1de696"/>
</p>
:::

## Using Code Selection:
Select the desired code in your editor by level to share code snippets. The selected code will be automatically inserted into the chat interface, allowing CodeGPT to provide more accurate and context-specific responses. Call the function using `@`.

:::note Code Selection

To read the name of the file or segment, you can use the slide bar to navigate through the name.
 
<p align="center">
    <img width="750" height="550"  src="https://github.com/user-attachments/assets/90a920ed-74c6-458b-9444-55c4b60128f9" />
</p>
:::

### Context level

Please enable it, and AI will be able to understand the context of your code. 

You have three levels of context:

- `Selected code`: manually selected code
- `Codebase`: we auto-select the codebase. Please index the codebase before on the `Codebase` button
- `Deep insights`: we enrich the responses with code knowledge graphs.

## Using Custom Context
Using custom contexts allows you to tailor the responses to specific situations.

<p align="center">
    <img width="450" height="250"  src="https://github.com/user-attachments/assets/3d02120a-bb92-4051-a92d-328e9cc1a504" />
</p>


### Add Files
1. Click the `+Add Context` button
2. Choose `#Files` to add a file from your current project as context
3. Click outside the window to save the changes

<p align="center">
    <img width="450" height="250"  src="https://github.com/user-attachments/assets/7c3487cc-402e-4d0a-91a5-29b64f202817" />
</p>

:::note 

You can also add the current file to the workshop automatically by clicking on the right ⚙️ icon and enabling the corresponding option 

<p align="center">
    <img width="450" height="250"  src="https://github.com/user-attachments/assets/d1080ef7-cd9b-48eb-8159-1ceecbbc9d3d" />
</p>

:::

### My agents
1. Click the `+Add Context` button
2. Choose `My agents` to get the list of agents and click the one that you want to use
3. Click outside the window to save the changes

<p align="center">
    <img width="450" height="250"  src="https://github.com/user-attachments/assets/67b2b971-0cab-4ce9-ba31-bc789ce34eff" />
</p>

### Docs

1. Click the `+Add Context` button
2. Choose `Docs` to get the list of CodeGPT Marketplace agents and click the one that you want to use
3. Click outside the window to save the changes

<p align="center">
    <img width="450" height="250"  src="https://github.com/user-attachments/assets/7bd2f40a-2f8a-441d-b769-fb453d090b1a" />
</p>


## Shortcuts
You can use the shortcuts to make the most of the CodeGPT Chat feature. Here are some of the most useful shortcuts:

- [`/Fix`](https://docs.codegpt.co/docs/tutorial-features/find_problems): Fix the code selected
- [`/Explain`](https://docs.codegpt.co/docs/tutorial-features/code_explanation): Explain the code selected
- [`/Refactor`](https://docs.codegpt.co/docs/tutorial-features/code_refactoring): Refactor the code selected
- [`/Document`](https://docs.codegpt.co/docs/tutorial-features/code_documentation): Generate documentation for the code selected
- [`/Unit Test`](https://docs.codegpt.co/docs/tutorial-features/unit_testing): Test the code selected
- [`/Comment`](ddd): Comment the code selected
- [`/Planning`](dddd): allow expert agents from our Marketplace to help you plan the code.


:::note Shortcuts

<p align="center">
    <img width="450" height="250"  src="https://github.com/user-attachments/assets/6aba86fa-0c6c-49f2-89bc-47456d2c61e5" />
</p>

<img width="413" alt="image" src="https://github.com/user-attachments/assets/3596f633-808b-4aed-90dd-d89a0a7c4280" />

:::

:::note CodeGPT: Features
To use any of the above features, log in to your CodeGPT account. You’ll get a limited number of free interactions each day.

If you want more usage and access to advanced AI models without setting up your own API keys, you can subscribe to a paid plan.

Prefer to use it for free? Just add your own API key (like from OpenAI or Anthropic), and you'll be billed directly by that provider.

To learn how to do this, please refer to the following [link](https://help.codegpt.co/en/articles/9939744-connect-codegpt-to-vscode)
:::

Make the most of CodeGPT Chat and experience a new level of productivity in your coding endeavors.

