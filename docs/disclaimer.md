# Important Note

There are a few things you need to know before you start testing the app:

- **we support passport document only**
- [NativeBase Market] doesn't collect or store any information you use during your testing.
- [appducks api] doesn't persist your data. It wipes up all images every now and then. read more about it [here]
- You have 3 ways to test the app:

  - use your own passport if you do not have any privacy concerns.
  - If you are having any privacy concerns, use fake passport for testing. You can find a lot in google serach. You can use [this image].
  - If you purchased the app already, you can easily upload your images into your own server. All you need is to change the /image/upload from [appducks API] to point to your own image uploading api. Just go to `src/store/actions.ts'` and change the following method:

  ```
  export const uploadFace = async (photo: any): Promise<any> => {

    .........

  }
  ```

[email me] if you need any help!

[nativebase market]: https://market.nativebase.io/
[appducks api]: https://api.appducks.com/#image-upload
[here]: https://api.appducks.com/#image-upload
[appducks]: https://api.appducks.com
[this image]: https://i.imgur.com/uGjALtm.png
[email me]: mailto:ali.makeen@icloud.com
