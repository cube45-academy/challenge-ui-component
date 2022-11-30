# Know how to create a reusable UI component

Your goal is simple: create a UI component that can be reused in your application.
For this task, we will make a simple number input (or "number spinner").
Here is the design that is expected by the UI designer :
![image](https://user-images.githubusercontent.com/3399355/204911077-36a91332-c579-4b24-9b7b-5468b36e5f37.png)

NOTE: I did the design myself, but let's just assume it's beautiful like a real UI designer would do and move on to the exercise.

You need to create a component that:
- Looks as close as possible to the above design (but if it's nicer, I won't blame you)
- Can be embedded several times in your app
- Decreases and increases the value in the text box when the buttons are pressed
- Limits the values that can be entered in the text box to decimal digits
- Lets the parent component retrieve the value as an integer value as soon as the value has changed
- [BONUS] let the parent specify min and or max value, and show an error if the value is invalid

Constraints:
- You can use whatever UI framework you want (few examples in the Variants sections)
- You can't reuse an existing number spinner, nor use the native `<input type="number" />`
- Use the best practices for the platform you choose (example: use MVVM for WPF, for example)

## Variants
You are free to use the language and/or framework you want, and the platform you want (though I might not be able to review them properly if I don't know the language)
Here are a few examples of what you can use to create the component (this is not an finite list, and you can do the challenge several times, with different PRs)
- vue.js + quasar
- vue.js + vuetify
- vue.js alone, with custom CSS
- web components
- WPF
