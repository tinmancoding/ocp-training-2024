# ocp-training-2024


## Word Picker

To run the word-picker API on your local machine:

```
cd word-picker
export FLASK_APP=./word_picker.py
flask run
```

To build the Docker image:

```
cd word-picker
docker build . -t word-picker:latest
```
