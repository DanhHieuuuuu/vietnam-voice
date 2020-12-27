# VIET NAM VOICE DATASET


# vietnam-voice [![CircleCI](https://circleci.com/gh/faustomorales/keras-ocr.svg?style=shield)](https://github.com/nguyentruonglau/VietNam-Voice/edit/main/README.md) [![Documentation Status](https://readthedocs.org/projects/keras-ocr/badge/?version=latest)](https://github.com/nguyentruonglau/VietNam-Voice/edit/main/README.md)

This is the audio dataset of the voices of 80 VietNamese

>
> Nguyễn Trường Lâu - Student at University of Information Technology (UIT)
>

![overview](https://github.com/nguyentruonglau/VietNam-Voice/blob/main/image/data.png  "VIET NAM VOICE DATASET")

## Over View

``` 
- Dataset include: 
  + 50 audio files / people
  + 2s / file 
- Data has been cleaned: noise filtering, sound reinforcement 
- Standardized data: 
  + Sample rate: 44100Hz 
  + Channels: Stereo 
  + Bit Depth: 32 bits
```

## Object

``` 
The purpose of this DATASET is DATA for Speaker Recognition Problem.
```

## Description

``` 
--data:
  --train
      -- 1-M-28
          -- 1.wav
          -- 2.wav
          -- ..
      -- 2-F-30
          -- 1.wav
          -- 2.wav
          -- ..
  --test
      -- 1-M-28
          -- 1.wav
          -- 2.wav
          -- ..
      -- 2-F-30
          -- 1.wav
          -- 2.wav
          -- ..


    1: numerical order
    M: male - F: female
    30: age number
```


## Citations
If you find the DATASET useful for your research, please consider citing our works
``` 
@article{voicenet,
  title={VIET NAM VOICE DATASET},
  author={Nguyễn Trường Lâu - Student at University of Information Technology (UIT)},
  booktitle={VIETNAMVOICE},
  year={2020}
}
```
