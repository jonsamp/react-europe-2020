# React Native Up and Going

To get started, view the slides in this directory.

## Presentation notes

There are a variety of ways to start a React Native project. Below is a comparison of Expo's Managed workflow, Bare workflow, and a non-Expo vanilla React Native workflow. Learn more [here](https://docs.expo.io/introduction/managed-vs-bare/).

## Workflow comparison

| Feature                                                | Managed workflow | Bare workflow                               | Vanilla React Native |
| ------------------------------------------------------ | ---------------- | ------------------------------------------- | -------------------- |
| Develop universal apps with only JavaScript/TypeScript | ✅               |                                             |                      |
| Use Expo to create your iOS and Android builds         | ✅               |                                             |                      |
| Use Expo's push notification service                   | ✅               | ✅                                          |                      |
| Use Expo's over the air updates features               | ✅               | ✅                                          |                      |
| Develop with the Expo client app                       | ✅               | ✅ (only if custom native code is disabled) |                      |
| Access to Expo SDK                                     | ✅               | ✅                                          |                      |
| Add custom native code and manage native dependencies  |                  | ✅                                          | ✅                   |
| Develop in Xcode and Android Studio                    |                  | ✅                                          | ✅                   |
| No access to Expo SDK                                  |                  |                                             | ✅                   |

## See more

In this directory, you'll also find three directories: **bare**, **managed**, and **vanilla-react-native**. The folders correspond with each workflow. **bare** and **managed** were created with `expo init`, and **vanilla-react-native** was created with `npx react-native init`.

## Troubleshooting

- You might have to use `sudo` on `yarn start` to get web working. The server creates an SSL connection so that you can access certain web APIs that require a secure connection.
- If you're having other errors, see [common development errors](https://docs.expo.io/workflow/common-development-errors/).
- Learn how to set up an [Android simulator](https://docs.expo.io/workflow/android-studio-emulator/).
- You may also need/want to download the Expo Client app on your phone and run it as your development device. (You must create an Expo account and log into it on both your computer and your device).
  - iOS app: https://itunes.apple.com/app/apple-store/id982107779
  - Androind app: https://play.google.com/store/apps/details?id=host.exp.exponent
