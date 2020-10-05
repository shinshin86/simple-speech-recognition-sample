# simple-speech-recognition-sample

Simple speech recognition sample.



**Note**

This sample has been tested on the PC version of Google Chrome only.



## Demo

This GIF is a demo of actual voice recognition.

![gif demo](./gif/demo.gif)



## Usage

```bash
# clone
git clone https://github.com/shinshin86/simple-speech-recognition-sample.git
cd simple-speech-recognition-sample

# Start local server then access on browser
# If you can use Python
python -m http.server
```



You can change the speech recognition settings with the query string.

```bash
http://localhost:8000/ # => Default setting. It will be recognized by the browser's language setting.
http://localhost:8000/?lang=en # => You can set the language to be recognized by parameter of lang.
http://localhost:8000/?realtime=true # => If parameter of realtime is set to true, recognition is done in real time.
http://localhost:8000/?lang=en&realtime=true # => Of course, multiple parameters are accepted.
```