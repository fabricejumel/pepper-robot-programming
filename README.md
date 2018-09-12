# PEPPER ROBOT CODES

[![NAOqi][naoqi-image]][naoqi-url] [![Python SDK ][sdk-image]][sdk-url] [![MIT][mit-image]][mit-url] [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)

Here one will find some useful codes in the `basic-codes` directory, for creating applications on pepper robot using python language.

Pepper control including movement, speech and camera programs using speech and command line can be found in the `remote` directory.

Pepper's one of the major application created is found in `object-detection` directory, it implements exploration and mapping in an unknown environment based on a graph algorithm which works in RealTime as pepper moves by identifying and plotting nodes which are represented using matplotlib. And at every node reached we can make pepper do some task here it captures pictures of the environment and gives it to a DL server, which by using [YOLO](https://pjreddie.com/darknet/yolo/) finds objects in the captured feed from pepper.

## Installation

I would highly recommend using python virtual environment for installing dependencies used in pepper programming. For installation of python virtual environment one can follow the [guide](http://docs.python-guide.org/en/latest/dev/virtualenvs/).

```bash
pip install -r requirements.txt
```

One also needs to add `naoqi` a third party python package for using `qi` drivers one can find the python package [here](https://community.ald.softbankrobotics.com/en/resources/software/language/en-gb/field_software_type/sdk/robot/nao-2).

If having a trouble while adding the python package on mac follow this [repo](https://github.com/maverickjoy/pepper-nao_python_installation_mac).

## Notes

- **Navigation and Mapping**

<p align="center"><img src="https://raw.githubusercontent.com/maverickjoy/pepper-codes/master/docs/navigation-1.png" width="650"></p>

---

<p align="center"><img src="https://raw.githubusercontent.com/maverickjoy/pepper-codes/master/docs/navigation-2.png" width="650"></p>

---

- **Video Link**

[![ASTHAMA SERACH VIDEO][video-image-1]][video-url-1]

- **Other Video Links**

[![FALL DETECTION VIDEO][video-image-2]][video-url-2]

[![TICTACTOE VIDEO][video-image-3]][video-url-3]


## License

MIT License 2018 © Vikram Singh and [contributors](https://github.com/maverickjoy/pepper-codes/graphs/contributors)

[sdk-url]: https://community.ald.softbankrobotics.com/en/resources/software/language/en-gb/robot/pepper-3
[sdk-image]: https://img.shields.io/badge/Python%202.7%20SDK-2.5.5-008C96.svg?style=flat

[naoqi-url]: https://developer.softbankrobotics.com/us-en/downloads/pepper
[naoqi-image]: https://img.shields.io/badge/NAOqi-2.5.5-008C96.svg

[mit-image]: https://img.shields.io/badge/license-MIT-blue.svg
[mit-url]: https://opensource.org/licenses/MIT

[video-image-1]: https://img.youtube.com/vi/lcxtWwkrp4c/0.jpg
[video-url-1]: https://youtu.be/lcxtWwkrp4c

[video-image-2]: https://img.youtube.com/vi/n_cCs7YTf70/0.jpg
[video-url-2]: https://youtu.be/n_cCs7YTf70

[video-image-3]: https://img.youtube.com/vi/a2yzU2n8eSA/0.jpg
[video-url-3]: https://youtu.be/a2yzU2n8eSA
