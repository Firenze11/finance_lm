# FinanceLM
Language model for investment analysis. Project for Stanford Deep Generative Models.

## Project Write-up
[Poster](https://docs.google.com/presentation/d/1ddiobt0MBLBStzkhEoboQrwvz-mbpOgDpAJqJv68GOk/edit#slide=id.g2a321ecdc05_0_0) |  [Report (TBD]()

## Code Walk-through
**Training:** We conducted three experiments fine-tuning Llama2 and GPT3.5.
* Supervised and unsupervised fine-tuning training code is in [llama_for_finance_finetuning.ipynb](https://github.com/Firenze11/finance_lm/blob/main/llama_for_finance_finetuning_.ipynb).
* Instruction fine-tuning of GPT code is in [finetune_GPT.ipynb](https://github.com/Firenze11/finance_lm/blob/main/finetune_GPT_.ipynb).

**Data:** 
* Data scraping for Llama2 unsupervised fine-tuning: [llama_scrape.ipynb](https://github.com/Firenze11/finance_lm/blob/main/llama_scrape.ipynb).
* Some utility functions are in [link]()

**Evaluation:**
* Evaluation code for Llama2 baseline and fine-tuned versions is in [llama_evaluate.ipynb](https://github.com/Firenze11/finance_lm/blob/main/llama_evaluate.ipynb).
* Evaluation of GPT models is in the same [file](https://github.com/Firenze11/finance_lm/blob/main/finetune_GPT_.ipynb) as fine-tuning.

## Model Artifacts
* Unsupervised fine-tuning of Llama2: [PEFT model on Huggingface Hub](https://huggingface.co/Firenze11/llama2-lora-finance/tree/main).
* Instruction fine-tuned GPT3.5 is [here](https://platform.openai.com/finetune/ftjob-W240Nm2DEa4JTIbyANX1yBbj?filter=all)
