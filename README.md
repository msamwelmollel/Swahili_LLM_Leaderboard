# 🏆 Swahili LLM-Leaderboard

A joint community effort to create a Swahili central leaderboard for LLMs. These models are currently evaluated on the Open LLM Leaderboard. Contributions and corrections are welcome! <br>
We refer to a model being "open" if it can be locally deployed and used commercially.

## Interactive Dashboard

https://swahili-llm-leaderboard.streamlit.app/<br>
https://huggingface.co/spaces/Mollel/swahili-llm-leaderboard

## Leaderboard

| Model Name | Publisher| Open? | Basemodel |Average| ARC  | HellaSwag      | MMLU         | TruthfulQA|Winogrande|GSM8K           |
| ---------- | -------- | ----- | --------- |------ | ---- | -------------- | ------------ | --------- | -------- | -------------- |
| [Mollel/Swahili Gemma](https://huggingface.co/Mollel/Swahili_Gemma)| Mollel| Yes|Gemma|61.32|58.96|76.4 |61.02| 52.1|75.61|43.82|
| [LeroyDyer/Mixtral_AI_SwahiliTron_7b](https://huggingface.co/LeroyDyer/Mixtral_AI_SwahiliTron_7b)| leroy Samuel Dyer| Yes|Mixtral|61.14|57.08|81.59 |58.49| 60.66|75.53|33.51|
| [Mollel/Swahili-Alpaca-Llama-3-8b_16bit](https://huggingface.co/Mollel/Swahili-Alpaca-Llama-3-8b_16bit)| Mollel| Yes|Llama-3|60.97|57.25|78.03|63.97| 50.13|76.87|39.58|
| [mwitiderrick/SwahiliInstruct-v0.1](https://huggingface.co/mwitiderrick/SwahiliInstruct-v0.1)| Derrick| Yes|Mistral|58.92|57.59|80.92 |57| 58.08|74.66|25.25|
| [mwitiderrick/SwahiliInstruct-v0.2](https://huggingface.co/mwitiderrick/SwahiliInstruct-v0.2)| Derrick| Yes|Mistral|54.25|55.2|78.22|50.3|57.08|73.24|11.45|

## How to Contribute

We are always happy for contributions! You can contribute by the following:

- table work (don't forget the links):
    - filling in missing entries
    - adding a new model as a new row to the leaderboard. Please keep the descending order.
    - adding a new benchmark as a new column in the leaderboard and the benchmark to the benchmarks table. Please keep the descending order.
- code work:
    - improving the existing code
    - requesting and implementing new features


## Sponsorship

The benchmark is English-based, and we need support translating it into Swahili. We welcome sponsorships to help advance this endeavor. Your sponsorship would facilitate this essential translation effort, bridging language barriers and making the benchmark accessible to a broader audience. We're grateful for the dedication shown by our collaborators and aim to extend this impact further with the support of sponsors committed to advancing language technologies."
