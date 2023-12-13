# TG-bot-with-ChatGPT

The telegram bot accepts a text analysis task and an attached file as input.
The file type (xlsx, csv, ppt) is determined, the contents are read, and the data types are converted to the desired format.
The task is passed to chatgpt.
The finished script is executed on the converted data.
The finished result is returned to the user in the form of an xlsx file (or png images with the answer).
