# Arabic-conversational-chatbot

**Note:** The deprecated files are kept just to keep track of old commits. They will be removed in the future.

This repository contains various scripts and files related to an Arabic conversational chatbot. Here is a brief description of each file:

- **ChatData.py:** This file is deprecated. The content got moved under chat-gpt2.ipynb.
- **Worker.ipynb:** This file is deprecated. The content got moved under chat-gpt2.ipynb.
- **arabic_conversation.json:** This file contains the Arabic conversation for the real Expo shop Facebook page after processing.
- **change_data_shape.ipynb:** This file takes the initial CSV data file and preprocesses it to generate the arabic_conversation.json file.
- **change_to_conversational.ipynb:** This script changes the JSON file of conversation and generates a new JSON file that adds the previous context into the current input.
- **chat-gpt2.ipynb:** This is the worker code. It imports data, trains the model, loads the model, and evaluates the model.
- **expo_chats.csv:** Initial CSV data file.
- **new_data.json:** Output of change_to_conversational.ipynb. Note: Please use the one saved in the drive instead. Drive: [Google Drive Link](https://drive.google.com/file/d/1_qgMG1nf8Ykb_FGKmlCgL22HjSFmIvdU/view) or generate it yourself.
- **simulation dialog for product table.ip** this is deprecated. The content got moved under simulation daiog for product .ipynb.
- **simulation daiog for product .ipynb:** This script is responsible for generating conversations from the database of the business.

