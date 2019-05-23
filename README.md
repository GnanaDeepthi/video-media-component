# VideoMedia Component using  AngularMaterial


<p align="center">
  <img src="https://github.com/GnanaDeepthi/video-media-component/blob/master/Images/video.png" width="750" title="hover text"><br><br>
  <img src="https://github.com/GnanaDeepthi/video-media-component/blob/master/Images/scroll.png" width="750" alt="scroll image"><br><br>
    <img src="https://github.com/GnanaDeepthi/video-media-component/blob/master/Images/modal.png" width="750" alt="modal">
</p>



To preview demo of VideomediaComponent, [Click Here](https://github-uo9w4i-cj7rui.stackblitz.io/).

### Prerequisites

Download the  VideoMedia component and install the required packages and run the application.


### Installing

```sh
$ npm install
```

### Run Server

```sh
$ ng serve
```

### Adding  VideoMedia component to your project

```sh
<app-edge-media-player videoMp4="../assets/sheeran.mp4" videoOgg="../assets/sample.ogg" [modal]="false"
  [sticky]="true" stickyPosition="right top">
  <span title>{{title}}</span>
  <span subtitle>{{subTitle}}</span>
</app-edge-media-player>
```

### Input for VideoMedia component

```sh
  @Input()  videoMp4: string;
    @Input()  videoOgg: string;
  @Input()  modal: boolean;
  @Input()  sticky: boolean;
  @Input()  stickyPosition: string;
```


| Input | Purpose |
| ------ | ------ |
| videoMp4 |   url of mp4 |
| videoOgg | url of ogg  |
| modal | Either to open the modal by default or not with provided boolean value  |
| sticky | Option to provide sticky nature based on boolean value when we scroll the video while playing  |
| stickyPosition | position of sticky either right top or right bottom or left top or left bottom  |


#### How it works?

- By clicking 'Open Modal' we can see the video playing in modal view.

- When playing the video if we scroll the window then we can see the video sticked in the stickyposition of the input we given. 


