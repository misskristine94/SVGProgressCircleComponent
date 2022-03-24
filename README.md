![Capture](https://user-images.githubusercontent.com/86930618/159821506-3d7930ed-cbed-4563-bd15-cdc1ae4d6c84.PNG)
# SVGProgressCircleComponent
Progress circle component for your canvas app!

This component has a number of input properties that you can use to customise the SVG without needing to edit the SVG code. It’s built of only two controls – an image (where the SVG code is) and a label which means that it will not impact the loading time of your app at all. It allows you to visualise progress/utilisation of various activities – total annual leave days taken, total number of tasks completed, or items left in stock – it’s up to you and your use case! 

◻ Value  – this property specifies the ‘progress’ value. This could be X holidays taken, X tasks completed, X items in stock

◼ MaxValue – use this property to set the max value. This could be the total holiday allowance, total number of tasks for the project, total number of items etc.

◻ Percentage – there is already a formula in this property so you don’t need to adjust it! It will calculate the percentage of utilisation – value divided by max value and multiplied by 100.

◼ Progress bar border – this property specifies the linecap of the progress bar – if you toggle the value to true, the linecap will be round, if you toggle it off – it will be square.#

◻ BackgroundCircleHexValue – this specifies the colour of the background circle which is set to light gray by default (#9f9f9f). Please only enter the hex value, there is no need to add the hashtag as I have configured this to happen in the background.

◼ BackgroundCircleLineThickness – use this to change the width of the background circle – you can make it narrower than the progress bar, or the same width, or any other width you wish! Please enter a numeric value.

◻ ProgressCircleHexValue – same as BackgroundCircleHexValue, this one however relates to the progress bar colour. 

◼ ProgressCircleLineThickness – same as BackgroundCircleLineWidth, this one however specifies the width of the progress bar.

◻ PercentageLabelColour – this property specifies the colour of the font of the percentage label.

◼ PercentageLabelFontSize – this property specifies the size of the percentage label.

◻ LinealGradient – this is a toggle (Boolean), if you like your visuals to look extra, toggle it to the right to have a nice gradient on your progress bar. If you toggle it to ‘off’, your progress bar will be of one colour only.

◼ LinealGradientHexValue1 and LinealGradientHexValue2 – only use these if your LinealGradient toggle is set to on. This property is responsible for the gradient of your progress bar, please enter hex values without ‘#’.

◻ BoxShadow – this property is another toggle. Set this to ‘on’ if you like to go the extra mile with your visuals – it will add box shadow to your SVG which will make it look more modern. Set this to off if you want your SVG to be ‘flat’.

If you have any enhancement ideas, or experience any issues at all - please reach out to me either by raising an issue or getting in touch on my social media:
LinkedIn - https://www.linkedin.com/in/kristine-kolodziejski-07b6a7212/
Twitter - @kristinekk94

Happy Power Apping 😊
