# Dataset

This repository contains the dataset used in the paper "Conversational Style Matching with Large Language Models".

The dataset consists of the following files:
- `train.jsonl`: 900 dialogues for training/fine-tuning
- `test.seen.jsonl`: 100 dialogues for testing on 20 seen styles
- `test.unseen.jsonl`: 200 dialogues for testing on 4 unseen styles

Each line in the files is a JSON object with the following fields:
- `id`: dialogue id (string)
- `style`: dialogue style (array of strings)
- `dialogue`: dialogue turns (array of objects)
  - `role`: speaker of the turn, either "user" or "assistant" (string)
  - `content`: utterance of the turn (string)

Note that each dialogue is turn-by-turn and has exactly 6 turns, and the first turn is always by the user.

# Citation

TBD.