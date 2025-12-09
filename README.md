# AI-ML-Assignment-6-Prompt-Engineering
Nathaniel Davis
Youtube Link: https://youtu.be/pZn8bTNOKO8


| run_id | technique               | accuracy (0–5) | format (0–5) | instruction (0–5) | parsed_json                                        | raw_output                                                                 |
|--------|--------------------------|----------------|--------------|-------------------|----------------------------------------------------|----------------------------------------------------------------------------|
| 0      | Baseline                 | 0.00           | 0.0          | 0.0               | None                                               | Here's the extracted data: 1. Product: Acme...                             |
| 1      | Role Prompting           | 0.00           | 0.0          | 0.0               | None                                               | Here is the extracted information in plain tex...                          |
| 2      | Strict Output Formatting | 3.75           | 5.0          | 1.5               | {"name": "Acme Super Blender (SB-200)", "price... | ```json\n{\n  "name": "Acme Super Blender (SB-...\n}\n```                 |
| 3      | Final Optimized Prompt   | 3.75           | 5.0          | 1.5               | {"name": "Acme Super Blender (SB-200)", "price... | {\n  "name": "Acme Super Blender (SB-200)",\n  ..                         |

