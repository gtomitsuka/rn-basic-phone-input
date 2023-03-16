# ☎️ rn-phone-number-input
![platforms](https://img.shields.io/badge/platforms-iOS-brightgreen.svg?style=flat-square&colorB=191A17)

<div align="center">
<b>A beautiful yet customizable phone number input component for React Native that feels native.</b>
<br/>
<a href="#Features">Features</a> • <a href="#Installation">Installation</a> • <a href="#Getting Started">Getting Started</a> • <a href="#Reference">Reference</a> • <a href="https://github.com/gtomitsuka/rn-phone-number-input/">Examples</a>
</div>

**⚠️ Warning**: This library doesn't support Android yet.

## Features
* International phone number input (E.164-compatible)
* Phone number masks
* Searchable country list
* Built-in number verification
* Supports auto-complete
* Supports Fabric (React Native 0.71+)
* Light & dark modes
* Written in TypeScript

## Installation
```
npm install rn-phone-number-input
```
or
```
yarn add rn-phone-number-input
```
And run `cd ios && pod install`

## Getting Started
```jsx
import PhoneNumberInput from 'rn-phone-number-input-og';

export const InputArea = () => {
  // input in e.164 format
  const [input, setInput] = setState('');

  return <PhoneNumberInput
            value={input}
            setValue={setInput}
            defaultCountryCode="+1"
          />
}
```

## Reference

The following props are available:

Keep in mind this library doesn't support web and doesn't have any current plans to do so.

## Examples
Examples can be found in the examples folder or as an Expo snack.
