# 🤖 Awesome vim LLM plugins

__Below is an exhaustive list of vim and neovim plugins__ hosted on GitHub which make use of Large Language Models and have commits after January 1, 2023.  To optimize for maximum freshness, plugins are listed in order of last commit date.

## Code writing and editing

Mature, fully-featured, configurable plugins are __highlighted in bold__.

* 2023-01-16 [naps62/pair-gpt.nvim](https://github.com/naps62/pair-gpt.nvim) (35☆) `#inline` `model:openai`
* 2023-02-08 [jdnewman85/openai-vim](https://github.com/jdnewman85/openai-vim) (5☆)`#inline` `model:openai`
* 2023-04-06 [thmsmlr/gpt.nvim](https://github.com/thmsmlr/gpt.nvim) (20☆) `#inline` `model:openai`
* 2023-04-06 [aduros/ai.vim](https://github.com/aduros/ai.vim) (265☆) `#inline` `model:openai`
* __2023-05-02 [dpayne/CodeGPT.nvim](https://github.com/dpayne/CodeGPT.nvim) (698☆) `#inline` `#templates` `model:openai`__
* __2023-06-25 [madox2/vim-ai](https://github.com/madox2/vim-ai) (354☆) `#inline` `#chat` `#templates` `model:openai`__
* 2023-07-03 [oelmekki/make-my-code-better.vim](https://github.com/oelmekki/make-my-code-better.vim) (2☆) `#inline` `model:openai`
* 2023-07-13 [tom-doerr/vim_codex](https://github.com/tom-doerr/vim_codex) (245☆) `#inline` `model:openai`
* __2023-07-20 [gsuuon/llm.nvim](https://github.com/gsuuon/llm.nvim) (38☆) `#inline` `#templates` `model:openai` `model:bard` `model:huggingface` `model:local`__
* __2023-08-02 [CoderCookE/vim-chatgpt](https://github.com/CoderCookE/vim-chatgpt) (141☆) `#inline` `model:openai`__
* __2023-08-16 [jackMort/ChatGPT.vim](https://github.com/jackMort/ChatGPT.vim) (2500☆) `#inline` `#workflow` `#chat` `#templates` `model:openai`__
* 2023-08-18 [dense-analysis/neural](https://github.com/dense-analysis/neural) (313☆) `#inline` `model:openai`
* 2023-08-19 [jayli/nvim-ai-coding](https://github.com/jayli/nvim-ai-coding) (6☆) `#inline` `model:openai`
* 2023-03-18 [0xStabby/chatgpt-vim](https://github.com/0xStabby/chatgpt-vim) (47☆) `#inline` `model:chatgpt` `model:openai`

## Conversation-focused

These plugins are all quite similar in functionality.  __Robitx/gp.nvim__ stands out with a rich set of configuration options, and also includes commands for writing and editing code (i.e. overlaps with the above section).

* 2023-01-07 [lambdalisue/butler.vim](https://github.com/lambdalisue/butler.vim) (29☆) `#chat` `model:openai`
* 2023-03-26 [IwasakiYuuki/ai-assistant.nvim](https://github.com/IwasakiYuuki/ai-assistant.nvim) (3☆) `#chat` `model:openai`
* 2023-04-22 [macrat/askgpt.vim](https://github.com/macrat/askgpt.vim) (2☆) `#chat` `model:openai`
* 2023-07-26 [yuki-yano/ai-review.vim](https://github.com/yuki-yano/ai-review.vim) (16☆) `#chat` `model:openai`
* 2023-08-11 [charlespascoe/vim-chatgpt](https://github.com/charlespascoe/vim-chatgpt) (1☆) `#chat` `model:openai`
* 2023-08-12 [micheam/ai-assistant-console](https://github.com/micheam/ai-assistant-console) (0☆) `#chat` `model:openai`
* 2023-08-23 [CamdenClark/flyboy](https://github.com/CamdenClark/flyboy) (25☆) `#chat` `model:openai`
* __2023-08-28 [Robitx/gp.nvim](https://github.com/Robitx/gp.nvim) (55☆) `#inline` `#chat` `#templates` `model:openai`__
* 2023-08-29 [martineausimon/nvim-bard](https://github.com/martineausimon/nvim-bard) (21☆) `#chat` `model:bard`

## Tab completion

These plugins are also pretty much identical in functionality, and perhaps more important to compare is (1) how much subscription costs, and (2) quality of the output.  One plugin that stands out is __huggingface/llm.nvim__, which uses free inference endpoints hosted on Hugging Face.

* 2023-05-10 [tzachar/cmp-tabnine](https://github.com/tzachar/cmp-tabnine) (263☆) `#autocomplete` `model:custom`
* 2023-08-22 [github/copilot.vim](https://github.com/github/copilot.vim) (6000☆) `#autocomplete` `model:custom`
* 2023-08-25 [zbirenbaum/copilot.lua](https://github.com/zbirenbaum/copilot.lua) (1400☆) `#autocomplete` `model:custom`
* 2023-08-28 [codota/tabnine-nvim](https://github.com/codota/tabnine-nvim) (206☆) `#autocomplete` `#chat` `model:custom`
* 2023-08-30 [Exafunction/codeium.vim](https://github.com/Exafunction/codeium.vim) (2100☆) `#autocomplete` `model:custom`
* __2023-08-31 [huggingface/llm.nvim](https://github.com/huggingface/llm.nvim) (243☆) `#autocomplete` `model:huggingface`__
* 2023-08-31 [zbirenbaum/copilot-cmp](https://github.com/zbirenbaum/copilot-cmp) (723☆) `#autocomplete` `model:custom`
* 2023-09-01 [TabbyML/tabby](https://github.com/TabbyML/tabby) (9500☆) `#autocomplete` `model:custom`

## Other

__james1236/backseat.nvim__ provides commentary in between lines of code, and __svermeulen/text-to-colorscheme__ helps set the mood while programming.

* __2023-04-15 [james1236/backseat.nvim](https://github.com/james1236/backseat.nvim) (143☆) `#augment` `model:openai`__
* 2023-05-27 [mthbernardes/codeexplain.nvim](https://github.com/mthbernardes/codeexplain.nvim) (79☆) `#augment` `model:local`
* __2023-06-26 [svermeulen/text-to-colorscheme](https://github.com/svermeulen/text-to-colorscheme) (187☆) `#other` `model:openai`__

## Tag explanations

### Functionality

* `#inline:` Writes, edits, or annotates code in the current buffer.  A popup, window, or tab might be used in limited circumstances to display information.
* `#chat:` Implements an interface focused on conversation, without significant support for copying to/from buffers.
* `#templates:` Supports building custom commands, prompts, or pipelines.
* `#workflow:` Significant functionality for editing code or viewing diffs before committing changes to the current buffer.
* `#augment:` Augments the programming experience somehow, but does not write or edit code.
* `#other:` Not related to programming, but still uses AI for some purpose within the editor.

### Models

* `model:openai:` OpenAI API.
* `model:chatgpt:` ChatGPT web interface (without API).
* `model:bard:` Google PaLM API.
* `model:huggingface:` Hugging Face inference API.
* `model:local:` Local model (e.g. invokes llama.cpp).
* `model:custom:` Any other model without an officially open API.
