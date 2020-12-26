## Example of `src/styles/theme/css-variables.scss`

<pre>
:root {
  
  --fl-color-white-50: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">
  --fl-color-white-100: #fcfcfb; <img src="https://via.placeholder.com/15/fcfcfb/fcfcfb">
  --fl-color-white-200: #f9f8f8; <img src="https://via.placeholder.com/15/f9f8f8/f9f8f8">
  --fl-color-white-300: #f7f5f5; <img src="https://via.placeholder.com/15/f7f5f5/f7f5f5">
  --fl-color-white-400: #f4f2f1; <img src="https://via.placeholder.com/15/f4f2f1/f4f2f1">
  --fl-color-white-500: #c4c2c1; <img src="https://via.placeholder.com/15/c4c2c1/c4c2c1">
  --fl-color-white-600: #939292; <img src="https://via.placeholder.com/15/939292/939292">
  --fl-color-white-700: #636262; <img src="https://via.placeholder.com/15/636262/636262">
  --fl-color-white-800: #333232; <img src="https://via.placeholder.com/15/333232/333232">
  --fl-color-white-900: #020202; <img src="https://via.placeholder.com/15/020202/020202">
  
  --fl-color-black-50: #010101; <img src="https://via.placeholder.com/15/010101/010101">
  --fl-color-black-100: #0d0d0d; <img src="https://via.placeholder.com/15/0d0d0d/0d0d0d">
  --fl-color-black-200: #1a1919; <img src="https://via.placeholder.com/15/1a1919/1a1919">
  --fl-color-black-300: #262626; <img src="https://via.placeholder.com/15/262626/262626">
  --fl-color-black-400: #333232; <img src="https://via.placeholder.com/15/333232/333232">
  --fl-color-black-500: #5b5b5b; <img src="https://via.placeholder.com/15/5b5b5b/5b5b5b">
  --fl-color-black-600: #848383; <img src="https://via.placeholder.com/15/848383/848383">
  --fl-color-black-700: #acacac; <img src="https://via.placeholder.com/15/acacac/acacac">
  --fl-color-black-800: #d5d4d4; <img src="https://via.placeholder.com/15/d5d4d4/d5d4d4">
  --fl-color-black-900: #fdfdfd; <img src="https://via.placeholder.com/15/fdfdfd/fdfdfd">
  
  --fl-color-accent-base: #f19a3e; <img src="https://via.placeholder.com/15/f19a3e/f19a3e">
  --fl-color-accent-baseRgb: 241,154,62;
  --fl-color-accent-tint: #f2a451; <img src="https://via.placeholder.com/15/f2a451/f2a451">
  --fl-color-accent-shade: #d48837; <img src="https://via.placeholder.com/15/d48837/d48837">
  --fl-color-accent-contrast: #000000; <img src="https://via.placeholder.com/15/000000/000000">
  --fl-color-accent-contrastRgb: 0,0,0;
  --fl-color-accent-shadowDark: #bb7830; <img src="https://via.placeholder.com/15/bb7830/bb7830">
  --fl-color-accent-shadowLight: #f3ad62; <img src="https://via.placeholder.com/15/f3ad62/f3ad62">

  --fl-color-primary-base: #0e8ee3; <img src="https://via.placeholder.com/15/0e8ee3/0e8ee3">
  --fl-color-primary-baseRgb: 14,142,227;
  --fl-color-primary-tint: #2699e6; <img src="https://via.placeholder.com/15/2699e6/2699e6">
  --fl-color-primary-shade: #0c7dc8; <img src="https://via.placeholder.com/15/0c7dc8/0c7dc8">
  --fl-color-primary-contrast: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">
  --fl-color-primary-contrastRgb: 255,255,255;
  --fl-color-primary-shadowDark: #0b6eb0; <img src="https://via.placeholder.com/15/0b6eb0/0b6eb0">
  --fl-color-primary-shadowLight: #3ca3e9; <img src="https://via.placeholder.com/15/3ca3e9/3ca3e9">

  --fl-color-error-base: #f53936; <img src="https://via.placeholder.com/15/f53936/f53936">
  --fl-color-error-baseRgb: 245,57,54;
  --fl-color-error-tint: #f64d4a; <img src="https://via.placeholder.com/15/f64d4a/f64d4a">
  --fl-color-error-shade: #d83230; <img src="https://via.placeholder.com/15/d83230/d83230">
  --fl-color-error-contrast: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">
  --fl-color-error-contrastRgb: 255,255,255;
  --fl-color-error-shadowDark: #be2c2a; <img src="https://via.placeholder.com/15/be2c2a/be2c2a">
  --fl-color-error-shadowLight: #f75f5c; <img src="https://via.placeholder.com/15/f75f5c/f75f5c">

  --fl-color-success-base: #70ee9c; <img src="https://via.placeholder.com/15/70ee9c/70ee9c">
  --fl-color-success-baseRgb: 112,238,156;
  --fl-color-success-tint: #7ef0a6; <img src="https://via.placeholder.com/15/7ef0a6/7ef0a6">
  --fl-color-success-shade: #63d189; <img src="https://via.placeholder.com/15/63d189/63d189">
  --fl-color-success-contrast: #000000; <img src="https://via.placeholder.com/15/000000/000000">
  --fl-color-success-contrastRgb: 0,0,0;
  --fl-color-success-shadowDark: #57b879; <img src="https://via.placeholder.com/15/57b879/57b879">
  --fl-color-success-shadowLight: #8bf2af; <img src="https://via.placeholder.com/15/8bf2af/8bf2af">

  --fl-color-warning-base: #f7ef52; <img src="https://via.placeholder.com/15/f7ef52/f7ef52">
  --fl-color-warning-baseRgb: 247,239,82;
  --fl-color-warning-tint: #f8f163; <img src="https://via.placeholder.com/15/f8f163/f8f163">
  --fl-color-warning-shade: #d9d248; <img src="https://via.placeholder.com/15/d9d248/d9d248">
  --fl-color-warning-contrast: #000000; <img src="https://via.placeholder.com/15/000000/000000">
  --fl-color-warning-contrastRgb: 0,0,0;
  --fl-color-warning-shadowDark: #bfb93f; <img src="https://via.placeholder.com/15/bfb93f/bfb93f">
  --fl-color-warning-shadowLight: #f9f273; <img src="https://via.placeholder.com/15/f9f273/f9f273">

  --fl-color-light-base: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">
  --fl-color-light-baseRgb: 255,255,255;
  --fl-color-light-tint: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">
  --fl-color-light-shade: #e0e0e0; <img src="https://via.placeholder.com/15/e0e0e0/e0e0e0">
  --fl-color-light-contrast: #000000; <img src="https://via.placeholder.com/15/000000/000000">
  --fl-color-light-contrastRgb: 0,0,0;
  --fl-color-light-shadowDark: #c5c5c5; <img src="https://via.placeholder.com/15/c5c5c5/c5c5c5">
  --fl-color-light-shadowLight: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">

  --fl-color-dark-base: #212121; <img src="https://via.placeholder.com/15/212121/212121">
  --fl-color-dark-baseRgb: 33,33,33;
  --fl-color-dark-tint: #373737; <img src="https://via.placeholder.com/15/373737/373737">
  --fl-color-dark-shade: #1d1d1d; <img src="https://via.placeholder.com/15/1d1d1d/1d1d1d">
  --fl-color-dark-contrast: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">
  --fl-color-dark-contrastRgb: 255,255,255;
  --fl-color-dark-shadowDark: #1a1a1a; <img src="https://via.placeholder.com/15/1a1a1a/1a1a1a">
  --fl-color-dark-shadowLight: #4b4b4b; <img src="https://via.placeholder.com/15/4b4b4b/4b4b4b">

  --fl-color-background-light-base: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">
  --fl-color-background-light-baseRgb: 255,255,255;
  --fl-color-background-light-tint: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">
  --fl-color-background-light-shade: #e0e0e0; <img src="https://via.placeholder.com/15/e0e0e0/e0e0e0">
  --fl-color-background-light-contrast: #000000; <img src="https://via.placeholder.com/15/000000/000000">
  --fl-color-background-light-contrastRgb: 0,0,0;
  --fl-color-background-light-shadowDark: #c5c5c5; <img src="https://via.placeholder.com/15/c5c5c5/c5c5c5">
  --fl-color-background-light-shadowLight: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">

  --fl-color-background-dark-base: #212121; <img src="https://via.placeholder.com/15/212121/212121">
  --fl-color-background-dark-baseRgb: 33,33,33;
  --fl-color-background-dark-tint: #373737; <img src="https://via.placeholder.com/15/373737/373737">
  --fl-color-background-dark-shade: #1d1d1d; <img src="https://via.placeholder.com/15/1d1d1d/1d1d1d">
  --fl-color-background-dark-contrast: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">
  --fl-color-background-dark-contrastRgb: 255,255,255;
  --fl-color-background-dark-shadowDark: #1a1a1a; <img src="https://via.placeholder.com/15/1a1a1a/1a1a1a">
  --fl-color-background-dark-shadowLight: #4b4b4b; <img src="https://via.placeholder.com/15/4b4b4b/4b4b4b">
  
  &.dark {
  
    --fl-color-white-50: #010101; <img src="https://via.placeholder.com/15/010101/010101">
    --fl-color-white-100: #0d0d0d; <img src="https://via.placeholder.com/15/0d0d0d/0d0d0d">
    --fl-color-white-200: #1a1919; <img src="https://via.placeholder.com/15/1a1919/1a1919">
    --fl-color-white-300: #262626; <img src="https://via.placeholder.com/15/262626/262626">
    --fl-color-white-400: #333232; <img src="https://via.placeholder.com/15/333232/333232">
    --fl-color-white-500: #5b5b5b; <img src="https://via.placeholder.com/15/5b5b5b/5b5b5b">
    --fl-color-white-600: #848383; <img src="https://via.placeholder.com/15/848383/848383">
    --fl-color-white-700: #acacac; <img src="https://via.placeholder.com/15/acacac/acacac">
    --fl-color-white-800: #d5d4d4; <img src="https://via.placeholder.com/15/d5d4d4/d5d4d4">
    --fl-color-white-900: #fdfdfd; <img src="https://via.placeholder.com/15/fdfdfd/fdfdfd">
  
    --fl-color-black-50: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">
    --fl-color-black-100: #fcfcfb; <img src="https://via.placeholder.com/15/fcfcfb/fcfcfb">
    --fl-color-black-200: #f9f8f8; <img src="https://via.placeholder.com/15/f9f8f8/f9f8f8">
    --fl-color-black-300: #f7f5f5; <img src="https://via.placeholder.com/15/f7f5f5/f7f5f5">
    --fl-color-black-400: #f4f2f1; <img src="https://via.placeholder.com/15/f4f2f1/f4f2f1">
    --fl-color-black-500: #c4c2c1; <img src="https://via.placeholder.com/15/c4c2c1/c4c2c1">
    --fl-color-black-600: #939292; <img src="https://via.placeholder.com/15/939292/939292">
    --fl-color-black-700: #636262; <img src="https://via.placeholder.com/15/636262/636262">
    --fl-color-black-800: #333232; <img src="https://via.placeholder.com/15/333232/333232">
    --fl-color-black-900: #020202; <img src="https://via.placeholder.com/15/020202/020202">
  
    --fl-color-dark-base: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">
    --fl-color-dark-baseRgb: 255,255,255;
    --fl-color-dark-tint: #e0e0e0; <img src="https://via.placeholder.com/15/ffffff/ffffff">
    --fl-color-dark-shade: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">
    --fl-color-dark-contrast: #000000; <img src="https://via.placeholder.com/15/000000/000000">
    --fl-color-dark-contrastRgb: 0,0,0;
    --fl-color-dark-shadowDark: #c5c5c5; <img src="https://via.placeholder.com/15/c5c5c5/c5c5c5">
    --fl-color-dark-shadowLight: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">

    --fl-color-light-base: #212121; <img src="https://via.placeholder.com/15/212121/212121">
    --fl-color-light-baseRgb: 33,33,33;
    --fl-color-light-tint: #1d1d1d; <img src="https://via.placeholder.com/15/212121/212121">
    --fl-color-light-shade: #373737; <img src="https://via.placeholder.com/15/373737/373737">
    --fl-color-light-contrast: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">
    --fl-color-light-contrastRgb: 255,255,255;
    --fl-color-light-shadowDark: #1a1a1a; <img src="https://via.placeholder.com/15/1a1a1a/1a1a1a">
    --fl-color-light-shadowLight: #4b4b4b; <img src="https://via.placeholder.com/15/4b4b4b/4b4b4b">

    --fl-color-background-dark-base: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">
    --fl-color-background-dark-baseRgb: 255,255,255;
    --fl-color-background-dark-tint: #e0e0e0; <img src="https://via.placeholder.com/15/ffffff/ffffff">
    --fl-color-background-dark-shade: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">
    --fl-color-background-dark-contrast: #000000; <img src="https://via.placeholder.com/15/000000/000000">
    --fl-color-background-dark-contrastRgb: 0,0,0;
    --fl-color-background-dark-shadowDark: #c5c5c5; <img src="https://via.placeholder.com/15/c5c5c5/c5c5c5">
    --fl-color-background-dark-shadowLight: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">

    --fl-color-background-light-base: #212121; <img src="https://via.placeholder.com/15/212121/212121">
    --fl-color-background-light-baseRgb: 33,33,33;
    --fl-color-background-light-tint: #1d1d1d; <img src="https://via.placeholder.com/15/212121/212121">
    --fl-color-background-light-shade: #373737; <img src="https://via.placeholder.com/15/373737/373737">
    --fl-color-background-light-contrast: #ffffff; <img src="https://via.placeholder.com/15/ffffff/ffffff">
    --fl-color-background-light-contrastRgb: 255,255,255;
    --fl-color-background-light-shadowDark: #1a1a1a; <img src="https://via.placeholder.com/15/1a1a1a/1a1a1a">
    --fl-color-background-light-shadowLight: #4b4b4b; <img src="https://via.placeholder.com/15/4b4b4b/4b4b4b">
  }
}
</pre>

## Example of `src/styles/theme/scss-variables.scss`

<pre>
$theme: (
  white: (
    50: #ffffff, <img src="https://via.placeholder.com/15/ffffff/ffffff">
    100: #fcfcfb, <img src="https://via.placeholder.com/15/fcfcfb/fcfcfb">
    200: #f9f8f8, <img src="https://via.placeholder.com/15/f9f8f8/f9f8f8">
    300: #f7f5f5, <img src="https://via.placeholder.com/15/f7f5f5/f7f5f5">
    400: #f4f2f1, <img src="https://via.placeholder.com/15/f4f2f1/f4f2f1">
    500: #c4c2c1, <img src="https://via.placeholder.com/15/c4c2c1/c4c2c1">
    600: #939292, <img src="https://via.placeholder.com/15/939292/939292">
    700: #636262, <img src="https://via.placeholder.com/15/636262/636262">
    800: #333232, <img src="https://via.placeholder.com/15/333232/333232">
    900: #020202, <img src="https://via.placeholder.com/15/020202/020202">
  ),
  black: (
    50: #010101, <img src="https://via.placeholder.com/15/010101/010101">
    100: #0d0d0d, <img src="https://via.placeholder.com/15/0d0d0d/0d0d0d">
    200: #1a1919, <img src="https://via.placeholder.com/15/1a1919/1a1919">
    300: #262626, <img src="https://via.placeholder.com/15/262626/262626">
    400: #333232, <img src="https://via.placeholder.com/15/333232/333232">
    500: #5b5b5b, <img src="https://via.placeholder.com/15/5b5b5b/5b5b5b">
    600: #848383, <img src="https://via.placeholder.com/15/848383/848383">
    700: #acacac, <img src="https://via.placeholder.com/15/acacac/acacac">
    800: #d5d4d4, <img src="https://via.placeholder.com/15/d5d4d4/d5d4d4">
    900: #fdfdfd, <img src="https://via.placeholder.com/15/fdfdfd/fdfdfd">
  ),
  
  accent: (
    base: #f19a3e, <img src="https://via.placeholder.com/15/f19a3e/f19a3e">
    baseRgb: '241,154,62',
    tint: #f2a451, <img src="https://via.placeholder.com/15/f2a451/f2a451">
    shade: #d48837, <img src="https://via.placeholder.com/15/d48837/d48837">
    contrast: #000000, <img src="https://via.placeholder.com/15/000000/000000">
    contrastRgb: '0,0,0',
    shadowDark: #bb7830, <img src="https://via.placeholder.com/15/bb7830/bb7830">
    shadowLight: #f3ad62, <img src="https://via.placeholder.com/15/f3ad62/f3ad62">
  ),

  primary: (
    base: #0e8ee3, <img src="https://via.placeholder.com/15/0e8ee3/0e8ee3">
    baseRgb: '14,142,227',
    tint: #2699e6, <img src="https://via.placeholder.com/15/2699e6/2699e6">
    shade: #0c7dc8, <img src="https://via.placeholder.com/15/0c7dc8/0c7dc8">
    contrast: #ffffff, <img src="https://via.placeholder.com/15/ffffff/ffffff">
    contrastRgb: '255,255,255',
    shadowDark: #0b6eb0, <img src="https://via.placeholder.com/15/0b6eb0/0b6eb0">
    shadowLight: #3ca3e9, <img src="https://via.placeholder.com/15/3ca3e9/3ca3e9">
  ),

  error: (
    base: #f53936, <img src="https://via.placeholder.com/15/f53936/f53936">
    baseRgb: '245,57,54',
    tint: #f64d4a, <img src="https://via.placeholder.com/15/f64d4a/f64d4a">
    shade: #d83230, <img src="https://via.placeholder.com/15/d83230/d83230">
    contrast: #ffffff, <img src="https://via.placeholder.com/15/ffffff/ffffff">
    contrastRgb: '255,255,255',
    shadowDark: #be2c2a, <img src="https://via.placeholder.com/15/be2c2a/be2c2a">
    shadowLight: #f75f5c, <img src="https://via.placeholder.com/15/f75f5c/f75f5c">
  ),

  success: (
    base: #70ee9c, <img src="https://via.placeholder.com/15/70ee9c/70ee9c">
    baseRgb: '112,238,156',
    tint: #7ef0a6, <img src="https://via.placeholder.com/15/7ef0a6/7ef0a6">
    shade: #63d189, <img src="https://via.placeholder.com/15/63d189/63d189">
    contrast: #000000, <img src="https://via.placeholder.com/15/000000/000000">
    contrastRgb: '0,0,0',
    shadowDark: #57b879, <img src="https://via.placeholder.com/15/57b879/57b879">
    shadowLight: #8bf2af, <img src="https://via.placeholder.com/15/8bf2af/8bf2af">
  ),

  warning: (
    base: #f7ef52, <img src="https://via.placeholder.com/15/f7ef52/f7ef52">
    baseRgb: '247,239,82',
    tint: #f8f163, <img src="https://via.placeholder.com/15/f8f163/f8f163">
    shade: #d9d248, <img src="https://via.placeholder.com/15/d9d248/d9d248">
    contrast: #000000, <img src="https://via.placeholder.com/15/000000/000000">
    contrastRgb: '0,0,0',
    shadowDark: #bfb93f, <img src="https://via.placeholder.com/15/bfb93f/bfb93f">
    shadowLight: #f9f273, <img src="https://via.placeholder.com/15/f9f273/f9f273">
  ),

  light: (
    base: #ffffff, <img src="https://via.placeholder.com/15/ffffff/ffffff">
    baseRgb: '255,255,255',
    tint: #ffffff, <img src="https://via.placeholder.com/15/ffffff/ffffff">
    shade: #e0e0e0, <img src="https://via.placeholder.com/15/e0e0e0/e0e0e0">
    contrast: #000000, <img src="https://via.placeholder.com/15/000000/000000">
    contrastRgb: '0,0,0',
    shadowDark: #c5c5c5, <img src="https://via.placeholder.com/15/c5c5c5/c5c5c5">
    shadowLight: #ffffff, <img src="https://via.placeholder.com/15/ffffff/ffffff">
  ),

  dark: (
    base: #212121, <img src="https://via.placeholder.com/15/212121/212121">
    baseRgb: '33,33,33',
    tint: #373737, <img src="https://via.placeholder.com/15/373737/373737">
    shade: #1d1d1d, <img src="https://via.placeholder.com/15/1d1d1d/1d1d1d">
    contrast: #ffffff, <img src="https://via.placeholder.com/15/ffffff/ffffff">
    contrastRgb: '255,255,255',
    shadowDark: #1a1a1a, <img src="https://via.placeholder.com/15/1a1a1a/1a1a1a">
    shadowLight: #4b4b4b, <img src="https://via.placeholder.com/15/4b4b4b/4b4b4b">
  ),

  background-light: (
    base: #ffffff, <img src="https://via.placeholder.com/15/ffffff/ffffff">
    baseRgb: '255,255,255',
    tint: #ffffff, <img src="https://via.placeholder.com/15/ffffff/ffffff">
    shade: #e0e0e0, <img src="https://via.placeholder.com/15/e0e0e0/e0e0e0">
    contrast: #000000, <img src="https://via.placeholder.com/15/000000/000000">
    contrastRgb: '0,0,0',
    shadowDark: #c5c5c5, <img src="https://via.placeholder.com/15/c5c5c5/c5c5c5">
    shadowLight: #ffffff, <img src="https://via.placeholder.com/15/ffffff/ffffff">
  ),

  background-dark: (
    base: #212121, <img src="https://via.placeholder.com/15/212121/212121">
    baseRgb: '33,33,33',
    tint: #373737, <img src="https://via.placeholder.com/15/373737/373737">
    shade: #1d1d1d, <img src="https://via.placeholder.com/15/1d1d1d/1d1d1d">
    contrast: #ffffff, <img src="https://via.placeholder.com/15/ffffff/ffffff">
    contrastRgb: '255,255,255',
    shadowDark: #1a1a1a, <img src="https://via.placeholder.com/15/1a1a1a/1a1a1a">
    shadowLight: #4b4b4b, <img src="https://via.placeholder.com/15/4b4b4b/4b4b4b">
  ),
);

// Use this function to get SCSS theme variable like this: ...color: color(firstLevel, secondLevel...)

@function color($keys...) {
  $map: $theme;
  @each $key in $keys {
    $map: map-get($map, $key);
  }
  @return $map;
}
</pre>
