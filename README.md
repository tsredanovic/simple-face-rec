# Playground for **face_recognition**

Playing around with the face_recognition package. Can recognize people if their image is provided.

## Pip installs
```bash
pip3 install cmake
pip3 install face_recognition
pip3 install opencv-python
```


## Init project
```bash
python3 -m venv ./venv
source venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

## Supply data
Create a `people.json` file with names and image paths in `simple-face-rec` direcotry:
```json
[
    {
        "name": "Barack Obama",
        "image_path": "./img/obama_barack/obama_barack_1.jpg"
    },
    {
        "name": "Joe Biden",
        "image_path": "./img/biden_joe/biden_joe_1.png"
    },
```

## Run project
```bash
source venv/bin/activate
python facerec/facerec.py
```
