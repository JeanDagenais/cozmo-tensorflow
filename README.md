# cozmo-tensorflow
Cozmo the Robot does things with TensorFlow

## Setup

Install the [Cozmo SDK](http://cozmosdk.anki.com/docs/)
```bash
virtualenv ~/.env/cozmo -p python3
source ~/.env/cozmo/bin/activate
pip install -r requirements.txt
```

## Ask Cozmo to help generate a photo dataset

Let's ask Cozmo to take pictures of something, let's say a bottle of seltzer. Place Cozmo directly in front of a bottle of seltzer on the ground, and make sure that he has enough space to rotate around the seltzer can to take pictures.
```bash
python3 cozmo-paparazzi.py rock
```

## References

This project is an extension of @nheidloff's [Cozmo visual recognition project](https://github.com/nheidloff/visual-recognition-for-cozmo-with-tensorflow).