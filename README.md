# diarization-benchmark

Repository to benchmark diarization and it's accuracy.
Partly pillaged from [picovoice diarization](https://github.com/Picovoice/speaker-diarization-benchmark)

uses the [`voxconverse` dataset](https://github.com/joonson/voxconverse) to benchmark

Azure has a weird way of installing client

https://github.com/Azure-Samples/cognitive-services-speech-sdk/blob/master/samples/batch/python/README.md



### To run,

Create a copy of the file in `/src/config/app.example.yaml` and setup the config and then run.

From the root directory, run

```
python3 src/benchmark.py
```