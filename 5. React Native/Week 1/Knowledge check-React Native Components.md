### 1. Which of the following are core components in React Native? Select all that apply.

- [ ] Maps
- [x] TextInput
- [x] View
- [x] Text

### 2. React Native uses component-based architecture, and code is reused between components. True or false?

- [ ] False
- [x] True


### 3. Which of the following make up React Native components? Select all that apply.

- [x] Core Components
- [x] Your Custom Native Components
- [ ] Community Components
- [ ] Utility components


### 4. Custom Native components are written in the following languages. Select all that apply.

- [ ] JavaScirpt
- [ ] React
- [x] Kotlin
- [x] Swift 



### 5. Study the code below and choose the correct output that you will expect to see on the emulator.

```javascript
import React from 'react';
import { Text, View } from 'react-native';

const Cat = () => {
  return (
    <View>
      <Text>I am also a cat!</Text>
    </View>
  );
}

const Cafe = () => {
  return (
    <View>
      <Text>Welcome!</Text>
      <Cat />
      <Cat />
      <Cat />
    </View>
  );
}

export default Cafe;
```


Welcome!
I am also a cat!
I am also a cat!
I am also a cat!



