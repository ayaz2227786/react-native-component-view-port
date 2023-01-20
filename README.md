# react-native-component-viewPort
A React Native SDK to check  component is in view port or not, means component is visible or not.


# Snippet

```const checkVisible = (isVisible: boolean) => {
if (isVisible) {
// View is visible now
} else {   // View is not visible now
}
};



<ScrollView>
<ComponentViewPort
 onChange={isVisible => checkVisible(isVisible)}>
  <View>
<Text>Is Visible Text </Text>
<View>

 </ComponentViewPort>

</ScrollView>
```
