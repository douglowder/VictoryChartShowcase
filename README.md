# Victory Charts Showcase (modified for TV)

A showcase of charts available in [Victory Native XL](https://github.com/FormidableLabs/victory-native-xl) based on my [YouTube Videos](https://www.youtube.com/@DanRNLab)

This branch is modified to use Expo SDK 52 plus React Native for TV 0.76, and build either for mobile (iOS, Android), or TV (Apple TV, Android TV).

## How to use

- `cd` into the project

- TV builds:

```sh
yarn
yarn prebuild:tv # Executes Expo prebuild with TV modifications
yarn ios # Build and run for Apple TV
yarn android # Build and run for Android TV
```

- Mobile builds:

```sh
yarn
yarn prebuild # Executes Expo prebuild without TV modifications
yarn ios # Build and run for iOS
yarn android # Build and run for Android mobile
```

## Sample Charts

### Line Chart

A line chart complete with gestures and a linear gradient area

<p align="center">
  <img src="./docs/line_chart.gif" />
</p>
